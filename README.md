# AI Engineering Journey

**PDF generation contract:** The master PDF contains only this root README, the frozen current Week 1 README, and the detailed Week 2 README. The rolling outline is intentionally not printed in the PDF.

Cloud-first roadmap from programming fundamentals to production AI systems.

## Source-of-truth hierarchy

1. **Root README:** long-range roadmap, hiring evidence, cost policy, deadlines, and rolling-plan rules.
2. **Current-week README:** exact daily execution plan.
3. **Next-week README:** exact daily execution plan prepared from the rolling outline.
4. **PLAN_OUTLINE.md:** single-file outline for all later weeks. It is not a set of prewritten daily plans.
5. **Master PDF:** printout of the root README + current week + next week only.

Week 1 is frozen by instruction and remains an immutable historical exception even after it is no longer the current week.

Repository:
<https://github.com/Dhawkins223/ai-engineering-journey>

Rolling outline:
<https://github.com/Dhawkins223/ai-engineering-journey/blob/main/PLAN_OUTLINE.md>

## Capacity and calendar rules

**Sustainable capacity: 30 productive hours per week.**

**Additional days off through January 4, 2027: none.**

- Tuesday through Sunday are study days.
- Monday remains the fixed rest day.
- November 26, December 24, December 25, December 31, and January 1 are study days because no additional days off were requested.
- Time estimates are planning estimates, not deadlines.
- If a block finishes early, move to the next scheduled block.
- If a block runs long, stop at a sensible checkpoint and roll it forward.
- Do not use Monday to catch up.
- Do not add courses or unrelated material to fill time.
- If sustainable capacity falls below 30 hours, extend the timeline rather than compressing work.

Official curriculum start:

**September 15, 2026**

## Academic honesty boundary

All CS50 assessment code stays in CS50's own environment:

<https://cs50.dev/>

For CS50 assessments:

- follow <https://cs50.harvard.edu/python/honesty/>
- do not publish CS50 problem-set solutions in this repository
- do not use external AI systems to suggest or complete CS50 assessment answers or code
- use CS50's own AI tools only where the course permits them

## Hiring evidence and career realism

The main career path remains:

1. Junior Software Engineer, Software Engineer I, QA Automation, Junior SDET, or scripting-oriented technical support/application support.
2. Python backend, API, application, or data-oriented software work.
3. ML-adjacent or applied-AI feature work after software and ML foundations are functional.
4. AI Engineer, Applied AI Engineer, LLM Engineer, or ML Engineer after stronger production software experience and AI-system evidence.

A direct AI Engineer hire as the first professional software role by August to September 2027 remains a **low-likelihood outcome**, not the base case.

Evidence:

- Stanford's 2026 AI Index reports that U.S. employment for software developers ages 22 to 25 fell nearly 20% from 2024, while older developer headcount continued to grow. Source: <https://hai.stanford.edu/ai-index/2026-ai-index-report/economy>
- LinkedIn reports that U.S. AI job postings roughly doubled since 2023 and that AI Engineer overtook Machine Learning Engineer as the most common AI role on LinkedIn. Source: <https://news.linkedin.com/2026/new-linkedin-research-finds-women-account-for-just-26-percent-of-ai-hires-as-ai-jobs-surge>
- LinkedIn's 2026 labor-market report says hiring in advanced economies is down roughly 20% to 35% from pre-pandemic levels. It does not isolate entry-level software hiring, so this is broad labor-market context rather than an entry-level statistic. Source: <https://economicgraph.linkedin.com/research/labor-market-report-2026>
- Stanford's AI Index reports that Python appeared in 258,674 U.S. AI job postings in 2025, nearly 30% more than in 2024. It also reports long-run increases in demand for AWS (+1,358%), scalability (+733%), and workflow management (+818%), while generative-AI skill mentions rose 111% from 2024 to 2025 and agentic-AI terms rose sharply. Source: <https://hai.stanford.edu/assets/files/ai_index_report_2026.pdf>

Current posting sample checked on September 16, 2026:

- ScaleTech AI Engineer: 5+ years overall software engineering experience. <https://jobs.lever.co/scale3c/813b5aeb-dadf-4926-9205-1e26290b8c82>
- BLEN AI Engineer: 5+ years professional software engineering experience plus at least 1 year shipping LLM/AI features. <https://jobs.lever.co/blencorp/4b2e3689-9720-4785-b0fe-d09bd5325f74>
- United Tech AI Engineer: 5+ years production Python experience. <https://jobs.lever.co/vacancies/37272803-0eba-49a4-93bd-5de6be83dd6b>
- RYZ Labs Full Stack AI Engineer: 5+ years as a Full Stack, Platform, or AI Engineer with production ownership. <https://jobs.lever.co/RyzLabs/8660eb6d-8f82-4602-8e04-de8cd3a4fd44>
- CYE Senior AI Engineer: 3+ years dedicated AI development, or 7+ years senior software engineering plus at least 1 year deep AI development. <https://jobs.lever.co/CYE/ba6f695a-5512-4fcb-bcb0-aa7d42c9c6c4>
- Simbe Applied AI Engineer: 3+ years in software engineering, applied ML, data engineering, computer-vision operations, customer-solutions engineering, or related technical work. <https://jobs.lever.co/SimbeRobotics/1460bcbc-984d-44c7-b638-9718a6dc1681>
- Xsolla Full Stack AI Engineer / Applied AI Engineer: 1 to 3 years full-stack development experience, plus GenAI/LLM-product experience. <https://jobs.lever.co/xsolla/ebb74747-c739-4247-bafc-a088c10fa643>

In this seven-posting convenience sample, six required at least 3 years of relevant experience and four required 5 or more years. This sample is directional, not statistically representative.

What is still unknown:

- There is no reliable public conversion rate for people starting from zero, studying for one year, having no professional software experience, and then getting hired directly as AI Engineers.
- Job-title definitions vary by employer.
- Internships, contract work, portfolio quality, interview performance, networking, and gaining professional software experience during the year can materially change the outcome.

Therefore August to September 2027 remains an AI application checkpoint, while the primary employment strategy is to gain software/backend experience as early as possible and then move toward ML-adjacent and AI-engineering work.


## Cost and free-access policy

Prices below were checked on September 16, 2026. Metered service prices can change, so recheck before paying.

| Resource | Current cost | Free option / audit | What the free option leaves out | Financial aid | First cost point in plan | Source |
| --- | --- | --- | --- | --- | --- | --- |
| GitHub Codespaces | Personal Free includes 120 core-hours and 15 GB-month storage. A 2-core codespace costs $0.18/hour after included usage; storage is $0.07/GB-month. | Not a course. Free quota is included with personal accounts. 120 core-hours equals about 60 wall-clock hours on a 2-core codespace. | Usage beyond the included compute/storage quota is blocked unless billing is enabled, then it is metered. | N/A | Week 1 only if the free quota is exceeded. Paid use is not automatically required. | <https://docs.github.com/en/billing/concepts/product-billing/github-codespaces> |
| DeepLearning.AI Mathematics for Machine Learning and Data Science on Coursera | $49/month subscription. | Coursera's newer preview model replaces traditional audit for most courses with free access to the first module. DeepLearning.AI specifically confirms the first module can be previewed free. | Full later modules, full assessment access, and the certificate require the paid experience. | Yes. | **Week 3: paid full access or approved financial aid becomes necessary for the planned full specialization.** | <https://www.deeplearning.ai/specializations/mathematics-for-machine-learning-and-data-science> |
| Andrew Ng Machine Learning Specialization on Coursera | $49/month subscription. | Coursera offers a first-module preview on many courses; the specialization itself is not fully free. | Full specialization access, graded work beyond preview availability, and certificates require the paid experience. | Yes. | **Week 21: paid full access or approved financial aid becomes necessary.** | <https://www.coursera.org/specializations/machine-learning-introduction> |
| OpenAI API used for the hosted-LLM project | Usage-based. GPT-5.4 Mini is currently $0.75 per 1M input tokens, $0.075 per 1M cached input tokens, and $4.50 per 1M output tokens. | Not a course. The GPT-5.4 Mini API page lists the Free tier as unsupported. | No free production API tier for this model. Usage requires API billing/credits. | No general learner financial-aid program for API usage. | **Week 18: metered API spend first becomes necessary if the plan uses OpenAI as specified.** | <https://developers.openai.com/api/docs/models/gpt-5.4-mini> |
| AWS, later Phase 6 | Pay-as-you-go by service after credits/free allowances. | New customers can receive $100 at signup and earn up to $100 more, with a free account plan for up to 6 months or until credits are exhausted. | Free plan has access only to select services/features and closes when the free-plan period or credits end unless upgraded. | N/A | After June, during Phase 6. | <https://aws.amazon.com/free/> |

Free resources in the plan include CS50P, CS50 SQL, MIT Missing Semester, FastAPI documentation, PostgreSQL documentation, PyTorch tutorials, Hugging Face LLM Course, Python documentation, and scikit-learn documentation.


## Long-range roadmap

### Phase 1 - Programming and engineering foundation
**September 15 to early November 2026**

- CS50P
- Git and GitHub workflow
- MIT Missing Semester tooling
- debugging/testing habits
- DeepLearning.AI mathematics begins in Week 3

