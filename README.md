# AI Engineering Journey

**PDF generation contract:** The master PDF is a generated printout of this root README followed by the current Week README. It contains no independent curriculum content.

Cloud-first roadmap from programming fundamentals to production AI systems.

## Source-of-truth hierarchy

This repository has one source of truth at each level:

1. Root README: long-range roadmap, career path, dates, capacity, deadline policy, and phase-level allocation.
2. Week README: the detailed daily execution plan for that week.
3. Master PDF: a generated printout of the root README followed by the current Week README. The PDF contains no independent curriculum content.

Current detailed week:
[Semester 1 Week 1](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-01/README.md)

Repository:
<https://github.com/Dhawkins223/ai-engineering-journey>

## Capacity and calendar rules

Sustainable study capacity:

**30 productive hours per week**

Cadence:

- Tuesday through Sunday are study days.
- Monday is a fixed rest day.
- Time estimates are planning estimates, not deadlines.
- If a block finishes early, move to the next scheduled block.
- If a block runs long, stop at a sensible checkpoint and roll the unfinished work forward.
- Do not use Monday to catch up.
- Do not add extra courses or material just because time remains.
- If sustained capacity later drops below 30 hours, extend the timeline rather than compressing the work.

Official curriculum start:

**September 15, 2026**

## Academic honesty boundary

All CS50 assessment code stays in CS50's own environment:

<https://cs50.dev/>

This public repository contains only original non-CS50 practice, original projects, notes, curriculum files, and tooling.

For CS50 assessments:

- follow the official academic honesty policy: <https://cs50.harvard.edu/python/honesty/>
- do not publish CS50 problem-set solutions in this repository
- do not use external AI systems to suggest or complete CS50 assessment answers or code
- use CS50's own AI tools only where the course permits them

## Career path

The primary career path is not "zero to AI Engineer in one jump."

The main ladder is:

1. Junior Software Engineer, Software Engineer I, QA Automation, Junior SDET, or technical support engineering with scripting.
2. Python backend, API, application, or data-oriented software work.
3. ML-adjacent or applied-AI feature work once software and ML foundations are functional.
4. AI Engineer, Applied AI Engineer, LLM Engineer, or ML Engineer after production software experience and stronger AI-system evidence.

The curriculum still builds toward AI engineering from the start, but the first professional role does not need to carry an AI title.

## Hiring realism for August to September 2027

Assessment:

**A direct AI Engineer hire as a first professional software role by August to September 2027 is low likelihood.**

I am not assigning a numeric probability because I could not find a reliable public dataset that tracks the exact cohort: people starting from zero, self-taught or newly trained, with no professional software experience, and then measures direct AI Engineer hiring within one year.

Evidence that pushes the estimate down:

- Stanford's 2026 AI Index reports that employment for software developers ages 22 to 25 fell nearly 20% from 2024, indicating a difficult early-career software market.
- LinkedIn's 2026 labor-market reporting says entry-level hiring remains weak even while AI roles continue to grow.
- A current convenience sample of seven live AI or applied-AI postings checked on September 16, 2026 found that six required at least 3 years of relevant professional experience, four required 5 or more years, and one listed 1 to 3 years. This is not a representative sample, but it shows that experience requirements are common while some lower-experience openings do exist.

Evidence that keeps the path worth pursuing:

- LinkedIn reports that U.S. AI job postings roughly doubled since 2023 and that AI Engineer is now the most common AI role on LinkedIn.
- Stanford reports strong growth in employer demand for Python, cloud, scalability, workflow management, generative AI, and agentic-system skills.

What remains unknown:

- There is no trustworthy public conversion rate from one year of self-study to AI Engineer employment.
- Job-title definitions vary substantially across employers.
- Portfolio quality, internships, contract work, networking, location, interview performance, and whether professional software experience is gained during the year can materially change the outcome.

Therefore, August to September 2027 remains an **AI application checkpoint**, not the base-case first job outcome. The base-case career strategy is to gain professional software or backend experience as early as possible, then move into ML-adjacent and AI-engineering work.

Evidence sources:

- LinkedIn, AI jobs and hiring, August 2026: <https://news.linkedin.com/2026/new-linkedin-research-finds-women-account-for-just-26-percent-of-ai-hires-as-ai-jobs-surge>
- LinkedIn, Labor Market Report 2026: <https://economicgraph.linkedin.com/research/labor-market-report-2026>
- Stanford HAI, 2026 AI Index Economy: <https://hai.stanford.edu/ai-index/2026-ai-index-report/economy>
- Stanford HAI, AI jobs chapter: <https://hai.stanford.edu/assets/files/ai_index_report_2026.pdf>

