# AI Engineering Journey

> **Employer-proof learning log.** This repository documents the path from zero programming knowledge to production-oriented AI engineering evidence. The degree is currently paused, so this plan is the main technical focus. No transcript, grades, student ID, or appeal information belongs in this public repository.

## Start-date correction

**Official execution start: Thursday, September 17, 2026.**

Week 1 README is frozen and is not edited. Its original calendar labels remain historical. Execute its six study sessions in sequence on:

| Frozen Week 1 session | Actual execution date |
| --- | --- |
| Day 1 | Thu Sep 17 |
| Day 2 | Fri Sep 18 |
| Day 3 | Sat Sep 19 |
| Day 4 | Sun Sep 20 |
| Rest | Mon Sep 21 |
| Day 5 | Tue Sep 22 |
| Day 6 | Wed Sep 23 |

Week 2 therefore runs **September 24 to September 30, 2026**. Numbered curriculum weeks continue in seven-day windows with Monday always off.

## Source-of-truth hierarchy

1. Root README: strategy, capacity modes, proof standards, costs, cloud decision, certificates, and policies.
2. Current-week README: frozen Week 1 during this startup window.
3. Next-week README: detailed Week 2 execution plan.
4. `PLAN_OUTLINE.md`: rolling week-by-week outline for later work.
5. Master PDF: generated from the root README, frozen Week 1, and detailed Week 2 only.

Repository:
<https://github.com/Dhawkins223/ai-engineering-journey>

Rolling outline:
<https://github.com/Dhawkins223/ai-engineering-journey/blob/main/PLAN_OUTLINE.md>

## Two capacity modes

| Mode | Capacity | Schedule | Rule |
| --- | ---: | --- | --- |
| Degree paused | **30 h/week** | Six 5-hour study sessions on non-Mondays | Current mode |
| Degree active | **24 h/week** | Six 4-hour study sessions on non-Mondays | Never compress; extend dates |

### If the degree resumes

The switch to 24 hours is immediate. Remaining work is rescaled by **30 / 24 = 1.25**, so the remaining timeline becomes about 25% longer.

Pause order:

1. Weekly coding-interview practice pauses first.
2. Light AWS study and AZ-900 preparation pause next.
3. Extra portfolio polish beyond the minimum employer-proof README/tests/results pauses next.
4. System-design practice pauses until the core track stabilizes.
5. Math-from-scratch project polish may pause, but Calcworkshop support remains attached to any active math topic.
6. If the switch occurs before the CS50 SQL deadline, DeepLearning.AI math may pause at an atomic lesson boundary so SQL can take priority.

Core work that does **not** get compressed:

- active CS50 course requirements
- required Calcworkshop support for active math topics
- core backend/ML/PyTorch/LLM course work
- minimum project tests and README evidence
- primary Azure deployment once backend work reaches that point

### Timeline effect

If 24-hour mode begins **January 4, 2027**, the remaining schedule is expected to extend by roughly 9 to 10 calendar weeks. The September 2027 AI application checkpoint would move to approximately **late November to early December 2027**.

If the degree resumes later, the delay is smaller and is recalculated from remaining planned hours.

### What happens to the CS50 SQL deadline

The official CS50 SQL deadline stays **December 31, 2026 at 23:59 UTC**. A degree restart does not move it.

If 24-hour mode begins before SQL is submitted:

- SQL receives the available study hours first.
- DSA, secondary-cloud study, portfolio polish, and math are paused as needed.
- Backend and LLM work move later.
- If remaining SQL work cannot fit into the remaining 24-hour weeks before December 31, the plan must say the certificate is at risk. Hours are never compressed and Monday is never used.

## Advance-early rule

Once **every done-when condition for the current week is satisfied**, the next week's named work may start immediately.

- Do not wait for the calendar boundary.
- Do not add filler.
- Early work counts as the next week's planned work.
- Monday remains off.
- If the next week contains a paid-resource start, confirm billing/financial aid before beginning it.

