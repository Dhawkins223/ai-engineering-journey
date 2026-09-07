# AI Engineering Journey

A cloud-first, one-year curriculum and portfolio repository designed to progress from programming fundamentals to **Production AI Systems / Agentic AI Engineering**.

This README is the source of truth for the curriculum so that any AI assistant, coding agent, reviewer, or collaborator can understand the objective, current phase, sequencing rules, environment, and what should happen next.

---

# 1. Primary Career Goal

Target role family:

**Software Engineer → AI Engineer → Production AI Systems / Agentic AI Engineer**

Target serious AI Engineer applications: **August–September 2027**.

The curriculum is intentionally broader than prompt engineering. The goal is to become capable of taking a problem from idea to production:

```text
problem
  ↓
data / context
  ↓
model or LLM approach
  ↓
evaluation
  ↓
API / application integration
  ↓
database / tools / retrieval
  ↓
tests
  ↓
CI/CD
  ↓
cloud deployment
  ↓
monitoring / security / cost control
  ↓
iteration
```

The final competency standard is:

> Independently take a real problem, choose an appropriate AI/ML approach, prepare the data/context, implement the system, evaluate it, expose it through software, test it, deploy it, monitor it, and explain the architecture and tradeoffs.

---

# 2. Curriculum Philosophy

This is not a certificate-collection plan and not a traditional data-science-only path.

The highest-value target is an engineer who can build reliable software systems around models, LLMs, tools, agents, data, evaluation, security, cloud infrastructure, and business workflows.

The curriculum therefore emphasizes:

- strong Python and software engineering
- SQL and databases
- Linux and cloud fluency
- APIs and backend engineering
- testing and CI/CD
- machine learning fundamentals
- PyTorch and deep learning
- transformers and LLMs
- RAG and vector search
- tool calling and agentic systems
- MCP
- AI evaluations and observability
- security and prompt-injection defense
- AWS and production cloud architecture
- MLOps / AI operations

The curriculum deliberately does **not** begin with advanced AI frameworks. Foundations come first.

---

# 3. Cloud-First Work Environment

Primary development model:

```text
GitHub Codespaces
      ↓
GitHub repository
      ↓
GitHub Actions
      ↓
Python / backend / ML / AI code
      ↓
AWS or another appropriate cloud service when production deployment becomes necessary
```

**Railway is intentionally not part of this learning environment.** It is reserved for other projects.

The local Windows machine is primarily an access point. Heavy local Docker/VM infrastructure is not required during the foundation phase.

Primary tools now:

- GitHub Codespaces
- browser-based VS Code
- Python
- Git/GitHub
- Linux terminal inside Codespaces
- pytest
- Ruff

Later tools are introduced only when required.

---

# 4. Time Commitment and Acceleration Rules

Normal sprint workload:

**5 hours/day × 6 days/week ≈ 30 hours/week**

One day per week is normally a rest/catch-up/acceleration day.

Important rule:

> Calendar dates are maximum windows, not gates.

If a course or competency is genuinely completed early, immediately begin the next prerequisite-compatible course.

Do not repeat material simply to fill a scheduled week.

Keep roughly three active learning tracks when practical:

1. Core programming / software engineering
2. Tools / data / cloud
3. Mathematics / ML / AI

---

# 5. Advancement Standard

Three competency levels are used:

### Familiar
Seen the concept and can recognize it.

### Functional
Can perform the task with documentation. This is usually enough to advance.

### Independent
Can perform common operations without a tutorial and explain the reasoning.

Do **not** wait for mastery before progressing.

The curriculum is competency-gated, not perfection-gated.

---

# 6. AI-Assistance Rule

AI tools may be used for:

- explanations
- debugging help after an attempt
- code review
- practice questions
- comparing approaches
- documentation lookup
- architectural discussion

AI should **not** generate entire foundational exercises for copy/paste.

Interview test:

> Can the learner explain every important line and decision?

If not, the work is not considered learned.

Always follow the academic-honesty requirements of any external course.

---

# 7. One-Year Roadmap