Current posting sample used only as directional evidence:

- ScaleTech AI Engineer, 5+ years software engineering: <https://jobs.lever.co/scale3c/813b5aeb-dadf-4926-9205-1e26290b8c82>
- BLEN AI Engineer, 5+ years professional software engineering: <https://jobs.lever.co/blencorp/4b2e3689-9720-4785-b0fe-d09bd5325f74>
- United Tech AI Engineer, 5+ years production Python: <https://jobs.lever.co/vacancies/37272803-0eba-49a4-93bd-5de6be83dd6b>
- RYZ Labs Full Stack AI Engineer, 5+ years: <https://jobs.lever.co/RyzLabs/8660eb6d-8f82-4602-8e04-de8cd3a4fd44>
- CYE Senior AI Engineer, 3+ years dedicated AI development: <https://jobs.lever.co/CYE/ba6f695a-5512-4fcb-bcb0-aa7d42c9c6c4>
- Simbe Applied AI Engineer, 3+ years related technical experience: <https://jobs.lever.co/SimbeRobotics/1460bcbc-984d-44c7-b638-9718a6dc1681>
- Xsolla Full Stack AI Engineer / Applied AI Engineer, 1 to 3 years full-stack experience: <https://jobs.lever.co/xsolla/ebb74747-c739-4247-bafc-a088c10fa643>

## Long-range roadmap

### Phase 1: Programming and engineering foundation
**September 15 to November 2, 2026**

Core outcomes:

- Python fundamentals through CS50P
- basic Git and GitHub workflow
- shell and developer-tool fluency
- debugging and testing habits
- practical ML mathematics begins in Week 3

CS50P:
<https://cs50.harvard.edu/python/>

### Phase 2: SQL, ML theory, backend foundations, and first LLM API system
**November 3, 2026 to January 31, 2027**

The work is parallel, but capacity is protected.

During November and most of December, CS50 SQL and ML mathematics get priority.

FastAPI and the small LLM API project begin only when SQL capacity clears, expected in late December if SQL is on schedule. They do not compete with the SQL deadline.

Phase 2 outcomes:

- relational database design and SQL
- continued probability, statistics, linear algebra, and optimization
- HTTP and REST
- FastAPI and Pydantic
- PostgreSQL application work
- one small hosted-LLM API application
- structured outputs where appropriate
- a small hand-written eval set
- basic latency, cost, and error-handling measurements

CS50 SQL:
<https://cs50.harvard.edu/sql/>

FastAPI:
<https://fastapi.tiangolo.com/tutorial/>

### Phase 3: Applied machine learning engineering
**February to March 2027**

Core outcomes:

- NumPy
- Pandas
- scikit-learn
- data cleaning and feature engineering
- train, validation, and test discipline
- cross-validation
- model evaluation
- model serving through an API
- an end-to-end ML project

### Phase 4: Deep learning
**April to May 2027**

Core outcomes:

- PyTorch
- tensors and dataloaders
- neural networks
- training and validation loops
- embeddings
- attention
- transformer fundamentals

PyTorch tutorials:
<https://docs.pytorch.org/tutorials/>

### Phase 5: LLM engineering, retrieval, and evals
**June to July 2027**

Core outcomes:

- LLM APIs
- Hugging Face Transformers
- embeddings and vector search
- retrieval-augmented generation
- structured outputs and tool calling
- grounding
- eval datasets and regression evals
- tracing and observability
- latency and cost measurement

Hugging Face LLM course:
<https://huggingface.co/learn/llm-course/>

### Phase 6: Agentic and production AI systems
**August to September 2027**

Core outcomes:

- tool-using agents
- MCP
- state and workflow orchestration
- human-in-the-loop patterns
- queues and asynchronous work
- model routing and fallbacks
- prompt-injection defenses
- permissions and least privilege
- AWS deployment
- monitoring and CI/CD
- production reliability

This phase is a specialization layer on top of software engineering, not a substitute for it.

## MIT Missing Semester replaces LFS101

The formal Linux Foundation LFS101 course is removed.

MIT Missing Semester 2026 is the tooling and shell track for Semester 1:

| Week | Lecture | Direct link |
| --- | --- | --- |
| 1 | Course Overview + Introduction to the Shell | <https://missing.csail.mit.edu/2026/course-shell/> |
| 2 | Command-line Environment | <https://missing.csail.mit.edu/2026/command-line-environment/> |
| 3 | Development Environment and Tools | <https://missing.csail.mit.edu/2026/development-environment/> |
| 4 | Debugging and Profiling | <https://missing.csail.mit.edu/2026/debugging-profiling/> |
| 5 | Version Control and Git | <https://missing.csail.mit.edu/2026/version-control/> |
| 6 | Packaging and Shipping Code | <https://missing.csail.mit.edu/2026/shipping-code/> |
| 7 | Agentic Coding | <https://missing.csail.mit.edu/2026/agentic-coding/> |
| 8 | Beyond the Code | <https://missing.csail.mit.edu/2026/beyond-code/> |
| 9 | Code Quality | <https://missing.csail.mit.edu/2026/code-quality/> |

