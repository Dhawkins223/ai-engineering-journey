# Phase 5 Week 40 Daily Plan

**Week:** June 15, 2027 to June 21, 2027  
**Study target:** 30 productive hours  
**Study days:** Tuesday through Sunday  
**Monday:** fixed rest day

**Primary focus:** Embeddings, datasets, semantic search, and retrieval foundations

Long-range roadmap:
<https://github.com/Dhawkins223/ai-engineering-journey/blob/main/README.md>

## Execution rules

- All time blocks are estimates.
- If a block's "done when" condition is met early, move to the next scheduled block.
- If time expires first, stop at a sensible checkpoint, record what remains, and roll it forward.
- Monday is never a catch-up day.
- Do not add courses or unrelated material to fill time.
- Rollover work from the previous week takes priority over new work.
- Original code belongs in the repository Codespace: <https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>
- CS50 assessment code stays only in <https://cs50.dev/> and follows <https://cs50.harvard.edu/python/honesty/>.

## Tuesday, June 15, 2027 - 5 hours

### Embeddings API reference - 180 minutes estimated

Open:
<https://developers.openai.com/api/reference/ruby/resources/embeddings/methods/create>

Learn how embeddings are created and what they represent.

Done when:

- a small batch of text is embedded successfully
- vector dimensions and basic similarity purpose are understood

### Retrieval dataset setup - 120 minutes estimated

Open:
<https://huggingface.co/learn/llm-course/chapter5/1>

Use Hugging Face Datasets concepts to prepare a small document corpus for retrieval.

Done when:

- the corpus loads reproducibly
- documents have stable source IDs

## Wednesday, June 16, 2027 - 5 hours

### Hugging Face Datasets Chapter 5 - 180 minutes estimated

Open:
<https://huggingface.co/learn/llm-course/chapter5/1>

Work through the scheduled datasets material relevant to retrieval.

Done when:

- the assigned section is complete

### Chunking experiment - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Create and compare at least two simple chunking strategies on the small corpus.

Done when:

- chunks preserve source IDs
- tradeoffs are documented

## Thursday, June 17, 2027 - 5 hours

### Semantic search with FAISS - 180 minutes estimated

Open:
<https://huggingface.co/learn/llm-course/chapter5/6>

Work through the semantic-search section.

Done when:

- a semantic search over the sample corpus returns results

### Retrieval eval cases - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Create hand-written queries with expected source documents.

Done when:

- at least 10 retrieval cases exist with expected relevant source IDs

## Friday, June 18, 2027 - 5 hours

### Embedding + retrieval integration - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Connect embeddings to the original project without adding generation yet.

Done when:

- query -> retrieved chunks works end to end

### Retrieval metrics / inspection - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Measure simple hit/recall-style retrieval success over the hand-written cases.

Done when:

- results are recorded without claiming more than the small eval supports

## Saturday, June 19, 2027 - 5 hours

### Retrieval failure analysis - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Inspect misses and categorize causes such as chunking, wording, or corpus gaps.

Done when:

- at least three failure categories are documented

### Controlled iteration - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Change one retrieval variable and rerun the same cases.

Done when:

- before/after results are recorded

## Sunday, June 20, 2027 - 5 hours

### Week 40 retrieval checkpoint - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Rebuild the retrieval index from scratch and rerun evals.

Done when:

- the retrieval pipeline is reproducible

### Documentation - 120 minutes estimated

Open:
<https://github.com/Dhawkins223/ai-engineering-journey>

Document corpus, chunking, embedding model/API, search method, and known limits.

Done when:

- the README matches the implementation

## Monday, June 21, 2027 - fixed rest day

**0 study hours.**

Do not use Monday for catch-up. Any unfinished work becomes the first priority on Tuesday.

## Weekly completion gate

1. A reproducible embedding/retrieval pipeline exists.
2. Retrieval has its own hand-written eval cases.
3. Source IDs are preserved through retrieval.
4. Changes are evaluated against the same cases.