## Phase 1 — Programming Foundation
**September–November 2026**

Core skills:

- Python
- Git
- GitHub
- Linux
- SQL
- relational database design
- testing fundamentals
- mathematics needed for ML
- basic data structures and algorithms

Primary outcomes:

- independently write small Python programs
- debug basic programs
- use Git branches/commits/push/pull
- work comfortably in a Linux terminal
- design/query relational databases
- write basic tests

---

## Phase 2 — Software Engineering / Backend
**November 2026–January 2027**

Core skills:

- HTTP
- REST APIs
- FastAPI
- Pydantic
- PostgreSQL
- authentication concepts
- pytest
- API testing
- application architecture
- environment variables and secrets
- GitHub Actions
- containers when appropriate
- cloud deployment

Primary project:

**Production backend service**

Expected components:

- FastAPI
- PostgreSQL
- validation
- authentication or authorization pattern
- automated tests
- CI
- cloud deployment
- structured logging

---

## Phase 3 — Machine Learning
**January–March 2027**

Core skills:

- NumPy
- Pandas
- data cleaning
- exploratory analysis
- statistics
- scikit-learn
- supervised learning
- unsupervised learning
- train/validation/test splits
- cross-validation
- feature engineering
- preprocessing pipelines
- metrics
- overfitting / underfitting
- bias / variance
- model selection
- experiment tracking concepts

Primary project:

**End-to-end ML system**

```text
real dataset
  ↓
cleaning
  ↓
feature engineering
  ↓
model selection
  ↓
cross-validation
  ↓
metrics / evaluation
  ↓
API
  ↓
deployment
  ↓
monitoring
```

---

## Phase 4 — Deep Learning
**March–May 2027**

Core skills:

- PyTorch
- tensors
- datasets / dataloaders
- neural-network architecture
- forward/backward propagation
- loss functions
- optimizers
- training loops
- validation
- embeddings
- NLP fundamentals
- attention
- transformers

The objective is conceptual and engineering competence, not becoming a research scientist.

---

## Phase 5 — LLM Engineering
**May–July 2027**

Core skills:

- LLM APIs
- Hugging Face Transformers
- tokenization
- embeddings
- prompt/context design
- structured outputs
- function/tool calling
- retrieval
- vector search
- RAG
- chunking strategies
- reranking concepts
- grounding
- citations/source attribution
- multimodal model usage
- latency and cost considerations

Primary objective:

Build systems that use models reliably rather than merely sending prompts to an API.

---

## Phase 6 — Agentic AI and Production AI Systems
**July–September 2027**

Core skills:

- agents
- tool use
- MCP
- memory/state
- workflow orchestration
- multi-step reasoning systems
- human-in-the-loop architecture
- multi-agent patterns when justified
- AI evaluations
- hallucination / grounding evaluation
- tracing
- observability
- model routing
- fallback strategies
- caching
- queues
- asynchronous processing
- security
- prompt-injection defense
- permissions / least privilege
- cost tracking
- latency tracking
- AWS
- infrastructure patterns
- CI/CD
- production deployment
- monitoring

Target specialization:

**Production AI Systems / Agentic AI Engineering**

---

# 8. Semester 1 — Foundation Semester

**Start:** September 8, 2026  
**Hard deadline:** December 14, 2026  
**Length:** 14 weeks / 98 days  
**Normal workload:** ~30 hours/week  
**Maximum planned workload:** ~420 hours

Three tracks:

- Track A: Programming & Software Engineering
- Track B: Developer Tools & Data
- Track C: Mathematics for AI

Important sequencing correction:

DeepLearning.AI mathematics does **not** start on Day 1 because basic Python familiarity is recommended. The first two weeks focus heavily on Python. Math begins in Week 3.

---

# 9. Semester 1 Courses

## Course 1 — Harvard CS50P: Introduction to Programming with Python

Official course:
https://cs50.harvard.edu/python/

Units:

0. Functions and Variables
1. Conditionals
2. Loops
3. Exceptions
4. Libraries
5. Unit Tests
6. File I/O
7. Regular Expressions
8. Object-Oriented Programming
9. Et Cetera
10. Final Project

