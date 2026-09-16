# Phase 5 Week 41 Daily Plan

**Week:** June 22, 2027 to June 28, 2027  
**Study target:** 30 productive hours  
**Study days:** Tuesday through Sunday  
**Monday:** fixed rest day

**Primary focus:** RAG integration, grounding, tool calling boundaries, and evals

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

## Tuesday, June 22, 2027 - 5 hours

### RAG integration - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Feed retrieved context into the LLM application while preserving source IDs.

Done when:

- query -> retrieve -> generate works end to end

### Grounding eval design - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Add cases that check whether answers are supported by retrieved context.

Done when:

- at least 10 grounding cases exist

## Wednesday, June 23, 2027 - 5 hours

### Citations/source attribution - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Return source references tied to retrieved chunks.

Done when:

- responses expose the source IDs actually used

### Grounding review - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Manually inspect a fixed sample for unsupported statements.

Done when:

- unsupported statements are logged, not hidden

## Thursday, June 24, 2027 - 5 hours

### Tool/function calling reference - 180 minutes estimated

Open:
<https://developers.openai.com/api/reference/cli/resources/responses/methods/create>

Study tool/function calling capabilities only far enough to understand controlled tool use.

Done when:

- you can describe the request/tool/result loop
- no unnecessary autonomous agent framework is introduced

### One bounded tool - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Add one safe, deterministic tool to the app if it materially helps the use case.

Done when:

- the tool has explicit input validation and a narrow permission boundary

## Friday, June 25, 2027 - 5 hours

### RAG regression eval - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Run retrieval and generation evals after integration.

Done when:

- results for retrieval and generation are both stored

### Latency/cost profiling - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Measure the added retrieval/generation latency and cost on representative cases.

Done when:

- representative measurements are documented

## Saturday, June 26, 2027 - 5 hours

### Failure handling - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Handle no-result retrieval, malformed input, provider failure, and tool failure.

Done when:

- each failure path returns controlled behavior

### Security review - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Review what user content can influence and what the model/tool is allowed to access.

Done when:

- trust boundaries and prohibited actions are written

## Sunday, June 27, 2027 - 5 hours

### Week 41 project checkpoint - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Run tests and evals from a clean environment.

Done when:

- the RAG application reproduces end to end

### Documentation and rollover - 120 minutes estimated

Open:
<https://github.com/Dhawkins223/ai-engineering-journey>

Update README and roll only unfinished assigned work.

Done when:

- sources, evals, cost/latency, and known failures are documented

## Monday, June 28, 2027 - fixed rest day

**0 study hours.**

Do not use Monday for catch-up. Any unfinished work becomes the first priority on Tuesday.

## Weekly completion gate

1. RAG works end to end with source attribution.
2. Retrieval and generation are evaluated separately.
3. At least one bounded tool is understood or implemented only if justified.
4. Failure and permission boundaries are explicit.