## Academic honesty boundary

All CS50 assessment code stays in:
<https://cs50.dev/>

Follow:
<https://cs50.harvard.edu/python/honesty/>

Do not publish CS50 problem-set code in public portfolio repositories. Do not use external AI systems to suggest or complete CS50 assessment answers or code.

## CS50P correction

The official CS50P Problem Sets page currently lists **Problem Sets 0 through 8 only**. There is no CS50P Problem Set 9.

Source:
<https://cs50.harvard.edu/python/psets/>

Week 9 "Et Cetera" is course material, and the **Final Project** is the final CS50P deliverable after it:
<https://cs50.harvard.edu/python/project/>

## Calcworkshop is required math support

Calcworkshop is required from Week 3 through the last scheduled math/evaluation support in July 2027.

**Standard Calcworkshop done-when:** watch the named lesson, then work the lesson's practice problems without notes until you can complete the representative problems assigned by the lesson and explain the method aloud. Each rolling-plan row gives the time budget.

### Math-topic mapping

| Curriculum dependency | Exact Calcworkshop lesson | Use |
| --- | --- | --- |
| Linear systems / row reduction | [Reduced Row Echelon Form](https://calcworkshop.com/linear-equations/reduced-row-echelon-form/) | DeepLearning.AI linear algebra |
| Vectors / linear combinations | [Vector Equations](https://calcworkshop.com/linear-equations/vector-equations-for-matrix-algebra/) | Linear algebra, embeddings |
| Matrix operations | [Matrix Operations and Determinants](https://calcworkshop.com/matrix-algebra/matrix-operations-and-determinants/) | Linear algebra, PyTorch tensors |
| Linear transformations | [Linear Transformations](https://calcworkshop.com/linear-equations/linear-transformations/) | Linear algebra, neural layers |
| Dot products | [3D Dot Product](https://calcworkshop.com/vectors-and-the-geometry-of-space/dot-product-in-3d/) | embeddings, attention prerequisite |
| Inner products / orthogonality | [Inner Product, Length, Orthogonality](https://calcworkshop.com/orthogonality/inner-product-length-and-orthogonality/) | embeddings, similarity |
| Eigenvalues / eigenvectors | [Eigenvalues and Eigenvectors](https://calcworkshop.com/eigenvalues/eigenvalues-and-eigenvectors/) | linear algebra |
| Least-squares geometry | [Least Squares Problems](https://calcworkshop.com/orthogonality/least-squares-problems/) | regression |
| Least-squares regression | [Least Squares Regression Line](https://calcworkshop.com/linear-regression/least-squares-regression-line/) | ML regression |
| Derivatives | [Derivative Rules](https://calcworkshop.com/derivatives/derivative-rules/) | ML optimization, backprop prerequisites |
| Chain rule | [Chain Rule](https://calcworkshop.com/derivatives/chain-rule/) | backprop |
| Partial derivatives | [Partial Derivative](https://calcworkshop.com/partial-derivatives/partial-derivative/) | multivariable optimization |
| Multivariable chain rule | [Multivariable Chain Rule](https://calcworkshop.com/partial-derivatives/multivariable-chain-rule/) | backprop prerequisite |
| Gradients / directional derivatives | [Directional Derivative](https://calcworkshop.com/partial-derivatives/directional-derivative/) | gradient concepts |
| Optimization | [Optimization in Calculus](https://calcworkshop.com/application-derivatives/optimization-calculus/) | ML optimization |
| Basic probability | [Probability Formula](https://calcworkshop.com/probability/probability-formula/) | probability, evals |
| Conditional probability | [Conditional Probability](https://calcworkshop.com/probability/conditional-probability/) | ML/evals |
| Bayes theorem | [Bayes Theorem](https://calcworkshop.com/probability/bayes-theorem/) | probabilistic reasoning |
| Expected value / variance, discrete | [Expected Value and Variance](https://calcworkshop.com/discrete-probability-distribution/standard-deviation-variance-expected-value/) | statistics / metrics |
| Expected value / variance, continuous | [Expected Value and Variance, Continuous](https://calcworkshop.com/continuous-probability-distribution/expected-value-variance-continuous-random-variable/) | statistics |
| Normal distribution | [Normal Distribution](https://calcworkshop.com/exploring-data/normal-distribution/) | inference / error analysis |
| Covariance / correlation | [Covariance vs Correlation](https://calcworkshop.com/joint-probability-distribution/covariance-vs-correlation/) | feature relationships |
| Confidence intervals | [Population Mean Confidence Interval](https://calcworkshop.com/confidence-interval/population-mean/) | eval uncertainty |
| Hypothesis testing | [Hypothesis Testing](https://calcworkshop.com/hypothesis-test/hypothesis-testing/) | experiment/eval comparisons |
| One-sample t test | [One Sample T Test](https://calcworkshop.com/hypothesis-test/one-sample-t-test/) | small-sample inference |

### Topics with no exact Calcworkshop lesson found

I searched Calcworkshop for these topics and did **not** find an exact lesson page:

- gradient descent
- softmax
- cross-entropy loss
- precision / recall / F1 / ROC-AUC
- transformer attention

The plan therefore uses the exact prerequisite-support lessons above, such as derivatives, multivariable chain rule, directional derivatives, probability, dot product, and inner product. These are explicitly support lessons, not claimed exact coverage.

## Calcworkshop cost comparison

Official pricing:
<https://calcworkshop.com/pricing/>

The plan uses Calcworkshop from approximately **October 1, 2026 through July 28, 2027**, about 10 billing months.

| Billing option | Price | Cost for planned usage |
| --- | ---: | ---: |
| Monthly | $29/month | **$290** for 10 months |
| Yearly | $249/year | **$249** |
| Difference |  | **Yearly saves $41** |

**Recommendation: yearly.** It costs less for the planned 10-month usage and covers the entire runway through the late-summer application phase.

Calcworkshop's official pricing/FAQ pages do not list a financial-aid program. The membership is required in this curriculum.

## Cloud evidence review: Azure primary, AWS lighter

I reviewed 10 current junior, entry-level, trainee, intern, or Software Engineer I postings on September 16, 2026 and counted named cloud platforms in the posting text.

| Posting | AWS | Azure | Link |
| --- | :---: | :---: | --- |
| VivSoft, Software Engineer - Entry Level | Yes | Yes | <https://vivsofttechnologiesfa.applytojob.com/apply/jobs/details/QLa8RzmXAc> |
| Vituity, Software Engineer I - Remote | No | Yes | <https://www.linkedin.com/jobs/view/software-engineer-i-remote-nationwide-at-vituity-4443262516> |
| Robert Half, Software Engineer I | Yes | Yes | <https://roberthalf.wd1.myworkdayjobs.com/en-US/RobertHalfCareers/job/Software-Engineer-I_JR-261277> |
| Red Hawk Technologies, Entry-Level AI Automation Engineer | No | No | <https://redhawktechnologies.applytojob.com/apply/9LknfI40ni/EntryLevel-AI-Automation-Engineer> |
| Corporate Tools, Junior Software Engineer | No | No | <https://www.corporatetools.com/job-postings/engineering-and-development/junior-software-engineer/> |
| BNSF, bnsf tech Trainee 2027 | No | No | <https://bnsf.jobs2web.com/job/REMOTE-bnsf-tech-Trainee-2027-%28Remote-US%29-US-76131/1428269800/> |
| CAI, Software Developer Intern | No | No | <https://builtin.com/job/software-developer-intern/11176807> |
| Tarpon Health, Junior Software Engineer | No | No | <https://jobs.gusto.com/postings/tarpon-health-inc-junior-software-engineer-ed46c096-21f8-4d95-9ee8-6eb19d73733d> |
| Canonical, Junior Software Developer - Observability | No | No | <https://job-boards.greenhouse.io/canonicaljobs/jobs/6662428> |
| Home Depot, Software Engineer - Remote | No | No | <https://www.linkedin.com/jobs/view/software-engineer-remote-at-the-home-depot-4464580072> |

**Count in this 10-posting sample: Azure 3, AWS 2, neither named 7.**

This is a small convenience sample, not a labor-market-share estimate.

### Cloud decision

**Primary cloud: Microsoft Azure.** It has the slight lead in this entry-level sample, and the Vituity Software Engineer I posting specifically asks for hands-on Azure experience.

**Lighter secondary cloud: AWS.** Learn portability concepts, core service vocabulary, and deployment differences, but do not duplicate the full Azure curriculum.

### First deployment moves earlier

The Phase 2 FastAPI/PostgreSQL backend must be deployed to **Azure App Service** before LLM work is considered phase-ready.

Official FastAPI deployment quickstart:
<https://learn.microsoft.com/en-us/azure/app-service/quickstart-python>

Target: **Week 18**, after backend tests and persistence are working.

## Cloud certification

At most one cloud certification is in this plan:

**Microsoft Certified: Azure Fundamentals, Exam AZ-900**
- Exam price: **$99 USD**
- Official source: <https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/>
- Target: Week 20, only after the Azure-deployed backend exists.
- Junior-role value: **minor signal, not a hiring substitute.** The reviewed junior postings emphasize hands-on cloud exposure more strongly than a fundamentals certificate. The deployed Azure project is the higher-value evidence.

If 24-hour degree-active mode begins, AZ-900 preparation is among the first tracks paused.

## Employer-visible proof standard

Courses are input. Public evidence is the output.

Each major project gets its own public repository once the first runnable milestone exists. Do **not** create empty placeholder repositories.

Every project README must include:

1. Problem
2. Architecture
3. How to run
4. Tests
5. Results
6. Known limitations

The learning log links to each project:

| Public repo | Phase | Employer-visible proof |
| --- | --- | --- |
| [python-expense-tracker](https://github.com/Dhawkins223/python-expense-tracker) | Phase 1 | Python, validation, tests, Git |
| [ai-math-linear-algebra-from-scratch](https://github.com/Dhawkins223/ai-math-linear-algebra-from-scratch) | Phase 1 | vectors/matrices/least-squares concepts implemented in Python/NumPy |
| [ai-math-gradient-descent-from-scratch](https://github.com/Dhawkins223/ai-math-gradient-descent-from-scratch) | Phase 1/2 | derivatives/gradients turned into a NumPy optimization implementation |
| [sports-analytics-database](https://github.com/Dhawkins223/sports-analytics-database) | Phase 2 | relational design, SQL, indexes, query evidence |
| [ai-math-probability-stats-from-scratch](https://github.com/Dhawkins223/ai-math-probability-stats-from-scratch) | Phase 2 | probability, simulation, confidence intervals, hypothesis-testing code |
| [fastapi-azure-backend](https://github.com/Dhawkins223/fastapi-azure-backend) | Phase 2 | FastAPI, PostgreSQL, tests, Azure deployment |
| [llm-api-evals](https://github.com/Dhawkins223/llm-api-evals) | Phase 2 | hosted LLM API, structured output, evals, latency/cost |
| [end-to-end-ml-system](https://github.com/Dhawkins223/end-to-end-ml-system) | Phase 3 | preprocessing, evaluation, API serving |
| [pytorch-deep-learning-system](https://github.com/Dhawkins223/pytorch-deep-learning-system) | Phase 4 | training/validation, checkpointing, reproducibility |
| [rag-evals-system](https://github.com/Dhawkins223/rag-evals-system) | Phase 5 | retrieval, sources, RAG, evals, tool boundary |
| [production-agentic-ai-system](https://github.com/Dhawkins223/production-agentic-ai-system) | Phase 6 | production workflow, MCP/tools, security, observability, cloud |

Project links become live when the corresponding repo is created at its first runnable milestone.

### Phase-end proof ritual

At the end of every phase:

- explain the phase project out loud in **5 minutes** as if answering an interviewer
- update the resume with only evidence that is actually complete
- update the GitHub profile/pinned repositories
- verify every public repo README has problem, architecture, run steps, tests, results, and limitations

## Math-from-scratch proof projects

| Major math area | Public repo | Required supporting Calcworkshop lessons |
| --- | --- | --- |
| Linear algebra | `ai-math-linear-algebra-from-scratch` | RREF, vector equations, matrix operations, transformations, dot/inner products, eigenvalues, least squares |
| Calculus / optimization | `ai-math-gradient-descent-from-scratch` | derivative rules, chain rule, partial derivatives, multivariable chain rule, directional derivative, optimization |
| Probability / statistics | `ai-math-probability-stats-from-scratch` | probability, conditional probability, Bayes, expected value/variance, normal distribution, covariance/correlation, confidence intervals, hypothesis tests |

Each repo must implement the mathematics directly enough to explain the operations, not simply call a high-level ML estimator.

## Coding interviews and system design

After CS50P is complete:

- schedule **1 to 1.5 hours/week** of coding-interview practice
- focus on arrays/lists, hash maps/dictionaries, stacks/queues, trees, graphs, recursion, searching/sorting, and common patterns
- LeetCode or equivalent problems are practice, not the main curriculum
- in 24-hour degree-active mode, this track pauses first

System-design basics begin before the AI application checkpoint, with dedicated blocks in the late PyTorch/LLM phases. Focus on API boundaries, databases, caching, queues, observability, failure modes, and scaling tradeoffs already present in the projects.

## Certificate inventory

| Certificate | Target | Cost in this plan | Evidence/source |
| --- | --- | ---: | --- |
| CS50P free CS50 Certificate | Week 7 or actual final-project completion week | **$0** | <https://cs50.harvard.edu/python/certificate/> |
| DeepLearning.AI Mathematics for Machine Learning and Data Science Specialization | Week 18 target | **$49/month subscription or approved financial aid** | <https://www.coursera.org/specializations/mathematics-for-machine-learning-and-data-science> |
| CS50 SQL free CS50 Certificate | Week 14/15, no later than official deadline | **$0** | <https://cs50.harvard.edu/sql/certificate/> |
| Microsoft Certified: Azure Fundamentals, AZ-900 | Week 20, optional | **$99** | <https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/> |
| Machine Learning Specialization | Week 29 target | **$49/month subscription or approved financial aid** | <https://www.coursera.org/specializations/machine-learning-introduction> |

No certificate is treated as stronger proof than a tested public project.

## Paid-resource and platform costs

| Resource | Current cost | Free option / what it omits | Aid | First paid point |
| --- | --- | --- | --- | --- |
| Calcworkshop | $29/month or $249/year | Public lesson pages provide descriptions, but membership unlocks full course videos/practice/tests | No financial-aid program listed on official pricing/FAQ | Week 3; **yearly recommended** |
| DeepLearning.AI Math specialization | $49/month | Coursera enrollment/preview availability varies; full specialization/certificate requires paid access or aid | Yes | Week 3 |
| Machine Learning Specialization | $49/month | Full graded specialization/certificate requires paid access or aid | Yes | Week 21 |
| OpenAI API | Metered usage | No general free production API assumption in this plan | No general learner aid | Week 19 |
| Azure | Pay as you go; new Azure free accounts currently offer $200 credit for 30 days plus free service allowances | Free account/allowances are suitable for proof-of-concept use; paid usage begins beyond allowances | N/A | Week 18 deployment if free credit/allowance is unavailable or exhausted |
| GitHub Codespaces | GitHub Free includes 120 core-hours/month and 15 GB-month storage. 2-core paid rate is $0.18/hour after included usage | A 2-core codespace consumes included usage at 2 core-hours per wall-clock hour | N/A | Only after included quota is exhausted |

Sources:
- Calcworkshop: <https://calcworkshop.com/pricing/>
- DeepLearning.AI Math: <https://www.coursera.org/specializations/mathematics-for-machine-learning-and-data-science>
- ML Specialization: <https://www.coursera.org/specializations/machine-learning-introduction>
- Codespaces: <https://docs.github.com/en/billing/concepts/product-billing/github-codespaces>
- Azure free account: <https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account>

## Codespaces budget rule

GitHub Free currently includes **120 core-hours/month**. On a 2-core codespace that is about **60 wall-clock hours/month** because the included-usage multiplier is 2.

Estimated active Codespaces use from this plan:

| Phase | Estimated active Codespaces time | Monthly estimate | Free-quota risk |
| --- | ---: | ---: | --- |
| Early foundation | 8 to 12 h/week | about 35 to 52 h/month | Usually under 60 h |
| Backend / ML / PyTorch / LLM project phases | 14 to 18 h/week | about 61 to 78 h/month | Likely exceeds free quota |

At roughly 14 h/week, the 60-hour wall-clock equivalent is reached near the end of a typical billing month. At 18 h/week it can be reached around the fourth study week.

Rules:

- **Stop the codespace after every session.**
- **Reopen the existing codespace instead of creating a new one.**
- Do not leave it idling while watching lectures or doing math.
- Use cs50.dev for CS50 assessment work.
- Check GitHub billing usage before enabling paid overages.

## CS50 SQL deadline plan

Official deadline: **December 31, 2026 at 23:59 UTC**.

Sources:
- <https://cs50.harvard.edu/sql/psets/>
- <https://cs50.harvard.edu/sql/project/>
- <https://cs50.harvard.edu/sql/faqs/>

With the September 17 start-date shift:

- Week 13, Dec 10 to Dec 16: Optimizing + Scaling are the priority.
- Week 14, Dec 17 to Dec 23: Final Project.
- Internal target: **submit Final Project by Sunday, Dec 20** if progress allows.
- Tue Dec 22 and Wed Dec 23 provide the first internal reserve.
- Week 15, Dec 24 to Dec 30, remains emergency SQL reserve if required.
- Monday Dec 28 remains off.
- Dec 30 remains the personal hard target.
- Dec 31 is not treated as planned working margin.

Backend/Azure work starts only when required SQL work is complete.

## Degree-resumption task

In the same week the plan switches from 30-hour mode to 24-hour mode:

- ask the academic advisor whether AI/ML coursework can count toward SER 4XX or technical electives
- ask whether the software-engineering capstone can be an AI project

No academic records or private account information should be added to this public repository.

## Long-range roadmap

| Phase | Main outcome | Employer-proof exit |
| --- | --- | --- |
| Phase 1, Python + math foundation | CS50P + core math | Python project + linear algebra/calculus math repos + 5-minute explanation + resume/GitHub update |
| Phase 2, SQL + backend + first LLM | SQL, FastAPI, PostgreSQL, Azure, LLM evals | SQL repo + probability repo + Azure backend + LLM eval repo + phase interview explanation |
| Phase 3, applied ML | ML specialization + end-to-end ML | tested ML system repo + metrics/limitations + phase interview explanation |
| Phase 4, PyTorch | deep-learning engineering | reproducible PyTorch repo + phase interview explanation |
| Phase 5, LLM/RAG/evals | retrieval, grounding, tools, evals | RAG/evals repo + system-design discussion + phase interview explanation |
| Phase 6, production/agentic AI | MCP/tools/security/observability/cloud | production-agentic repo + application-ready GitHub/resume |

Detailed rolling schedule:
<https://github.com/Dhawkins223/ai-engineering-journey/blob/main/PLAN_OUTLINE.md>
