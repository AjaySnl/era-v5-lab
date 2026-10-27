# Licence table and strategy v0

Shared G10 licence file (`teams/10-post-training/licences/licence_table.md`).

## Team workflow (Core Team · 12 members)

- Keep this **one shared file** (`teams/10-post-training/licences/licence_table.md`).
- Give it **one section for each dataset** (for example `StarCoder`, `Stack Exchange`, `Indic web`).
- Each of the 12 G10 Core Team members adds the licence, source, and decision (`TSAI reserves`) for their own dataset in their own section by pull request to the lead's branch (`g10-week1-post-training`).
- The team lead (Sai Teja) merges the member PRs, removes duplicates in the consolidated licence table, and opens one PR to `theschoolofai/era-v5-lab` `main`.

---

## Consolidated licence table (deduplicated across datasets)

| Set | Source | Language | Licence | Decision |
| --- | --- | --- | --- | --- |
| code-python | bigcode/starcoderdata | Code | other (per-file permissive Stack licences; attribution required) | TSAI reserves |
---

## Dataset sections by G10 Core Team member (12)

### 1. Sai Teja (Lead) — StarCoder (`code-python` · `bigcode/starcoderdata`)

- **Core team:** 10. Post-training and Agentic (Lead) · **Week 2:** 9. Evaluation · **Week 3:** 12. Quantization and Serving
- **Set:** `code-python`
- **Language:** `Code`
- **Source:** `bigcode/starcoderdata`
- **Licence:** `other` — StarCoder training corpus drawn from The Stack; each file retains its upstream licence and attribution notice. Commercial use must follow per-file attribution terms.
- **Decision:** `TSAI reserves`

### 2. Ajay Kumar — Dataset section *(placeholder for PR to `g10-week1-post-training`)*

- **Set:** *(TBD via PR)*
- **Language:** *(TBD via PR)*
- **Source:** *(TBD via PR)*
- **Licence:** *(TBD via PR)*
- **Decision:** `TSAI reserves`

### 3. Amit T — Indic web (`ind-mr-fw2` · FineWeb-2 Marathi)

- **Set:** `ind-mr-fw2` — FineWeb-2 Marathi split (`data/mr/`)
- **Language:** Marathi (`mr`)
- **Source:** `HuggingFaceFW/fineweb-2` (Hugging Face, 2024; Common Crawl curated web pipeline)
- **Licence:** `ODC-By v1.0` (Open Data Commons Attribution License v1.0). Commercial use is explicitly permitted with attribution.
- **Decision:** `TSAI reserves` — commercial-use only rule satisfied. Attribution requirement to be fulfilled in the public model card and training datasheet. Raw data not committed to repository.

### 4. Anirudh Narla — Dataset section *(placeholder for PR to `g10-week1-post-training`)*

- **Set:** *(TBD via PR)*
- **Language:** *(TBD via PR)*
- **Source:** *(TBD via PR)*
- **Licence:** *(TBD via PR)*
- **Decision:** `TSAI reserves`

### 5. Ashish Kamble — Dataset section *(placeholder for PR to `g10-week1-post-training`)*

- **Set:** *(TBD via PR)*
- **Language:** *(TBD via PR)*
- **Source:** *(TBD via PR)*
- **Licence:** *(TBD via PR)*
- **Decision:** `TSAI reserves`

### 6. Hema Varshini Palpandian — Dataset section *(placeholder for PR to `g10-week1-post-training`)*

- **Set:** *(TBD via PR)*
- **Language:** *(TBD via PR)*
- **Source:** *(TBD via PR)*
- **Licence:** *(TBD via PR)*
- **Decision:** `TSAI reserves`

### 7. Lokesh Arundathi — Dataset section *(placeholder for PR to `g10-week1-post-training`)*

- **Set:** *(TBD via PR)*
- **Language:** *(TBD via PR)*
- **Source:** *(TBD via PR)*
- **Licence:** *(TBD via PR)*
- **Decision:** `TSAI reserves`

