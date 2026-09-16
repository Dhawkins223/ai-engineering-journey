# Phase 5 Week 38 Daily Plan

**Week:** June 1, 2027 to June 7, 2027  
**Study target:** 30 productive hours  
**Study days:** Tuesday through Sunday  
**Monday:** fixed rest day

**Primary focus:** LLM engineering foundations - hosted API, structured outputs, eval-first workflow

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

## Tuesday, June 1, 2027 - 5 hours

### Hosted LLM API - Responses - 180 minutes estimated

Open:
<https://developers.openai.com/api/reference/cli/resources/responses/methods/create>

Read the current API reference and make a minimal original call from the Phase 2 application.

Done when:

- one request succeeds
- input/output handling is explicit

### LLM project boundary - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Define one narrow capability for the June LLM project and a small hand-written eval set before expanding features.

Done when:

- the use case and non-goals are written
- at least 10 eval cases exist

## Wednesday, June 2, 2027 - 5 hours

### Structured output / validation - 180 minutes estimated

Open:
<https://developers.openai.com/api/reference/cli/resources/responses/methods/create>

Use schema-constrained or explicitly validated output where the application needs structure.

Done when:

- one endpoint returns validated structured data
- invalid output is handled

### Eval harness - 120 minutes estimated

Open:
<https://developers.openai.com/api/reference/java/resources/evals/methods/create>

Implement a small repeatable evaluation harness or equivalent test runner for the hand-written cases.

Done when:

- the eval cases run repeatedly and produce stored results

## Thursday, June 3, 2027 - 5 hours

### Error handling and retries - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Add bounded error handling for API failures, invalid responses, and timeouts.

Done when:

- failure paths do not crash the whole app
- retry behavior is bounded and documented

### Cost and latency measurement - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Record request latency and token/cost information available from the API.

Done when:

- at least one representative run has latency and cost recorded

## Friday, June 4, 2027 - 5 hours

### Prompt/context iteration - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Improve the system instructions/context only against the eval set, not anecdotes.

Done when:

- a before/after eval comparison is recorded
- changes are tied to observed failure cases

### Regression tests - 120 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Turn important deterministic boundaries into normal tests.

Done when:

- tests cover validation, error paths, and parsing

## Saturday, June 5, 2027 - 5 hours

### LLM API project integration - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Integrate the current capability into the existing backend cleanly.

Done when:

- the endpoint works end to end

### Evaluation review - 120 minutes estimated

Open:
<https://developers.openai.com/api/reference/java/resources/evals/methods/create>

Review failures and categorize them without hiding poor cases.

Done when:

- failure categories and next actions are documented

## Sunday, June 6, 2027 - 5 hours

### Week 38 project checkpoint - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Rerun tests, evals, and a representative API request from a clean environment.

Done when:

- the project can be reproduced

### Rollover / documentation - 120 minutes estimated

Open:
<https://github.com/Dhawkins223/ai-engineering-journey>

Finish assigned work only and update the README.

Done when:

- the README explains capability, eval method, known failures, cost, and latency

## Monday, June 7, 2027 - fixed rest day

**0 study hours.**

Do not use Monday for catch-up. Any unfinished work becomes the first priority on Tuesday.

## Weekly completion gate

1. The hosted LLM API is integrated into original software.
2. A repeatable eval set exists before adding RAG.
3. Latency, cost, and known failure modes are documented.
4. No API key is committed.