Target finish:

**October 26, 2026 maximum**

Stretch target:

**October 12–19, 2026**

CS50P final-project requirements should be followed exactly according to the current course specification.

Core competency:

- write Python independently
- structure functions
- validate input
- handle errors
- use libraries
- test code
- work with files
- use regex
- understand OOP

---

## Course 2 — GitHub Foundations (GH-900)

Core areas:

- Git/GitHub basics
- repositories
- collaboration
- modern development
- GitHub Projects
- privacy/security/administration
- GitHub community

Practical Git commands that must become functional:

```bash
git init
git status
git add
git commit
git log
git diff
git branch
git switch
git merge
git clone
git pull
git push
```

Concepts:

- repository
- commit
- branch
- merge
- remote
- origin
- pull request
- issue
- fork
- clone
- README
- `.gitignore`
- license
- Actions
- Codespaces
- branch protection
- 2FA
- permissions

Certification target:

**Weeks 5–7**

---

## Course 3 — Harvard CS50 SQL

Official course:
https://cs50.harvard.edu/sql/

Units:

0. Querying
1. Relating
2. Designing
3. Writing
4. Viewing
5. Optimizing
6. Scaling
7. Final project

Core concepts:

- SELECT
- WHERE
- ORDER BY
- GROUP BY
- JOIN
- subqueries
- primary keys
- foreign keys
- normalization
- CREATE TABLE
- INSERT
- UPDATE
- DELETE
- views
- indexes
- transactions
- constraints
- database design
- SQLite
- PostgreSQL concepts

Starts after CS50P or immediately when CS50P is completed early.

---

## Course 4 — Linux Foundation LFS101: Introduction to Linux

Primary objective:

Become comfortable enough with Linux to work in cloud and production environments. Do not turn this into sysadmin specialization.

Commands to practice:

```bash
pwd
ls
cd
mkdir
touch
cp
mv
rm
cat
less
grep
find
head
tail
chmod
ps
top
kill
curl
wget
ssh
pip
python
```

Concepts:

- filesystem
- users/groups
- permissions
- processes
- package management
- shell
- networking
- environment variables
- SSH
- logs
- Bash scripting
- pipes and redirection

---

## Course 5 — DeepLearning.AI Mathematics for Machine Learning and Data Science

Starts:

**Week 3**

Core areas:

### Linear Algebra
- scalars
- vectors
- matrices
- dot products
- systems of equations
- linear transformations
- eigenvalues/eigenvectors

### Calculus
- functions
- derivatives
- partial derivatives
- gradients
- optimization
- gradient descent

### Probability / Statistics
- random variables
- distributions
- expected value
- variance
- Gaussian distribution
- sampling
- estimation
- confidence intervals
- hypothesis testing
- Bayesian concepts

The objective is practical ML mathematics, not proof-heavy pure mathematics.

---

# 10. Semester 1 Weekly Schedule

## Week 1 — Sep 8–14

- CS50P Functions & Variables
- CS50P Conditionals
- Git/GitHub basics
- small Python exercises
- personal budget calculator v0.1
- no ML math yet

## Week 2 — Sep 15–21

- Python loops
- exceptions
- Git add/commit/push/pull
- command-line expense tracker v0.1
- no ML math yet

## Week 3 — Sep 22–28

- Python libraries
- Git branches
- GitHub Flow
- pull requests
- math begins
- scalars/vectors/matrices
- linear equations

## Week 4 — Sep 29–Oct 5

- pytest / unit testing
- GitHub collaboration
- matrix operations
- dot products
- linear transformations
- add tests to Python work

## Week 5 — Oct 6–12

- file I/O
- regular expressions
- GH-900 review
- eigenvalues/eigenvectors

## Week 6 — Oct 13–19

- object-oriented programming
- GH-900 practice/exam
- calculus
- slopes
- derivatives
- optimization

## Week 7 — Oct 20–26

- CS50P final project
- finish GH-900
- derivatives / optimization

