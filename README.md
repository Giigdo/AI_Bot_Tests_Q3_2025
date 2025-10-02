# AI_Bot_Tests_Q3_2025
Data sets for AI bot tests responding to Anishinaabemowin summer of 2025. Includes CSV data of word and phrase translation accross 5 bots and conversations with 3 LLM Chat Bots in Anishinaabemowin.

## License and Citation
This dataset is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

### How to Cite
If you use this data in your research, please cite:

McConnell, A., & Ly, J. (2025). Anishinaabemowin AI Translation Tool Evaluation Dataset [Data set]. GitHub. https://github.com/[your-username]/[repo-name]

### Associated Publications
This data supports the following research:
- McConnell, A., & Ly, J. (2025). "Beyond Universal AI: Developing Culturally-Specific Intelligence Tests for Indigenous Language Technologies." Connected Minds 2025, Toronto, ON.

# Anishinaabemowin AI Translation Tool Evaluation Dataset

**Authors:** Andrew McConnell & Jasmine Ly  
**Institution:** York University, Digital Media PhD Program  
**Conference:** Connected Minds 2025, Toronto, ON (October 6-8, 2025)

## Overview

This repository contains the complete dataset from systematic testing of AI translation tools for Anishinaabemowin (Ojibwe language). The research is an initial evaluation of the efficacy, accuracy, and cultural appropriateness of commercially available AI systems for Indigenous language education.

## Research Context

With a 4% decline in Indigenous language speakers from 1991-2021 (Statistics Canada), and one-third of speakers having learned as a second language, AI language tools hold promise for supporting learners—particularly those in off-reserve locations with limited access to fluent speakers. However, the trustworthiness and accuracy of these tools is critical for effective language preservation and revitalization.

## Dataset Contents

### Phase 1: Comparative Tool Analysis
- **`2025-08-12-14 Ojibwe Translation Tests *.csv`** 4 files - Results from testing 5 AI tools with 17 Anishinaabemowin words and 2 complex sentences
- **Methodology:** Structured documentation with validation against print and online Anishinaabemowin dictionaries
- **Tools tested:** AnythingTranslate, Musely.ai, Ojibwechat, ChatGPT Indigenous Language Supporter, Claude.ai Pro
- **Timeline:** 3 days of testing at random intervals by 2 researchers

### Phase 2: Guardrail Development
- **`AI TEST 2025-08-17 JSON File.md`** - Cultural protocol guardrails for Indigenous language AI in JSON format
- **`AI TEST 2025-08-17 JSON **.md`** - 4 files - Results from testing JSON-controlled conversations in Claude, Chat GPT and Perplexity
- **Focus:** Bilingual response formats (Anishinaabemowin first, English in brackets), gentle correction methodologies, community authority deference

### Phase 3: Open Conversation Testing
- **`AI TEST***.md`** - 4 files - Results from "cold start" conversations without guardrails
- **Systems tested:** Perplexity, ChatGPT Indigenous Language Bot, Claude.ai
- **Analysis:** Error types, consistency patterns, learning risks for novice speakers

### Supporting Documentation
- **`methodology.md`** - Detailed testing protocols and validation procedures

## Key Findings

### Tool Performance Summary
- **AnythingTranslate & Musely.ai:** Completely unreliable, different translations each query
- **ChatGPT, Claude.ai and Perplexity:** Best overall, but demonstrated grammatical understanding but consistent word stem errors
- **Ojibwechat:** Demonstrated some understanding but produced gramatical errors and defaults to translation
- **All systems:** Exhibited errors requiring fluent speaker verification

### Translation Error Example
**English:** "stop walking"  
**AI Translation (ChatGPT):** "gego bimosen" ❌ (means "don't walk")  
**Correct Translation:** "boon bimosen" ✓ (means "stop walking")

This demonstrates English-based reasoning (negation vs. cessation) that poses learning risks.

### JSON Guardrail Promise
Successfully enforced culturally appropriate behaviors including bilingual formats and gentle correction methods, but underlying word accuracy issues persist.

## Research Implications

### Risk Assessment
- **Highest Risk:** Beginner learners without fluent speaker access (cannot verify outputs)
- **Moderate Risk:** Intermediate learners with occasional verification capability  
- **Lowest Risk:** Advanced learners with regular community speaker access

### Educational Impact
AI systems are high-risk for isolated learners who may internalize errors as correct language patterns. Current tools require intensive community oversight and systematic verification protocols.

## Related Publications

This dataset supports the following research:

**McConnell, A., & Ly, J. (2025).** "Anishinaabemowin Aabajichigan Gaawiin Nibwaakaasii (Efficacy of AI for Ojibwe Language Education)" *Connected Minds 2025*, Toronto, ON, October 6-8, 2025.

**Conference Poster:** [Link to poster PDF when available]

## How to Use This Data

### For Researchers
- Evaluate AI translation tool effectiveness for Indigenous languages
- Develop culturally appropriate AI evaluation frameworks
- Study patterns in AI language learning risks

### For Educators
- Assess which tools (if any) are safe for classroom use
- Understand error patterns to correct post-use
- Develop verification protocols with fluent speakers

### For Indigenous Communities
- Validate AI tools before adoption in language programs
- Inform community-controlled AI development
- Support data sovereignty in language revitalization

## Methodology

### Testing Protocol
1. **Standardized word/phrase list:** 17 words + 2 complex sentences
2. **Multiple researchers:** Cross-validation of results
3. **Dictionary verification:** Comparison against authoritative Anishinaabemowin sources
4. **Systematic documentation:** Consistency tracking in intial tests to demonstrate all models have errors
5. **Iterative testing:** Multiple queries to assess consistency

### Cultural Protocols
Research conducted with respect for Indigenous knowledge systems and in support of language revitalization efforts. Testing focused on publicly available AI tools to assess community safety. No traditional knowledge used or shared with the AI. Worked exclusively with the language data the LLM already possessed.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

**You are free to:**
- Share — copy and redistribute the material
- Adapt — remix, transform, and build upon the material

**Under the following terms:**
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.

See `LICENSE` file for full license text.

## Citation

If you use this dataset in your research, please cite: