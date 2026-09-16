# AI Engineering Journey

> **Employer-proof learning log.** This repository documents the path from zero programming knowledge to production-oriented AI engineering evidence. It is designed to produce public, inspectable proof of skill without publishing private academic records or identifiers.

## Start-date correction

**Official execution start: Thursday, September 17, 2026.**

Week 1 README is frozen and is not edited. Its original calendar labels remain historical. Execute its six study sessions in sequence on:

| Frozen README label | Execute on |
| --- | --- |
| Tuesday, September 15 blocks | Thursday, September 17 |
| Wednesday, September 16 blocks | Friday, September 18 |
| Thursday, September 17 blocks | Saturday, September 19 |
| Friday, September 18 blocks | Sunday, September 20 |
| Monday, September 21 rest | Monday, September 21 |
| Saturday, September 19 blocks | Tuesday, September 22 |
| Sunday, September 20 blocks | Wednesday, September 23 |

Week 2 therefore runs **September 24 to September 30, 2026**. Numbered curriculum weeks continue in seven-day windows with Monday always off.

## Source-of-truth hierarchy

1. Root README: strategy, capacity modes, proof standards, costs, cloud decision, certificates, and policies.
2. Current-week README: frozen Week 1 during this startup window.
3. Next-week README: detailed Week 2 execution plan.
4. `PLAN_OUTLINE.md`: rolling week-by-week outline for later work.
5. Master PDF: generated from the root README, frozen Week 1, and detailed Week 2 only.