## Week 8 — Oct 27–Nov 2

- CS50 SQL: Querying
- Linux terminal/filesystem
- gradients

## Week 9 — Nov 3–9

- SQL: Relating
- Linux files/text
- gradient descent

## Week 10 — Nov 10–16

- SQL: Designing
- Linux users/permissions/processes
- probability fundamentals

## Week 11 — Nov 17–23

- SQL: Writing
- Bash
- environment variables
- probability distributions

## Week 12 — Nov 24–30

- SQL: Viewing
- networking
- HTTP
- SSH
- curl
- statistics / sampling

## Week 13 — Dec 1–7

- SQL: Optimizing
- Bash scripts
- Python on Linux
- confidence intervals
- hypothesis testing
- Bayesian concepts

## Week 14 — Dec 8–14

- SQL: Scaling
- SQL final project
- LFS101 completion
- mathematics completion/review

---

# 11. Week 1 Detailed Operating Plan

**Target:** 30 productive hours

Normal structure:

- Tuesday: 5h
- Wednesday: 5h
- Thursday: 5h
- Friday: 5h
- Saturday: 5h
- Sunday: 5h
- Monday: 0 planned; rest/catch-up/accelerate

Approximate distribution:

- CS50P instruction: ~10h
- Python exercises/problem sets: ~7h
- Git/GitHub: ~6h
- independent programming: ~4h
- budget project: ~2h
- review/documentation: ~1h

Week 1 competency gate:

1. Write a small Python program without copying a tutorial.
2. Understand variables, types, functions, arguments, parameters, and return values.
3. Use `if / elif / else` correctly.
4. Read and investigate a basic Python error.
5. Use `git add → commit → push` independently.
6. Have a functioning Python program in GitHub that can be explained line-by-line.

If completed early, immediately begin Week 2.

---

# 12. Semester 1 Portfolio

## Project 1 — Python Expense Tracker

Purpose:

Demonstrate:

- Python
- functions
- OOP
- exceptions
- file handling
- tests
- Git
- documentation

Potentially usable as the CS50P final project if it satisfies all current course rules.

---

## Project 2 — Sports Analytics Database

Potential schema:

- teams
- players
- games
- events
- statistics
- predictions
- model_runs

Demonstrate:

- relational modeling
- SQL
- joins
- indexes
- constraints
- query design
- optimization
- documentation

Potentially usable as the CS50 SQL final project if it satisfies all current course rules.

---

## Project 3 — AI Engineering Journey Repository

This repository itself demonstrates:

- Git/GitHub
- Codespaces
- documentation
- CI
- progressive engineering practices
- learning history

Small exercises are **not** to be presented as major portfolio projects.

---

# 13. Semester 2 — Backend + Machine Learning Acceleration

Semester 2 should begin immediately after Semester 1 or sooner where prerequisites are complete.

The updated Semester 2 direction is:

### Track A — Backend Engineering

- FastAPI
- HTTP
- REST
- Pydantic
- PostgreSQL
- authentication concepts
- validation
- testing
- logging

### Track B — Data Engineering for ML

- NumPy
- Pandas
- data cleaning
- transformations
- exploratory analysis

### Track C — Andrew Ng Machine Learning Specialization

Core concepts:

- supervised learning
- regression
- classification
- regularization
- neural-network introduction
- decision trees
- unsupervised learning
- recommender concepts
- reinforcement-learning introduction where included

### Engineering layer

- GitHub Actions
- containers where useful
- deployment
- basic cloud infrastructure
- DSA essentials

DSA scope:

- arrays
- hash maps
- stacks
- queues
- trees
- graphs
- Big-O
- recursion
- searching
- sorting
- common interview patterns

Do not turn this into a hundreds-of-LeetCode grind.

---

# 14. Later Technical Curriculum

## Machine Learning Stack

- NumPy
- Pandas
- scikit-learn
- statistical evaluation
- feature engineering
- pipelines
- experiment tracking
- model serving

## Deep Learning Stack

- PyTorch
- neural networks
- optimization
- embeddings
- NLP
- attention
- transformers

