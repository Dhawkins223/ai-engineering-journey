# Phase 5 Week 42 Daily Plan

**Week:** June 29, 2027 to July 5, 2027  
**Study target:** 10 productive hours  
**Study days:** Tuesday through Sunday  
**Monday:** fixed rest day

**Primary focus:** June closeout - consolidate the production LLM/RAG system before July

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

## Tuesday, June 29, 2027 - 5 hours

### June regression run - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Run the complete test, retrieval-eval, and generation-eval suites on the current June system.

Done when:

- all suites run from a clean environment
- failures are saved and categorized

### Reliability backlog - 120 minutes estimated

Open:
<https://github.com/Dhawkins223/ai-engineering-journey>

Convert observed failures into a prioritized July backlog. Do not add new July material yet.

Done when:

- the backlog is ranked by impact and evidence

## Wednesday, June 30, 2027 - 5 hours

### June architecture checkpoint - 180 minutes estimated

Open:
<https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=1360636553>

Verify API -> retrieval -> model -> bounded tools -> structured output -> source attribution.

Done when:

- the full path works on representative cases
- trust boundaries and failure paths are clear

### June portfolio update - 120 minutes estimated

Open:
<https://github.com/Dhawkins223/ai-engineering-journey>

Update the project README with what actually works as of June 30.

Done when:

- the README includes architecture, eval method, current results, limitations, latency/cost notes, and next risks

## Plan boundary

This master plan currently stops on June 30, 2027. The remaining days of this calendar week belong to the July continuation and are not scheduled in this document.

## Weekly completion gate

1. June's LLM/RAG system is reproducible.
2. Tests and evals run from a clean environment.
3. Known failures are explicitly recorded.
4. The portfolio documentation reflects the actual system as of June 30.