No additional Linux course is scheduled in Semester 1.

## Weeks 8 to 14 capacity plan

Every row fits the 30-hour weekly ceiling.

FastAPI and the LLM project are intentionally absent from Weeks 8 to 14 unless SQL finishes early. This is the correction for the previous overload.

| Week | Dates | CS50 SQL | ML math / statistics | Missing Semester | Deadline slack / rollover | Total |
| --- | --- | ---: | ---: | ---: | ---: | ---: |
| 8 | Nov 3-9 | 19h | 8h | 1h | 2h | 30h |
| 9 | Nov 10-16 | 19h | 8h | 1h | 2h | 30h |
| 10 | Nov 17-23 | 20h | 8h | 0h | 2h | 30h |
| 11 | Nov 24-30 | 20h | 8h | 0h | 2h | 30h |
| 12 | Dec 1-7 | 20h | 8h | 0h | 2h | 30h |
| 13 | Dec 8-14 | 21h | 7h | 0h | 2h | 30h |
| 14 | Dec 15-21 | 20h | 6h | 0h | 4h | 30h |

The SQL sequence is Querying, Relating, Designing, Writing, Viewing, Optimizing, Scaling, then the final project. The 19 to 21 hours allocated to SQL are course-wide weekly budgets, not promises that every unit will take the same amount of time.

## CS50 SQL deadline and fallback

Current official deadline:

**December 31, 2026 at 23:59 UTC**

In U.S. Eastern Time on that date, this is **6:59 PM EST**.

Official problem-set deadline page:
<https://cs50.harvard.edu/sql/psets/>

Official final-project page:
<https://cs50.harvard.edu/sql/project/>

Official FAQ:
<https://cs50.harvard.edu/sql/faqs/>

The current FAQ says:

> "best to assume the final deadline is 31 December 2026."

It also says:

> "We cannot make any exceptions to the deadlines for any reason."

The FAQ says that if the course is extended, work completed in 2026 can carry into 2027. An extension is not guaranteed, so this plan does not rely on it.

Internal SQL target:

- Week 14 ends December 21.
- Target the final project for completion by December 18 when progress allows.
- December 19 to 21 is internal course slack.
- December 22 to 30 is a deadline reserve. At the normal Tuesday-through-Sunday cadence, this creates up to 40 additional study hours before the official deadline while still preserving Monday rest.

Fallback if SQL slips:

1. Pause FastAPI, LLM API work, and any other Phase 2 implementation that has not already begun.
2. Use the December 22 to 30 reserve exclusively for unfinished required CS50 SQL work.
3. Do not use Monday December 28.
4. Treat December 30 as the personal submission deadline to avoid relying on the final hours of December 31.
5. If required work remains after the official deadline, do not assume late submissions will be accepted. Check the current CS50 SQL FAQ and Gradebook.
6. If CS50 formally extends the course, continue under the published extension policy. If it does not, the roadmap continues with the underlying SQL skills, but the plan does not pretend the certificate can still be completed late.

## Portfolio progression

The portfolio should show increasing production depth:

1. Original Python project.
2. Original SQL/database project.
3. Production-style FastAPI/PostgreSQL backend.
4. Small LLM API application with evals.
5. End-to-end ML system.
6. Flagship production AI system with retrieval, tools, evals, observability, security, and cloud deployment.

CS50 assessment code is never a public portfolio project.

## Employment checkpoints

These are competency checkpoints, not guarantees.

### Foundation checkpoint
Start applying to:

- software internships and apprenticeships
- Junior Software Engineer / Software Engineer I where requirements fit
- QA Automation / Junior SDET
- scripting-oriented technical support or application support

### Backend checkpoint
Add:

- Python backend roles
- API and application engineering roles
- junior data/backend roles

### ML-adjacent checkpoint
Add:

- applied ML software roles
- ML-adjacent engineering roles
- data/ML engineering roles where the requirements match actual experience

### AI checkpoint, August to September 2027
Apply selectively to AI Engineer, Applied AI Engineer, AI Software Engineer, LLM Engineer, and suitable ML Engineer roles if the production portfolio and interview competency are there.

The main strategy remains: get professional software experience as early as possible, then move toward AI engineering.
