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

## Target realism

At the currently declared workload of about **30 hours per week**, applying for AI Engineer and Applied AI Engineer roles by August to September 2027 is realistic as an application target.

It is not a guarantee of being competitive for every AI Engineer opening. Many roles still expect professional software engineering experience. The goal is to be technically ready to apply broadly, with production-oriented portfolio evidence, while also applying earlier to junior software, backend, and ML-adjacent roles.

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

Current declared weekly capacity:

**30 productive hours per week**

This number is retained because it is the only explicit weekly capacity currently declared in the repository and prior plan. If a different realistic weekly capacity is set, rescale the blocks instead of silently increasing daily workload.

Study cadence:

- Tuesday through Sunday: study days
- Monday: fixed rest day
- unfinished work rolls into the next study day or next week
- Monday is never converted into catch-up time

All time blocks are estimates.

For every block:

- if the "done when" condition is met early, move to the next block
- if the estimate expires first, stop at a sensible checkpoint, record the blocker, and roll the unfinished work forward
- do not add hours merely to preserve a calendar label
- competency gates matter more than exact minutes

Calendar dates are maximum windows, not mastery guarantees.

If a competency is genuinely completed early, move to the next prerequisite-compatible topic.

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

# 6. Academic Honesty and AI-Assistance Rules

## CS50 boundary

All official CS50 assessment code stays in **cs50.dev**.

This public repository contains only:

- original non-CS50 practice programs
- original projects
- notes
- curriculum files
- tooling and CI configuration

Do not copy CS50 problem-set code into this public repository, even after submission.

For CS50 assessments:

- use https://cs50.dev/
- follow https://cs50.harvard.edu/python/honesty/
- do not use ChatGPT, Claude, Copilot, Gemini, or other external AI systems to suggest or complete answers or lines of code
- use CS50's own AI tools only where the course permits them
- do not publish assessment solutions

## Outside CS50 assessments

AI may be used for:

- explanations
- debugging help after an attempt
- code review
- practice questions
- comparing approaches
- documentation lookup
- architecture discussion

Preferred requests include:

- Explain why this error occurs.
- Give me one hint, not the solution.
- Ask me questions that lead me to the answer.
- Review my solution after I finish it.
- Give me a similar practice problem.

If the learner cannot explain the important lines and decisions, the work is not considered learned.

---

# 7. One-Year Roadmap

The phases intentionally overlap. Software engineering, ML theory, and AI-system work are not treated as a strict waterfall.

## Phase 1 - Programming and Engineering Foundation
**September to November 2026**

Core skills:

- Python
- Git
- GitHub
- Linux shell
- SQL
- relational database design
- testing fundamentals
- practical mathematics for ML
- basic data structures and algorithms

Primary outcomes:

- independently write small Python programs
- read tracebacks and debug basic failures
- use Git safely
- work in a Linux shell
- design/query relational databases
- write tests
- understand where Python fits in a larger software system

## Phase 2 - Backend + First LLM API System + ML Theory
**November 2026 to January 2027**

Tracks run in parallel.

### Backend track

- HTTP
- REST
- FastAPI
- Pydantic
- PostgreSQL
- authentication concepts
- pytest
- API testing
- structured logging
- environment variables and secrets
- GitHub Actions
- cloud deployment
- containers when justified

### Small LLM API project

Build a small API-backed AI application after basic FastAPI and HTTP skills are functional.

The project should include:

- one hosted LLM API
- clear system/user input boundaries
- structured output where appropriate
- a small set of hand-written evaluation cases
- basic pass/fail or rubric-based evals
- latency and cost notes
- error handling
- no agent-framework requirement

The purpose is to learn early how an LLM fits inside software without skipping software-engineering fundamentals.

### ML theory in parallel

Begin or continue:

- linear algebra
- calculus for optimization
- probability/statistics
- supervised-learning concepts
- loss functions
- overfitting/underfitting
- evaluation metrics

## Phase 3 - Applied Machine Learning Engineering
**January to March 2027**

Core skills:

- NumPy
- Pandas
- data cleaning
- exploratory analysis
- scikit-learn
- feature engineering
- preprocessing pipelines
- train/validation/test splits
- cross-validation
- supervised learning
- unsupervised learning
- metrics
- model selection
- experiment tracking concepts
- model serving

Primary project flow:

real dataset -> cleaning -> feature engineering -> model selection -> cross-validation -> evaluation -> API -> deployment -> monitoring

## Phase 4 - Deep Learning
**March to May 2027**

Core skills:

- PyTorch
- tensors
- datasets/dataloaders
- neural networks
- loss functions
- optimizers
- training loops
- validation
- embeddings
- NLP fundamentals
- attention
- transformers