CS50P: <https://cs50.harvard.edu/python/>

### Phase 2 - SQL, backend, first LLM API system
**November 2026 to early February 2027**

- CS50 SQL
- mathematics continues
- HTTP, REST, FastAPI, Pydantic
- PostgreSQL
- API testing
- first hosted-LLM API application
- hand-written evals
- latency, cost, and failure handling

CS50 SQL: <https://cs50.harvard.edu/sql/>

FastAPI: <https://fastapi.tiangolo.com/tutorial/>

### Phase 3 - Applied machine learning engineering
**February to early April 2027**

- Andrew Ng Machine Learning Specialization
- NumPy and scikit-learn practice
- preprocessing and feature engineering
- model selection/evaluation
- end-to-end ML system

Machine Learning Specialization: <https://www.coursera.org/specializations/machine-learning-introduction>

### Phase 4 - Deep learning
**April to May 2027**

- PyTorch fundamentals
- datasets/dataloaders
- models, autograd, optimization
- training/validation loops
- embeddings, sequence models, transformer building blocks

PyTorch tutorials: <https://docs.pytorch.org/tutorials/>

### Phase 5 - LLM engineering, retrieval, and evals
**June to July 2027**

- hosted LLM APIs
- Hugging Face Transformers
- embeddings and semantic search
- RAG and source attribution
- retrieval/generation evals
- bounded tool calling
- latency/cost/failure analysis

Hugging Face LLM Course: <https://huggingface.co/learn/llm-course/>

### Phase 6 - Agentic and production AI systems
**August to September 2027**

- tool-using agents
- MCP
- workflow orchestration
- queues/asynchronous work
- model routing/fallbacks
- prompt-injection defenses
- least privilege
- AWS deployment
- observability, CI/CD, reliability

## Rolling-plan rule

Only the current week and next week should have detailed daily READMEs.

The later schedule lives in one file:

<https://github.com/Dhawkins223/ai-engineering-journey/blob/main/PLAN_OUTLINE.md>

### Sunday procedure for creating the next detailed week

On Sunday, after the week's required work:

1. Open PLAN_OUTLINE.md and read the next week's row.
2. List any rollover from the current week before new work.
3. Recheck the official resource links for changes or deadlines.
4. Allocate no more than 30 hours across Tuesday through Sunday. Keep Monday at 0 hours.
5. Give every block a concrete deliverable, such as a named submission recorded in Gradebook, a passing test count, a working endpoint, a committed project artifact, or a specific module completed.
6. Never use circular wording such as "the planned segment is complete."
7. If the outline row is flagged HIGH LOAD or the rollover makes it exceed 30 hours, move downstream work. Do not compress the week.
8. Mark any newly required paid resource and recheck its current price before purchase.
9. Create the new next-week README and keep the previous week's detailed README only if it is the frozen Week 1 exception.
10. Regenerate the PDF from root README + current-week README + next-week README only.

## CS50 SQL deadline and reserve

Official CS50 SQL deadline:

**December 31, 2026 at 23:59 UTC**

Sources:

- <https://cs50.harvard.edu/sql/psets/>
- <https://cs50.harvard.edu/sql/project/>
- <https://cs50.harvard.edu/sql/faqs/>

The FAQ says it is "best to assume the final deadline is 31 December 2026" and says, "We cannot make any exceptions to the deadlines for any reason."

Rebuilt internal schedule:

- Week 12 begins Optimizing after Viewing is submitted.
- Week 13 completes Optimizing and Scaling.
- Week 14 is primarily the final project.
- Internal target for final-project submission: **Thursday, December 17**.
- Planned SQL reserve: **Friday December 18, Saturday December 19, and Sunday December 20**, up to 15 hours.
- Monday December 21 remains a rest day.
- Week 15 begins backend work on December 22 if SQL is complete.

This moves the planned reserve before the holiday period.

Fallback:

- If SQL is still unfinished after December 20, Week 15 backend work moves.
- December 22 and December 23 become emergency SQL spillover days first.
- If required SQL work still remains after December 23, the learner must choose between using the remaining normal study days before the official deadline or accepting the risk of not completing the certificate. No plan should pretend the deadline can be ignored.
- The roadmap never relies on a future CS50 extension.

## Current detailed files

- Frozen current Week 1: <https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-01/README.md>
- Detailed next Week 2: <https://github.com/Dhawkins223/ai-engineering-journey/blob/main/semester-1/week-02/README.md>
- Later rolling outline: <https://github.com/Dhawkins223/ai-engineering-journey/blob/main/PLAN_OUTLINE.md>