### 8. Rammohan Madhusudan — Indic web (`ind-hi-hplt` · HPLT 3.0 `hin_Deva`)

- **Set:** `ind-hi-hplt`
- **Language:** `Hindi` (`hin_Deva`)
- **Source:** HPLT 3.0 monolingual, sorted release: `data.hplt-project.org/three/sorted/hin_Deva` (web crawl from Internet Archive and Common Crawl; catalogue at `hplt-project.org/datasets/v3.0`)
- **Licence:** `CC0-1.0` for the **packaging only**. HPLT's Terms of Use: "We do not own any of the text from which these text data has been extracted" and "We license the actual packaging of these text data under the Creative Commons CC0 license". The underlying web text keeps its original copyright (no per-document licence is given). HPLT 3.0 filters robots.txt opt-outs and removes sources on a takedown request in the next release.
- **Decision:** `TSAI reserves`. Commercial use of the collection is allowed (CC0). For the web text itself, treat it like every other web-crawl source: honour robots.txt opt-outs and takedown requests, keep each document's source URL so it can be removed, and do not redistribute raw text.

### 9. Ranjani Chandrasekaran — Indic web (`ind-hi-indiccorp`)

- **Set:** `ind-hi-indiccorp` — IndicCorpV2 Hindi subset (`data/hi-{1,2,3}.txt`)
- **Language:** Hindi (`hi`)
- **Source:** `ai4bharat/IndicCorpV2` (HuggingFace, AI4Bharat)
- **Licence:** CC-BY-4.0 — attribution required; commercial use permitted
- **Decision:** `TSAI reserves` (satisfies commercial-use rule via CC-BY-4.0 attribution; attribution to be carried in the model card)


### 10. Ravi Naik — Dataset section *(placeholder for PR to `g10-week1-post-training`)*

- **Set:** *(TBD via PR)*
- **Language:** *(TBD via PR)*
- **Source:** *(TBD via PR)*
- **Licence:** *(TBD via PR)*
- **Decision:** `TSAI reserves`

### 11. Syed Abdul — Dataset section *(placeholder for PR to `g10-week1-post-training`)*

- **Set:** *(TBD via PR)*
- **Language:** *(TBD via PR)*
- **Source:** *(TBD via PR)*
- **Licence:** *(TBD via PR)*
- **Decision:** `TSAI reserves`

### 12. Vikash Ranjan — Stack Exchange / Dataset section *(placeholder for PR to `g10-week1-post-training`)*

- **Set:** *(TBD via PR)*
- **Language:** *(TBD via PR)*
- **Source:** *(TBD via PR)*
- **Licence:** *(TBD via PR)*
- **Decision:** `TSAI reserves`

---

## Strategy v0

- **Commercial-use data only:** Any dataset or file whose licence is missing or restricts commercial use is excluded.
- **Decision authority:** `TSAI reserves` all dataset release and retention decisions across all members.
- **Repository hygiene:** Raw Parquet, Arrow, or binary training files never enter `era-v5-lab` (enforced by `pr-guard`).
- **Token & effort rules:** 256 reserved special tokens (`0..255`) and four plain-text effort levels (`1k`, `4k`, `16k`, `64k`).
- **Benchmark decontamination protocol:** All training splits (code and text) must be programmatically decontaminated against evaluation benchmarks (SWE-bench, HumanEval, MBPP, LiveCodeBench, BigCodeBench) using 13-gram exact match and embedding-similarity filtering prior to post-training.
- **Provenance & attribution ledger:** Every permissive dataset (ODC-By, CC-BY, Apache-2.0, MIT, Stack per-file notices) has its snapshot timestamp, source repository URL, and licensing terms recorded for automatic aggregation into the release model card.
- **Right-to-be-forgotten & takedown handling:** For curated web crawls (FineWeb-2, HPLT 3.0), maintain source URL manifests to fulfill upstream robots.txt exclusions, DMCA notices, and GDPR Article 17 deletion requests across training checkpoint iterations.
