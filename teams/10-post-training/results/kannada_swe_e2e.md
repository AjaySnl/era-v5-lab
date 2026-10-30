# Kannada chat-format and SWE verification

Kannada chat serialization and browser output are verified using the shared
`render.py` format for `ind-kn-fw2`.

## Coverage

- Words: `ಮನೆ`, `ಕನ್ನಡ`, `ಅಕ್ಕ`, `ಶಕ್ತಿ`.
- ZWNJ: `ಒನ್‌ಪ್ಲಸ್`, with `U+200C` after virama.
- RA: default, ZWJ-before-virama and legacy ZWJ-after-virama sequences.
- Exact text preservation across message fields and all four effort levels.
- SWE demonstration: failing tests → code patch → passing tests in a temporary copy.

## Verified results

- All 26 G10 tests passed.
- Local and Docker SWE runs had one failing test before the patch and both tests
  passed afterward.
- The 11-message trajectory round-tripped at `1k`, `4k`, `16k` and `64k`.
- All eight browser examples matched the expected appearance in Chrome on Linux
  using Noto Sans Kannada. The screenshot is included in the PR.
- The Kannada conversation in `chat_format_v0.md` was also visually confirmed.

Character preservation is checked automatically; visual appearance was checked
separately in the browser. The shared renderer and token allocation are unchanged.

## Reproduce

From the repository root:

```sh
python3 -B -m pytest -q -p no:cacheprovider teams/10-post-training/tests
python3 -B teams/10-post-training/swe-task/run_kannada_e2e.py --output-dir /tmp/g10-kannada-local
python3 -B teams/10-post-training/swe-task/preview_kannada.py
```

Browser preview: `file:///tmp/g10-kannada-preview.html`.
