# AI Engineering Journey

**PDF generation contract:** The master PDF is generated from this root README plus every numbered Week README through June 30, 2027, in week order. It contains no independent curriculum content.

Cloud-first roadmap from programming fundamentals to production AI systems.

## Source-of-truth hierarchy

1. **Root README:** long-range roadmap, capacity, career path, deadline policy, phase dates, and week index.
2. **Week README:** exact daily execution plan, hours, links, and done-when gates for that week.
3. **Master PDF:** printout of the root README followed by the Week READMEs. If the PDF and repo disagree, the repo files are authoritative.

Repository:
<https://github.com/Dhawkins223/ai-engineering-journey>

## Capacity and calendar rules

**Sustainable capacity: 30 productive hours per week.**

- Tuesday through Sunday are study days.
- Monday is a fixed rest day.
- Standard full week: 6 study days x 5 hours = 30 hours.
- Time estimates are planning estimates, not deadlines.
- If a block finishes early, move to the next scheduled block.
- If a block runs long, stop at a sensible checkpoint and roll it forward.
- Never use Monday to catch up.
- Do not add courses or unrelated material to fill time.
- If sustainable capacity drops below 30 hours, extend the timeline rather than compressing the work.

Official curriculum start:

**September 15, 2026**

Detailed plan currently generated through:

**June 30, 2027**

## Academic honesty boundary

All CS50 assessment code stays in CS50's own environment:

<https://cs50.dev/>

For CS50 assessments:

- follow <https://cs50.harvard.edu/python/honesty/>
- do not publish CS50 problem-set solutions in this repository
- do not use external AI systems to suggest or complete CS50 assessment answers or code
- use CS50's own AI tools only where the course permits them

This repository contains original non-CS50 practice, original projects, notes, curriculum files, and tooling.

## Main career path

The main career plan is not a one-step jump from zero to AI Engineer.

1. Junior Software Engineer, Software Engineer I, QA Automation, Junior SDET, or scripting-oriented technical support/application support.
2. Python backend, API, application, or data-oriented software work.
3. ML-adjacent or applied-AI feature work after software and ML foundations are functional.
4. AI Engineer, Applied AI Engineer, LLM Engineer, or ML Engineer after stronger production software experience and AI-system evidence.

August to September 2027 remains an **AI application checkpoint**, not the assumed first-job outcome.

A direct AI Engineer hire as the first professional software role by that date is **low likelihood**. There is no reliable public dataset giving a clean probability for the exact cohort of people starting from zero, self-teaching for one year, having no professional software experience, and then getting hired directly into an AI Engineer title. Current AI demand is strong, but many live AI postings still ask for multiple years of software or AI experience.

Evidence sources:

- LinkedIn AI hiring research: <https://news.linkedin.com/2026/new-linkedin-research-finds-women-account-for-just-26-percent-of-ai-hires-as-ai-jobs-surge>
- LinkedIn Labor Market Report 2026: <https://economicgraph.linkedin.com/research/labor-market-report-2026>
- Stanford HAI 2026 AI Index Economy: <https://hai.stanford.edu/ai-index/2026-ai-index-report/economy>
- Stanford HAI 2026 AI Index report: <https://hai.stanford.edu/assets/files/ai_index_report_2026.pdf>

The strategy is to gain professional software experience as early as possible while continuing the AI curriculum.

## Long-range roadmap

### Phase 1 - Programming and engineering foundation
**September 15 to November 2, 2026**

Core outcomes:

- CS50P Python fundamentals
- Git and GitHub workflow
- shell/developer-tool fluency
- debugging and testing habits
- DeepLearning.AI mathematics begins in Week 3

CS50P:
<https://cs50.harvard.edu/python/>

Mathematics specialization:
<https://www.coursera.org/specializations/mathematics-for-machine-learning-and-data-science>

### Phase 2 - SQL, backend, first LLM API system
**November 3, 2026 to February 1, 2027**