The goal is engineering competence, not research-scientist depth.

## Phase 5 - LLM Engineering, Retrieval, and Evals
**May to July 2027**

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
- chunking
- reranking concepts
- grounding
- citations/source attribution
- multimodal usage
- eval datasets
- regression evals
- hallucination/grounding checks
- tracing and observability
- latency and cost measurement

Evals are treated as part of LLM engineering, not as an end-stage add-on.

## Phase 6 - Agentic and Production AI Systems
**July to September 2027**

Core skills:

- agents
- tool use
- MCP
- memory/state
- workflow orchestration
- human-in-the-loop patterns
- multi-agent patterns when justified
- queues
- asynchronous processing
- caching
- model routing
- fallback strategies
- permissions and least privilege
- prompt-injection defense
- data-exfiltration controls
- AWS
- production deployment
- monitoring
- CI/CD
- reliability engineering

Target specialization:

**Production AI Systems / Agentic AI Engineering**

---

# 8. Semester 1 - Foundation Semester

**Official start:** September 15, 2026  
**End:** December 21, 2026  
**Length:** 14 weeks  
**Target:** about 30 productive hours per week  
**Study days:** Tuesday through Sunday  
**Monday:** fixed rest day

Three tracks:

- Track A: Programming and Software Engineering
- Track B: Developer Tools and Data
- Track C: Mathematics for AI

Math starts in **Week 3** and continues in parallel.

CS50P runs through **Week 7**, ending November 2, 2026.

SQL becomes the primary database course in **Week 8**.

Shell basics start in Week 1. Formal Linux study expands later in the semester.

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

## Course 2 - Git and GitHub

Week 1 Git is intentionally narrow.

Required in Week 1:

- clone
- status
- add
- commit
- push
- log

Delayed until **Week 3 or later**:

- branches
- diff
- pull requests
- GitHub Flow
- GitHub Foundations certification path

The goal in Week 1 is to form a reliable basic source-control habit without overloading the first Python week.

## MIT Missing Semester shell basics

Week 1 includes one hour using:

https://missing.csail.mit.edu/2026/course-shell/

Required skills:

- pwd
- ls
- cd
- mkdir
- running a Python file from the shell

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

## Course 5 - DeepLearning.AI Mathematics for Machine Learning and Data Science

Starts in **Week 3** and continues through the semester in parallel with Python, SQL, and later backend work.

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

## Week 1 - Sep 15 to Sep 21

- CS50P Functions and Variables
- CS50P Conditionals
- official CS50 Problem Set 0 and early Problem Set 1 work in cs50.dev only
- original non-CS50 Python practice in this repository
- Git: clone, status, add, commit, push, log
- one hour of shell basics
- scheduled traceback/debugging practice
- Personal Budget Calculator v0.1
- Monday rest

## Week 2 - Sep 22 to Sep 28

- CS50P Loops
- CS50P Exceptions
- finish any rolled Week 1 work before advancing
- original loop/exception practice
- Git repetition using only the Week 1 command set
- no formal GitHub Foundations yet

## Week 3 - Sep 29 to Oct 5

- CS50P Libraries
- Git branches and diff
- GitHub Flow and pull requests
- GitHub Foundations path begins
- math begins: vectors, matrices, linear equations

## Week 4 - Oct 6 to Oct 12

- CS50P Unit Tests
- pytest
- GitHub collaboration
- matrix operations
- dot products
- linear transformations

## Week 5 - Oct 13 to Oct 19

- CS50P File I/O
- regular expressions
- GitHub Foundations study
- eigenvalues/eigenvectors

## Week 6 - Oct 20 to Oct 26

- CS50P Object-Oriented Programming
- GitHub Foundations study/exam prep
- calculus
- derivatives
- optimization

## Week 7 - Oct 27 to Nov 2

- CS50P Et Cetera
- CS50P final project
- finish core GitHub Foundations work
- gradients and gradient descent

## Week 8 - Nov 3 to Nov 9

- CS50 SQL Querying
- Linux filesystem/terminal
- math continuation
- first backend/HTTP orientation if the Python competency gate is met

## Week 9 - Nov 10 to Nov 16

- SQL Relating
- Linux files/text
- probability fundamentals
- backend basics continue where ready

## Week 10 - Nov 17 to Nov 23

- SQL Designing
- Linux users/permissions/processes
- probability/statistics
- FastAPI introduction when prerequisites are met

## Week 11 - Nov 24 to Nov 30

- SQL Writing
- Bash/environment variables
- statistics
- FastAPI/Pydantic practice
- first small LLM API experiment may begin if HTTP/API basics are functional

## Week 12 - Dec 1 to Dec 7

- SQL Viewing
- networking/HTTP/SSH/curl
- statistics/sampling
- small LLM API project plus basic eval cases