Repository:
[AI Engineering Journey repo](https://github.com/Dhawkins223/ai-engineering-journey)

Rolling outline:
[Rolling plan outline](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/PLAN_OUTLINE.md)

## Two capacity modes

| Mode | Capacity | Schedule | Rule |
| --- | ---: | --- | --- |
| **Full-time mode** | **30 h/week** | Six 5-hour study sessions on non-Mondays | Current default |
| **Part-time mode** | **24 h/week** | Six 4-hour study sessions on non-Mondays | Never compress; extend dates |

### Part-time mode behavior

The switch to 24 hours is immediate. Remaining work is rescaled by **30 / 24 = 1.25**, so a block of remaining work generally needs about 25% more calendar time.

Pause order in part-time mode:

1. **AWS light-study work pauses first.**
2. **AZ-900 preparation pauses next.**
3. Extra portfolio polish beyond the minimum employer-proof README/tests/results pauses next.
4. Nonessential system-design polish pauses next.
5. Math-from-scratch project polish may pause, but required Calcworkshop support remains attached to any active math topic.
6. If the switch occurs before the CS50 SQL deadline, DeepLearning.AI math may pause at an atomic lesson boundary so SQL can take priority.

**Coding-interview practice does not pause.**

Core work that does **not** get compressed:

- active CS50 course requirements
- required Calcworkshop support for active math topics
- core backend/ML/PyTorch/LLM course work
- minimum project tests and README evidence
- primary Azure deployment once backend work reaches that point
- scheduled coding-interview practice

### Combined weekly load example

If part-time mode runs alongside one **3-credit course in a 7.5-week session**, using the planning assumption of about **45 hours of work per credit**:

- course workload: 3 credits x 45 hours = 135 hours total
- 135 / 7.5 weeks = about **18 hours/week**
- AI engineering plan: **24 hours/week**
- combined planned load: about **42 hours/week**

The AI engineering plan stays at **24 hours/week** unless the capacity number is explicitly changed.

### Timeline effect

If part-time mode begins on **January 4, 2027**, the remaining schedule is expected to extend by roughly 9 to 10 calendar weeks before later interview-practice adjustments. The rolling plan recalculates dates from remaining work rather than compressing it.

### What happens to the CS50 SQL deadline

The official CS50 SQL deadline stays **December 31, 2026 at 23:59 UTC**.

If part-time mode begins before SQL is submitted:

- SQL receives available study hours first.
- AWS, AZ-900, extra polish, and other downstream work move later.
- coding-interview practice remains scheduled after CS50P.
- backend and LLM work move later.
- if remaining SQL work cannot fit into the remaining 24-hour weeks before December 31, the plan must state that the certificate is at risk. Hours are never compressed and Monday is never used.

## Advance-early rule

Once **every done-when condition for the current week is satisfied**, the next week's named work may start immediately.

- Do not wait for the calendar boundary.
- Do not add filler.
- Early work counts as the next week's planned work.
- Monday remains off.
- If the next week contains a paid-resource start, confirm billing/financial aid before beginning it.

## Academic honesty boundary

All CS50 assessment code stays in:
[CS50 coding environment](https://cs50.dev/)

Follow:
[CS50 Academic Honesty](https://cs50.harvard.edu/python/honesty/)

Do not publish CS50 problem-set code in public portfolio repositories. Do not use external AI systems to suggest or complete CS50 assessment answers or code.

## CS50P correction

The official CS50P Problem Sets page currently lists **Problem Sets 0 through 8 only**. There is no CS50P Problem Set 9.

Source:
[CS50P Problem Sets](https://cs50.harvard.edu/python/psets/)

Week 9 "Et Cetera" is course material, and the **Final Project** is the final CS50P deliverable after it:
[CS50P Final Project](https://cs50.harvard.edu/python/project/)

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
| Exponential functions | [Exponential Equations](https://calcworkshop.com/expos-logs/exponential-equations/) | softmax/exponential support |
| Logarithms | [Logarithmic Functions](https://calcworkshop.com/expos-logs/logarithmic-functions/) | cross-entropy/log support |
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
- softmax as a complete ML operation
- cross-entropy loss as a complete ML loss function
- precision / recall / F1 / ROC-AUC
- transformer attention

For softmax and cross-entropy, the plan now requires the exact **Exponential Equations** and **Logarithmic Functions** lessons as prerequisite support. Those lessons cover the exponential and logarithmic mathematics, but they are not presented as complete softmax or cross-entropy lessons.

## Calcworkshop cost comparison

Official pricing:
[Calcworkshop pricing](https://calcworkshop.com/pricing/)

The plan uses Calcworkshop from approximately **October 1, 2026 through July 28, 2027**, about 10 billing months.

| Billing option | Price | Cost for planned usage |
| --- | ---: | ---: |
| Monthly | $29/month | **$290** for 10 months |
| Yearly | $249/year | **$249** |
| Difference |  | **Yearly saves $41** |

**Recommendation: yearly.** It costs less for the planned 10-month usage and covers the entire runway through the late-summer application phase.

Calcworkshop's official pricing/FAQ pages do not list a financial-aid program. The membership is required in this curriculum.

The yearly membership is a **one-time, non-recurring payment** and does not auto-renew. Calcworkshop's Payment terms also state that subscription time **cannot be paused or resumed once it has started**. See [Calcworkshop Payment terms](https://calcworkshop.com/terms/#payment).

## Cloud evidence review: Azure primary, AWS lighter

I reviewed 10 current junior, entry-level, trainee, intern, or Software Engineer I postings on September 16, 2026 and counted named cloud platforms in the posting text.

| Posting | AWS | Azure | Link |
| --- | :---: | :---: | --- |
| VivSoft, Software Engineer - Entry Level | Yes | Yes | [VivSoft entry-level posting](https://vivsofttechnologiesfa.applytojob.com/apply/jobs/details/QLa8RzmXAc) |
| Vituity, Software Engineer I - Remote | No | Yes | [Vituity Software Engineer I posting](https://www.linkedin.com/jobs/view/software-engineer-i-remote-nationwide-at-vituity-4443262516) |
| Robert Half, Software Engineer I | Yes | Yes | [Robert Half Software Engineer I posting](https://roberthalf.wd1.myworkdayjobs.com/en-US/RobertHalfCareers/job/Software-Engineer-I_JR-261277) |
| Red Hawk Technologies, Entry-Level AI Automation Engineer | No | No | [Red Hawk entry-level AI posting](https://redhawktechnologies.applytojob.com/apply/9LknfI40ni/EntryLevel-AI-Automation-Engineer) |
| Corporate Tools, Junior Software Engineer | No | No | [Corporate Tools junior posting](https://www.corporatetools.com/job-postings/engineering-and-development/junior-software-engineer/) |
| BNSF, bnsf tech Trainee 2027 | No | No | [BNSF trainee posting](https://bnsf.jobs2web.com/job/REMOTE-bnsf-tech-Trainee-2027-%28Remote-US%29-US-76131/1428269800/) |
| CAI, Software Developer Intern | No | No | [CAI software intern posting](https://builtin.com/job/software-developer-intern/11176807) |
| Tarpon Health, Junior Software Engineer | No | No | [Tarpon Health junior posting](https://jobs.gusto.com/postings/tarpon-health-inc-junior-software-engineer-ed46c096-21f8-4d95-9ee8-6eb19d73733d) |
| Canonical, Junior Software Developer - Observability | No | No | [Canonical junior posting](https://job-boards.greenhouse.io/canonicaljobs/jobs/6662428) |
| Home Depot, Software Engineer - Remote | No | No | [Home Depot software posting](https://www.linkedin.com/jobs/view/software-engineer-remote-at-the-home-depot-4464580072) |

**Count in this 10-posting sample: Azure 3, AWS 2, neither named 7.**

With only a 3-to-2 split and **7 of 10 postings naming neither cloud**, this sample is best treated as a **tie**. It is a small convenience sample, not a labor-market-share estimate.

### Cloud decision

**Primary cloud: Microsoft Azure.** The sample does not decide the choice. Azure remains primary because this plan needs depth in one cloud, an Azure deployment is already integrated into the backend proof project, and switching primary clouds would add duplication without stronger evidence.

**Lighter secondary cloud: AWS.** Learn portability concepts, core service vocabulary, and deployment differences, but do not duplicate the full Azure curriculum.

### First deployment moves earlier

The Phase 2 FastAPI/PostgreSQL backend must be deployed to **Azure App Service** before LLM work is considered phase-ready.

Official FastAPI deployment quickstart:
[Azure App Service Python quickstart](https://learn.microsoft.com/en-us/azure/app-service/quickstart-python)

Target: **Week 18**, after backend tests and persistence are working.

## Cloud certification

At most one cloud certification is in this plan:

**Microsoft Certified: Azure Fundamentals, Exam AZ-900**
- Exam price: **$99 USD**
- Official source: [Azure Fundamentals certification](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/)
- Target: Week 20, only after the Azure-deployed backend exists.
- Junior-role value: **minor signal, not a hiring substitute.** The reviewed junior postings emphasize hands-on cloud exposure more strongly than a fundamentals certificate. The deployed Azure project is the higher-value evidence.

If part-time mode begins, AWS light-study work pauses first and AZ-900 preparation pauses second.

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
| `python-expense-tracker` | Phase 1 | Python, validation, tests, Git |
| `ai-math-linear-algebra-from-scratch` | Phase 1 | vectors/matrices/least-squares concepts implemented in Python/NumPy |
| `ai-math-gradient-descent-from-scratch` | Phase 1/2 | derivatives/gradients turned into a NumPy optimization implementation |
| `sports-analytics-database` | Phase 2 | relational design, SQL, indexes, query evidence |
| `ai-math-probability-stats-from-scratch` | Phase 2 | probability, simulation, confidence intervals, hypothesis-testing code |
| `fastapi-azure-backend` | Phase 2 | FastAPI, PostgreSQL, tests, Azure deployment |
| `llm-api-evals` | Phase 2 | hosted LLM API, structured output, evals, latency/cost |
| `end-to-end-ml-system` | Phase 3 | preprocessing, evaluation, API serving |
| `pytorch-deep-learning-system` | Phase 4 | training/validation, checkpointing, reproducibility |
| `rag-evals-system` | Phase 5 | retrieval, sources, RAG, evals, tool boundary |
| `production-agentic-ai-system` | Phase 6 | production workflow, MCP/tools, security, observability, cloud |

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

After CS50P:

- schedule **1 to 1.5 h/week** of coding-interview practice during the middle of the plan
- focus on arrays/lists, hash maps/dictionaries, stacks/queues, trees, graphs, recursion, searching/sorting, and common patterns
- use a direct problem list such as [LeetCode Problemset](https://leetcode.com/problemset/) rather than adding another course
- **do not pause coding-interview practice in part-time mode**

### Application-ramp interview load

During the final **2 to 3 months before the application checkpoint**:

- Weeks 46 to 49: raise interview practice to **3 h/week**
- Weeks 50 to 55: raise interview practice to **4 h/week**
- move displaced project-hardening work downstream instead of compressing it
- the added interview load moves the application checkpoint to **Wednesday, October 6, 2027** in the current full-time-mode outline

If part-time mode is active during this ramp, the same 3 to 4 hours/week of interview practice remains protected and the application checkpoint moves later as needed.

System-design basics begin before the application checkpoint, with dedicated blocks in the late PyTorch/LLM phases. Focus on API boundaries, databases, caching, queues, observability, failure modes, and scaling tradeoffs already present in the projects.

## Certificate inventory

| Certificate | Target | Cost in this plan | Evidence/source |
| --- | --- | ---: | --- |
| CS50P free CS50 Certificate | Week 7 or actual final-project completion week | **$0** | [CS50P certificate](https://cs50.harvard.edu/python/certificate/) |
| DeepLearning.AI Mathematics for Machine Learning and Data Science Specialization | Week 18 target | **$49/month subscription or approved financial aid** | [DeepLearning.AI Math specialization](https://www.coursera.org/specializations/mathematics-for-machine-learning-and-data-science) |
| CS50 SQL free CS50 Certificate | Week 14/15, no later than official deadline | **$0** | [CS50 SQL certificate](https://cs50.harvard.edu/sql/certificate/) |
| Microsoft Certified: Azure Fundamentals, AZ-900 | Week 20, optional | **$99** | [Azure Fundamentals certification](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/) |
| Machine Learning Specialization | Week 29 target | **$49/month subscription or approved financial aid** | [Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction) |

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
- Calcworkshop: [Calcworkshop pricing](https://calcworkshop.com/pricing/)
- DeepLearning.AI Math: [DeepLearning.AI Math specialization](https://www.coursera.org/specializations/mathematics-for-machine-learning-and-data-science)
- ML Specialization: [Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction)
- Codespaces: [Codespaces billing](https://docs.github.com/en/billing/concepts/product-billing/github-codespaces)
- Azure free account: [Azure free account](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account)

## 12-month planned cost summary

The table below uses the current full-time-mode dates and assumes no Coursera financial aid. OpenAI API and Azure are budget ranges because actual usage is metered.

| Item | Planned billing window | Estimated cost |
| --- | --- | ---: |
| Calcworkshop yearly membership | Oct 1, 2026 through Jul 28, 2027 usage fits inside one 12-month membership | **$249** |
| DeepLearning.AI Math Specialization | Week 3 Oct 1, 2026 through Week 18 Jan 20, 2027 = **4 subscription months** at $49 | **$196** |
| Machine Learning Specialization | Week 21 Feb 4, 2027 through Week 29 Apr 7, 2027 = **3 subscription months** at $49 | **$147** |
| AZ-900 exam | Optional, one attempt | **$99** |
| OpenAI API learning usage | Planned LLM/eval projects, using [GPT-5.4 Mini pricing](https://developers.openai.com/api/docs/models/gpt-5.4-mini) as the reference point | **$5-$30** budget |
| Azure learning/deployment usage | Use [Azure free account allowances](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account) and [App Service Free tier](https://azure.microsoft.com/en-us/pricing/details/app-service/windows/) where practical; delete idle paid resources | **$0-$75** budget |

### Total

- **Including optional AZ-900:** **$696-$796**
- **Excluding optional AZ-900:** **$597-$697**

These totals exclude any GitHub Codespaces overage and taxes. Coursera financial aid can reduce the specialization totals.

Sources: [Calcworkshop pricing](https://calcworkshop.com/pricing/), [Calcworkshop Payment terms](https://calcworkshop.com/terms/#payment), [DeepLearning.AI Math pricing](https://www.coursera.org/specializations/mathematics-for-machine-learning-and-data-science), [Machine Learning Specialization pricing](https://www.coursera.org/specializations/machine-learning-introduction), and [AZ-900 certification](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/).

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
- **Reopen the existing Codespace from [Your Codespaces](https://github.com/codespaces) instead of using Week 1's new-Codespace link.**
- Do not leave it idling while watching lectures or doing math.
- Use cs50.dev for CS50 assessment work.
- Check GitHub billing usage before enabling paid overages.

## CS50 SQL deadline plan

Official deadline: **December 31, 2026 at 23:59 UTC**.

Sources:
- [CS50 SQL Problem Sets](https://cs50.harvard.edu/sql/psets/)
- [CS50 SQL Final Project](https://cs50.harvard.edu/sql/project/)
- [CS50 SQL FAQ](https://cs50.harvard.edu/sql/faqs/)

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
[Rolling plan outline](https://github.com/Dhawkins223/ai-engineering-journey/blob/main/PLAN_OUTLINE.md)