## LLM Engineering Stack

- Hugging Face
- LLM APIs
- structured outputs
- embeddings
- retrieval
- vector search
- RAG
- reranking
- tool calling
- multimodal AI

## Agentic AI Stack

- agents
- tool orchestration
- MCP
- state
- memory
- workflows
- human-in-the-loop
- multi-agent systems only when justified

## AI Reliability / Evaluation

- evaluation datasets
- regression tests for AI behavior
- hallucination checks
- grounding checks
- tracing
- observability
- latency
- token usage
- cost optimization
- guardrails
- model fallbacks
- error handling

## Security

- secret management
- IAM concepts
- least privilege
- prompt injection
- data exfiltration risks
- tool permissions
- input/output validation
- dependency security

## Cloud / Production

Primary cloud target:

**AWS**

Likely concepts/services later:

- IAM
- S3
- compute
- networking fundamentals
- CloudWatch
- Lambda where appropriate
- ECS/container deployment where appropriate
- Bedrock where appropriate
- SageMaker where appropriate
- queues
- caching
- managed databases

Cloud choice should be architecture-driven, not certification-driven.

---

# 15. Production AI Architecture Skills

By the final phase, the learner should understand and practice:

- API architecture
- event-driven systems
- queues
- asynchronous jobs
- caching
- database design
- vector search
- model routing
- fallbacks
- rate limits
- retries
- idempotency
- structured logs
- metrics
- traces
- cost control
- latency budgets
- scalable inference concepts
- distributed-system fundamentals
- human escalation paths

---

# 16. Flagship Production AI Project

The final flagship should resemble a real production AI application rather than a notebook demo.

Expected architecture:

```text
User / Client
    ↓
API
    ↓
Authentication / Authorization
    ↓
AI Orchestration Layer
    ↓
────────────────────────────────────
│ Retrieval / Vector Search         │
│ LLM / Model                       │
│ Tools / APIs                      │
│ Structured Outputs               │
│ Agent / Workflow State            │
────────────────────────────────────
    ↓
PostgreSQL / persistent storage
    ↓
Evaluation / Observability / Tracing
    ↓
Cloud deployment
```

Expected production characteristics:

- authentication
- PostgreSQL
- RAG when justified
- source grounding/citations
- evaluation suite
- observability
- caching
- error handling
- cost tracking
- latency tracking
- CI/CD
- security controls
- cloud deployment

Existing real projects may evolve into capstones if technically appropriate. Do not build artificial resume projects solely to check boxes.

---

# 17. Certifications — Priority Rules

Certifications are secondary to real engineering ability.

Early certification:

- GitHub Foundations GH-900

Possible later certifications when the underlying skills exist:

- AWS Machine Learning Engineer Associate
- NVIDIA Generative AI / LLM credential where relevant
- Terraform Associate where infrastructure-as-code becomes useful
- other AI/cloud credentials only if they support a job target

Do **not** rush advanced cloud or AI certifications before practical experience.

Avoid obsolete certifications.

---

# 18. What Is Intentionally Deprioritized

Not part of the immediate pathway:

- C
- C++
- Java certification
- JavaScript frameworks during foundation phase
- React during foundation phase
- Kubernetes early
- Terraform early
- Spark early
- Kafka early
- Airflow early
- multiple cloud platforms
- TensorFlow unless a project/job requires it
- advanced LeetCode grind
- advanced pure mathematics before practical ML
- fine-tuning LLMs before basic LLM systems are understood
- agent frameworks before APIs/RAG/evals/tool use are understood

These tools are not necessarily bad. They are simply lower priority for this target.

---

# 19. Employment Strategy

The goal is to begin earning engineering experience before the entire AI curriculum is finished.

## After Semester 1

Reasonable targets:

- Junior Software Engineer
- Software Engineer I
- Junior Developer
- Python development/support
- QA Automation
- Junior SDET
- Application Support Developer
- Technical Support Engineer with scripting
- software internships/apprenticeships
- some junior data-oriented roles using Python/SQL

Do **not** market as an AI Engineer yet solely from Semester 1.