## Week 13 - Dec 8 to Dec 14

- SQL Optimizing
- Bash scripts
- confidence intervals/hypothesis testing
- backend/LLM project continuation

## Week 14 - Dec 15 to Dec 21

- SQL Scaling
- SQL final project
- Semester 1 math review
- shell/Linux review
- backend/LLM project checkpoint
- Semester 1 competency review

---

# 11. Week 1 Operating Rules

Detailed day-by-day work lives in:

semester-1/week-01/README.md

and the revised Week 1 PDF.

Week 1 completion gate:

1. Write a small original Python program without copying a tutorial.
2. Explain variables, types, functions, parameters, arguments, and return values.
3. Use basic conditionals correctly.
4. Read and investigate a basic Python traceback.
5. Use basic shell navigation.
6. Use clone, status, add, commit, push, and log for original repository work.
7. Keep all CS50 assessment code in cs50.dev.
8. Keep Monday as a rest day.

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

**Semester 1 - Week 1**

Current source-of-truth Week 1 file:

semester-1/week-01/README.md

Follow the revised Week 1 PDF and this repository, not older schedules.

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


---

# 26. Python Learning Protocol — Problem-Solving Layer

This protocol supplements CS50P. It does **not** replace the curriculum or add a second full Python course.

The useful ideas are:

- use one primary long-form Python course
- practice writing code instead of only watching lessons
- deliberately train problem-solving
- visualize execution when concepts are hard to understand
- use AI as a tutor rather than an answer generator
- understand where Python fits in a real software/AI system
- begin building small original projects before feeling completely ready

## 26.1 One-Course Rule

**CS50P remains the canonical Python course.**

Do not add Zero to Mastery, Bro Code, Automate the Boring Stuff, or another full beginner Python course at the same time.

Supplemental resources are allowed only for targeted practice or visualization.

Reason:

> Multiple beginner courses create repetition without necessarily increasing independent problem-solving ability.

## 26.2 Daily Problem-Solving Warm-Up

After the learner is functional with variables, functions, and conditionals, begin each Python study session with a short problem-solving warm-up.

Recommended resource:

https://www.codewars.com/kata/search/python

Rules:

- Python only
- begin with **8 kyu**
- one kata per study session
- target 10–15 minutes
- hard cap: 20 minutes before switching to the stuck protocol
- do not copy another solution before attempting the problem
- after solving, compare one or two community solutions and identify one cleaner idea
- do not allow Codewars to replace the day's main curriculum work

Progression:

~~~text
8 kyu
  ↓
comfortable solving independently
  ↓
7 kyu
  ↓
DSA phase later
  ↓
selected LeetCode problems
~~~

There is no requirement to grind large numbers of problems.

## 26.3 Stuck Protocol

Feeling stuck is expected. The learner should not immediately outsource the problem to AI.

Use this sequence:

~~~text
1. Restate the problem in plain English.
2. Write the expected input and output.
3. Break the problem into smaller steps.
4. Try a small example manually.
5. Write pseudocode.
6. Attempt the code.
7. Read the error / traceback.
8. Check official documentation or course notes.
9. Use Python Tutor if execution flow is unclear.
10. Ask AI for a hint or explanation, not a complete solution.
11. Retry the solution independently.
12. Explain the finished solution without looking at it.
~~~

Suggested timer:

- 20–25 minutes of focused independent effort
- short break if needed
- then escalate through the protocol

The objective is not to remain stuck indefinitely. The objective is to avoid skipping the reasoning stage.

## 26.4 Python Tutor

Resource:

https://pythontutor.com/

Use Python Tutor when a concept is difficult to visualize, especially:

- variable assignment
- function calls
- scope
- loops
- conditionals
- lists/dictionaries
- recursion later
- object references later

Python Tutor should be used to answer:

> What is Python doing at each step?

It is a visualization/debugging supplement, not a replacement for writing code.

## 26.5 Practice Python

Resource:

https://www.practicepython.org/exercises/

Practice Python contains more than 40 small beginner exercises.

It is introduced **after loops and basic exception handling are functional**, rather than on Day 1.

Recommended use:

- 2–3 exercises per week
- choose exercises aligned with concepts already learned
- solve in Codespaces
- store selected solutions under the appropriate weekly exercises directory
- attempt the problem before viewing any published solution
- do not complete all 40 simply to check a box

This resource exists to increase independent code-writing repetitions.

## 26.6 30 Days of Python — Selective Project Bank

Reference:

https://github.com/Asabeneh/30-Days-Of-Python

Do **not** run this as a second parallel Python course.

Use it selectively after the core CS50P fundamentals are established.

Useful later topics include:

- functions
- modules
- exceptions
- regex
- file handling
- virtual environments
- classes/objects
- web concepts
- APIs
- Pandas

Skip or defer content that conflicts with the main curriculum sequence.

The repository is a **practice/project bank**, not a curriculum authority.

## 26.7 Software-Lifecycle Context

Very early in the curriculum, maintain a high-level picture of where Python will eventually sit:

~~~text
user / client
    ↓
frontend or external system
    ↓
Python API / backend
    ↓
business logic
    ↓
database / files / external APIs
    ↓
ML model or LLM
    ↓
evaluation / monitoring
    ↓
cloud infrastructure
~~~

During Weeks 1–2, spend no more than roughly **60–90 minutes total** on this architecture orientation.

The purpose is context, not premature infrastructure study.

Do not derail the foundation phase by trying to learn Docker, AWS, FastAPI, databases, and ML all at once.

## 26.8 Build Before Feeling Ready

Once enough syntax exists to create a small program, begin original projects.

The project sequence is:

~~~text
tiny exercises
   ↓
budget calculator
   ↓
expense tracker
   ↓
database-backed application
   ↓
production backend
   ↓
ML system
   ↓
production AI system
~~~

Each project should require some independent decisions rather than copying a tutorial line-for-line.

Projects should evolve in complexity as skills are acquired.

## 26.9 Product-Building / SaaS Principle

Building a real product can be valuable, but it is **not a Week 1 objective**.

After backend engineering fundamentals are functional, one portfolio project may be developed as a real product with:

- FastAPI
- PostgreSQL
- authentication
- payments only if the product genuinely needs them
- CI/CD
- cloud deployment
- logging/monitoring
- later, AI/ML capabilities where justified

The purpose is to create evidence of production engineering ability, not to force every project into a startup.

Existing Hawknetic projects may be used when they provide a better real-world problem than an invented tutorial application.

## 26.10 Revised Daily Python Session Pattern

Once the Codewars warm-up begins, a typical Python-focused study block becomes:

~~~text
10–15 min   8-kyu Codewars warm-up
60–90 min   CS50P lesson / problem set
45–90 min   independent implementation
10–20 min   debugging / Python Tutor / documentation
5–10 min    explain what was learned + commit meaningful work
~~~

The 10–15 minute warm-up comes **out of existing practice time**. It does not increase the 30-hour weekly workload.

## 26.11 AI Tutor Rules — Strengthened

When asking an AI assistant for help with foundational Python, preferred requests are:

- "Explain why this error occurs."
- "Give me one hint, not the solution."
- "Ask me questions that lead me to the answer."
- "Review my solution after I finish it."
- "Show me what concept I am misunderstanding."
- "Give me a similar practice problem."

Avoid:

- "Write the assignment for me."
- pasting a full generated answer into CS50
- accepting code that cannot be explained line-by-line

AI is functioning correctly when it **increases the learner's reasoning ability**, not when it removes the reasoning.

## 26.12 What We Are Explicitly Not Adopting

Some claims from informal Python-learning content are too aggressive and are **not** part of this roadmap.

We do not assume that:

- knowing basic Python alone makes someone job-ready
- completing 30 beginner projects equals professional experience
- building a SaaS is required for employability
- Codewars performance alone measures engineering ability
- every Python learner should immediately learn Docker/backend/ML simultaneously

Professional readiness still requires the broader roadmap in this README:

**Python + Git + Linux + SQL + software engineering + APIs + testing + databases + deployment + ML + AI systems.**

## 26.13 Immediate Integration Into Semester 1

The following changes take effect now:

### Week 1
- Keep CS50P as the only long-form Python course.
- Use Python Tutor when functions/conditionals are confusing.
- Introduce the stuck protocol immediately.
- Do not add another Python course.
- After Functions & Variables plus basic Conditionals are functional, optionally begin one **8-kyu Codewars** problem at the start of Python sessions.
- Codewars is capped at 15 minutes normally and 20 minutes maximum.

### Weeks 2–3
- Continue one short Codewars warm-up per Python study session.
- After Loops and Exceptions are functional, add **2–3 Practice Python exercises per week**.
- Start using pseudocode before non-trivial exercises.

### Weeks 4–7
- Continue CS50P as primary.
- Use selected Practice Python / 30 Days of Python exercises only when they reinforce the current CS50P topic.
- Increase independent project work.
- Do not increase total weekly hours merely to fit supplemental material.

### After CS50P
- Shift emphasis from beginner exercises to the Expense Tracker, SQL, backend engineering, and progressively more realistic projects.
- Codewars continues as a small problem-solving warm-up.
- LeetCode is deferred until the DSA/interview phase.

This protocol is subordinate to the competency gates and acceleration rules already defined above.
