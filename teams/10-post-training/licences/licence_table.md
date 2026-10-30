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
| chandassu | BodduSriPavan111/chandassu | Telugu | MIT (commercial use allowed) | TSAI reserves |
| ind-mr-fw2 | [HuggingFaceFW/fineweb-2](https://huggingface.co/datasets/HuggingFaceFW/fineweb-2) | Marathi (mr) | ODC-By v1.0 (commercial use permitted with attribution) | TSAI reserves |
| ind-ta-sangraha-v | [ai4bharat/sangraha](https://huggingface.co/datasets/ai4bharat/sangraha) | Tamil (ta) | CC-BY-4.0 (commercial use permitted with attribution) | TSAI reserves |
| ind-hi-hplt | [data.hplt-project.org/three/sorted/hin_Deva](https://data.hplt-project.org/three/sorted/hin_Deva) | Hindi (hi) | CC0-1.0 (packaging) / Web terms | TSAI reserves |
| ind-hi-indiccorp | [ai4bharat/IndicCorpV2](https://huggingface.co/datasets/ai4bharat/IndicCorpV2) | Hindi (hi) | CC-BY-4.0 (commercial use permitted with attribution) | TSAI reserves |
| rl-code-r2e-gym | [R2E-Gym/R2E-Gym-Subset](https://huggingface.co/datasets/R2E-Gym/R2E-Gym-Subset) | Code (Python SWE) | apache-2.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| rl-code-swe-gym | [SWE-Gym/SWE-Gym](https://huggingface.co/datasets/SWE-Gym/SWE-Gym) | Code (Python SWE) | mit (Hub tag; commercial use permitted per tag) | TSAI reserves |
| rl-code-acecode-87k | [TIGER-Lab/AceCode-87K](https://huggingface.co/datasets/TIGER-Lab/AceCode-87K) | Code (Python) | mit (Hub tag; commercial use permitted per tag) | excluded |
| rl-code-deepcoder | [agentica-org/DeepCoder-Preview-Dataset](https://huggingface.co/datasets/agentica-org/DeepCoder-Preview-Dataset) | Code (competitive) | mit (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-code-commitpackft | [bigcode/commitpackft](https://huggingface.co/datasets/bigcode/commitpackft) | Code (350+ languages) | mit (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-code-self-oss-instruct | [bigcode/self-oss-instruct-sc2-exec-filter-50k](https://huggingface.co/datasets/bigcode/self-oss-instruct-sc2-exec-filter-50k) | Code (Python) | odc-by (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-code-magicoder-oss | [ise-uiuc/Magicoder-OSS-Instruct-75K](https://huggingface.co/datasets/ise-uiuc/Magicoder-OSS-Instruct-75K) | Code (polyglot) | mit (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-code-codefeedback | [m-a-p/CodeFeedback-Filtered-Instruction](https://huggingface.co/datasets/m-a-p/CodeFeedback-Filtered-Instruction) | Code (polyglot) | apache-2.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-rl-code-rstar-coder | [microsoft/rStar-Coder](https://huggingface.co/datasets/microsoft/rStar-Coder) | Code (competitive) | cc-by-4.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| rl-code-swe-rebench-v2 | [nebius/SWE-rebench-V2](https://huggingface.co/datasets/nebius/SWE-rebench-V2) | Code (20 languages incl. Go) | cc-by-4.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-code-swe-rebench-openhands | [nebius/SWE-rebench-openhands-trajectories](https://huggingface.co/datasets/nebius/SWE-rebench-openhands-trajectories) | Code (agent trajectories) | cc-by-4.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-code-nemotron-cp-v2 | [nvidia/Nemotron-SFT-Competitive-Programming-v2](https://huggingface.co/datasets/nvidia/Nemotron-SFT-Competitive-Programming-v2) | Code (competitive, SQL) | cc-by-4.0, odc-by, mit (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-code-nemotron-swe-v3 | [nvidia/Nemotron-SFT-SWE-v3](https://huggingface.co/datasets/nvidia/Nemotron-SFT-SWE-v3) | Code (agent trajectories) | cc-by-4.0, apache-2.0, mit, bsd-3-clause, bsd-2-clause (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-code-nemotron-terminal | [nvidia/Nemotron-Terminal-Corpus](https://huggingface.co/datasets/nvidia/Nemotron-Terminal-Corpus) | Code (terminal agent) | cc-by-4.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-code-opencodereasoning | [nvidia/OpenCodeReasoning](https://huggingface.co/datasets/nvidia/OpenCodeReasoning) | Code (competitive) | cc-by-4.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-code-opencodereasoning-2 | [nvidia/OpenCodeReasoning-2](https://huggingface.co/datasets/nvidia/OpenCodeReasoning-2) | Code (competitive) | cc-by-4.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| rl-code-codeforces | [open-r1/codeforces](https://huggingface.co/datasets/open-r1/codeforces) | Code (competitive) | cc-by-4.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-code-codeforces-cots | [open-r1/codeforces-cots](https://huggingface.co/datasets/open-r1/codeforces-cots) | Code (competitive) | cc-by-4.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-indic-aya-collection | [CohereLabs/aya_collection](https://huggingface.co/datasets/CohereLabs/aya_collection) | Multilingual incl. Indic | apache-2.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-indic-aya-dataset | [CohereLabs/aya_dataset](https://huggingface.co/datasets/CohereLabs/aya_dataset) | Multilingual incl. Indic | apache-2.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-indic-indic-align | [ai4bharat/indic-align](https://huggingface.co/datasets/ai4bharat/indic-align) | 14 Indic languages | cc-by-4.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-indic-samvaad-hi | [sarvamai/samvaad-hi-v1](https://huggingface.co/datasets/sarvamai/samvaad-hi-v1) | Hindi, English, Hinglish | apache-2.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-indic-code-oss-codes-coding | [oss-codes/Coding-Conversational-Dataset-Indic](https://huggingface.co/datasets/oss-codes/Coding-Conversational-Dataset-Indic) | Indic (Hindi, Tamil, ...) + code | mit (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-indic-code-oss-codes-cs | [oss-codes/Computer-Science-Conversational-Dataset-Indic](https://huggingface.co/datasets/oss-codes/Computer-Science-Conversational-Dataset-Indic) | Indic + computer science | mit (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-indic-math-orca-math-hi | [BhabhaAI/orca-math-word-problems-200k-hindi-filtered](https://huggingface.co/datasets/BhabhaAI/orca-math-word-problems-200k-hindi-filtered) | Hindi (math) | mit (Hub tag; commercial use permitted per tag) | excluded |
| sft-indic-math-aryabhatta-orca-hi | [GenVRadmin/Aryabhatta-Orca-Maths-Hindi](https://huggingface.co/datasets/GenVRadmin/Aryabhatta-Orca-Maths-Hindi) | Hindi (math) | mit (Hub tag; commercial use permitted per tag) | excluded |
| rl-math-dapo-17k | [BytedTsinghua-SIA/DAPO-Math-17k](https://huggingface.co/datasets/BytedTsinghua-SIA/DAPO-Math-17k) | English / Mathematics | apache-2.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| rl-math-big-math | [SynthLabsAI/Big-Math-RL-Verified](https://huggingface.co/datasets/SynthLabsAI/Big-Math-RL-Verified) | English / Mathematics | apache-2.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-math-nemotron-proofs | [nvidia/Nemotron-Math-Proofs-v1](https://huggingface.co/datasets/nvidia/Nemotron-Math-Proofs-v1) | English / Mathematics | cc-by-sa-4.0 (Hub tag; share-alike, team decision needed) | excluded |
| sft-math-nemotron-math-v2 | [nvidia/Nemotron-Math-v2](https://huggingface.co/datasets/nvidia/Nemotron-Math-v2) | English / Mathematics | cc-by-4.0, cc-by-sa-4.0 (Hub tag; share-alike, team decision needed) | excluded |
| sft-math-openmathinstruct-2 | [nvidia/OpenMathInstruct-2](https://huggingface.co/datasets/nvidia/OpenMathInstruct-2) | English / Mathematics | cc-by-4.0 (Hub tag; commercial use permitted per tag) | excluded |
| sft-rl-math-openmathreasoning | [nvidia/OpenMathReasoning](https://huggingface.co/datasets/nvidia/OpenMathReasoning) | English / Mathematics | cc-by-4.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-math-openr1-math | [open-r1/OpenR1-Math-220k](https://huggingface.co/datasets/open-r1/OpenR1-Math-220k) | English / Mathematics | apache-2.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-math-numinamath-1.5 | [project-numina/NuminaMath-1.5](https://huggingface.co/datasets/project-numina/NuminaMath-1.5) | English / Mathematics | apache-2.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-math-numinamath-cot | [project-numina/NuminaMath-CoT](https://huggingface.co/datasets/project-numina/NuminaMath-CoT) | English / Mathematics | apache-2.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| rl-math-deepmath-103k | [zwhe99/DeepMath-103K](https://huggingface.co/datasets/zwhe99/DeepMath-103K) | English / Mathematics | mit (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-stem-code-nemotron-post-v1 | [nvidia/Nemotron-Post-Training-Dataset-v1](https://huggingface.co/datasets/nvidia/Nemotron-Post-Training-Dataset-v1) | English / Math, STEM, Code | cc-by-4.0 (Hub tag; commercial use permitted per tag) | excluded |
| sft-stem-code-nemotron-post-v2 | [nvidia/Nemotron-Post-Training-Dataset-v2](https://huggingface.co/datasets/nvidia/Nemotron-Post-Training-Dataset-v2) | Multilingual / Math, STEM, Code | cc-by-4.0 (Hub tag; commercial use permitted per tag) | excluded |
| sft-stem-code-openthoughts3 | [open-thoughts/OpenThoughts3-1.2M](https://huggingface.co/datasets/open-thoughts/OpenThoughts3-1.2M) | English / Math, Code, Science | apache-2.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
| sft-science-nemotron-science | [nvidia/Nemotron-Science-v1](https://huggingface.co/datasets/nvidia/Nemotron-Science-v1) | English / Science | cc-by-4.0 (Hub tag; commercial use permitted per tag) | TSAI reserves |
---

## Dataset sections by G10 Core Team member (12)

### 1. Sai Teja (Lead) — StarCoder (`code-python` · `bigcode/starcoderdata`)

- **Core team:** 10. Post-training and Agentic (Lead) · **Week 2:** 9. Evaluation · **Week 3:** 12. Quantization and Serving
- **Set:** `code-python`
- **Language:** `Code`
- **Source:** `bigcode/starcoderdata`
- **Licence:** `other` — StarCoder training corpus drawn from The Stack; each file retains its upstream licence and attribution notice. Commercial use must follow per-file attribution terms.
- **Decision:** `TSAI reserves`

### 1b. Sai Teja (Lead) — Chandassu (`BodduSriPavan111/chandassu`)

- **Core team:** 10. Post-training and Agentic (Lead) · **Week 2:** 9. Evaluation · **Week 3:** 12. Quantization and Serving
- **Set:** `chandassu`
- **Language:** Telugu (`te`)
- **Source:** `BodduSriPavan111/chandassu` (4,651 padyams; eight metres in vruttamu, jaathi, and vupajaathi)
- **Licence:** `MIT` — commercial use is allowed. The dataset card names the licence as MIT.
- **Decision:** `TSAI reserves`
- **Reading note:** 1,134 Vemana poems store a carriage return as the plain letters `_x000D_`. 23 poems have words replaced by `...`. ZWNJ and ZWJ stay in the text. They are not a licence issue.

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

### 6. Hema Varshini Palpandian — Tamil (`ind-ta-sangraha-v`)

- **Set:** `ind-ta-sangraha-v`
- **Language:** Tamil (`ta`; source split `tam`)
- **Source:** `ai4bharat/sangraha`, Verified Tamil subset.
- **Licence:** `CC-BY-4.0` — publisher-declared; permits commercial use with attribution, a licence link and notice of changes.
- **Decision:** `TSAI reserves` — source checks and SFT/RL selection pending.
- **Reading note:** 500 Tamil documents. No tested chat/tool markers found. Document URLs and the source release are missing from the sample; verify provenance before training.

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


### 10. Ravi Naik — SFT and RL candidates for coding, Indic, math and science

Coverage: the target model is for coding, Indian languages, math and science, so this section lists 40 SFT and RL datasets screened for commercial use (Hugging Face licence tag read on 29 Oct 2026). Each entry below (10a, 10b, ...) has the standard fields, `TSAI reserves` as the decision, and one line of our opinion. Non-commercial, untagged and benchmark-only sets (GSM8K, MATH) are left out. Eight of the sets below are marked `excluded` after the TSAI ruling in the G10 chat (30 Oct); they stay in the table with the reason. DeepCoder-Preview and Nemotron-Science-v1 wait for the G9 (Evaluation) decontamination test. The full screen, the excluded sets, per-dataset caveats, benchmark-overlap notes and 20-row samples are in [team10-datasets](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets).

### 10a. RaviNaik — R2E-Gym-Subset (`rl-code-r2e-gym`)

- **Stage:** RL
- **Set:** `rl-code-r2e-gym`
- **Language:** Code (Python SWE)
- **Source:** [`R2E-Gym/R2E-Gym-Subset`](https://huggingface.co/datasets/R2E-Gym/R2E-Gym-Subset)
- **Licence:** `apache-2.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use. Permissive tag, SWE tasks with tests. Compare the repos with SWE-bench repos.
- **Details and 20-row sample:** [R2E-Gym__R2E-Gym-Subset](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/R2E-Gym__R2E-Gym-Subset)

### 10b. RaviNaik — SWE-Gym (`rl-code-swe-gym`)

- **Stage:** RL
- **Set:** `rl-code-swe-gym`
- **Language:** Code (Python SWE)
- **Source:** [`SWE-Gym/SWE-Gym`](https://huggingface.co/datasets/SWE-Gym/SWE-Gym)
- **Licence:** `mit` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use. The Python repos keep their own licences. Compare the 11 repos with SWE-bench.
- **Details and 20-row sample:** [SWE-Gym__SWE-Gym](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/SWE-Gym__SWE-Gym)

### 10c. RaviNaik — AceCode-87K (`rl-code-acecode-87k`)

- **Stage:** RL
- **Set:** `rl-code-acecode-87k`
- **Language:** Code (Python)
- **Source:** [`TIGER-Lab/AceCode-87K`](https://huggingface.co/datasets/TIGER-Lab/AceCode-87K)
- **Licence:** `mit` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `excluded` — TSAI ruling in the G10 chat (30 Oct): quarantined sets stay out of the lab and out of every training mix. Reason: Questions were rewritten by GPT-4o-mini, so OpenAI terms apply.
- **Our opinion:** excluded, as ruled by TSAI. Tests per problem. Questions were rewritten by GPT-4o-mini, so OpenAI terms apply to that text. Check HumanEval/MBPP overlap.
- **Details and 20-row sample:** [TIGER-Lab__AceCode-87K](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/TIGER-Lab__AceCode-87K)

### 10d. RaviNaik — DeepCoder-Preview-Dataset (`rl-code-deepcoder`)

- **Stage:** RL
- **Set:** `rl-code-deepcoder`
- **Language:** Code (competitive)
- **Source:** [`agentica-org/DeepCoder-Preview-Dataset`](https://huggingface.co/datasets/agentica-org/DeepCoder-Preview-Dataset)
- **Licence:** `mit` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, `train` only. The training set holds 600 LiveCodeBench problems from before 1 Aug 2024 and the `test` data is LiveCodeBench plus CodeElo. Per TSAI, the source name goes to G9 (Evaluation) for a decontamination test; no use before that.
- **Details and 20-row sample:** [agentica-org__DeepCoder-Preview-Dataset](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/agentica-org__DeepCoder-Preview-Dataset)

### 10e. RaviNaik — commitpackft (`sft-code-commitpackft`)

- **Stage:** SFT
- **Set:** `sft-code-commitpackft`
- **Language:** Code (350+ languages)
- **Source:** [`bigcode/commitpackft`](https://huggingface.co/datasets/bigcode/commitpackft)
- **Licence:** `mit` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. Commit data with repo licences filtered upstream; low benchmark risk but untested.
- **Details and 20-row sample:** [bigcode__commitpackft](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/bigcode__commitpackft)

### 10f. RaviNaik — self-oss-instruct-sc2-exec-filter-50k (`sft-code-self-oss-instruct`)

- **Stage:** SFT
- **Set:** `sft-code-self-oss-instruct`
- **Language:** Code (Python)
- **Source:** [`bigcode/self-oss-instruct-sc2-exec-filter-50k`](https://huggingface.co/datasets/bigcode/self-oss-instruct-sc2-exec-filter-50k)
- **Licence:** `odc-by` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use. Self-generated and execution-filtered. ODC-By needs attribution.
- **Details and 20-row sample:** [bigcode__self-oss-instruct-sc2-exec-filter-50k](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/bigcode__self-oss-instruct-sc2-exec-filter-50k)

### 10g. RaviNaik — Magicoder-OSS-Instruct-75K (`sft-code-magicoder-oss`)

- **Stage:** SFT
- **Set:** `sft-code-magicoder-oss`
- **Language:** Code (polyglot)
- **Source:** [`ise-uiuc/Magicoder-OSS-Instruct-75K`](https://huggingface.co/datasets/ise-uiuc/Magicoder-OSS-Instruct-75K)
- **Licence:** `mit` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. The Hub tag is MIT. Instructions were generated with GPT-3.5, so OpenAI terms apply. Verify HumanEval decontamination.
- **Details and 20-row sample:** [ise-uiuc__Magicoder-OSS-Instruct-75K](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/ise-uiuc__Magicoder-OSS-Instruct-75K)

### 10h. RaviNaik — CodeFeedback-Filtered-Instruction (`sft-code-codefeedback`)

- **Stage:** SFT
- **Set:** `sft-code-codefeedback`
- **Language:** Code (polyglot)
- **Source:** [`m-a-p/CodeFeedback-Filtered-Instruction`](https://huggingface.co/datasets/m-a-p/CodeFeedback-Filtered-Instruction)
- **Licence:** `apache-2.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. Built from several instruction sets, one of them Evol-Instruct code. Check HumanEval/MBPP overlap.
- **Details and 20-row sample:** [m-a-p__CodeFeedback-Filtered-Instruction](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/m-a-p__CodeFeedback-Filtered-Instruction)

### 10i. RaviNaik — rStar-Coder (`sft-rl-code-rstar-coder`)

- **Stage:** SFT + RL
- **Set:** `sft-rl-code-rstar-coder`
- **Language:** Code (competitive)
- **Source:** [`microsoft/rStar-Coder`](https://huggingface.co/datasets/microsoft/rStar-Coder)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use. Has SFT and RL splits. Check LiveCodeBench/CodeElo overlap, since no decontamination is stated on the card.
- **Details and 20-row sample:** [microsoft__rStar-Coder](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/microsoft__rStar-Coder)

### 10j. RaviNaik — SWE-rebench-V2 (`rl-code-swe-rebench-v2`)

- **Stage:** RL
- **Set:** `rl-code-swe-rebench-v2`
- **Language:** Code (20 languages incl. Go)
- **Source:** [`nebius/SWE-rebench-V2`](https://huggingface.co/datasets/nebius/SWE-rebench-V2)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use. The card warns that only the original SWE-bench repos were excluded. Remove task IDs that overlap with our eval set.
- **Details and 20-row sample:** [nebius__SWE-rebench-V2](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nebius__SWE-rebench-V2)

### 10k. RaviNaik — SWE-rebench-openhands-trajectories (`sft-code-swe-rebench-openhands`)

- **Stage:** SFT
- **Set:** `sft-code-swe-rebench-openhands`
- **Language:** Code (agent trajectories)
- **Source:** [`nebius/SWE-rebench-openhands-trajectories`](https://huggingface.co/datasets/nebius/SWE-rebench-openhands-trajectories)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use. OpenHands trajectories. Apply the same task-ID overlap check.
- **Details and 20-row sample:** [nebius__SWE-rebench-openhands-trajectories](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nebius__SWE-rebench-openhands-trajectories)

### 10l. RaviNaik — Nemotron-SFT-Competitive-Programming-v2 (`sft-code-nemotron-cp-v2`)

- **Stage:** SFT
- **Set:** `sft-code-nemotron-cp-v2`
- **Language:** Code (competitive, SQL)
- **Source:** [`nvidia/Nemotron-SFT-Competitive-Programming-v2`](https://huggingface.co/datasets/nvidia/Nemotron-SFT-Competitive-Programming-v2)
- **Licence:** `cc-by-4.0, odc-by, mit` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. Per-subset licences (CC-BY-4.0, ODC-By, MIT). The Exercism subset is decontaminated against Aider.
- **Details and 20-row sample:** [nvidia__Nemotron-SFT-Competitive-Programming-v2](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__Nemotron-SFT-Competitive-Programming-v2)

### 10m. RaviNaik — Nemotron-SFT-SWE-v3 (`sft-code-nemotron-swe-v3`)

- **Stage:** SFT
- **Set:** `sft-code-nemotron-swe-v3`
- **Language:** Code (agent trajectories)
- **Source:** [`nvidia/Nemotron-SFT-SWE-v3`](https://huggingface.co/datasets/nvidia/Nemotron-SFT-SWE-v3)
- **Licence:** `cc-by-4.0, apache-2.0, mit, bsd-3-clause, bsd-2-clause` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use. Mixed permissive licences. Check overlap with the SWE-bench variants we report.
- **Details and 20-row sample:** [nvidia__Nemotron-SFT-SWE-v3](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__Nemotron-SFT-SWE-v3)

### 10n. RaviNaik — Nemotron-Terminal-Corpus (`sft-code-nemotron-terminal`)

- **Stage:** SFT
- **Set:** `sft-code-nemotron-terminal`
- **Language:** Code (terminal agent)
- **Source:** [`nvidia/Nemotron-Terminal-Corpus`](https://huggingface.co/datasets/nvidia/Nemotron-Terminal-Corpus)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. The teacher model is not stated on the card. Check Terminal-Bench overlap.
- **Details and 20-row sample:** [nvidia__Nemotron-Terminal-Corpus](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__Nemotron-Terminal-Corpus)

### 10o. RaviNaik — OpenCodeReasoning (`sft-code-opencodereasoning`)

- **Stage:** SFT
- **Set:** `sft-code-opencodereasoning`
- **Language:** Code (competitive)
- **Source:** [`nvidia/OpenCodeReasoning`](https://huggingface.co/datasets/nvidia/OpenCodeReasoning)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. DeepSeek-R1-family traces, so check the teacher's terms. The card excludes the CodeContests and open-r1/codeforces test splits.
- **Details and 20-row sample:** [nvidia__OpenCodeReasoning](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__OpenCodeReasoning)

### 10p. RaviNaik — OpenCodeReasoning-2 (`sft-code-opencodereasoning-2`)

- **Stage:** SFT
- **Set:** `sft-code-opencodereasoning-2`
- **Language:** Code (competitive)
- **Source:** [`nvidia/OpenCodeReasoning-2`](https://huggingface.co/datasets/nvidia/OpenCodeReasoning-2)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. Same teacher-terms check as OpenCodeReasoning.
- **Details and 20-row sample:** [nvidia__OpenCodeReasoning-2](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__OpenCodeReasoning-2)

### 10q. RaviNaik — codeforces (`rl-code-codeforces`)

- **Stage:** RL
- **Set:** `rl-code-codeforces`
- **Language:** Code (competitive)
- **Source:** [`open-r1/codeforces`](https://huggingface.co/datasets/open-r1/codeforces)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. The Codeforces problem text may not be covered by the dataset licence (header CC-BY-4.0, body ODC-By 4.0). Use `train` only.
- **Details and 20-row sample:** [open-r1__codeforces](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/open-r1__codeforces)

### 10r. RaviNaik — codeforces-cots (`sft-code-codeforces-cots`)

- **Stage:** SFT
- **Set:** `sft-code-codeforces-cots`
- **Language:** Code (competitive)
- **Source:** [`open-r1/codeforces-cots`](https://huggingface.co/datasets/open-r1/codeforces-cots)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. R1 traces on Codeforces problems. Use the `_decontaminated` configs.
- **Details and 20-row sample:** [open-r1__codeforces-cots](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/open-r1__codeforces-cots)

### 10s. RaviNaik — aya_collection (`sft-indic-aya-collection`)

- **Stage:** SFT
- **Set:** `sft-indic-aya-collection`
- **Language:** Multilingual incl. Indic
- **Source:** [`CohereLabs/aya_collection`](https://huggingface.co/datasets/CohereLabs/aya_collection)
- **Licence:** `apache-2.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. Templated tasks; the card does not state the source sets or model terms, and sub-dataset licences are unchecked.
- **Details and 20-row sample:** [CohereLabs__aya_collection](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/CohereLabs__aya_collection)

### 10t. RaviNaik — aya_dataset (`sft-indic-aya-dataset`)

- **Stage:** SFT
- **Set:** `sft-indic-aya-dataset`
- **Language:** Multilingual incl. Indic
- **Source:** [`CohereLabs/aya_dataset`](https://huggingface.co/datasets/CohereLabs/aya_dataset)
- **Licence:** `apache-2.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use. Human-written prompt/completion pairs under Apache-2.0 per the card. The cleanest Indic set found.
- **Details and 20-row sample:** [CohereLabs__aya_dataset](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/CohereLabs__aya_dataset)

### 10u. RaviNaik — indic-align (`sft-indic-indic-align`)

- **Stage:** SFT
- **Set:** `sft-indic-indic-align`
- **Language:** 14 Indic languages
- **Source:** [`ai4bharat/indic-align`](https://huggingface.co/datasets/ai4bharat/indic-align)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** check (high risk), lean exclude. Many parts have Llama-2-70B-Chat responses, and the Llama 2 licence limits using its outputs to improve other models (my reading, not legal advice). It also holds translated Dolly, OpenAssistant, WikiHow and ShareGPT prompts.
- **Details and 20-row sample:** [ai4bharat__indic-align](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/ai4bharat__indic-align)

### 10v. RaviNaik — samvaad-hi-v1 (`sft-indic-samvaad-hi`)

- **Stage:** SFT
- **Set:** `sft-indic-samvaad-hi`
- **Language:** Hindi, English, Hinglish
- **Source:** [`sarvamai/samvaad-hi-v1`](https://huggingface.co/datasets/sarvamai/samvaad-hi-v1)
- **Licence:** `apache-2.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. The card does not say which model wrote the replies.
- **Details and 20-row sample:** [sarvamai__samvaad-hi-v1](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/sarvamai__samvaad-hi-v1)

### 10w. RaviNaik — Coding-Conversational-Dataset-Indic (`sft-indic-code-oss-codes-coding`)

- **Stage:** SFT
- **Set:** `sft-indic-code-oss-codes-coding`
- **Language:** Indic (Hindi, Tamil, ...) + code
- **Source:** [`oss-codes/Coding-Conversational-Dataset-Indic`](https://huggingface.co/datasets/oss-codes/Coding-Conversational-Dataset-Indic)
- **Licence:** `mit` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** check. Small; origin and generator not verified.
- **Details and 20-row sample:** [oss-codes__Coding-Conversational-Dataset-Indic](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/oss-codes__Coding-Conversational-Dataset-Indic)

### 10x. RaviNaik — Computer-Science-Conversational-Dataset-Indic (`sft-indic-code-oss-codes-cs`)

- **Stage:** SFT
- **Set:** `sft-indic-code-oss-codes-cs`
- **Language:** Indic + computer science
- **Source:** [`oss-codes/Computer-Science-Conversational-Dataset-Indic`](https://huggingface.co/datasets/oss-codes/Computer-Science-Conversational-Dataset-Indic)
- **Licence:** `mit` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** check. Small; origin and generator not verified.
- **Details and 20-row sample:** [oss-codes__Computer-Science-Conversational-Dataset-Indic](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/oss-codes__Computer-Science-Conversational-Dataset-Indic)

### 10y. RaviNaik — orca-math-word-problems-200k-hindi-filtered (`sft-indic-math-orca-math-hi`)

- **Stage:** SFT
- **Set:** `sft-indic-math-orca-math-hi`
- **Language:** Hindi (math)
- **Source:** [`BhabhaAI/orca-math-word-problems-200k-hindi-filtered`](https://huggingface.co/datasets/BhabhaAI/orca-math-word-problems-200k-hindi-filtered)
- **Licence:** `mit` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `excluded` — TSAI ruling in the G10 chat (30 Oct): quarantined sets stay out of the lab and out of every training mix. Reason: Hindi translation of Orca-Math, which was generated with GPT-4, so OpenAI terms apply.
- **Our opinion:** excluded, as ruled by TSAI. Hindi translation of Orca-Math, which is GPT-4 generated, so OpenAI terms apply.
- **Details and 20-row sample:** [BhabhaAI__orca-math-word-problems-200k-hindi-filtered](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/BhabhaAI__orca-math-word-problems-200k-hindi-filtered)

### 10z. RaviNaik — Aryabhatta-Orca-Maths-Hindi (`sft-indic-math-aryabhatta-orca-hi`)

- **Stage:** SFT
- **Set:** `sft-indic-math-aryabhatta-orca-hi`
- **Language:** Hindi (math)
- **Source:** [`GenVRadmin/Aryabhatta-Orca-Maths-Hindi`](https://huggingface.co/datasets/GenVRadmin/Aryabhatta-Orca-Maths-Hindi)
- **Licence:** `mit` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `excluded` — TSAI ruling in the G10 chat (30 Oct): quarantined sets stay out of the lab and out of every training mix. Reason: Hindi translation of Orca-Math, which was generated with GPT-4, so OpenAI terms apply.
- **Our opinion:** excluded, as ruled by TSAI. Hindi translation of Orca-Math, which is GPT-4 generated, so OpenAI terms apply.
- **Details and 20-row sample:** [GenVRadmin__Aryabhatta-Orca-Maths-Hindi](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/GenVRadmin__Aryabhatta-Orca-Maths-Hindi)

### 10aa. RaviNaik — DAPO-Math-17k (`rl-math-dapo-17k`)

- **Stage:** RL
- **Set:** `rl-math-dapo-17k`
- **Language:** English / Mathematics
- **Source:** [`BytedTsinghua-SIA/DAPO-Math-17k`](https://huggingface.co/datasets/BytedTsinghua-SIA/DAPO-Math-17k)
- **Licence:** `apache-2.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use. Verifiable answers. Check AIME and MATH-500 overlap.
- **Details and 20-row sample:** [BytedTsinghua-SIA__DAPO-Math-17k](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/BytedTsinghua-SIA__DAPO-Math-17k)

### 10ab. RaviNaik — Big-Math-RL-Verified (`rl-math-big-math`)

- **Stage:** RL
- **Set:** `rl-math-big-math`
- **Language:** English / Mathematics
- **Source:** [`SynthLabsAI/Big-Math-RL-Verified`](https://huggingface.co/datasets/SynthLabsAI/Big-Math-RL-Verified)
- **Licence:** `apache-2.0` — Hugging Face tag read on 29 Oct 2026; gated dataset. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use. Gated (auto-approval) so the card and a sample were not read. Assume overlap with MATH and GSM8K-style sources until read.
- **Details and 20-row sample:** [SynthLabsAI__Big-Math-RL-Verified](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/SynthLabsAI__Big-Math-RL-Verified)

### 10ac. RaviNaik — Nemotron-Math-Proofs-v1 (`sft-math-nemotron-proofs`)

- **Stage:** SFT
- **Set:** `sft-math-nemotron-proofs`
- **Language:** English / Mathematics
- **Source:** [`nvidia/Nemotron-Math-Proofs-v1`](https://huggingface.co/datasets/nvidia/Nemotron-Math-Proofs-v1)
- **Licence:** `cc-by-sa-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `excluded` — TSAI ruling in the G10 chat (30 Oct): quarantined sets stay out of the lab and out of every training mix. Reason: Contains CC-BY-SA-4.0 (share-alike) parts.
- **Our opinion:** excluded, as ruled by TSAI. CC-BY-SA-4.0 is share-alike and needs a team decision.
- **Details and 20-row sample:** [nvidia__Nemotron-Math-Proofs-v1](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__Nemotron-Math-Proofs-v1)

### 10ad. RaviNaik — Nemotron-Math-v2 (`sft-math-nemotron-math-v2`)

- **Stage:** SFT
- **Set:** `sft-math-nemotron-math-v2`
- **Language:** English / Mathematics
- **Source:** [`nvidia/Nemotron-Math-v2`](https://huggingface.co/datasets/nvidia/Nemotron-Math-v2)
- **Licence:** `cc-by-4.0, cc-by-sa-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `excluded` — TSAI ruling in the G10 chat (30 Oct): quarantined sets stay out of the lab and out of every training mix. Reason: Contains CC-BY-SA-4.0 (share-alike) parts.
- **Our opinion:** excluded, as ruled by TSAI. Mixed CC-BY-4.0 and CC-BY-SA-4.0; the share-alike part needs a team decision. The card says it is decontaminated.
- **Details and 20-row sample:** [nvidia__Nemotron-Math-v2](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__Nemotron-Math-v2)

### 10ae. RaviNaik — OpenMathInstruct-2 (`sft-math-openmathinstruct-2`)

- **Stage:** SFT
- **Set:** `sft-math-openmathinstruct-2`
- **Language:** English / Mathematics
- **Source:** [`nvidia/OpenMathInstruct-2`](https://huggingface.co/datasets/nvidia/OpenMathInstruct-2)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `excluded` — TSAI ruling in the G10 chat (30 Oct): quarantined sets stay out of the lab and out of every training mix. Reason: Solutions were generated with Llama-3.1-405B, and the Llama licence limits using its outputs to train other models.
- **Our opinion:** excluded, as ruled by TSAI. Generated with Llama-3.1-405B, so Llama licence terms apply. Built from GSM8K and MATH train problems.
- **Details and 20-row sample:** [nvidia__OpenMathInstruct-2](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__OpenMathInstruct-2)

### 10af. RaviNaik — OpenMathReasoning (`sft-rl-math-openmathreasoning`)

- **Stage:** SFT + RL prompts
- **Set:** `sft-rl-math-openmathreasoning`
- **Language:** English / Mathematics
- **Source:** [`nvidia/OpenMathReasoning`](https://huggingface.co/datasets/nvidia/OpenMathReasoning)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. Traces from DeepSeek-R1 and QwQ, so check teacher terms. The card says benchmark decontamination was applied.
- **Details and 20-row sample:** [nvidia__OpenMathReasoning](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__OpenMathReasoning)

### 10ag. RaviNaik — OpenR1-Math-220k (`sft-math-openr1-math`)

- **Stage:** SFT
- **Set:** `sft-math-openr1-math`
- **Language:** English / Mathematics
- **Source:** [`open-r1/OpenR1-Math-220k`](https://huggingface.co/datasets/open-r1/OpenR1-Math-220k)
- **Licence:** `apache-2.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. R1 traces on NuminaMath 1.5 problems, so it inherits the NuminaMath overlap.
- **Details and 20-row sample:** [open-r1__OpenR1-Math-220k](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/open-r1__OpenR1-Math-220k)

### 10ah. RaviNaik — NuminaMath-1.5 (`sft-math-numinamath-1.5`)

- **Stage:** SFT
- **Set:** `sft-math-numinamath-1.5`
- **Language:** English / Mathematics
- **Source:** [`project-numina/NuminaMath-1.5`](https://huggingface.co/datasets/project-numina/NuminaMath-1.5)
- **Licence:** `apache-2.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. Sources include amc_aime and olympiads with no decontamination stated; web-scraped problem text may not be covered by the dataset licence.
- **Details and 20-row sample:** [project-numina__NuminaMath-1.5](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/project-numina__NuminaMath-1.5)

### 10ai. RaviNaik — NuminaMath-CoT (`sft-math-numinamath-cot`)

- **Stage:** SFT
- **Set:** `sft-math-numinamath-cot`
- **Language:** English / Mathematics
- **Source:** [`project-numina/NuminaMath-CoT`](https://huggingface.co/datasets/project-numina/NuminaMath-CoT)
- **Licence:** `apache-2.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. Sources include gsm8k, math, amc_aime and olympiads; decontaminate before use.
- **Details and 20-row sample:** [project-numina__NuminaMath-CoT](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/project-numina__NuminaMath-CoT)

### 10aj. RaviNaik — DeepMath-103K (`rl-math-deepmath-103k`)

- **Stage:** RL (and SFT)
- **Set:** `rl-math-deepmath-103k`
- **Language:** English / Mathematics
- **Source:** [`zwhe99/DeepMath-103K`](https://huggingface.co/datasets/zwhe99/DeepMath-103K)
- **Licence:** `mit` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use. The card says it was decontaminated against common benchmarks.
- **Details and 20-row sample:** [zwhe99__DeepMath-103K](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/zwhe99__DeepMath-103K)

### 10ak. RaviNaik — Nemotron-Post-Training-Dataset-v1 (`sft-stem-code-nemotron-post-v1`)

- **Stage:** SFT
- **Set:** `sft-stem-code-nemotron-post-v1`
- **Language:** English / Math, STEM, Code
- **Source:** [`nvidia/Nemotron-Post-Training-Dataset-v1`](https://huggingface.co/datasets/nvidia/Nemotron-Post-Training-Dataset-v1)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `excluded` — TSAI ruling in the G10 chat (30 Oct): quarantined sets stay out of the lab and out of every training mix. Reason: Responses come from Qwen and DeepSeek teacher models; gated, and prompt provenance is not cleared.
- **Our opinion:** excluded, as ruled by TSAI. Responses come from Qwen and DeepSeek models, so check their terms. Some prompts must be fetched separately from their original sources under their own terms.
- **Details and 20-row sample:** [nvidia__Nemotron-Post-Training-Dataset-v1](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__Nemotron-Post-Training-Dataset-v1)

### 10al. RaviNaik — Nemotron-Post-Training-Dataset-v2 (`sft-stem-code-nemotron-post-v2`)

- **Stage:** SFT
- **Set:** `sft-stem-code-nemotron-post-v2`
- **Language:** Multilingual / Math, STEM, Code
- **Source:** [`nvidia/Nemotron-Post-Training-Dataset-v2`](https://huggingface.co/datasets/nvidia/Nemotron-Post-Training-Dataset-v2)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026; gated dataset. A tag is not legal clearance.
- **Decision:** `excluded` — TSAI ruling in the G10 chat (30 Oct): quarantined sets stay out of the lab and out of every training mix. Reason: Responses come from Qwen and DeepSeek teacher models; gated, and prompt provenance is not cleared.
- **Our opinion:** excluded, as ruled by TSAI. Gated so the card was not read. Earlier notes say models trained on it may fall under Qwen and DeepSeek licences.
- **Details and 20-row sample:** [nvidia__Nemotron-Post-Training-Dataset-v2](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__Nemotron-Post-Training-Dataset-v2)

### 10am. RaviNaik — OpenThoughts3-1.2M (`sft-stem-code-openthoughts3`)

- **Stage:** SFT
- **Set:** `sft-stem-code-openthoughts3`
- **Language:** English / Math, Code, Science
- **Source:** [`open-thoughts/OpenThoughts3-1.2M`](https://huggingface.co/datasets/open-thoughts/OpenThoughts3-1.2M)
- **Licence:** `apache-2.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. Mixed question sources; no decontamination stated on the card.
- **Details and 20-row sample:** [open-thoughts__OpenThoughts3-1.2M](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/open-thoughts__OpenThoughts3-1.2M)

### 10an. RaviNaik — Nemotron-Science-v1 (`sft-science-nemotron-science`)

- **Stage:** SFT
- **Set:** `sft-science-nemotron-science`
- **Language:** English / Science
- **Source:** [`nvidia/Nemotron-Science-v1`](https://huggingface.co/datasets/nvidia/Nemotron-Science-v1)
- **Licence:** `cc-by-4.0` — Hugging Face tag read on 29 Oct 2026. A tag is not legal clearance.
- **Decision:** `TSAI reserves`
- **Our opinion:** use, check. Generated with GPT-OSS-120B (open-weight). Questions mimic GPQA style, so run a near-duplicate check against GPQA. Per TSAI, the source name goes to G9 (Evaluation) for a decontamination test; no use before that.
- **Details and 20-row sample:** [nvidia__Nemotron-Science-v1](https://github.com/RaviNaik/ERA/tree/main/v5/capstone/team10-datasets/nvidia__Nemotron-Science-v1)

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