## After backend phase

Stronger targets:

- Python Backend Engineer
- Software Engineer I
- API/backend roles
- platform-support engineering
- data/backend roles

## After ML phase

Add:

- junior ML-oriented software roles
- applied ML roles
- data/ML engineering roles where experience requirements fit

## Summer/Fall 2027

Begin serious applications for:

- AI Engineer
- Applied AI Engineer
- LLM Engineer
- AI Software Engineer
- Agentic AI Engineer
- ML Engineer where skill alignment fits

Hiring is not guaranteed by a date. Competency is the primary gate.

---

# 20. Resume Story We Are Building

Desired eventual positioning:

> Software Engineer with production Python/backend/cloud experience, machine learning fundamentals, and hands-on experience building, evaluating, deploying, and monitoring LLM/agentic AI systems.

Avoid presenting as:

> Someone who completed many AI courses and certificates.

The portfolio and deployed engineering work should provide the evidence.

---

# 21. Repository Structure

```text
ai-engineering-journey/
├── .devcontainer/
│   └── devcontainer.json
├── .github/
│   └── workflows/
│       └── python-ci.yml
├── semester-1/
│   ├── week-01/
│   │   ├── exercises/
│   │   ├── projects/
│   │   └── notes/
│   ├── week-02/
│   ├── week-03/
│   └── ...
├── projects/
├── tests/
├── .env.example
├── .gitignore
├── requirements.txt
├── pyproject.toml
└── README.md
```

As the curriculum progresses, additional semester/phase directories can be added.

---

# 22. Engineering Standards for This Repository

- Keep dependencies minimal.
- Never commit API keys, credentials, tokens, `.env`, or secrets.
- Prefer reproducible cloud environments.
- Use meaningful commits.
- Use branches and pull requests as Git competence grows.
- Test before pushing.
- Keep exercises separate from portfolio projects.
- Avoid unnecessary abstractions.
- Avoid premature frameworks.
- Introduce tools only when the curriculum or a real project requires them.
- Prefer official documentation and authoritative courses.
- Fix CI failures rather than ignoring them.
- Document important architecture decisions.
- Do not allow AI assistants to silently change the curriculum sequence without a clear technical reason.

---

# 23. Instructions for AI Assistants and Coding Agents

Any AI working in this repository should follow these rules:

1. Read this README before making curriculum or architecture decisions.
2. Determine the learner's current phase before introducing new tooling.
3. Do not jump directly to advanced AI frameworks while fundamentals are incomplete.
4. Do not solve foundational coursework wholesale unless explicitly asked for a worked solution outside academic-integrity constraints.
5. Prefer explanation, debugging guidance, review, and scaffolding during foundational learning.
6. Keep the environment cloud-first and lightweight.
7. Do not add Railway to this learning repository.
8. Do not install heavyweight ML/AI packages before their phase unless a real task requires them.
9. Preserve portfolio-quality engineering practices.
10. If a competency is completed early, accelerate to the next prerequisite-compatible skill.
11. If a proposed tool does not materially improve employability or production AI competence, question whether it belongs in the roadmap.
12. The long-term specialization is **Production AI Systems / Agentic AI Engineering**, backed by software engineering and ML fundamentals.

---

# 24. Current Status

Current phase:

**Semester 1 — Week 1**

Immediate priorities:

1. CS50P Functions & Variables
2. CS50P Conditionals
3. Git/GitHub foundations
4. small independently written Python programs
5. Week 1 budget calculator
6. commit and push work from Codespaces

Math begins in Week 3.

SQL and Linux become primary tracks after the early Python/Git phase or sooner if prerequisite work is completed early.

---

# 25. Definition of Success

The objective is not simply to finish this README's checklist.

Success means being able to build and defend a production-quality AI system:

- explain the code
- explain the data
- explain the model choice
- explain the evaluation
- explain the architecture
- explain failure modes
- explain security boundaries
- explain cost/latency tradeoffs
- deploy it
- monitor it
- improve it

That is the standard this curriculum is designed to reach.