Core outcomes:

- CS50 SQL and relational design
- ML mathematics completion
- HTTP, REST, FastAPI, Pydantic
- PostgreSQL application work
- API testing
- first small hosted-LLM API application
- hand-written evals, latency, cost, and failure handling

CS50 SQL:
<https://cs50.harvard.edu/sql/>

FastAPI:
<https://fastapi.tiangolo.com/tutorial/>

### Phase 3 - Applied machine learning engineering
**February 2 to April 5, 2027**

Core outcomes:

- Andrew Ng Machine Learning Specialization
- NumPy and scikit-learn practice
- preprocessing and feature engineering
- model selection and evaluation
- supervised and unsupervised learning
- end-to-end ML system

Course 1:
<https://www.coursera.org/learn/machine-learning/>

Course 2:
<https://www.coursera.org/learn/advanced-learning-algorithms/>

Course 3:
<https://www.coursera.org/learn/unsupervised-learning-recommenders-reinforcement-learning>

### Phase 4 - Deep learning with PyTorch
**April 6 to May 31, 2027**

Core outcomes:

- PyTorch tensors, data pipelines, models, autograd, optimization
- reproducible training/validation loops
- embeddings and sequence modeling
- attention/transformer building blocks
- deep-learning project checkpoint

PyTorch tutorials:
<https://docs.pytorch.org/tutorials/>

### Phase 5 - LLM engineering, retrieval, and evals
**June 1 to July 2027**

Detailed plans in this repository currently run through **June 30**.

Core outcomes by June 30:

- hosted LLM API integration
- structured output and validation
- eval-first workflow
- Hugging Face transformer/tokenizer fundamentals
- embeddings and semantic search
- RAG with source attribution
- retrieval and generation evals
- bounded tool-calling concepts
- latency, cost, and failure analysis

Hugging Face LLM course:
<https://huggingface.co/learn/llm-course/>

### Phase 6 - Agentic and production AI systems
**August to September 2027**

Core outcomes:

- tool-using agents
- MCP
- state/workflow orchestration
- human-in-the-loop patterns
- queues and asynchronous work
- model routing and fallbacks
- prompt-injection defenses
- permissions/least privilege
- AWS deployment
- monitoring, CI/CD, and reliability

This phase is a specialization layer on top of software engineering, not a substitute for it.

## MIT Missing Semester replaces LFS101

No formal LFS101 course is scheduled.

MIT Missing Semester 2026 is the Semester 1 tooling track:

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

## Weeks 8 to 14 capacity plan

Every row fits the 30-hour ceiling.

| Week | CS50 SQL | ML math | Missing Semester | Original DB project | Protected rollover/slack | Total |
| --- | ---: | ---: | ---: | ---: | ---: | ---: |
| 8 | 20h | 5h | 1h | 2h | 2h | 30h |
| 9 | 20h | 5h | 1h | 2h | 2h | 30h |
| 10 | 20h | 5h | 0h | 3h | 2h | 30h |
| 11 | 20h | 5h | 0h | 3h | 2h | 30h |
| 12 | 20h | 5h | 0h | 3h | 2h | 30h |
| 13 | 21h | 5h | 0h | 2h | 2h | 30h |
| 14 | 20h | 5h | 0h | 1h | 4h | 30h |

FastAPI and the LLM project do not compete with SQL during Weeks 8 to 14. They begin only after SQL capacity clears.

## CS50 SQL deadline and fallback

Official deadline:

**December 31, 2026 at 23:59 UTC**

Official pages:

- Problem sets: <https://cs50.harvard.edu/sql/psets/>
- Final project: <https://cs50.harvard.edu/sql/project/>
- FAQ: <https://cs50.harvard.edu/sql/faqs/>

The FAQ says:

> "best to assume the final deadline is 31 December 2026."

It also says:

> "We cannot make any exceptions to the deadlines for any reason."

The plan does not rely on a future course extension.

Internal target:

- aim to finish the SQL final project by December 18
- December 19 to 21 is internal slack
- December 22 to 30 is deadline reserve
- December 30 is the personal final submission target
- Monday December 28 remains a rest day

If SQL slips, pause new backend/LLM work and use the reserve for required SQL work first.

## Portfolio progression

1. Original Python project.
2. Original SQL/database project.
3. Production-style FastAPI/PostgreSQL backend.
4. Small LLM API application with evals.
5. End-to-end ML system.
6. Deep-learning project.
7. RAG/LLM system with retrieval, evals, sources, reliability notes, and bounded tools.
8. Later flagship production AI system with cloud deployment, observability, security, and agentic capabilities where justified.

CS50 assessment code is never a public portfolio project.

## Detailed week index through June 30, 2027

| Week | Dates | Daily plan |
| --- | --- | --- |
| 1 | Sep 15 to Sep 21, 2026 | [Week 1 daily plan](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-01/README.md) |
| 2 | Sep 22 to Sep 28, 2026 | [CS50P Loops and Exceptions, command-line environment, original Python practice](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-02/README.md) |
| 3 | Sep 29 to Oct 5, 2026 | [CS50P Libraries, Git branches/diff/GitHub workflow, linear algebra begins](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-03/README.md) |
| 4 | Oct 6 to Oct 12, 2026 | [CS50P Unit Tests, pytest thinking, linear algebra, debugging/profiling](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-04/README.md) |
| 5 | Oct 13 to Oct 19, 2026 | [CS50P File I/O, linear algebra completion, Git/version-control depth](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-05/README.md) |
| 6 | Oct 20 to Oct 26, 2026 | [CS50P Regular Expressions and OOP start, calculus begins, packaging/shipping](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-06/README.md) |
| 7 | Oct 27 to Nov 2, 2026 | [CS50P OOP, Et Cetera, final project, calculus, agentic coding lecture](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-07/README.md) |
| 8 | Nov 3 to Nov 9, 2026 | [CS50 SQL Querying + calculus + Beyond the Code](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-08/README.md) |
| 9 | Nov 10 to Nov 16, 2026 | [CS50 SQL Relating + calculus completion + Code Quality](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-09/README.md) |
| 10 | Nov 17 to Nov 23, 2026 | [CS50 SQL Designing + probability/statistics](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-10/README.md) |
| 11 | Nov 24 to Nov 30, 2026 | [CS50 SQL Writing + probability/statistics](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-11/README.md) |
| 12 | Dec 1 to Dec 7, 2026 | [CS50 SQL Viewing + probability/statistics](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-12/README.md) |
| 13 | Dec 8 to Dec 14, 2026 | [CS50 SQL Optimizing + probability/statistics](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-13/README.md) |
| 14 | Dec 15 to Dec 21, 2026 | [CS50 SQL Scaling + final project + math completion](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-14/README.md) |
| 15 | Dec 22 to Dec 28, 2026 | [SQL deadline reserve first; FastAPI begins only if SQL is complete](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-2/week-15/README.md) |
| 16 | Dec 29 to Jan 4, 2027 | [Final SQL deadline protection, then backend foundations](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-2/week-16/README.md) |
| 17 | Jan 5 to Jan 11, 2027 | [FastAPI routes, validation, PostgreSQL, testing](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-2/week-17/README.md) |
| 18 | Jan 12 to Jan 18, 2027 | [FastAPI dependencies, security basics, PostgreSQL, first LLM API orientation](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-2/week-18/README.md) |
| 19 | Jan 19 to Jan 25, 2027 | [Small LLM API application, structured responses, hand-written evals](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-2/week-19/README.md) |
| 20 | Jan 26 to Feb 1, 2027 | [Complete Phase 2 backend + LLM project](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-2/week-20/README.md) |
| 21 | Feb 2 to Feb 8, 2027 | [Machine Learning Specialization Course 1 - Introduction to ML and linear regression](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-3/week-21/README.md) |
| 22 | Feb 9 to Feb 15, 2027 | [Machine Learning Specialization Course 1 - Multiple linear regression and feature engineering](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-3/week-22/README.md) |
| 23 | Feb 16 to Feb 22, 2027 | [Machine Learning Specialization Course 1 - Classification and regularization](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-3/week-23/README.md) |
| 24 | Feb 23 to Mar 1, 2027 | [Machine Learning Specialization Course 2 - Neural networks](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-3/week-24/README.md) |
| 25 | Mar 2 to Mar 8, 2027 | [Machine Learning Specialization Course 2 - Neural network training](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-3/week-25/README.md) |
| 26 | Mar 9 to Mar 15, 2027 | [Machine Learning Specialization Course 2 - Applying ML, bias/variance, error analysis](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-3/week-26/README.md) |
| 27 | Mar 16 to Mar 22, 2027 | [Machine Learning Specialization Course 2 - Decision trees and ensembles](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-3/week-27/README.md) |
| 28 | Mar 23 to Mar 29, 2027 | [Machine Learning Specialization Course 3 - Unsupervised learning and recommenders](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-3/week-28/README.md) |
| 29 | Mar 30 to Apr 5, 2027 | [Machine Learning Specialization completion + end-to-end ML system](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-3/week-29/README.md) |
| 30 | Apr 6 to Apr 12, 2027 | [PyTorch foundations - quickstart and tensors](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-4/week-30/README.md) |
| 31 | Apr 13 to Apr 19, 2027 | [PyTorch data pipeline - Datasets, DataLoaders, transforms](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-4/week-31/README.md) |
| 32 | Apr 20 to Apr 26, 2027 | [PyTorch models and autograd](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-4/week-32/README.md) |
| 33 | Apr 27 to May 3, 2027 | [PyTorch optimization and model persistence](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-4/week-33/README.md) |
| 34 | May 4 to May 10, 2027 | [Deep learning project - training loop, baselines, validation](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-4/week-34/README.md) |
| 35 | May 11 to May 17, 2027 | [Embeddings and NLP fundamentals](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-4/week-35/README.md) |
| 36 | May 18 to May 24, 2027 | [Attention and transformer building blocks](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-4/week-36/README.md) |
| 37 | May 25 to May 31, 2027 | [Deep learning capstone checkpoint](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-4/week-37/README.md) |
| 38 | Jun 1 to Jun 7, 2027 | [LLM engineering foundations - hosted API, structured outputs, eval-first workflow](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-5/week-38/README.md) |
| 39 | Jun 8 to Jun 14, 2027 | [Hugging Face transformers - model/tokenizer usage and transformer concepts](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-5/week-39/README.md) |
| 40 | Jun 15 to Jun 21, 2027 | [Embeddings, datasets, semantic search, and retrieval foundations](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-5/week-40/README.md) |
| 41 | Jun 22 to Jun 28, 2027 | [RAG integration, grounding, tool calling boundaries, and evals](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-5/week-41/README.md) |
| 42 | Jun 29 to Jul 5, 2027 | [June closeout - consolidate the production LLM/RAG system before July](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/phase-5/week-42/README.md) |

## Employment checkpoints

### Foundation checkpoint

- software internships and apprenticeships
- Junior Software Engineer / Software Engineer I
- QA Automation / Junior SDET
- scripting-oriented technical support or application support

### Backend checkpoint

- Python backend roles
- API/application engineering roles
- junior data/backend roles

### ML-adjacent checkpoint

- applied ML software roles
- ML-adjacent engineering roles
- data/ML roles where actual requirements fit

### AI checkpoint, August to September 2027

Apply selectively to AI Engineer, Applied AI Engineer, AI Software Engineer, LLM Engineer, and suitable ML Engineer roles if the production portfolio and interview competency support it.

The main strategy remains: get professional software experience as early as possible, then move toward AI engineering.
