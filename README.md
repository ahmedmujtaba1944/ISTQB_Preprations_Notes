# 📘 ISTQB® CTFL v4.0 — Complete Preparation Notes (Foundation Level)

> **One-stop study guide** for the ISTQB® Certified Tester Foundation Level (CTFL) exam, written from the **official CTFL Syllabus v4.0.1** and the official ISTQB® exam structure.
> Prepared for taking the exam from **Pakistan** 🇵🇰.
>
> ⚠️ The **official syllabus is the only source the exam questions are written from**. These notes summarize it chapter by chapter — if anything here ever disagrees with the syllabus PDF, **the syllabus wins**.

---

## 📑 Table of Contents

**Part A – Exam Information**
1. [Exam Facts at a Glance](#1-exam-facts-at-a-glance)
2. [Questions per Chapter & K-Levels](#2-questions-per-chapter--k-levels)
3. [Taking the Exam from Pakistan](#3-taking-the-exam-from-pakistan)
4. [Official Study Material (and what's in this repo)](#4-official-study-material-and-whats-in-this-repo)
5. [4-Week Study Plan](#5-4-week-study-plan)
6. [My Focus Areas (from my practice-exam mistakes)](#6-my-focus-areas-from-my-practice-exam-mistakes)

**Part B – Chapter Notes (Syllabus v4.0.1)**
- [Chapter 1 – Fundamentals of Testing](#chapter-1--fundamentals-of-testing-180-min--8-questions)
- [Chapter 2 – Testing Throughout the SDLC](#chapter-2--testing-throughout-the-sdlc-130-min--6-questions)
- [Chapter 3 – Static Testing](#chapter-3--static-testing-80-min--4-questions)
- [Chapter 4 – Test Analysis and Design](#chapter-4--test-analysis-and-design-390-min--11-questions)
- [Chapter 5 – Managing the Test Activities](#chapter-5--managing-the-test-activities-335-min--9-questions)
- [Chapter 6 – Test Tools](#chapter-6--test-tools-20-min--2-questions)

**Part C – Practice**
- [Worked Examples for Every K3 Topic](#part-c--worked-examples-for-every-k3-topic)
- [Q&A Bank – Chapter-wise Practice Questions](#part-d--qa-bank-chapter-wise-practice-questions)

**Part E – Revision**
- [Must-Know Lists (the "magic numbers")](#part-e--must-know-lists-the-magic-numbers)
- [v3.1 → v4.0 Terminology Changes](#v31--v40-terminology-changes)
- [Exam-Day Strategy](#exam-day-strategy)
- [Last-Night Cheat Sheet](#last-night-cheat-sheet)

---

# PART A – EXAM INFORMATION

## 1. Exam Facts at a Glance

| Item | Detail |
|---|---|
| Certification | ISTQB® Certified Tester Foundation Level (CTFL) **v4.0** |
| Current syllabus | **CTFL Syllabus v4.0.1** (examined version is "CTFL v4.0") |
| Questions | **40** multiple-choice |
| Points | **1 point per question** (40 total) |
| Pass mark | **26 / 40 (65%)** |
| Duration | **60 minutes** |
| Extra time | **+25% (75 min total)** if you take the exam in a language that is not your native language — confirm with your exam provider at registration |
| Negative marking | **None** → never leave a question blank |
| Pre-requisite | None |
| Validity | **Lifetime** — CTFL does not expire |
| Question format | Single answer (A/B/C/D) **or** "Select TWO" (A–E). A "select TWO" question scores only if **both** picks are correct |

## 2. Questions per Chapter & K-Levels

**K-levels (cognitive levels) used in the exam:**

| K-level | Meaning | Typical verbs in the LO | Questions | ~Time each |
|---|---|---|---|---|
| **K1** – Remember | Recall a term or fact | identify, recall, recognize | **8** | 1 min |
| **K2** – Understand | Explain, compare, classify | explain, distinguish, compare, summarize, exemplify | **24** | 1 min |
| **K3** – Apply | Use a technique on a scenario | use, apply, prepare | **8** | 3 min |

**Questions per chapter (official exam structure):**

| Chapter | Training time | Questions | K1 | K2 | K3 |
|---|---|---|---|---|---|
| 1. Fundamentals of Testing | 180 min | **8** | 2 | 6 | 0 |
| 2. Testing Throughout the SDLC | 130 min | **6** | 2 | 4 | 0 |
| 3. Static Testing | 80 min | **4** | 2 | 2 | 0 |
| 4. Test Analysis and Design | 390 min | **11** | 0 | 6 | **5** |
| 5. Managing the Test Activities | 335 min | **9** | 1 | 5 | **3** |
| 6. Test Tools | 20 min | **2** | 1 | 1 | 0 |
| **Total** | ~19 h | **40** | 8 | 24 | 8 |

> 💡 **Chapters 4 + 5 = 20 questions (50% of the exam)** and contain **all 8 K3 (calculation/application) questions**. Chapter 1 + 2 = another 14. Master these four chapters and you pass.

**Where the K3 questions come from:**
- Ch 4 (5 questions): Equivalence Partitioning, Boundary Value Analysis, Decision Tables, State Transition, ATDD
- Ch 5 (3 questions): Estimation techniques, Test case prioritization, Defect report

## 3. Taking the Exam from Pakistan

| Option | Details |
|---|---|
| **PSTB – Pakistan Software Testing Board** | The official ISTQB® **Member Board for Pakistan** (founded 2015). Address on the ISTQB directory: Room E-216, FAST-NU, A.K. Brohi Road, H-11/4, Islamabad. Website: **https://pstb.pk** · Email: **info@pstb.pk**. PSTB has historically run exam sessions in **Lahore, Islamabad and Karachi**. |
| **PITB reimbursement (Punjab)** | In **July 2025** PITB signed an MoU with PSTB under which ISTQB exam candidates could get their **certification cost reimbursed**. Ask PSTB/PITB whether this scheme is still open before you pay. |
| **Other accredited exam providers** | ISTQB® keeps the official list here: **https://istqb.org/exam-providers/?directory_type=exam-providers&exam=CTFL%204.0** — some providers offer **online remote-proctored** exams (e.g., AT*SQA/ASTQB list the CTFL voucher at **USD 229** for 2026). Check that the provider accepts candidates from Pakistan. |
| **Verify your certificate** | All passed candidates appear in the ISTQB® **Successful Candidate Register**: https://scr.istqb.org |

**Registration checklist**
- [ ] Check current exam fee, dates and city on **pstb.pk** (an older PSTB page listed **Rs 30,000** — confirm the current amount)
- [ ] Ask about the **PITB reimbursement** if you are in Punjab
- [ ] Request the **+25% extra time** (non-native English) if eligible
- [ ] Use your name exactly as on your **CNIC/passport** (it goes on the certificate)
- [ ] Bring original **CNIC/passport** on exam day

## 4. Official Study Material (and what's in this repo)

**Official ISTQB® CTFL page:** https://istqb.org/certifications/certified-tester-foundation-level-ctfl-v4-0/
**Official ISTQB® Glossary:** https://glossary.istqb.org

| Material | In this repo | Latest on istqb.org (Oct 2026) | Action |
|---|---|---|---|
| CTFL Syllabus | [v4.0.1](ISTQB_CTFL_Syllabus_v4.0.1.pdf) | v4.0.1 | ✅ Up to date |
| Sample Exam A | [Q v1.6](ISTQB_CTFL_v4.0_Sample-Exam-A-Questions_v1.6.pdf) | **v1.7** | ⬆️ Download newer version |
| Sample Exam B | [Q v1.6](ISTQB_CTFL_v4.0_Sample-Exam-B-Questions_v1.6.pdf) / [A v1.6](ISTQB_CTFL_v4.0_Sample-Exam-B-Answers_v1.6.pdf) | **v1.7** | ⬆️ Download newer version |
| Sample Exam C | [Q v1.5](ISTQB_CTFL_v4.0_Sample-Exam-C-Questions_v1.5.pdf) / [A v1.5](ISTQB_CTFL_v4.0_Sample-Exam-C-Answers_v1.5.pdf) | **v1.6** | ⬆️ Download newer version |
| Sample Exam D | [Q v1.4](ISTQB_CTFL_v4.0_Sample-Exam-D-Questions_v1.4.pdf) / [A v1.4](ISTQB_CTFL_v4.0_Sample-Exam-D-Answers_v1.4.pdf) | **v1.5** | ⬆️ Download newer version |
| Exam Structure Tables | [v1.10](ISTQB_Exam-Structure-Tables_v1.10.pdf) | v1.19 | ⬆️ CTFL numbers unchanged (40 Q / 26 pass / 60 min) |
| Extra sample exams 3 & 4 | [Exam 3 Q](CTFL-4.0-Sample-Exam3-2-Questions.pdf) · [Exam 4 Q](CTFL-4.0-Sample-Exam4-3-Questions.pdf) | — | Extra practice |

> Note: Sample Exam A **Answers** is not yet uploaded to this repo — download it from istqb.org together with the newer versions.

## 5. 4-Week Study Plan

| Week | Days | Study | Practice |
|---|---|---|---|
| **1** | Mon–Tue | Ch 1 (Fundamentals) — read syllabus + these notes | Ch 1 Q&A below |
|  | Wed | Ch 2 (SDLC) | Ch 2 Q&A |
|  | Thu | Ch 3 (Static) | Ch 3 Q&A |
|  | Fri–Sun | Revise Ch 1–3, make flashcards of all lists | — |
| **2** | Mon–Tue | Ch 4: EP + BVA (2-value & 3-value) | Worked examples 1–3 |
|  | Wed | Ch 4: Decision tables + State transition | Worked examples 4–5 |
|  | Thu | Ch 4: White-box + Experience-based + Collaboration (ATDD) | Worked examples 6–7, Ch 4 Q&A |
|  | Fri–Sun | Re-do all K3 examples from scratch without looking | — |
| **3** | Mon–Tue | Ch 5: Planning, estimation, prioritization, pyramid, quadrants | Worked examples 8–9 |
|  | Wed | Ch 5: Risk, monitoring/control, CM, defect report | Ch 5 Q&A |
|  | Thu | Ch 6 Tools | Ch 6 Q&A |
|  | Sat | **Official Sample Exam A** (timed, 60 min) | Review every wrong answer against the syllabus |
|  | Sun | **Official Sample Exam B** (timed) | Review |
| **4** | Mon | **Official Sample Exam C** (timed) | Review |
|  | Tue | **Official Sample Exam D** (timed) | Review |
|  | Wed–Thu | Sample Exams 3 & 4 + weak areas | Target **≥ 32/40** consistently |
|  | Fri | Read the full syllabus once more | Must-Know Lists |
|  | Sat | Last-Night Cheat Sheet only, sleep early | — |

> 🎯 **Target:** Score **32+ / 40** on official sample exams before booking. Pass mark is 26, but the real exam is usually a little harder than you expect — keep a safety margin.

## 6. My Focus Areas (from my practice-exam mistakes)

Scores so far: **Sample A 27 · B 24 · C 25 · D 31 · Exam 3 34 · Exam 4 31** → trend is improving, but A/B/C were close to the pass line (26).

Topics I got wrong most often (from my score sheet) and where to fix them:

| Weak topic | Where in these notes |
|---|---|
| BVA 2-value vs 3-value, coverage % | [4.2.2](#422-boundary-value-analysis-bva--k3) · [Example 2 & 3](#example-2--bva-2-value-vs-3-value) |
| State transition diagram/table → test cases & coverage | [4.2.4](#424-state-transition-testing--k3) · [Example 5](#example-5--state-transition-testing) |
| Decision tables → test cases | [4.2.3](#423-decision-table-testing--k3) · [Example 4](#example-4--decision-table-testing) |
| ATDD / user story → test cases, acceptance criteria types | [4.5](#45-collaboration-based-test-approaches) · [Example 7](#example-7--atdd) |
| Estimation techniques ("read question carefully") | [5.1.4](#514-estimation-techniques--k3) · [Example 8](#example-8--estimation) |
| Branch testing / coverage items | [4.3](#43-white-box-test-techniques) · [Example 6](#example-6--statement--branch-coverage) |
| Review types (informal / walkthrough / technical / inspection) | [3.2.4](#324-review-types--k2) |
| Regression vs confirmation testing | [2.2.3](#223-confirmation-testing-vs-regression-testing--k2) |
| Error vs defect vs failure, testing vs debugging | [1.1.2](#112-testing-vs-debugging--k2) · [1.2.3](#123-error--defect--failure--root-cause--k2) |
| Product vs project risk, risk level, mitigation/transfer | [5.2](#52-risk-management) |
| Testware per activity, risk register, traceability | [1.4.3](#143-testware--k2) · [1.4.4](#144-traceability--k2) |
| Tester vs test-manager responsibilities | [1.4.5](#145-roles-in-testing--k2) |
| Entry/exit criteria, test case prioritization, defect report | [5.1.3](#513-entry-criteria-vs-exit-criteria--k2) · [5.1.5](#515-test-case-prioritization--k3) · [5.5](#55-defect-management--k3) |

---

# PART B – CHAPTER NOTES (SYLLABUS v4.0.1)

> Each section heading shows the **Learning Objective (LO)** and its **K-level**. K1 = memorize the list. K2 = understand the difference/example. K3 = be able to do the calculation.

---

## Chapter 1 – Fundamentals of Testing (180 min · 8 questions)

**Keywords:** coverage, debugging, defect, error, failure, quality, quality assurance, root cause, test analysis, test basis, test case, test completion, test condition, test control, test data, test design, test execution, test implementation, test monitoring, test object, test objective, test planning, test procedure, test process, test result, testing, testware, traceability, validation, verification

### 1.1 What is Testing?

**Testing** = a set of activities to **discover defects** and **evaluate the quality** of software work products. The work product being tested is called the **test object**.

Two common misconceptions the exam likes to test:
1. ❌ "Testing = only running tests." → ✅ Testing also includes planning, analysis, design, reviews, reporting etc.
2. ❌ "Testing = only verification." → ✅ Testing includes **verification** *and* **validation**.

| Verification | Validation |
|---|---|
| "Are we building the product **right**?" | "Are we building the **right** product?" |
| Checks the system meets **specified requirements** | Checks the system meets **users' and stakeholders' needs** in its operational environment |

| Static testing | Dynamic testing |
|---|---|
| Software is **not executed** | Software **is executed** |
| Reviews + static analysis | Uses test techniques to derive test cases |

Testing is also a **management activity** (planned, estimated, monitored, controlled) and largely an **intellectual activity** (analytical, critical and systems thinking). Further reading standard: **ISO/IEC/IEEE 29119-1**.

#### 1.1.1 Typical Test Objectives — K1

Memorize this list (9 objectives):
1. **Evaluating work products** (requirements, user stories, designs, code)
2. **Causing failures and finding defects**
3. **Ensuring required coverage** of a test object
4. **Reducing the risk level** of inadequate software quality
5. **Verifying** whether specified requirements have been fulfilled
6. **Verifying compliance** with contractual, legal and regulatory requirements
7. **Providing information to stakeholders** for informed decisions
8. **Building confidence** in the quality of the test object
9. **Validating** that the test object is complete and works as stakeholders expect

Test objectives **vary with context**: the work product, test level, risks, SDLC, and business factors (corporate structure, competition, time to market).

#### 1.1.2 Testing vs Debugging — K2

| Testing | Debugging |
|---|---|
| **Triggers failures** (dynamic) or **finds defects directly** (static) | **Finds, analyzes and removes the cause** (defect) |
| A testing activity | **NOT** a testing activity (a development activity) |

**Debugging process after dynamic testing:** 1) **Reproduce** the failure → 2) **Diagnose** (find the defect) → 3) **Fix** the defect.
Then: **Confirmation testing** checks the fix worked (preferably done **by the same person who ran the initial test**) → **Regression testing** checks the fix didn't break anything else.

**After static testing:** debugging only needs to **remove** the defect — no reproduction or diagnosis is needed because static testing finds defects directly and **cannot cause failures**.

### 1.2 Why is Testing Necessary?

Testing is a form of **quality control** that helps achieve test objectives within scope, time, quality and budget constraints. **Any stakeholder** can use testing skills — it is not restricted to the test team.

#### 1.2.1 Testing's Contributions to Success — K2

- **Cost-effective way to detect defects** → defects removed by debugging → **indirectly** improves quality
- **Directly evaluates quality** at various SDLC phases → supports decisions such as **the release decision**
- Gives users **indirect representation** on the project (testers make sure user needs are considered — cheaper than involving real users throughout)
- May be **required** to meet contractual, legal or regulatory standards

#### 1.2.2 Testing vs Quality Assurance (QA) — K1

| Testing (= Quality Control) | Quality Assurance |
|---|---|
| **Product**-oriented | **Process**-oriented |
| **Corrective** | **Preventive** |
| Focus: achieving quality levels in the product | Focus: implementing and **improving processes** ("good process → good product") |
| Test results used to **fix defects** | Test results used as **feedback on how well processes perform** |
| — | Applies to development **and** testing; **everyone's responsibility** |

Other forms of quality control (besides testing): formal methods (model checking, proof of correctness), simulation, prototyping.

#### 1.2.3 Error → Defect → Failure → Root Cause — K2

```
 Human ERROR (mistake)  ──produces──►  DEFECT (fault, bug)  ──may cause──►  FAILURE
   (in a person's head)                 (in a work product)                 (observable wrong behavior at runtime)
```

| Term | Meaning | Example |
|---|---|---|
| **Error (mistake)** | A human action that produces a wrong result | Developer misunderstands the discount rule |
| **Defect (fault, bug)** | An imperfection in a work product (requirements, code, test script, build file…) | Code uses `>` instead of `>=` |
| **Failure** | System does something it shouldn't, or doesn't do what it should | Customer aged exactly 60 doesn't get the senior discount |
| **Root cause** | The **fundamental reason** for the problem (e.g., the situation that led to the error) | Requirements were never reviewed; developer was under time pressure |

Key facts:
- Errors happen due to **time pressure, complexity, tiredness, lack of training**, etc.
- A defect **may or may not** cause a failure (some always, some only in specific conditions, some never).
- Failures can also be caused by **environmental conditions** (e.g., radiation/electromagnetic fields causing defects in firmware).
- **Root cause analysis** is done when a failure occurs or a defect is found; fixing the root cause **prevents similar future defects**.

> 🧠 **Exam trap:** "The developer typed the wrong variable name" → that's the **error**. "The wrong variable name in the code" → **defect**. "The report shows the wrong total" → **failure**. "Developers had no coding standard / no training" → **root cause**.

### 1.3 The Seven Testing Principles — K2

| # | Principle | Meaning in one line |
|---|---|---|
| 1 | **Testing shows the presence, not the absence of defects** | Testing reduces the probability of hidden defects but can **never prove** the software is defect-free |
| 2 | **Exhaustive testing is impossible** | Except trivial cases. Use **test techniques, test case prioritization and risk-based testing** to focus effort |
| 3 | **Early testing saves time and money** | Defects removed early don't cause defects in derived work products → lower cost of quality. Start **static and dynamic** testing as early as possible |
| 4 | **Defects cluster together** | A few components contain most defects (**Pareto principle**). Predicted & actual clusters are input for **risk-based testing** |
| 5 | **Tests wear out** *(was "pesticide paradox")* | Repeating the same tests finds fewer new defects → modify tests/data, write new ones. **But** repeating is beneficial for **automated regression testing** |
| 6 | **Testing is context dependent** | No single approach fits all — e.g., safety-critical vs mobile game |
| 7 | **Absence-of-defects fallacy** | Fixing all defects / verifying all requirements doesn't guarantee success — the system may still not meet user needs → also do **validation** |

> 🧠 Memory hook: **"P-E-E-D-T-C-A"** → **P**resence, **E**xhaustive, **E**arly, **D**efects cluster, **T**ests wear out, **C**ontext, **A**bsence-of-defects.

### 1.4 Test Activities, Testware and Test Roles

#### 1.4.1 Test Activities and Tasks — K2

A **test process** = the set of test activities. Activities may look sequential but are often **iterative or in parallel**, and are **tailored** to the project (decided in test planning). Reference: **ISO/IEC/IEEE 29119-2**.

| Activity | Key tasks | Answers |
|---|---|---|
| **Test planning** | Define **test objectives** and select the **approach** within constraints | — |
| **Test monitoring & control** | **Monitoring** = ongoing check of all test activities, compare **actual vs plan**. **Control** = take **actions** to meet objectives | — |
| **Test analysis** | Analyze the **test basis** → identify **testable features** → define & prioritize **test conditions** (considering risk). Also evaluate test basis/object for defects and **testability** | **"WHAT to test?"** (in measurable coverage criteria) |
| **Test design** | Elaborate test conditions into **test cases** and other testware (e.g., **test charters**); identify **coverage items**; define **test data requirements**, design **test environment**, identify infrastructure & tools | **"HOW to test?"** |
| **Test implementation** | **Create/acquire testware** (test data); organize test cases into **test procedures** and **test suites**; create manual/automated **scripts**; build the **test execution schedule**; **build & verify the test environment** | "Do we now have everything to run?" |
| **Test execution** | **Run tests** per schedule (test runs), manual or automated (incl. continuous testing, pair testing); **compare actual vs expected**; **log results**; **analyze anomalies**; **report defects** | — |
| **Test completion** | At milestones (release, end of iteration, test level done): create **change requests/backlog items** for unresolved defects; **archive/hand over** useful testware; **shut down environment** to agreed state; analyze **lessons learned**; create the **test completion report** | — |

> 🧠 **Exam trap:** "Building and verifying the test environment" = **Implementation**. "**Designing** the test environment / identifying infrastructure" = **Design**. "Prioritizing test **conditions**" = **Analysis**. "Arranging test procedures in an execution schedule" = **Implementation**.

#### 1.4.2 Test Process in Context — K2

Contextual factors that shape **how** testing is done:
1. **Stakeholders** (needs, expectations, willingness to cooperate)
2. **Team members** (skills, experience, availability, training needs)
3. **Business domain** (criticality, risks, market needs, legal regulations)
4. **Technical factors** (type of software, architecture, technology)
5. **Project constraints** (scope, time, budget, resources)
6. **Organizational factors** (structure, policies, practices)
7. **SDLC** (engineering practices, development methods)
8. **Tools** (availability, usability, compliance)

These affect: **test strategy, test techniques, degree of automation, required coverage, level of detail of testware, test reporting**.

#### 1.4.3 Testware — K2

**Testware** = output work products of the test activities. Kept consistent with **configuration management**.

| Activity | Testware (work products) |
|---|---|
| **Planning** | **Test plan**, test schedule, **risk register**, entry criteria, exit criteria *(schedule, risk register & criteria are often part of the test plan)* |
| **Monitoring & control** | **Test progress reports**, documentation of **control directives**, risk information |
| **Analysis** | (Prioritized) **test conditions** (e.g., acceptance criteria), **defect reports on the test basis** |
| **Design** | (Prioritized) **test cases**, **test charters**, **coverage items**, **test data requirements**, **test environment requirements** |
| **Implementation** | **Test procedures**, manual & automated **test scripts**, **test suites**, **test data**, **test execution schedule**, **test environment items** (stubs, drivers, simulators, service virtualization) |
| **Execution** | **Test logs**, **defect reports** |
| **Completion** | **Test completion report**, action items for improvement, documented **lessons learned**, **change requests** (e.g., product backlog items) |

> **Risk register** = list of risks with **risk likelihood, risk impact** and **mitigation** information.

> 🧠 Note the difference: test **data requirements** = Design; test **data** itself = Implementation. Test **environment requirements** = Design; test **environment items** (stubs, drivers) = Implementation.

#### 1.4.4 Traceability — K2

Maintain traceability between **test basis ↔ testware (test conditions, risks, test cases) ↔ test results ↔ defects**.

Value of traceability:
- Supports **coverage evaluation** (e.g., test cases → requirements shows which requirements are covered)
- Test results → risks lets you evaluate **residual risk**
- Determines the **impact of changes**
- Facilitates **audits** and helps meet **IT governance** criteria
- Makes progress and completion **reports easier to understand**
- Helps communicate technical aspects of testing to stakeholders
- Gives information to assess **product quality, process capability and project progress** against business goals

#### 1.4.5 Roles in Testing — K2

| Test management role | Testing role |
|---|---|
| Overall responsibility for the **test process, test team, leadership** | Overall responsibility for the **engineering (technical)** aspect of testing |
| Focus: **planning, monitoring, control, completion** | Focus: **analysis, design, implementation, execution** |
| Can be done by a test manager, team leader, development manager, or partly by the Agile team | Done by testers (or anyone with the skills) |

One person may hold both roles at the same time; different people may hold them at different times.

> 🧠 **Exam trap:** "Which is a task of the **testing** role?" → anything in analysis/design/implementation/execution (e.g., *creating test data, evaluating test basis, running tests, logging defects*). Writing the test plan or the completion report → **test management** role.

### 1.5 Essential Skills and Good Practices in Testing

#### 1.5.1 Generic Skills Required for Testing — K2

| Skill | Why |
|---|---|
| **Testing knowledge** | Increase **effectiveness** (e.g., using test techniques) |
| **Thoroughness, carefulness, curiosity, attention to detail, being methodical** | Find defects, especially hard-to-find ones |
| **Good communication, active listening, team player** | Interact with stakeholders, report & discuss defects |
| **Analytical thinking, critical thinking, creativity** | Increase **effectiveness** |
| **Technical knowledge** | Increase **efficiency** (e.g., using appropriate tools) |
| **Domain knowledge** | Understand and communicate with end users/business |

Testers are often the **"bearers of bad news"** → communication skills are crucial. **Confirmation bias** can make people reject bad news. Communicate defects **constructively**.

#### 1.5.2 Whole Team Approach — K1

- Comes from **Extreme Programming (XP)**
- **Anyone** with the knowledge and skills can do **any task**; **everyone is responsible for quality**
- Team shares the same **workspace** (physical or virtual) — co-location helps communication
- Benefits: improves **team dynamics**, enhances **communication and collaboration**, creates **synergy** by using all skill sets
- Testers help business reps write **acceptance tests** and agree **test strategy/automation approach** with developers
- ⚠️ **Not always appropriate** — e.g., **safety-critical** systems may need a **high level of test independence**

#### 1.5.3 Independence of Testing — K2

| Level of independence | Who tests |
|---|---|
| **None** | The **author** tests their own work |
| **Some** | **Peers** from the same team |
| **High** | Testers from **outside the author's team but inside the organization** |
| **Very high** | Testers from **outside the organization** |

Best practice: **multiple levels** — e.g., developers do component & component-integration testing, test team does system & system-integration testing, business reps do acceptance testing.

| ✅ Benefits | ❌ Drawbacks |
|---|---|
| Independent testers find **different kinds of defects** (different backgrounds, perspectives, **biases**) | **Isolation** from the dev team → lack of collaboration, communication problems, **adversarial relationship** |
| Can **verify, challenge or disprove assumptions** made by stakeholders | Developers may **lose their sense of responsibility for quality** |
|  | Testers may be seen as a **bottleneck** or **blamed for release delays** |

> Independence is **not a replacement for familiarity** — developers can efficiently find many defects in their own code.

---

## Chapter 2 – Testing Throughout the SDLC (130 min · 6 questions)

**Keywords:** acceptance testing, black-box testing, component integration testing, component testing, confirmation testing, functional testing, integration testing, maintenance testing, non-functional testing, regression testing, shift left, system integration testing, system testing, test level, test object, test type, white-box testing

### 2.1 Testing in the Context of an SDLC

**SDLC models:**
- **Sequential**: Waterfall, **V-model**
- **Iterative**: Spiral, Prototyping
- **Incremental**: Unified Process

**Methods & Agile practices:** ATDD, BDD, DDD (domain-driven design), XP, FDD (feature-driven development), Kanban, Lean IT, Scrum, TDD.

#### 2.1.1 Impact of the SDLC on Testing — K2

The chosen SDLC affects:
1. **Scope and timing** of test activities (test levels & types)
2. **Level of detail** of test documentation
3. Choice of **test techniques and test approach**
4. **Extent of test automation**
5. **Role and responsibilities** of a tester

| Sequential (Waterfall/V) | Iterative / Incremental | Agile |
|---|---|---|
| Early phases: testers do **requirement reviews, test analysis, test design** | Each iteration delivers a working increment → **static & dynamic testing at all test levels in every iteration** | Change expected throughout → **lightweight documentation** |
| Code comes late → **dynamic testing can't start early** | Needs **fast feedback** and **extensive regression testing** | **Extensive test automation** for regression |
|  |  | Manual testing mostly **experience-based** (little upfront analysis/design) |

#### 2.1.2 Good Testing Practices for ANY SDLC — K1

1. For **every development activity** there is a **corresponding test activity**
2. **Different test levels** have **specific and different objectives** (comprehensive but no redundancy)
3. **Test analysis and design** for a level **begins during the corresponding development phase** (early testing)
4. Testers **review work products as soon as drafts are available** (supports shift left)

#### 2.1.3 Test-First Approaches (Testing as a Driver for Development) — K1

All three: tests defined **before** code → implement **early testing** & **shift left**, support **iterative** development, and tests may persist as **automated regression tests**.

| Approach | Key points |
|---|---|
| **TDD** – Test-Driven Development | Directs **coding** through test cases. Cycle: **write test → write code to pass → refactor** test & code. Developer/unit level |
| **ATDD** – Acceptance Test-Driven Development | Tests derived from **acceptance criteria** as part of the **system design** process; written **before** the part of the application is developed |
| **BDD** – Behavior-Driven Development | Desired behavior written in **simple natural language** understood by stakeholders, usually **Given / When / Then**; then translated into **executable tests** |

#### 2.1.4 DevOps and Testing — K2

**DevOps** = organizational approach bringing **development (incl. testing) and operations** together with common goals. Requires a **cultural shift**. Promotes team autonomy, fast feedback, integrated toolchains, **CI/CD**, delivery pipeline.

| ✅ Benefits for testing | ❌ Risks / challenges |
|---|---|
| **Fast feedback** on code quality and regressions | **Delivery pipeline** must be defined and established |
| **CI promotes shift left** (developers submit code with component tests & static analysis) | **CI/CD tools** must be introduced and maintained |
| Automated CI/CD helps establish **stable test environments** | **Test automation** needs extra resources; hard to establish & maintain |
| Better visibility of **non-functional** characteristics (performance, reliability) | |
| Pipeline automation **reduces repetitive manual testing** | |
| **Regression risk minimized** by large automated regression suites | |

> ⚠️ **Manual testing — especially from the user's perspective — is still needed** in DevOps.

#### 2.1.5 Shift Left — K2

**Shift left = early testing principle** → test earlier in the SDLC (but **don't neglect** later testing).

Good practices for shift left:
1. **Review specifications from a tester's perspective** (find ambiguity, incompleteness, inconsistency)
2. **Write test cases before the code** and run code in a test harness during implementation
3. Use **CI** and, even better, **CD** (fast feedback, automated component tests)
4. Do **static analysis** of source code **before** dynamic testing (or as part of automation)
5. Start **non-functional testing at component level** where possible

Shift left may cost **more training/effort early** but should **save effort/cost later**. **Stakeholder buy-in** is essential.

#### 2.1.6 Retrospectives and Process Improvement — K2

Held at end of project/iteration, at release milestones, or **when needed**. Participants: testers, developers, architects, product owner, BAs… They discuss:
1. What was **successful** and should be **retained**?
2. What was **not successful** and could be **improved**?
3. **How** to incorporate improvements and retain successes?

Results are recorded, normally in the **test completion report**. Improvements must be **followed up**.

Benefits for testing: increased **test effectiveness/efficiency**; increased **quality of testware**; **team bonding and learning**; improved **quality of the test basis**; better **dev–test cooperation**.

### 2.2 Test Levels and Test Types

- **Test level** = group of test activities organized and managed together; an **instance of the test process** at a given development stage. (Sequential models: exit criteria of one level are often part of entry criteria of the next.)
- **Test type** = group of test activities related to **specific quality characteristics**; most test types can be performed at **every** test level.

#### 2.2.1 The Five Test Levels — K2

| Test level | Focus | Typically done by / notes |
|---|---|---|
| **Component testing** (unit testing) | Components **in isolation** | **Developers**, in their dev environment; needs **test harnesses / unit test frameworks** |
| **Component integration testing** (unit integration) | **Interfaces & interactions between components** | Depends on **integration strategy**: **bottom-up, top-down, big-bang** |
| **System testing** | Overall behavior & capabilities of the **whole system**: end-to-end **functional** + **non-functional** | Often an **independent test team**; based on **system specifications**; some NFRs (e.g., usability) best tested on the complete system in a representative environment; simulations of subsystems possible |
| **System integration testing** | Interfaces between the system and **other systems / external services** | Needs test environments **similar to operational** |
| **Acceptance testing** | **Validation** & **readiness for deployment** — meets the **user's business needs** | Ideally by **intended users**. Forms: **UAT, operational acceptance (OAT), contractual, regulatory, alpha, beta** |

Test levels are distinguished by: **test object, test objectives, test basis, defects & failures, approach & responsibilities**.

> 🧠 **Alpha** = at the developer's site by potential users; **Beta** = at the users' own locations. (Both are forms of acceptance testing.)

#### 2.2.2 The Four Test Types — K2

| Test type | What it evaluates |
|---|---|
| **Functional testing** | **"What"** the system should do. Checks functional **completeness, correctness, appropriateness** |
| **Non-functional testing** | **"How well"** the system behaves — quality characteristics from **ISO/IEC 25010** |
| **Black-box testing** | **Specification-based** — tests derived from documentation, not internal structure. Checks behavior against **specifications** |
| **White-box testing** | **Structure-based** — tests derived from **implementation/internal structure** (code, architecture, workflows, data flows). Aim: **cover the structure** to an acceptable level |

**ISO/IEC 25010 non-functional characteristics (8):**
1. Performance efficiency
2. Compatibility
3. Usability (also called **interaction capability**)
4. Reliability
5. Security
6. Maintainability
7. Portability (also called **flexibility**)
8. Safety

> 🧠 Mnemonic: **"PC-URS-MPS"** → **P**erformance, **C**ompatibility, **U**sability, **R**eliability, **S**ecurity, **M**aintainability, **P**ortability, **S**afety.

Notes: non-functional testing can **start early** (reviews, component tests); many NFR tests **reuse functional tests** with a non-functional check (e.g., response time); **late discovery** of non-functional defects is a **serious project threat**; may need special environments (e.g., **usability lab**).

**All four test types can be applied at all test levels** (with different focus).

#### 2.2.3 Confirmation Testing vs Regression Testing — K2

| Confirmation testing (re-testing) | Regression testing |
|---|---|
| Confirms the **original defect was fixed** | Confirms the change caused **no adverse consequences** elsewhere |
| Re-run tests that **failed** due to the defect, and/or **add new tests** for changes made in the fix | Re-run tests on the **same component, other components, connected systems, and even the environment** |
| If time/money is short: just re-run the steps that reproduce the failure | Do an **impact analysis** first to decide the scope |
| Done **first** | Done **after** (even for a fix already confirmation-tested) |

- Regression suites grow every iteration and run many times → **strong candidate for automation**; start automation **early**; include in **CI**.
- Both are needed at **all test levels** where defects are fixed or changes made.

### 2.3 Maintenance Testing — K2

**Categories of maintenance** (ISO/IEC 14764): **corrective**, **adaptive** (to environment changes), **improving performance or maintainability**. Releases may be **planned** or **unplanned (hot fixes)**.

Maintenance testing = test the **change itself** + **regression test** the unchanged parts (usually most of the system). **Impact analysis** may be done **before** a change to decide whether to make it.

**Scope depends on:**
1. **Degree of risk** of the change
2. **Size of the existing system**
3. **Size of the change**

**Triggers for maintenance testing:**

| Trigger | Examples / what to test |
|---|---|
| **Modifications** | Planned enhancements (release-based), corrective changes, **hot fixes** |
| **Upgrades or migrations** of the operational environment | Platform change → test the new environment + changed software; **data conversion** testing when migrating data from another application |
| **Retirement** | End of life → test **data archiving**; test **restore and retrieval** procedures if data must be kept |

---

## Chapter 3 – Static Testing (80 min · 4 questions)

**Keywords:** anomaly, dynamic testing, formal review, informal review, inspection, review, static analysis, static testing, technical review, walkthrough

### 3.1 Static Testing Basics

Static testing = evaluate work products **without executing** them — by **manual examination (reviews)** or **tools (static analysis)**. Objectives: improve quality, detect defects, assess **readability, completeness, correctness, testability, consistency**. Usable for **both verification and validation**.

- Testers, business reps and developers collaborate in **example mapping, collaborative user story writing, backlog refinement** to make sure user stories meet criteria such as the **Definition of Ready** and have **testable acceptance criteria**.
- **Static analysis**: finds problems before dynamic testing with **less effort** (no test cases needed, tools used); often part of **CI**; also evaluates **maintainability and security**. Spelling checkers and readability tools are also static analysis tools.

#### 3.1.1 Work Products Examinable by Static Testing — K1

**Almost any** work product: requirement specs, **source code**, test plans, **test cases**, **product backlog items**, **test charters**, project documentation, **contracts**, **models**.
- **Reviews**: any work product that can be **read and understood**.
- **Static analysis**: needs a **formal structure** to check against (models, code, text with formal syntax).
- ❌ **Not appropriate**: work products hard for humans to interpret and that should not be analyzed by tools — e.g., **3rd-party executable code (legal reasons)**.

#### 3.1.2 Value of Static Testing — K2

- Finds defects in the **earliest phases** (early testing principle)
- Finds defects **dynamic testing cannot** (e.g., **unreachable code**, design patterns not implemented as desired, defects in **non-executable** work products)
- Evaluates quality and **builds confidence** in work products; stakeholders confirm requirements reflect **actual needs**
- Creates **shared understanding** and **improves communication** → involve a **wide variety of stakeholders**
- Reviews cost money, but **overall project cost is usually much lower** than without reviews
- Static analysis finds some code defects **more efficiently** than dynamic testing → fewer defects, lower development effort

#### 3.1.3 Static vs Dynamic Testing — K2

| Static testing | Dynamic testing |
|---|---|
| Finds **defects directly** | Causes **failures**; defects found by subsequent analysis |
| Easily reaches **rarely executed / hard-to-reach code paths** | Hard to reach those paths |
| Works on **non-executable** work products too | Only **executable** work products |
| Measures characteristics **not dependent on execution** (e.g., **maintainability**) | Measures characteristics **dependent on execution** (e.g., **performance efficiency**) |

Both **complement** each other; some defect types can only be found by one of them.

**Defects easier/cheaper to find by static testing:**
- **Requirements** defects: inconsistencies, ambiguities, contradictions, omissions, inaccuracies, duplications
- **Design** defects: inefficient database structures, poor modularization
- Certain **coding** defects: variables with undefined values, **undeclared variables**, **unreachable or duplicated code**, **excessive complexity**
- **Deviations from standards** (e.g., naming conventions)
- **Incorrect interface specifications** (mismatched number, type or order of parameters)
- Certain **security vulnerabilities** (e.g., **buffer overflows**)
- **Gaps or inaccuracies in test basis coverage** (e.g., missing tests for an acceptance criterion)

### 3.2 Feedback and Review Process

#### 3.2.1 Benefits of Early and Frequent Stakeholder Feedback — K1

- **Early communication** of potential quality problems
- Without it: product may not match stakeholder vision → **costly rework, missed deadlines, blame games, even project failure**
- Prevents **misunderstandings about requirements**; changes understood and implemented **earlier**
- Team understands what they build better; focuses on features with **most value** and most positive impact on **identified risks**

#### 3.2.2 Review Process Activities (ISO/IEC 20246) — K2

| # | Activity | Key tasks |
|---|---|---|
| 1 | **Planning** | Define **scope**: purpose, work product, quality characteristics to evaluate, focus areas, **exit criteria**, supporting info (standards), effort and timeframes |
| 2 | **Review initiation** | Make sure **everyone and everything is ready**: participants have access to the work product, understand their **roles**, have everything needed |
| 3 | **Individual review** | Each reviewer assesses quality and logs **anomalies, recommendations, questions** using review techniques (e.g., **checklist-based, scenario-based**) |
| 4 | **Communication and analysis** | Anomalies are **not necessarily defects** → analyze & discuss; decide **status, ownership, actions** (typically in a **review meeting**); decide the quality level and follow-up actions |
| 5 | **Fixing and reporting** | Create a **defect report** for each defect; when **exit criteria** are met the work product can be **accepted**; report review results |

> 🧠 Mnemonic: **"P-I-I-C-F"** → **P**lan, **I**nitiate, **I**ndividual, **C**ommunicate, **F**ix. The more formal the review, the more tasks are needed. A large work product may need **several reviews**.

#### 3.2.3 Roles and Responsibilities in Reviews — K1

| Role | Responsibility |
|---|---|
| **Manager** | Decides **what** is reviewed; provides **resources** (staff, time) |
| **Author** | **Creates and fixes** the work product |
| **Moderator** (= **facilitator**) | Ensures **effective running of review meetings**: mediation, **time management**, **safe environment** to speak freely |
| **Scribe** (= **recorder**) | **Collates anomalies** from reviewers; records decisions and new anomalies found in the meeting |
| **Reviewer** | **Performs reviews** (project member, subject matter expert, any stakeholder) |
| **Review leader** | **Overall responsibility** for the review: decides **who** is involved, organizes **when and where** |

> 🧠 **Exam trap:** Manager = *what* + resources. Review leader = *who, when, where*. Moderator = runs the *meeting*.

#### 3.2.4 Review Types — K2

Formality depends on: SDLC, process maturity, **criticality & complexity** of the work product, **legal/regulatory** requirements, need for an **audit trail**. The same work product can be reviewed with different types (informal first, formal later).

| | **Informal review** | **Walkthrough** | **Technical review** | **Inspection** |
|---|---|---|---|---|
| Formality | Lowest — **no defined process**, no formal documented output | Low–medium | Medium–high | **Most formal** — follows the **complete generic process** |
| Led by | — | **The author** | **A moderator** | Review leader (**author cannot be review leader or scribe**) |
| Reviewers | Anyone | Anyone | **Technically qualified** | Participants with defined roles (full process) |
| Individual review before meeting | Optional | Optional (**not required**) | Typically yes | **Yes** (complete process) |
| Main objective | **Detecting anomalies** | Many: evaluate quality, build confidence, **educate reviewers**, gain consensus, generate ideas, motivate authors, detect anomalies | **Gain consensus and make decisions on a technical problem**; also detect anomalies, evaluate quality, generate ideas… | **Find the maximum number of anomalies**; evaluate quality, build confidence, motivate authors |
| Metrics | Not required | Not required | Not required | **Yes — collected and used to improve the SDLC & inspection process** |

> 🧠 Quick identifiers in exam questions:
> - "**Author leads**", "educate", "walk through the document" → **Walkthrough**
> - "**Technical** experts", "**decide** on a technical problem", "moderator" → **Technical review**
> - "**Metrics** collected", "**formal process**", "maximum number of defects", "author can't be scribe" → **Inspection**
> - "Pair review", "buddy check", "no documented output" → **Informal review**

#### 3.2.5 Success Factors for Reviews — K1

1. **Clear objectives** and **measurable exit criteria** — **evaluating participants must NEVER be an objective**
2. Choose the **appropriate review type** for objectives, work product, participants, project needs and context
3. Review **small chunks** (reviewers don't lose concentration)
4. Give **feedback** to stakeholders and authors so they can improve
5. Give participants **adequate time to prepare**
6. **Management support**
7. Make reviews part of the **organization's culture** (learning, process improvement)
8. **Adequate training** for all participants
9. **Facilitate meetings**

---

## Chapter 4 – Test Analysis and Design (390 min · 11 questions)

**Keywords:** acceptance criteria, acceptance test-driven development, black-box test technique, boundary value analysis, branch coverage, checklist-based testing, collaboration-based test approach, coverage, coverage item, decision table testing, equivalence partitioning, error guessing, experience-based test technique, exploratory testing, state transition testing, statement coverage, test technique, white-box test technique

> ⭐ **The most important chapter**: 11 questions, **5 of them K3 calculations**. Practice every technique by hand until you can do it in < 3 minutes.

### 4.1 Test Techniques Overview — K2

Test techniques help in **test analysis (what)** and **test design (how)**: create a **small but sufficient** set of test cases systematically, and identify **test conditions, coverage items and test data**. Reference: **ISO/IEC/IEEE 29119-4**.

| Category | Also called | Based on | Key point |
|---|---|---|---|
| **Black-box** | **Specification-based** | **Specified behavior**, without reference to internal structure | Test cases are **independent of implementation** → still useful if code changes but behavior doesn't |
| **White-box** | **Structure-based** | **Internal structure and processing** | Test cases **depend on the design** → can only be created **after** design/implementation |
| **Experience-based** | — | Tester's **knowledge and experience** | Effectiveness depends on **tester skill**; finds defects black/white-box may miss → **complementary** |

| Black-box techniques | White-box techniques | Experience-based techniques |
|---|---|---|
| Equivalence Partitioning (EP) | Statement testing | Error guessing |
| Boundary Value Analysis (BVA) | Branch testing | Exploratory testing |
| Decision Table Testing |  | Checklist-based testing |
| State Transition Testing |  |  |

Plus **collaboration-based approaches** (4.5): user stories, acceptance criteria, ATDD — focus on **defect avoidance**.

### 4.2 Black-Box Test Techniques

#### 4.2.1 Equivalence Partitioning (EP) — K3

- Divides data into **partitions** where all values are expected to be **processed the same way**.
- Theory: if one value in a partition finds a defect, any other value in it would too → **one test per partition is enough**.
- Partitions can be for **inputs, outputs, configuration items, internal values, time-related values, interface parameters**.
- Partitions may be continuous/discrete, ordered/unordered, finite/infinite. They **must not overlap** and **must be non-empty**.
- **Valid partition** = values that should be processed (or whose processing is specified). **Invalid partition** = values that should be ignored/rejected (or whose processing is not specified).
- **Coverage items = the partitions** (valid **and** invalid).
- **Coverage % = partitions exercised ÷ total partitions identified × 100**
- **Each Choice coverage** (multiple sets of partitions / several parameters): each partition from **each set** exercised **at least once** — does **not** consider combinations. Minimum tests = size of the **largest** set.

> 🧠 **Exam trap:** For 100% EP coverage you need **at least one test per partition including invalid ones**. One test can cover **one valid partition from each parameter** at the same time, but you should test **invalid partitions one at a time** (to avoid defect masking — good practice).

#### 4.2.2 Boundary Value Analysis (BVA) — K3

- Exercises the **boundaries of equivalence partitions** → only for **ordered** partitions.
- **Boundary values** = the **minimum and maximum** values of a partition.
- Why: developers often make errors at boundaries (boundary **misplaced above/below** or **omitted**).

| | **2-value BVA** | **3-value BVA** |
|---|---|---|
| Coverage items per boundary | **2**: the boundary value + its **closest neighbor in the adjacent partition** | **3**: the boundary value + **both** neighbors |
| Rigor | Less | **More rigorous** — can find defects 2-value misses |
| Coverage % | boundary values exercised ÷ total boundary values | (boundaries + neighbors) exercised ÷ total (boundaries + neighbors) |

**Syllabus example of why 3-value is stronger:** correct code `if (x ≤ 10)` wrongly written as `if (x = 10)`. 2-value tests x = 10 and x = 11 → both give the "right" result → defect **not** found. 3-value adds **x = 9** → defect found.

> 🧠 **How to do it fast (the way the official sample exams do it):**
> 1. Write down **ALL** equivalence partitions of the domain — valid **and** invalid.
> 2. The **boundary values** = the **min and max of every partition** (only where they exist — an open-ended partition like "13 and above" has no max).
> 3. **2-value BVA** coverage items = exactly those boundary values (each boundary's closest neighbor in the adjacent partition is itself a boundary value).
> 4. **3-value BVA** coverage items = each boundary value **± 1 step**, keeping only values that exist in the domain, then **remove duplicates**.
> 5. Watch the **step size** (whole numbers? money with 2 decimals → step 0.01).
>
> *Official Sample Exam B example:* password length partitions **{0–5} too short, {6–12} OK, {13+} too long** → boundary values **0, 5, 6, 12, 13** (2-value). 3-value adds **1, 4, 7, 11, 14** → total **0, 1, 4, 5, 6, 7, 11, 12, 13, 14** (no −1, because a length can't be negative).

#### 4.2.3 Decision Table Testing — K3

Used for **combinations of conditions → different outcomes** (business rules, complex logic).

- **Rows** = conditions and actions. **Columns** = **decision rules** (unique combination of conditions + resulting actions).
- **Limited-entry** table: conditions/actions are Boolean (T/F). **Extended-entry**: multiple values (ranges, partitions, discrete values).

| Notation | Meaning |
|---|---|
| **T** | Condition satisfied |
| **F** | Condition not satisfied |
| **–** | Condition **irrelevant** for the outcome |
| **N/A** | Condition **infeasible** for the rule |
| **X** | Action **should occur** |
| *(blank)* | Action **should not** occur |

- **Full table:** number of columns = **2ⁿ** for n Boolean conditions (e.g., 3 conditions → 8 rules).
- **Simplify** by deleting **infeasible** columns; **minimize** by merging columns where a condition doesn't affect the outcome (minimization algorithms are out of scope).
- **Coverage items = columns with feasible combinations.** 100% = every feasible column exercised.
- **Coverage % = exercised columns ÷ feasible columns × 100**
- ✅ Strength: systematic, finds **gaps and contradictions** in requirements. ❌ Rules grow **exponentially** → use minimized table or risk-based selection.

#### 4.2.4 State Transition Testing — K3

- A **state diagram** shows possible **states** and **valid transitions**. A transition is triggered by an **event**, optionally qualified by a **guard condition**, and may produce an **action**.
- Label syntax: **`event [guard condition] / action`**
- A **state table** is equivalent: **rows = states**, **columns = events** (+ guards), cells = target state (+ action). **Empty cells = invalid transitions** — the state table shows invalid transitions **explicitly**; the diagram does not.
- A test case = **sequence of events** → sequence of state changes; one test usually covers **several transitions**.

| Coverage criterion | Coverage items | 100% means | Strength |
|---|---|---|---|
| **All states** | States | Every state visited | Weakest |
| **Valid transitions** (= **0-switch**) | Single valid transitions | Every valid transition exercised | **Most widely used**; 100% here ⇒ 100% all states |
| **All transitions** | All transitions in the **state table** (valid + invalid) | All valid transitions exercised **and** all invalid transitions **attempted** | Strongest; ⇒ 100% all states + valid transitions. **Minimum for mission/safety-critical** software |

- Test **only one invalid transition per test case** → avoids **defect masking** (one defect hiding another).
- Coverage % = items exercised (or attempted) ÷ total items × 100.

### 4.3 White-Box Test Techniques

Only two are examined: **statement testing** and **branch testing** (more rigorous ones exist for safety-critical systems; also API-level or neuron coverage — out of scope).

#### 4.3.1 Statement Testing — K2

- **Coverage items = executable statements.**
- **Statement coverage = statements exercised ÷ total executable statements × 100**
- 100% statement coverage ⇒ every executable statement executed at least once (so every defective statement *is executed*).
- ❌ Does **not** guarantee finding **data-dependent** defects (e.g., division by zero only when denominator = 0).
- ❌ Does **not** guarantee all **decision logic/branches** are tested.

#### 4.3.2 Branch Testing — K2

- **Branch** = transfer of control between two nodes in the **control flow graph** — either **unconditional** (straight-line) or **conditional** (decision outcome: if/then **true/false**, each **switch/case** outcome, **loop** continue/exit).
- **Coverage items = branches.**
- **Branch coverage = branches exercised ÷ total branches × 100**
- 100% branch coverage ⇒ all branches (conditional **and** unconditional) exercised.
- ❌ May not find defects that require a **specific path**.
- ✅ **Branch coverage SUBSUMES statement coverage**: 100% branch ⇒ 100% statement, **but NOT vice versa**.

> 🧠 **Exam trap:** An `if` **without** an `else` still has **two** outcomes (true and false). A test that only takes the true path can give **100% statement coverage but only 50% of the decision outcomes**.

#### 4.3.3 Value of White-Box Testing — K2

- ✅ The **entire implementation** is considered → finds defects even when the specification is **vague, outdated or incomplete**.
- ❌ If a requirement was **never implemented**, white-box testing may **not detect** the resulting **defects of omission**.
- Can be used in **static testing** too (dry runs of code, reviewing pseudocode or logic modeled as a control flow graph, code not ready to execute).
- Black-box testing alone gives **no measure of actual code coverage**; white-box gives an **objective coverage measure** and shows where to add tests → more confidence.

### 4.4 Experience-based Test Techniques

#### 4.4.1 Error Guessing — K2

Anticipate errors, defects and failures based on the tester's knowledge of:
- How the application **worked in the past**
- **Types of errors developers tend to make** and resulting defects
- **Failures in other, similar applications**

Errors/defects/failures may relate to: **input** (valid input rejected, parameters missing), **output** (wrong format/result), **logic** (missing cases, wrong operator), **computation** (wrong operand), **interfaces** (parameter mismatch), **data** (incorrect initialization, wrong type).

**Fault attacks** = a structured way to implement error guessing: create/acquire a **list of possible errors, defects and failures** and design tests to expose them (built from experience, defect data, common knowledge about why software fails).

#### 4.4.2 Exploratory Testing — K2

- Tests are **simultaneously designed, executed and evaluated** while the tester **learns** about the test object.
- **Session-based testing**: within a **time box**, guided by a **test charter** (with test objectives), followed by a **debriefing** with stakeholders; test objectives may be treated as **high-level test conditions**; results recorded on **test session sheets**.
- **Useful when:** specifications are **few/inadequate**, there is **significant time pressure**, or to **complement** formal techniques.
- More effective with an **experienced** tester with **domain knowledge** and skills like **analytical skills, curiosity, creativity**.
- Can **incorporate other techniques** (e.g., EP).

#### 4.4.3 Checklist-Based Testing — K2

- Tester designs, implements and executes tests to cover **test conditions from a checklist**.
- Checklists built from **experience**, knowledge of **what's important to the user**, or **why and how software fails**.
- Items often phrased as **questions**; each must be checkable **separately and directly**.
- ❌ Should **NOT** contain: items that can be **checked automatically**, items better suited as **entry/exit criteria**, or items that are **too general**.
- Can support functional & non-functional testing (e.g., **Nielsen's 10 usability heuristics**).
- Entries become **less effective over time** (developers learn) → **update regularly** based on defect analysis, but don't let it grow **too long**.
- In the absence of detailed test cases it gives **guidelines and consistency**. High-level checklists → **more variability**: potentially **greater coverage but less repeatability**.

### 4.5 Collaboration-based Test Approaches

Focus on **defect avoidance** through collaboration and communication (other techniques focus on defect detection).

#### 4.5.1 Collaborative User Story Writing — K2

**The 3 C's** of a user story:
| C | Meaning |
|---|---|
| **Card** | The **medium** describing the story (index card, entry on an electronic board) |
| **Conversation** | Explains **how the software will be used** (verbal or documented) |
| **Confirmation** | The **acceptance criteria** |

**Format:** *"As a **[role]**, I want **[goal]**, so that I can **[business value]**"* + acceptance criteria.

- Written collaboratively (brainstorming, **mind mapping**) from **three perspectives: business, development, testing** → shared vision.
- Good stories are **INVEST**: **I**ndependent, **N**egotiable, **V**aluable, **E**stimable, **S**mall, **T**estable.
- If a stakeholder **doesn't know how to test** a story → the story may be **unclear**, **not valuable** to them, or they just **need help testing**.

#### 4.5.2 Acceptance Criteria — K2

= Conditions an implementation must meet to be **accepted by stakeholders** → can be viewed as the **test conditions**. Usually a result of the **Conversation**.

Used to:
1. Define the **scope** of the user story
2. Reach **consensus** among stakeholders
3. Describe both **positive and negative** scenarios
4. Serve as the **basis for user story acceptance testing**
5. Allow accurate **planning and estimation**

**Two most common formats:**
| Format | Example |
|---|---|
| **Scenario-oriented** | **Given/When/Then** (BDD) |
| **Rule-oriented** | **Bullet-point verification list**, or **tabulated input-output mapping** |

A team may use a custom format as long as criteria are **well-defined and unambiguous**.

#### 4.5.3 Acceptance Test-Driven Development (ATDD) — K3

- **Test-first** approach: test cases created **before** implementing the story, by people with **different perspectives** (customers, developers, testers). Manual or automated.
- **Step 1 – Specification workshop:** analyze, discuss and write the user story and its acceptance criteria; resolve **incompleteness, ambiguities, defects**.
- **Step 2 – Create test cases** (whole team or the tester), based on acceptance criteria; they are **examples** of how the software works (examples = tests). Techniques from 4.2–4.4 can be applied.
- **Order of test cases:**
  1. **Positive** tests first (correct behavior, no exceptions — the "happy path")
  2. Then **negative** tests
  3. Then **non-functional** characteristics (performance, usability…)
- Test cases written in **natural language** stakeholders understand: **preconditions, inputs, postconditions**.
- Rules: test cases must **cover all characteristics of the story** and **must not go beyond it**; **no two test cases should describe the same characteristic**.
- When captured in an automation-friendly format, developers automate them → acceptance tests become **executable requirements**.

> 🧠 **Exam trap (K3 ATDD):** You'll get a user story + acceptance criteria and must pick the test case that **correctly implements one criterion**. Eliminate options that: test something **not in the story**, contradict a criterion, or have a wrong expected result.

---

## Chapter 5 – Managing the Test Activities (335 min · 9 questions)

**Keywords:** defect management, defect report, entry criteria, exit criteria, product risk, project risk, risk, risk analysis, risk assessment, risk control, risk identification, risk level, risk management, risk mitigation, risk monitoring, risk-based testing, test approach, test completion report, test control, test monitoring, test plan, test planning, test progress report, test pyramid, test strategy, testing quadrants

### 5.1 Test Planning

#### 5.1.1 Purpose and Content of a Test Plan — K2

A **test plan** describes **test objectives, resources and processes** for a test project. It:
- Documents the **means and schedule** for achieving test objectives
- Helps ensure activities **meet established criteria**
- Serves as **communication** with team and stakeholders
- Demonstrates adherence to the **test policy and test strategy** (or explains deviations)

Planning makes testers **think ahead** about risks, schedules, people, tools, costs, effort.

**Typical content (ISO/IEC/IEEE 29119-3):**
1. **Context** of testing (scope, objectives, test basis)
2. **Assumptions and constraints**
3. **Stakeholders** (roles, responsibilities, relevance, hiring & training needs)
4. **Communication** (forms, frequency, templates)
5. **Risk register** (product & project risks)
6. **Test approach** (test levels, types, techniques, deliverables, **entry & exit criteria**, **independence**, **metrics**, test data & environment requirements, deviations from policy/strategy)
7. **Budget and schedule**

#### 5.1.2 Tester's Contribution to Iteration and Release Planning — K1

| Release planning | Iteration planning |
|---|---|
| Looks ahead to the **product release**; defines/re-defines the **product backlog**; splits big stories | Looks ahead to the end of **one iteration**; concerned with the **iteration backlog** |
| Testers: write **testable user stories & acceptance criteria**, take part in **project & quality risk analysis**, **estimate test effort** for stories, determine the **test approach**, **plan testing** for the release | Testers: **detailed risk analysis** of stories, determine **testability**, **break stories into tasks** (esp. testing tasks), **estimate test effort** for all testing tasks, identify & refine **functional and non-functional** aspects |

#### 5.1.3 Entry Criteria vs Exit Criteria — K2

| **Entry criteria** | **Exit criteria** |
|---|---|
| **Preconditions** to start an activity | What must be achieved to **declare an activity complete** |
| If not met → activity more difficult, time-consuming, costly, risky | — |
| Typical: **availability of resources** (people, tools, environments, test data, budget, time); **availability of testware** (test basis, testable requirements, user stories, test cases); **initial quality level** of the test object (e.g., **all smoke tests passed**) | Typical: **measures of thoroughness** (coverage achieved, number of unresolved defects, defect density, number of failed tests); **binary yes/no** criteria (planned tests executed, static testing done, all defects reported, all regression tests automated) |
| Agile name: **Definition of Ready (DoR)** | Agile name: **Definition of Done (DoD)** |

- Defined **per test level**; differ by test objectives.
- **Running out of time or budget** is also a valid exit criterion **if stakeholders have reviewed and accepted the risk** of going live.

#### 5.1.4 Estimation Techniques — K3

Estimates are based on **assumptions** and always have **estimation error**. Small tasks are estimated more accurately → **decompose** large tasks.

| Technique | Type | How it works |
|---|---|---|
| **Estimation based on ratios** | **Metrics-based** | Use **historical ratios** from the organization's own similar projects. *E.g., dev:test was 3:2; new dev effort 600 person-days → test = 600 × 2/3 = **400 person-days***. Own historical data is the **best source**. |
| **Extrapolation** | **Metrics-based** | Measure **early in the current project**, then extrapolate (mathematical model). Very suitable for **iterative** SDLCs. *E.g., next iteration effort = average of last 3 iterations.* |
| **Wideband Delphi** | **Expert-based**, iterative | Experts estimate **in isolation** → results collected → if estimates are outside agreed boundaries, experts **discuss** → re-estimate in isolation → repeat until **consensus**. **Planning Poker** is an Agile variant using numbered cards. |
| **Three-point estimation** | **Expert-based** | Optimistic **a**, most likely **m**, pessimistic **b**. **E = (a + 4m + b) / 6**. Standard deviation **SD = (b − a) / 6**. *E.g., a=6, m=9, b=18 → E = (6+36+18)/6 = **10**, SD = 12/6 = **2** → **10 ± 2 person-hours (8 to 12)***. |

> 🧠 **Exam trap:** Read carefully whether the ratio is **dev:test** or **test:dev**, and whether the question asks for **test effort only** or **total effort**. In three-point, don't forget the **4×** on the most likely value.

#### 5.1.5 Test Case Prioritization — K3

| Strategy | Run first… |
|---|---|
| **Risk-based** | Tests covering the **most important risks** (from risk analysis) |
| **Coverage-based** | Tests achieving the **highest coverage** (e.g., statement coverage). **Additional coverage** variant: highest coverage first, then each next test is the one adding the **most additional** coverage |
| **Requirements-based** | Tests for the **highest-priority requirements** (priorities set by stakeholders) |

⚠️ **Dependencies override priority:** if a high-priority test depends on a lower-priority test, the **lower-priority test must run first**. Also consider **resource availability** (tools, environments, people available only in certain windows).

#### 5.1.6 Test Pyramid — K1

- Shows that tests have different **granularity**; supports **test automation** and **effort allocation**.
- **Bottom layer:** small, **isolated, fast** tests checking small pieces → **many** needed.
- **Top layer:** complex, **end-to-end**, slower tests checking large pieces → **few** needed.
- Going **up**: granularity ↓, isolation ↓, execution time ↑.
- Layers vary: original (Cohn) = **unit → service → UI**; another popular = **unit (component) → integration (component integration) → end-to-end**.

```
          /\        E2E / UI tests       → few, slow, low isolation
         /  \
        /----\      Service / Integration tests
       /      \
      /--------\    Unit / Component tests → many, fast, isolated
```

#### 5.1.7 Testing Quadrants — K2

By **Brian Marick**, for Agile. Two axes: **business-facing vs technology-facing** and **support the team (guide development) vs critique the product (measure against expectations)**.

| | **Support the team** | **Critique the product** |
|---|---|---|
| **Business facing** | **Q2**: functional tests, **examples**, **user story tests**, user experience **prototypes**, **API testing**, **simulations** — check acceptance criteria; **manual or automated** | **Q3**: **exploratory** testing, **usability** testing, **user acceptance** testing — user-oriented, **often manual** |
| **Technology facing** | **Q1**: **component** tests and **component integration** tests — **automated**, part of **CI** | **Q4**: **smoke** tests and **non-functional** tests (**except usability**) — **often automated** |

> 🧠 Memory: **Q1** = unit (tech + team). **Q2** = functional/story (business + team). **Q3** = exploratory/usability/UAT (business + critique). **Q4** = performance/security/smoke (tech + critique). **Usability is Q3, not Q4!**

### 5.2 Risk Management

**Main activities:**
- **Risk analysis** = **risk identification** + **risk assessment**
- **Risk control** = **risk mitigation** + **risk monitoring**

**Risk-based testing** = test activities selected, prioritized and managed based on risk analysis and risk control.

#### 5.2.1 Risk Definition and Risk Level — K1

**Risk** = a potential event, hazard, threat or situation whose occurrence causes an **adverse effect**. Two factors:
- **Risk likelihood** — probability of occurrence (**greater than 0 and less than 1**)
- **Risk impact (harm)** — the consequences

Together they give the **risk level**. Higher level → treat with higher priority.
- **Quantitative:** **Risk level = likelihood × impact**
- **Qualitative:** use a **risk matrix** (e.g., High/Medium/Low)

#### 5.2.2 Project Risks vs Product Risks — K2

| **Project risks** | **Product risks** (quality risks) |
|---|---|
| Related to **management and control of the project** | Related to **product quality characteristics** (ISO 25010) |
| **Organizational**: delays in deliveries, inaccurate estimates, cost cutting | Missing or wrong **functionality**, **incorrect calculations**, **runtime errors** |
| **People**: insufficient skills, conflicts, communication problems, **staff shortage** | **Poor architecture**, **inefficient algorithms** |
| **Technical**: **scope creep**, poor tool support | **Inadequate response time**, poor **user experience** |
| **Supplier**: third-party delivery failure, supplier bankruptcy | **Security vulnerabilities** |
| Impact: project **schedule, budget, scope** | Consequences: **user dissatisfaction**; loss of **revenue, trust, reputation**; **damage to third parties**; high maintenance costs, help-desk overload; **criminal penalties**; in extreme cases physical damage, **injury or death** |

> 🧠 **Exam trap:** "Test environment not ready on time" / "tester leaves the company" = **project** risk. "System may calculate tax wrongly" / "slow response under load" = **product** risk.

#### 5.2.3 Product Risk Analysis — K2

Goal: provide **awareness of product risk** to **focus test effort** and **minimize residual product risk**. Start **early** in the SDLC.
- **Risk identification**: produce a comprehensive list of risks (brainstorming, workshops, interviews, **cause-effect diagrams**)
- **Risk assessment**: **categorize** risks, determine **likelihood, impact, level**, **prioritize**, propose **ways to handle** them

Results of product risk analysis are used to:
1. Determine the **test scope**
2. Determine **test levels** and propose **test types**
3. Determine **test techniques** and **coverage** to achieve
4. **Estimate test effort** per task
5. **Prioritize testing** to find critical defects **as early as possible**
6. Decide whether **activities other than testing** could reduce risk

#### 5.2.4 Product Risk Control — K2

- **Risk mitigation** = implement actions proposed in assessment to **reduce risk level**
- **Risk monitoring** = ensure mitigation is **effective**, gather info to **improve assessment**, identify **emerging risks**

**Response options:** **risk mitigation by testing**, **risk acceptance**, **risk transfer**, **contingency plan**.

**Mitigating product risks through testing:**
1. Select **testers with the right experience and skills** for the risk type
2. Apply an appropriate level of **independence of testing**
3. Perform **reviews and static analysis**
4. Apply appropriate **test techniques and coverage levels**
5. Apply appropriate **test types** addressing the affected quality characteristics
6. Perform **dynamic testing, including regression testing**

### 5.3 Test Monitoring, Test Control and Test Completion

- **Test monitoring** = **gathering information** about testing → assess progress and whether **exit criteria** are satisfied (e.g., coverage of risks, requirements, acceptance criteria).
- **Test control** = uses monitoring info to give **control directives** (guidance + corrective actions). Examples:
  - **Reprioritizing tests** when an identified risk becomes an issue
  - **Re-evaluating** whether a test item meets entry/exit criteria due to **rework**
  - **Adjusting the test schedule** for a delayed test environment
  - **Adding new resources** when needed
- **Test completion** = collect data from completed activities to **consolidate experience, testware and information**; happens when a **test level** completes, an **iteration** ends, a test project is **completed or cancelled**, a system is **released**, or a **maintenance release** is completed.

#### 5.3.1 Metrics Used in Testing — K1

| Category | Examples |
|---|---|
| **Project progress** | Task completion, resource usage, test effort |
| **Test progress** | Test case implementation progress, test environment preparation progress, number of tests run/not run, passed/failed, test execution time |
| **Product quality** | Availability, response time, **mean time to failure** |
| **Defect** | Number & priorities of defects found/fixed, **defect density**, **defect detection percentage** |
| **Risk** | **Residual risk** level |
| **Coverage** | Requirements coverage, code coverage |
| **Cost** | Cost of testing, organizational **cost of quality** |

#### 5.3.2 Test Reports: Purpose, Content, Audience — K2

| **Test progress report** | **Test completion report** |
|---|---|
| Supports **ongoing test control**; generated **regularly** (daily, weekly) | Summarizes a **completed** test activity (test level, cycle, iteration); prepared when ideally exit criteria are met; occurs **once** |
| Content: **testing period**; **progress** (ahead/behind schedule) & notable deviations; **impediments & workarounds**; **test metrics**; **new & changed risks**; **testing planned for next period** | Content: **test summary**; **testing & product quality evaluation** vs the test plan (objectives, exit criteria); **deviations from the plan** (schedule, duration, effort); **impediments & workarounds**; **test metrics**; **unmitigated risks, defects not fixed**; **lessons learned** |
| Often **frequent and informal** to the team | Follows a **set template** |

Different **audiences** need different information and affect **formality and frequency**. ISO/IEC/IEEE 29119-3 calls progress reports **"test status reports"**.

#### 5.3.3 Communicating Test Status — K2

Options: **verbal** communication; **dashboards** (CI/CD dashboards, task boards, **burn-down charts**); **electronic channels** (email, chat); **online documentation**; **formal test reports**. **Distributed teams** (distance/time zones) may need **more formal** communication. Tailor information to each stakeholder.

### 5.4 Configuration Management (CM) — K2

CM identifies, controls and tracks work products (test plans, strategies, conditions, cases, scripts, results, logs, reports) as **configuration items**.
- For complex items (e.g., a **test environment**), CM records the **items it consists of, their relationships and versions**.
- Once approved for testing, an item becomes a **baseline** → changed **only via formal change control**.
- CM keeps a record of changes when a new baseline is created → you can **revert to a previous baseline** to **reproduce previous test results**.

CM ensures:
- All configuration items (incl. **test items**) are **uniquely identified, version controlled, tracked for changes, and related to each other** → **traceability**
- All documentation and software items are **referenced unambiguously** in testware

In DevOps pipelines (CI/CD), **automated CM** is normally included.

### 5.5 Defect Management — K3

Reported **anomalies** may turn out to be real defects or something else (**false positive**, **change request**). A defect management process includes a **workflow** from **discovery to closure** + **classification rules**: **log → analyze & classify → decide response (fix or keep as is) → close**. All stakeholders must follow it; handle **static testing defects** similarly.

**Objectives of a defect report:**
1. Give those resolving the defect **enough information** to resolve it
2. Provide a means of **tracking work product quality**
3. Provide **ideas for process improvement** (development and test)

**Typical defect report contents (dynamic testing):**
1. **Unique identifier**
2. **Title** with short summary
3. **Date** observed, **issuing organization**, **author** (and role)
4. Identification of the **test object** and **test environment**
5. **Context** (test case being run, test activity, SDLC phase, technique/checklist/test data used)
6. **Description of the failure** to enable reproduction: **steps**, logs, database dumps, **screenshots**, recordings
7. **Expected and actual results**
8. **Severity** (degree of **impact** on stakeholders/requirements)
9. **Priority** to fix
10. **Status** (open, deferred, duplicate, waiting to be fixed, awaiting confirmation testing, re-opened, closed, rejected)
11. **References** (e.g., to the test case)

Tools may auto-fill identifier, date, author, initial status. ISO/IEC/IEEE 29119-3 calls defect reports **"incident reports"**.

> 🧠 **Severity vs Priority:** **Severity** = how bad the **impact** is (technical). **Priority** = how **urgently** to fix (business). A typo in the company logo on the home page: **low severity, high priority**. A crash in a rarely used admin report: **high severity, lower priority**.

---

## Chapter 6 – Test Tools (20 min · 2 questions)

**Keyword:** test automation

### 6.1 Tool Support for Testing — K2

| Tool type | How it supports testing |
|---|---|
| **Test management tools** | Increase test process **efficiency**: manage SDLC, requirements, tests, defects, configuration |
| **Static testing tools** | Support **reviews and static analysis** |
| **Test design & implementation tools** | Generate **test cases, test data, test procedures** |
| **Test execution & coverage tools** | **Automated test execution** and **coverage measurement** |
| **Non-functional testing tools** | Non-functional tests that are **difficult or impossible manually** (e.g., load) |
| **DevOps tools** | Delivery **pipeline**, workflow tracking, **automated builds**, **CI/CD** |
| **Collaboration tools** | Facilitate **communication** |
| **Scalability & deployment standardization tools** | **Virtual machines, containerization** |
| **Any other tool that assists testing** | e.g., a **spreadsheet** is a test tool in a testing context |

### 6.2 Benefits and Risks of Test Automation — K1

Buying a tool **does not guarantee success** — effort needed for introduction, maintenance, training.

| ✅ Potential benefits | ❌ Potential risks |
|---|---|
| **Time saved** on repetitive manual work (regression runs, re-entering data, comparing results, checking coding standards) | **Unrealistic expectations** about the tool's benefits (functionality, ease of use) |
| **Fewer simple human errors** through consistency & repeatability | **Inaccurate estimates** of time, cost, effort to introduce the tool, maintain scripts, change the manual process |
| **More objective assessment** (e.g., coverage) and measures too complex for humans | Using a tool when **manual testing is more appropriate** |
| **Easier access to test information** (statistics, graphs, aggregated data) for management & reporting | **Over-reliance** on the tool, ignoring human **critical thinking** |
| **Reduced execution time** → earlier defect detection, faster feedback, faster time to market | **Vendor dependency** (vendor goes out of business, retires/sells the tool, poor support) |
| **More time for testers** to design new, deeper, more effective tests | **Open-source** tool may be **abandoned** or need frequent updates |
|  | Tool **not compatible** with the development platform |
|  | Tool **doesn't comply** with **regulatory/safety** standards |

---

# PART C – WORKED EXAMPLES FOR EVERY K3 TOPIC

> All 8 K3 questions in the exam are "apply the technique" questions. Do each example **on paper first**, then check the solution.

### Example 1 – Equivalence Partitioning

**Scenario:** A cinema ticket system accepts **age** as a whole number. Ticket types: **0–2 free**, **3–12 child**, **13–59 adult**, **60–120 senior**. Any age **below 0 or above 120 is rejected**.

**Step 1 – Partitions:**

| # | Partition | Valid/Invalid | Example test value |
|---|---|---|---|
| P1 | age ≤ −1 | Invalid | −5 |
| P2 | 0 – 2 | Valid (free) | 1 |
| P3 | 3 – 12 | Valid (child) | 8 |
| P4 | 13 – 59 | Valid (adult) | 30 |
| P5 | 60 – 120 | Valid (senior) | 75 |
| P6 | age ≥ 121 | Invalid | 130 |

**Answer:** 6 partitions → **minimum 6 test cases** for 100% EP coverage.

**Coverage question:** Tests use ages **8, 30, 130**. Coverage = **3 / 6 = 50%**.

**Each Choice twist:** Add a second input **day type** = {Weekday, Weekend, Public holiday} (3 partitions). Each Choice coverage needs every partition of each input at least once → minimum tests = size of the **largest** set = **6** (e.g., pair each age partition with a day type, re-using day types).

### Example 2 – BVA (2-value vs 3-value)

Same cinema domain. Partitions: **{≤ −1}, {0–2}, {3–12}, {13–59}, {60–120}, {≥ 121}**.

**Boundary values** (min & max of every partition that has them):
`−1 | 0, 2 | 3, 12 | 13, 59 | 60, 120 | 121` → **10 boundary values**

**2-value BVA** coverage items (10): **−1, 0, 2, 3, 12, 13, 59, 60, 120, 121**

**3-value BVA** – each boundary and both neighbors:

| Boundary | Values |
|---|---|
| −1 | −2, −1, 0 |
| 0 | −1, 0, 1 |
| 2 | 1, 2, 3 |
| 3 | 2, 3, 4 |
| 12 | 11, 12, 13 |
| 13 | 12, 13, 14 |
| 59 | 58, 59, 60 |
| 60 | 59, 60, 61 |
| 120 | 119, 120, 121 |
| 121 | 120, 121, 122 |

Unique values: **−2, −1, 0, 1, 2, 3, 4, 11, 12, 13, 14, 58, 59, 60, 61, 119, 120, 121, 122** → **19 test values**.

**Coverage question:** Tests use ages **0, 12, 13, 60, 100**. 2-value BVA coverage = boundary values hit (0, 12, 13, 60) = **4 / 10 = 40%** (100 is not a boundary value).

### Example 3 – BVA with Decimals

**Scenario:** An online shop charges delivery for orders **PKR 0.01 – 4,999.99**; orders of **PKR 5,000.00 and above** get free delivery. The system cannot accept amounts below 0.01. Step size = **0.01**.

- Partitions: **{0.01 – 4,999.99}**, **{5,000.00 and above}**
- Boundary values: **0.01, 4,999.99, 5,000.00** (the second partition has no maximum)
- **2-value BVA:** 0.01, 4,999.99, 5,000.00 → **3 values**
- **3-value BVA:** 0.01's neighbors are 0.00 (**not in domain → drop**) and 0.02; 4,999.99 → 4,999.98 & 5,000.00; 5,000.00 → 4,999.99 & 5,000.01
  → **0.01, 0.02, 4,999.98, 4,999.99, 5,000.00, 5,000.01** → **6 values**

> ⚠️ A classic mistake is using step 1 (e.g., 4,999 and 5,001) when the data has 2 decimal places.

### Example 4 – Decision Table Testing

**Business rule (loan application):**
- If the applicant **has a previous default**, the loan is **rejected**.
- Otherwise, the loan is **approved** if the applicant is an **existing customer** **or** has **salary ≥ PKR 150,000**.
- An existing customer with salary ≥ PKR 150,000 (and no default) also gets a **reduced interest rate**.

**Full limited-entry table (3 conditions → 2³ = 8 rules):**

| Conditions / Actions | R1 | R2 | R3 | R4 | R5 | R6 | R7 | R8 |
|---|---|---|---|---|---|---|---|---|
| C1: Previous default? | F | F | F | F | T | T | T | T |
| C2: Existing customer? | T | T | F | F | T | T | F | F |
| C3: Salary ≥ 150k? | T | F | T | F | T | F | T | F |
| A1: Approve | X | X | X |  |  |  |  |  |
| A2: Reject |  |  |  | X | X | X | X | X |
| A3: Reduced rate | X |  |  |  |  |  |  |  |

**Minimized table** (R5–R8 have the same outcome when C1 = T, so C2 and C3 are irrelevant "–"):

| Conditions / Actions | R1 | R2 | R3 | R4 | R5' |
|---|---|---|---|---|---|
| C1: Previous default? | F | F | F | F | T |
| C2: Existing customer? | T | T | F | F | – |
| C3: Salary ≥ 150k? | T | F | T | F | – |
| A1: Approve | X | X | X |  |  |
| A2: Reject |  |  |  | X | X |
| A3: Reduced rate | X |  |  |  |  |

→ **5 test cases** give 100% coverage of the minimized table.

**Coverage question:** Tests: TC1 (no default, existing, 200k), TC2 (no default, new, 50k), TC3 (no default, new, 60k), TC4 (default, existing, 300k).
TC1 → R1, TC2 → R4, TC3 → R4 (again), TC4 → R5'. Columns covered: R1, R4, R5' = **3 / 5 = 60%**.

**Finding a gap:** If the requirement didn't say what happens to "new customer, salary < 150k, no default" (R4), the decision table would **expose that gap** — a key strength of the technique.

### Example 5 – State Transition Testing

**Online order** — states: **Created, Paid, Shipped, Delivered, Cancelled**.

```
                 pay                 ship                deliver
   [Created] ───────────► [Paid] ───────────► [Shipped] ───────────► [Delivered]
       │                    │
       │ cancel             │ cancel / refund
       ▼                    ▼
   [Cancelled] ◄────────────┘
```

**State table** (rows = states, columns = events; "—" = **invalid** transition):

| State \ Event | pay | ship | deliver | cancel |
|---|---|---|---|---|
| **Created** | Paid | — | — | Cancelled |
| **Paid** | — | Shipped | — | Cancelled / refund |
| **Shipped** | — | — | Delivered | — |
| **Delivered** | — | — | — | — |
| **Cancelled** | — | — | — | — |

- States = **5** · Valid transitions = **5** · Table cells = 5 × 4 = **20** → invalid transitions = **15**

**a) Minimum tests for 100% all-states coverage = 2**
- T1: Created → pay → Paid → ship → Shipped → deliver → Delivered (4 states)
- T2: Created → cancel → Cancelled

**b) Minimum tests for 100% valid-transitions (0-switch) coverage = 3**
- T1: pay, ship, deliver (3 transitions)
- T2: Created –cancel→ Cancelled
- T3: Created –pay→ Paid –cancel→ Cancelled
- *Reason:* Delivered and Cancelled are final states; there are 3 different transitions into final states, and each test can end in only one.

**c) Coverage of T1 alone:** all states = 4/5 = **80%**; valid transitions = 3/5 = **60%**.

**d) All-transitions coverage:** 5 valid + **15 invalid** to attempt. With **one invalid transition per test case** (to avoid defect masking) you need **at least 15 test cases**; the valid transitions can be covered along the way.

### Example 6 – Statement & Branch Coverage

```
1  read amount, member
2  if amount > 5000 then
3      discount = 10%
4  end if
5  if member == true then
6      points = amount / 100
7  else
8      points = 0
9  end if
10 print discount, points
```

- Executable statements: lines **1, 2, 3, 5, 6, 8, 10** → **7** (`end if` / `else` are not executable statements)
- Decisions: **2** (line 2 and line 5) → **4 decision outcomes** (2 × True/False)

| Test | amount | member | Statements executed | Decision outcomes |
|---|---|---|---|---|
| A | 6000 | true | 1, 2, 3, 5, 6, 10 | D1-T, D2-T |
| B | 100 | false | 1, 2, 5, 8, 10 | D1-F, D2-F |

- **Test A alone:** statement coverage = 6/7 = **85.7%**; decision outcomes = 2/4 = **50%**
- **A + B:** statement coverage = 7/7 = **100%**; decision outcomes = 4/4 = **100%**
- **Minimum** tests for 100% statement = **2** (line 6 and line 8 can't run in the same test). Minimum for 100% branch = **2**.

> 🧠 Key idea: In this code, line 3 runs only when D1 is True. A test that makes D1 True covers line 3, but the **False outcome of D1** (skipping line 3) is a separate branch that statement coverage doesn't require. That's why **100% statement ≠ 100% branch**, while **100% branch ⇒ 100% statement**.

### Example 7 – ATDD

**User story:** *As a registered customer, I want to apply a promo code at checkout, so that I can get a discount on my order.*

**Acceptance criteria:**
1. A valid, unexpired code reduces the order total by the code's percentage.
2. An expired code shows the message "Code expired" and the total is unchanged.
3. Only one promo code can be applied per order.
4. Codes are not case-sensitive.

**Which test case correctly derives from the acceptance criteria?**
- **A)** Given an order of PKR 2,000 and valid code "EID10" (10%), when the customer enters "eid10", then the total becomes PKR 1,800. ✅
- **B)** Given an order of PKR 2,000 and expired code "EID10", when the customer applies it, then the total becomes PKR 1,800. ❌ contradicts AC2
- **C)** Given an order with code "EID10" applied, when the customer applies "SALE20", then both discounts are combined. ❌ contradicts AC3
- **D)** Given a guest user (not logged in), when they enter a code, then they are asked to register. ❌ goes **beyond** the story (guests are not in scope)

**Answer: A** — it tests AC1 and AC4 together, with a correct expected result.

**ATDD order reminder:** positive (happy path) → negative → non-functional.

### Example 8 – Estimation

**a) Ratio-based:** In a previous similar project, development took **800** person-days and testing **600** person-days (ratio 4:3). New project development is estimated at **1,200** person-days.
→ Test effort = 1,200 × 3/4 = **900 person-days**. (Total effort would be 2,100 — read what the question asks!)

**b) Extrapolation:** Test effort in the last three iterations: **18, 22, 20** person-days. Averaged extrapolation for the next iteration = (18 + 22 + 20) / 3 = **20 person-days**.

**c) Three-point:** a (optimistic) = **4**, m (most likely) = **7**, b (pessimistic) = **16** person-hours.
→ E = (4 + 4×7 + 16) / 6 = (4 + 28 + 16) / 6 = 48 / 6 = **8**
→ SD = (16 − 4) / 6 = **2** → estimate = **8 ± 2 person-hours (6 to 10)**

**d) Wideband Delphi:** Round 1 (in isolation): 10, 12, 30 days. 30 is outside the agreed range → experts discuss reasons → Round 2 in isolation: 14, 15, 18 → within range → consensus (e.g., ~15 days). **Planning Poker** = Agile variant with numbered cards.

### Example 9 – Test Case Prioritization

**a) Priority with dependencies** (1 = highest):

| Test | Priority | Depends on |
|---|---|---|
| TC-A | 2 | — |
| TC-B | 1 | TC-D |
| TC-C | 3 | — |
| TC-D | 4 | — |
| TC-E | 5 | — |

TC-B has highest priority but needs TC-D → run **TC-D, TC-B**, then **TC-A** (2), **TC-C** (3), **TC-E** (5).
**Order: D → B → A → C → E**

**b) Additional coverage prioritization** (code has statements S1–S8):

| Test | Statements covered |
|---|---|
| TC1 | S1, S2, S3, S4, S5 |
| TC2 | S1, S2, S6 |
| TC3 | S5, S6, S7, S8 |
| TC4 | S1, S6 |

1. Highest coverage first → **TC1** (5 statements)
2. Additional coverage now: TC2 adds {S6} = 1, TC3 adds {S6, S7, S8} = 3, TC4 adds {S6} = 1 → **TC3**
3. All 8 statements now covered → TC2 and TC4 add 0 (run in any order)
**Order: TC1 → TC3 → (TC2, TC4)**

### Example 10 – Risk Level

**Quantitative** (likelihood 0–1 × impact 1–5):

| Risk | Likelihood | Impact | Risk level |
|---|---|---|---|
| R1: Payment gateway fails under peak Eid sale load | 0.6 | 5 | **3.0** |
| R2: Wrong tax calculation | 0.3 | 4 | **1.2** |
| R3: Typo in help page | 0.8 | 1 | **0.8** |

→ Test in order **R1, R2, R3** (risk-based testing). R1 → performance testing with high coverage; R3 → light checklist testing or accept.

**Qualitative** (risk matrix):

| Likelihood \ Impact | Low | Medium | High |
|---|---|---|---|
| **High** | Medium | High | **Very high** |
| **Medium** | Low | Medium | High |
| **Low** | Very low | Low | Medium |

### Example 11 – Defect Report

| Field | Example |
|---|---|
| ID | BUG-1042 |
| Title | Checkout total not reduced when promo code entered in lowercase |
| Date / Author / Org | 12-Oct-2026 · Ahmed (Tester) · QA team |
| Test object & environment | Web shop v3.4.1, build 1187 · Chrome 129 · QA environment |
| Context | TC-PROMO-07 (ATDD for promo story), system testing, sprint 22 |
| Steps to reproduce | 1) Log in as registered customer 2) Add items worth PKR 2,000 3) Go to checkout 4) Enter "eid10" 5) Click Apply |
| Expected result | Total = PKR 1,800 (codes are not case-sensitive per AC4) |
| Actual result | Error "Invalid code"; total stays PKR 2,000 |
| Severity | Medium (feature fails for a common input) |
| Priority | High (Eid campaign starts Friday) |
| Status | Open |
| References | User story US-311, AC4; screenshot attached; log excerpt attached |

> 🧠 **Exam trap (K3 "prepare a defect report"):** You'll be asked which information is **missing** or **most important to add**. Usually it's **expected vs actual result**, **steps to reproduce**, **test environment/version**, or **severity/priority**.

---

# PART D – Q&A BANK (CHAPTER-WISE PRACTICE QUESTIONS)

> These are **original practice questions** written in the official exam style, mapped to the syllabus LOs. Click **"Show answer"** to reveal the answer and explanation.
> After these, do the **official ISTQB® Sample Exams A–D** under exam conditions (60 minutes, no notes).

---

## Chapter 1 – Practice Questions

**Q1.1 (FL-1.1.1, K1)** Which of the following is a typical test objective?
- a) Removing the defects found during testing
- b) Proving that the software has no remaining defects
- c) Building confidence in the quality of the test object
- d) Writing the requirements specification

<details><summary>Show answer</summary>

**c)** Building confidence is one of the nine typical test objectives. (a) is debugging, (b) is impossible (principle 1), (d) is not a test objective.
</details>

**Q1.2 (FL-1.1.2, K2)** Which statement BEST describes the difference between testing and debugging?
- a) Testing removes defects; debugging finds them
- b) Testing can trigger failures caused by defects; debugging finds, analyzes and removes the causes of failures
- c) Debugging is a test activity done by testers after test execution
- d) Static testing always requires debugging to reproduce the failure first

<details><summary>Show answer</summary>

**b)** Debugging (reproduce → diagnose → fix) is a development activity, not a test activity. After static testing there is nothing to reproduce — debugging just removes the defect.
</details>

**Q1.3 (FL-1.2.3, K2)** Under strong deadline pressure, a developer misread a requirement and coded *simple* interest instead of *compound* interest. Customers then received bank statements with wrong balances. Which is the **failure**?
- a) The time pressure on the developer
- b) The developer misreading the requirement
- c) The simple-interest formula in the code
- d) The wrong balances on the customers' statements

<details><summary>Show answer</summary>

**d)** Failure = observable wrong behavior. (a) = root cause, (b) = error (mistake), (c) = defect.
</details>

**Q1.4 (FL-1.2.2, K1)** Which statement about testing and quality assurance (QA) is correct?
- a) Testing is process-oriented and preventive; QA is product-oriented and corrective
- b) QA is process-oriented and preventive; testing is product-oriented and corrective
- c) Testing and QA are the same and the terms can be used interchangeably
- d) QA is only the responsibility of the test team

<details><summary>Show answer</summary>

**b)** QA focuses on processes (prevention); testing is a form of quality control focusing on the product (correction). QA is everyone's responsibility.
</details>

**Q1.5 (FL-1.3.1, K2)** The same automated regression suite has run every night for a year. It now rarely finds new defects, although users keep reporting problems in new features. Which principle applies?
- a) Defects cluster together
- b) Exhaustive testing is impossible
- c) Tests wear out
- d) Testing is context dependent

<details><summary>Show answer</summary>

**c)** Repeating the same tests becomes ineffective at finding *new* defects → update tests and add new ones. (Note: re-running them is still useful as regression protection.)
</details>

**Q1.6 (FL-1.3.1, K2)** A team fixed every defect found and verified all specified requirements, yet users refused the system because it does not support their real workflow. Which principle does this illustrate?
- a) Absence-of-defects fallacy
- b) Testing shows the presence, not the absence of defects
- c) Early testing saves time and money
- d) Tests wear out

<details><summary>Show answer</summary>

**a)** Verification alone does not guarantee success — validation is also needed.
</details>

**Q1.7 (FL-1.3.1, K2)** Most of the failures in production came from 2 of the 30 modules, so the team focuses extra testing on those two modules. Which principle supports this decision?
- a) Exhaustive testing is impossible
- b) Defects cluster together
- c) Testing is context dependent
- d) Absence-of-defects fallacy

<details><summary>Show answer</summary>

**b)** Defect clustering (Pareto) — actual and predicted clusters are an input to risk-based testing.
</details>

**Q1.8 (FL-1.4.1, K2)** In which test activity are the test environment built and verified, test data created, and test procedures arranged into a test execution schedule?
- a) Test design
- b) Test implementation
- c) Test execution
- d) Test analysis

<details><summary>Show answer</summary>

**b)** Test implementation. *Designing* the environment and defining *test data requirements* belong to test design.
</details>

**Q1.9 (FL-1.4.1, K2)** Which task belongs to **test analysis**?
- a) Identifying coverage items and test data requirements
- b) Evaluating the test basis to identify defects and assess testability
- c) Comparing actual and expected results
- d) Archiving testware for future use

<details><summary>Show answer</summary>

**b)** Analysis = "what to test": analyze test basis, define & prioritize test conditions, evaluate testability. (a) design, (c) execution, (d) completion.
</details>

**Q1.10 (FL-1.4.3, K2)** Which work product is typically produced during **test planning**?
- a) Test charter
- b) Test log
- c) Risk register
- d) Test suite

<details><summary>Show answer</summary>

**c)** Planning work products: test plan, test schedule, risk register, entry & exit criteria. (a) design, (b) execution, (d) implementation.
</details>

**Q1.11 (FL-1.4.4, K2)** Which BEST shows the value of traceability between test results and risks?
- a) It shows which test cases are automated
- b) It allows evaluating the level of residual risk in the test object
- c) It reduces the number of test cases needed
- d) It replaces the need for a test plan

<details><summary>Show answer</summary>

**b)** Test results ↔ risks → residual risk. Test cases ↔ requirements → requirements coverage.
</details>

**Q1.12 (FL-1.4.5, K2)** Which task is MAINLY performed by the **test management role**?
- a) Designing test cases using boundary value analysis
- b) Executing test procedures and logging defects
- c) Creating the test completion report
- d) Creating test data

<details><summary>Show answer</summary>

**c)** Test management role focuses on planning, monitoring, control and completion. (a), (b), (d) are testing-role tasks.
</details>

**Q1.13 (FL-1.5.2, K1)** Which is an advantage of the whole team approach?
- a) It guarantees the highest level of test independence
- b) It improves team dynamics, communication and collaboration
- c) Only testers are responsible for quality
- d) It is always the best choice, including for safety-critical systems

<details><summary>Show answer</summary>

**b)** Everyone is responsible for quality; it may NOT suit safety-critical contexts needing high independence.
</details>

**Q1.14 (FL-1.5.3, K2)** Which is a potential **drawback** of independent testing?
- a) Independent testers recognize different kinds of defects
- b) Independent testers can challenge stakeholders' assumptions
- c) Developers may lose a sense of responsibility for quality
- d) Independent testers have different cognitive biases than authors

<details><summary>Show answer</summary>

**c)** (a), (b), (d) are benefits. Other drawbacks: isolation, communication problems, being seen as a bottleneck.
</details>

**Q1.15 (FL-1.5.1, K2)** Which generic tester skill MAINLY increases the **efficiency** of testing?
- a) Curiosity
- b) Technical knowledge, e.g., using appropriate test tools
- c) Domain knowledge
- d) Active listening

<details><summary>Show answer</summary>

**b)** The syllabus links technical knowledge to efficiency, testing knowledge and analytical/critical thinking to effectiveness.
</details>

### Chapter 1 – Quick-Fire Flashcards

| Question | Answer |
|---|---|
| Is debugging a testing activity? | **No** |
| Who should preferably do confirmation testing? | The **same person who ran the original test** |
| Another name for error / defect? | Error = **mistake**; defect = **fault, bug** |
| Can a failure happen without a defect? | **Yes** — environmental conditions (radiation, EM fields) |
| How many testing principles? | **7** |
| Old name of "tests wear out"? | **Pesticide paradox** |
| Which activity answers "what to test"? / "how to test"? | **Analysis** / **Design** |
| Where are test charters created? | **Test design** |
| Where are test logs created? | **Test execution** |
| What does a risk register contain? | Risks + **likelihood, impact, mitigation** |
| Two principal test roles? | **Test management role** and **testing role** |
| Whole team approach comes from? | **Extreme Programming (XP)** |
| Four levels of independence? | Author → peers in team → testers outside team, inside org → testers outside org |
| How many contextual factors affect the test process? | **8** (stakeholders, team, business domain, technical, project constraints, organizational, SDLC, tools) |

---

## Chapter 2 – Practice Questions

**Q2.1 (FL-2.1.1, K2)** In a sequential (V-model) project, what is typical for testers during the early phases?
- a) Running dynamic tests on the first code builds
- b) Participating in requirement reviews, test analysis and test design
- c) Running automated regression tests in every iteration
- d) Doing mostly exploratory testing

<details><summary>Show answer</summary>

**b)** Code arrives late in sequential models, so dynamic testing cannot happen early.
</details>

**Q2.2 (FL-2.1.2, K1)** Which is a good testing practice that applies to ALL SDLCs?
- a) Test analysis and design for a test level start during the corresponding development phase
- b) All testing is performed by an independent test team
- c) Test documentation is always detailed
- d) Testing starts only after the code is complete

<details><summary>Show answer</summary>

**a)** The four practices: a test activity for every dev activity; different objectives per level; analysis & design start in the corresponding dev phase; testers review drafts early.
</details>

**Q2.3 (FL-2.1.3, K1)** Which approach expresses desired behavior in natural language using Given/When/Then so that stakeholders can understand it, and then translates it into executable tests?
- a) TDD
- b) ATDD
- c) BDD
- d) DDD

<details><summary>Show answer</summary>

**c)** BDD. TDD = test → code → refactor at code level; ATDD = tests from acceptance criteria as part of system design.
</details>

**Q2.4 (FL-2.1.4, K2)** Which statement about DevOps and testing is correct?
- a) DevOps removes the need for manual testing
- b) CI promotes shift left by encouraging developers to submit code with component tests and static analysis
- c) DevOps makes test automation cheaper to set up and maintain
- d) DevOps reduces visibility of non-functional characteristics

<details><summary>Show answer</summary>

**b)** Manual testing from the user's perspective is still needed; automation needs extra resources; DevOps *increases* visibility of non-functional characteristics.
</details>

**Q2.5 (FL-2.1.5, K2)** Which is an example of **shift left**?
- a) Running a full performance test only after system testing is complete
- b) Performing static analysis of source code before dynamic testing
- c) Postponing reviews until all requirements are final
- d) Increasing acceptance testing time

<details><summary>Show answer</summary>

**b)** Other shift-left practices: tester-perspective spec reviews, tests before code, CI/CD, non-functional testing from component level.
</details>

**Q2.6 (FL-2.1.6, K2)** Where are the results of a retrospective normally recorded?
- a) In the test plan
- b) In the defect reports
- c) In the test completion report
- d) In the risk register

<details><summary>Show answer</summary>

**c)** Retrospective results are normally part of the test completion report, and improvements must be followed up.
</details>

**Q2.7 (FL-2.2.1, K2)** A team tests the interface between their online shop and an external payment provider's service. Which test level is this?
- a) Component integration testing
- b) System testing
- c) System integration testing
- d) Acceptance testing

<details><summary>Show answer</summary>

**c)** Interfaces with *other systems and external services* = system integration testing. Interfaces *between components* = component integration testing.
</details>

**Q2.8 (FL-2.2.1, K2)** Which test level is MOST dependent on an integration strategy such as bottom-up, top-down or big-bang?
- a) Component testing
- b) Component integration testing
- c) Acceptance testing
- d) System testing

<details><summary>Show answer</summary>

**b)**
</details>

**Q2.9 (FL-2.2.2, K2)** Checking that a monthly sales report is generated **within 3 seconds** is an example of which test type?
- a) Functional testing
- b) Non-functional testing
- c) White-box testing
- d) Confirmation testing

<details><summary>Show answer</summary>

**b)** Response time = performance efficiency (ISO 25010) → non-functional. It may reuse a functional test with an added time check.
</details>

**Q2.10 (FL-2.2.3, K2)** A defect in the login page was fixed. The tester re-runs the failed test (it passes) and then runs a set of tests on the profile and checkout pages that use the same authentication module. What are these two activities?
- a) Regression testing, then confirmation testing
- b) Confirmation testing, then regression testing
- c) Both are confirmation testing
- d) Both are regression testing

<details><summary>Show answer</summary>

**b)** Re-running the failed test = confirmation; checking unchanged areas for side effects = regression.
</details>

**Q2.11 (FL-2.3.1, K2)** A company moves its HR system to a new cloud platform and migrates employee data from an old application. Which trigger for maintenance testing is this, and what extra testing is needed?
- a) Modification — only confirmation testing
- b) Upgrade/migration — tests of the new environment and data conversion testing
- c) Retirement — data archiving tests
- d) Hot fix — no regression testing needed

<details><summary>Show answer</summary>

**b)** Migration of the operational environment requires testing the new environment, the changed software, and data conversion.
</details>

**Q2.12 (FL-2.3.1, K2)** Which factors determine the **scope** of maintenance testing?
- a) Number of testers, test tools, budget
- b) Degree of risk of the change, size of the existing system, size of the change
- c) Number of defects found in the previous release only
- d) The SDLC model being used

<details><summary>Show answer</summary>

**b)**
</details>

**Q2.13 (FL-2.2.1, K2)** Which of the following is NOT one of the main forms of acceptance testing listed in the syllabus?
- a) Operational acceptance testing
- b) Contractual and regulatory acceptance testing
- c) Component acceptance testing
- d) Alpha and beta testing

<details><summary>Show answer</summary>

**c)** Main forms: UAT, operational, contractual, regulatory, alpha, beta.
</details>

### Chapter 2 – Quick-Fire Flashcards

| Question | Answer |
|---|---|
| Examples of sequential models? | **Waterfall, V-model** |
| Examples of iterative models? | **Spiral, prototyping** |
| Example of incremental model? | **Unified Process** |
| What 5 things does the SDLC impact in testing? | Scope & timing, documentation detail, techniques & approach, automation extent, tester role |
| TDD cycle? | **Test → Code → Refactor** |
| What does DevOps require culturally? | Bridging dev (incl. testing) and operations with **equal value** |
| 3 retrospective questions? | What went well (keep)? What didn't (improve)? How to apply both? |
| 5 test levels? | Component, component integration, system, system integration, acceptance |
| 4 test types? | Functional, non-functional, black-box, white-box |
| 8 ISO 25010 non-functional characteristics? | Performance efficiency, compatibility, usability, reliability, security, maintainability, portability, safety |
| New alternative names in 25010? | Usability = **interaction capability**; portability = **flexibility** |
| What should be done before regression testing to define scope? | **Impact analysis** |
| 3 maintenance triggers? | **Modifications, upgrades/migrations, retirement** |
| Maintenance categories (ISO 14764)? | Corrective, adaptive, improve performance/maintainability |

---

## Chapter 3 – Practice Questions

**Q3.1 (FL-3.1.1, K1)** Which work product is NOT appropriate for static testing?
- a) A test charter
- b) A contract
- c) Third-party executable code that must not be analyzed for legal reasons
- d) A product backlog item

<details><summary>Show answer</summary>

**c)** Almost any readable work product can be reviewed; static analysis needs a formal structure.
</details>

**Q3.2 (FL-3.1.3, K2)** Which statement correctly contrasts static and dynamic testing?
- a) Static testing causes failures; dynamic testing finds defects directly
- b) Static testing finds defects directly; dynamic testing causes failures that are then analyzed
- c) Only dynamic testing can be applied to non-executable work products
- d) Static testing can measure performance efficiency

<details><summary>Show answer</summary>

**b)** Static testing can measure maintainability (not dependent on execution); dynamic testing measures performance efficiency.
</details>

**Q3.3 (FL-3.1.3, K2)** Which defect is typically easier and cheaper to find with static testing than with dynamic testing?
- a) Slow response time under load
- b) A memory leak visible after 12 hours of operation
- c) Unreachable code and undeclared variables
- d) Incorrect rendering on one specific mobile device

<details><summary>Show answer</summary>

**c)**
</details>

**Q3.4 (FL-3.1.2, K2)** Which is a value of static testing?
- a) It can detect defects in the earliest phases of the SDLC and in non-executable work products
- b) It removes the need for dynamic testing
- c) It is always cheaper than any other activity
- d) It measures the reliability of running software

<details><summary>Show answer</summary>

**a)**
</details>

**Q3.5 (FL-3.2.2, K2)** In which review activity are anomalies analyzed and decisions made about their status, ownership and required actions?
- a) Planning
- b) Individual review
- c) Communication and analysis
- d) Fixing and reporting

<details><summary>Show answer</summary>

**c)** Typically in a review meeting. Exit criteria are defined in **planning**; defect reports are created in **fixing and reporting**.
</details>

**Q3.6 (FL-3.2.3, K1)** Which review role ensures the effective running of review meetings, including mediation, time management and a safe environment?
- a) Review leader
- b) Moderator (facilitator)
- c) Manager
- d) Scribe

<details><summary>Show answer</summary>

**b)**
</details>

**Q3.7 (FL-3.2.3, K1)** Who decides **what** is to be reviewed and provides resources such as staff and time?
- a) Manager
- b) Review leader
- c) Author
- d) Moderator

<details><summary>Show answer</summary>

**a)** The review leader decides *who* is involved and *when/where*.
</details>

**Q3.8 (FL-3.2.4, K2)** A review is led by the author; its goals include educating reviewers and gaining consensus, and individual preparation is not required. Which review type is this?
- a) Informal review
- b) Walkthrough
- c) Technical review
- d) Inspection

<details><summary>Show answer</summary>

**b)**
</details>

**Q3.9 (FL-3.2.4, K2)** Which is a characteristic of an **inspection**?
- a) It does not follow a defined process
- b) The author usually acts as the scribe
- c) Metrics are collected and used to improve the SDLC and the inspection process
- d) Its main objective is to educate reviewers

<details><summary>Show answer</summary>

**c)** In an inspection the author cannot be review leader or scribe; the main objective is to find the maximum number of anomalies.
</details>

**Q3.10 (FL-3.2.5, K1)** Which is a success factor for reviews?
- a) Using the review results to evaluate participants' performance
- b) Reviewing the whole document in one long session
- c) Defining clear objectives and measurable exit criteria
- d) Keeping management out of the review process

<details><summary>Show answer</summary>

**c)** Evaluating participants must never be an objective; review small chunks; management support is needed.
</details>

**Q3.11 (FL-3.2.1, K1)** Which is a benefit of early and frequent stakeholder feedback?
- a) It removes the need for acceptance testing
- b) It prevents misunderstandings about requirements and allows earlier implementation of changes
- c) It guarantees that requirements never change
- d) It reduces the need for test automation

<details><summary>Show answer</summary>

**b)**
</details>

### Chapter 3 – Quick-Fire Flashcards

| Question | Answer |
|---|---|
| Two forms of static testing? | **Reviews** (manual) and **static analysis** (tool) |
| What does static analysis require of the work product? | A **formal structure** (code, models, formal syntax) |
| Can static testing be used for validation? | **Yes** — both verification and validation |
| Which standard defines the review process? | **ISO/IEC 20246** |
| 5 review activities? | Planning, review initiation, individual review, communication & analysis, fixing & reporting |
| 6 review roles? | Manager, author, moderator (facilitator), scribe (recorder), reviewer, review leader |
| 4 review types (least → most formal)? | Informal → walkthrough → technical review → inspection |
| Who leads a walkthrough? A technical review? | **Author** / **Moderator** |
| Which roles can't the author take in an inspection? | **Review leader** and **scribe** |
| Main objective of an informal review? | **Detecting anomalies** |
| Are all anomalies defects? | **No** — they must be analyzed |
| Example of security defect found statically? | **Buffer overflow** |

---

## Chapter 4 – Practice Questions

**Q4.1 (FL-4.1.1, K2)** For which category of test techniques do test cases remain useful when the implementation changes but the required behavior stays the same?
- a) White-box test techniques
- b) Black-box test techniques
- c) Experience-based test techniques
- d) Static analysis techniques

<details><summary>Show answer</summary>

**b)** Black-box tests are independent of the implementation. White-box tests can only be created after design/implementation.
</details>

**Q4.2 (FL-4.2.1, K3)** A discount field accepts whole numbers from **0 to 50** (percent). Negative values and values above 50 are rejected. What is the minimum number of test cases for 100% equivalence partitioning coverage?
- a) 1
- b) 2
- c) 3
- d) 6

<details><summary>Show answer</summary>

**c)** Partitions: {≤ −1} invalid, {0–50} valid, {≥ 51} invalid → 3.
</details>

**Q4.3 (FL-4.2.1, K3)** A test object has **5** identified equivalence partitions (3 valid, 2 invalid). The executed tests cover 2 valid partitions and 1 invalid partition. What is the EP coverage?
- a) 40%
- b) 60%
- c) 67%
- d) 100%

<details><summary>Show answer</summary>

**b)** 3 / 5 = 60%. Invalid partitions count as coverage items too.
</details>

**Q4.4 (FL-4.2.2, K3)** A water-temperature sensor (whole °C) reports: **≤ 0 "Freezing"**, **1–99 "Liquid"**, **≥ 100 "Boiling"**. Which set gives 100% **2-value** BVA coverage?
- a) 0, 1, 99, 100
- b) −1, 0, 1, 99, 100, 101
- c) 0, 50, 100
- d) 1, 99

<details><summary>Show answer</summary>

**a)** Boundary values = max of {≤0} = 0; min/max of {1–99} = 1, 99; min of {≥100} = 100 → 4 values.
</details>

**Q4.5 (FL-4.2.2, K3)** Same sensor. How many test values are needed for 100% **3-value** BVA coverage?
- a) 4
- b) 6
- c) 8
- d) 12

<details><summary>Show answer</summary>

**c)** 0 → −1, 0, 1 · 1 → 0, 1, 2 · 99 → 98, 99, 100 · 100 → 99, 100, 101 → unique: **−1, 0, 1, 2, 98, 99, 100, 101 = 8**.
</details>

**Q4.6 (FL-4.2.2, K3)** Same sensor. Tests are run with **0, 50, 100, 101**. What is the **2-value** BVA coverage?
- a) 25%
- b) 50%
- c) 75%
- d) 100%

<details><summary>Show answer</summary>

**b)** Boundary values are 0, 1, 99, 100. Covered: 0 and 100 → 2/4 = 50%. (50 and 101 are not boundary values.)
</details>

**Q4.7 (FL-4.2.3, K3)** A full limited-entry decision table has **4** Boolean conditions. How many rules (columns) does it have before simplification?
- a) 4
- b) 8
- c) 16
- d) 32

<details><summary>Show answer</summary>

**c)** 2⁴ = 16.
</details>

**Q4.8 (FL-4.2.3, K3)** Consider this decision table for online shopping:

| | R1 | R2 | R3 | R4 |
|---|---|---|---|---|
| Member? | T | T | F | F |
| Order ≥ PKR 3,000? | T | F | T | F |
| Free shipping | X | X | X | |
| Gift voucher | X | | | |

A **non-member** places an order of **PKR 5,000**. What is the expected result?
- a) Free shipping and gift voucher
- b) Free shipping only
- c) Gift voucher only
- d) Neither

<details><summary>Show answer</summary>

**b)** Member = F, Order ≥ 3,000 = T → R3 → free shipping only.
</details>

**Q4.9 (FL-4.2.3, K3)** A minimized decision table has **6** feasible columns. The tests exercise columns R1, R2, R2, R5. What is the decision table coverage?
- a) 33%
- b) 50%
- c) 67%
- d) 83%

<details><summary>Show answer</summary>

**b)** Unique columns covered: R1, R2, R5 = 3 / 6 = 50%.
</details>

**Q4.10 (FL-4.2.4, K3)** A smart lock has states **Locked, Unlocked, Open** and these valid transitions: Locked –unlock→ Unlocked, Unlocked –lock→ Locked, Unlocked –open→ Open, Open –close→ Unlocked. Starting in Locked, what is the minimum number of test cases for 100% **valid transitions** coverage?
- a) 1
- b) 2
- c) 3
- d) 4

<details><summary>Show answer</summary>

**a)** One sequence covers all four: Locked →unlock→ Unlocked →open→ Open →close→ Unlocked →lock→ Locked.
</details>

**Q4.11 (FL-4.2.4, K3)** Same smart lock with 4 events (unlock, lock, open, close). How many **invalid** transitions appear in the full state table?
- a) 4
- b) 8
- c) 12
- d) 16

<details><summary>Show answer</summary>

**b)** 3 states × 4 events = 12 cells − 4 valid = 8 invalid.
</details>

**Q4.12 (FL-4.2.4, K2)** Which state transition coverage criterion should be the **minimum** for mission- and safety-critical software?
- a) All states coverage
- b) Valid transitions (0-switch) coverage
- c) All transitions coverage
- d) Each choice coverage

<details><summary>Show answer</summary>

**c)** All transitions coverage subsumes all states and valid transitions coverage.
</details>

**Q4.13 (FL-4.3.1/4.3.2, K2)** Which statement is TRUE?
- a) 100% statement coverage guarantees 100% branch coverage
- b) 100% branch coverage guarantees 100% statement coverage
- c) 100% branch coverage guarantees that all defects are found
- d) Statement coverage counts only conditional branches

<details><summary>Show answer</summary>

**b)** Branch coverage subsumes statement coverage, not vice versa.
</details>

**Q4.14 (FL-4.3.1, K2)** A program has 20 executable statements; tests executed 15 of them. Which is correct?
- a) Statement coverage is 75%, and all decision outcomes have been tested
- b) Statement coverage is 75%; it is unknown whether all decision outcomes were tested
- c) Branch coverage is 75%
- d) Statement coverage is 15%

<details><summary>Show answer</summary>

**b)** 15/20 = 75%. Statement coverage tells you nothing definitive about branch coverage.
</details>

**Q4.15 (FL-4.3.3, K2)** What is a weakness of white-box test techniques?
- a) They cannot be used when the specification is vague
- b) They may not detect defects of omission when a requirement was not implemented
- c) They cannot be used in static testing
- d) They don't provide any measure of coverage

<details><summary>Show answer</summary>

**b)** White-box *strength*: works even with vague specs and gives an objective coverage measure; can be used in static testing (dry runs).
</details>

**Q4.16 (FL-4.4.1, K2)** A tester builds a list of likely failures (wrong date formats, empty mandatory fields, division by zero) based on past defects and designs tests to provoke them. What is this?
- a) Checklist-based testing
- b) Fault attack (error guessing)
- c) Exploratory testing
- d) Decision table testing

<details><summary>Show answer</summary>

**b)** Fault attacks are a structured way to implement error guessing.
</details>

**Q4.17 (FL-4.4.2, K2)** Which statement about exploratory testing is correct?
- a) It cannot use other test techniques such as EP
- b) In session-based testing it is done in a time box guided by a test charter, followed by a debriefing
- c) It is only useful when detailed specifications exist
- d) It does not depend on tester skill

<details><summary>Show answer</summary>

**b)** It's useful when specifications are poor or under time pressure, and is more effective with experienced testers.
</details>

**Q4.18 (FL-4.4.3, K2)** Which item should NOT be included in a test checklist?
- a) "Does the error message explain how to fix the input?"
- b) "Is the page title consistent with the menu item?"
- c) An item that can be checked automatically by a tool
- d) "Can the user cancel the operation at any step?"

<details><summary>Show answer</summary>

**c)** Also avoid items better suited as entry/exit criteria and items that are too general.
</details>

**Q4.19 (FL-4.5.1, K2)** In the "3 C's" of user stories, what does **Confirmation** refer to?
- a) The medium on which the story is written
- b) The discussion about how the software will be used
- c) The acceptance criteria
- d) The product owner's signature

<details><summary>Show answer</summary>

**c)** Card = medium, Conversation = discussion, Confirmation = acceptance criteria.
</details>

**Q4.20 (FL-4.5.2, K2)** Acceptance criteria written as a **bullet-point verification list** are an example of which format?
- a) Scenario-oriented
- b) Rule-oriented
- c) Given/When/Then
- d) State-based

<details><summary>Show answer</summary>

**b)** Rule-oriented = bullet list or tabulated input–output mapping. Scenario-oriented = Given/When/Then.
</details>

**Q4.21 (FL-4.5.3, K3)** In ATDD, which order of test cases is typical?
- a) Non-functional → negative → positive
- b) Negative → positive → non-functional
- c) Positive → negative → non-functional
- d) Only positive tests are created

<details><summary>Show answer</summary>

**c)**
</details>

**Q4.22 (FL-4.5.3, K3)** User story: *"As a bank customer, I want to transfer money between my own accounts, so that I can manage my funds."* Acceptance criteria: (1) transfer amount must be between PKR 1 and PKR 500,000; (2) the source account must have sufficient balance; (3) a confirmation number is shown after success. Which test case is BEST derived from the criteria?
- a) Transfer PKR 10,000 to another customer's account and check a confirmation number is shown
- b) Transfer PKR 600,000 between own accounts and check the transfer succeeds
- c) Transfer PKR 5,000 from an account with balance PKR 2,000 and check the transfer is rejected
- d) Check that the customer can change their password during the transfer

<details><summary>Show answer</summary>

**c)** A correct negative test for AC2. (a) goes beyond the story (other customer's account), (b) has a wrong expected result (violates AC1), (d) is unrelated to the story.
</details>

### Chapter 4 – Quick-Fire Flashcards

| Question | Answer |
|---|---|
| Other name for black-box / white-box techniques? | **Specification-based** / **structure-based** |
| 4 black-box techniques? | **EP, BVA, decision tables, state transition** |
| 2 white-box techniques? | **Statement testing, branch testing** |
| 3 experience-based techniques? | **Error guessing, exploratory testing, checklist-based testing** |
| EP coverage items? | **Partitions** (valid + invalid) |
| Can partitions overlap? | **No** — and they must be non-empty |
| BVA works only for which partitions? | **Ordered** partitions |
| 2-value vs 3-value items per boundary? | **2** (boundary + neighbor in adjacent partition) vs **3** (boundary + both neighbors) |
| Decision table coverage items? | **Feasible columns** |
| "–" vs "N/A" in decision tables? | "–" = **irrelevant**; "N/A" = **infeasible** |
| State transition label syntax? | **event [guard] / action** |
| Which model shows invalid transitions explicitly? | **State table** (empty cells) |
| Other name for valid transitions coverage? | **0-switch coverage** |
| Most widely used state transition criterion? | **Valid transitions coverage** |
| Why one invalid transition per test? | To avoid **defect masking** |
| What is a branch? | A transfer of control between two nodes in the **control flow graph** |
| Collaboration-based approaches focus on? | **Defect avoidance** |
| INVEST? | Independent, Negotiable, Valuable, Estimable, Small, Testable |
| User story format? | As a [role], I want [goal], so that I can [business value] |
| First step of ATDD? | **Specification workshop** |

---

## Chapter 5 – Practice Questions

**Q5.1 (FL-5.1.1, K2)** Which of the following is typical content of a test plan?
- a) Detailed test logs from execution
- b) Test approach, including test levels, entry and exit criteria, and metrics to collect
- c) Source code of automated test scripts
- d) Defect reports from the previous release

<details><summary>Show answer</summary>

**b)** Test plan content: context, assumptions & constraints, stakeholders, communication, risk register, test approach, budget & schedule.
</details>

**Q5.2 (FL-5.1.2, K1)** How does a tester add value in **iteration** planning?
- a) By defining the product vision
- b) By breaking user stories into tasks, particularly testing tasks, and estimating test effort
- c) By approving the release budget
- d) By writing the company test policy

<details><summary>Show answer</summary>

**b)** Also: detailed risk analysis of stories, determining testability, refining functional & non-functional aspects.
</details>

**Q5.3 (FL-5.1.3, K2)** Which is a typical **entry** criterion for system testing?
- a) 90% requirements coverage achieved
- b) All smoke tests have passed on the delivered build
- c) No open critical defects remain
- d) All regression tests are automated

<details><summary>Show answer</summary>

**b)** Initial quality level of the test object is an entry criterion. (a), (c), (d) are exit criteria.
</details>

**Q5.4 (FL-5.1.3, K2)** In Agile development, exit criteria are often called…
- a) Definition of Ready
- b) Definition of Done
- c) Acceptance criteria
- d) Release criteria

<details><summary>Show answer</summary>

**b)** Entry criteria for a user story = Definition of Ready.
</details>

**Q5.5 (FL-5.1.4, K3)** Using three-point estimation, experts give: optimistic **2**, most likely **5**, pessimistic **14** person-days. What is the estimate and its standard deviation?
- a) 7 ± 2 person-days
- b) 6 ± 2 person-days
- c) 5 ± 12 person-days
- d) 6 ± 4 person-days

<details><summary>Show answer</summary>

**b)** E = (2 + 4×5 + 14) / 6 = 36 / 6 = **6**; SD = (14 − 2) / 6 = **2**.
</details>

**Q5.6 (FL-5.1.4, K3)** In a previous similar project, development took **300** person-days and testing **120** person-days. The new project's development is estimated at **450** person-days. Using ratio-based estimation, what is the estimated **test** effort?
- a) 120 person-days
- b) 180 person-days
- c) 270 person-days
- d) 630 person-days

<details><summary>Show answer</summary>

**b)** Ratio test/dev = 120/300 = 0.4 → 450 × 0.4 = **180**. (630 would be total effort.)
</details>

**Q5.7 (FL-5.1.4, K2)** Experts estimate independently, discuss estimates outside the agreed range, then re-estimate in isolation until consensus. Which technique is this?
- a) Extrapolation
- b) Three-point estimation
- c) Wideband Delphi
- d) Ratio-based estimation

<details><summary>Show answer</summary>

**c)** Planning Poker is its Agile variant.
</details>

**Q5.8 (FL-5.1.5, K3)** Tests with priorities (1 = highest) and dependencies:
TC1 – priority 3; TC2 – priority 1, depends on TC4; TC3 – priority 2; TC4 – priority 5; TC5 – priority 4.
What is the correct execution order?
- a) TC2, TC3, TC1, TC5, TC4
- b) TC4, TC2, TC3, TC1, TC5
- c) TC2, TC4, TC3, TC1, TC5
- d) TC3, TC1, TC5, TC4, TC2

<details><summary>Show answer</summary>

**b)** TC2 is highest but needs TC4 first → TC4, TC2, then TC3 (2), TC1 (3), TC5 (4).
</details>

**Q5.9 (FL-5.1.6, K1)** Which statement about the test pyramid is correct?
- a) Tests at the top are the fastest and most isolated
- b) Lower layers contain many small, isolated, fast tests
- c) The pyramid always has exactly three layers named unit, service and UI
- d) End-to-end tests are needed in the largest numbers

<details><summary>Show answer</summary>

**b)** Going up: lower granularity, lower isolation, longer execution time, fewer tests. Number and names of layers can vary.
</details>

**Q5.10 (FL-5.1.7, K2)** In the testing quadrants, which quadrant contains **usability testing** and **exploratory testing**?
- a) Q1 – technology facing, support the team
- b) Q2 – business facing, support the team
- c) Q3 – business facing, critique the product
- d) Q4 – technology facing, critique the product

<details><summary>Show answer</summary>

**c)** Q3 also contains UAT. Q4 has smoke and non-functional tests **except usability**.
</details>

**Q5.11 (FL-5.2.1, K1)** Risk A: likelihood 0.2, impact 5. Risk B: likelihood 0.5, impact 3. Risk C: likelihood 0.9, impact 1. Which has the highest risk level (quantitative)?
- a) Risk A
- b) Risk B
- c) Risk C
- d) All are equal

<details><summary>Show answer</summary>

**b)** A = 1.0, B = **1.5**, C = 0.9.
</details>

**Q5.12 (FL-5.2.2, K2)** Which is a **product** risk?
- a) The test environment may be delivered late
- b) A key tester may leave the company
- c) The system may calculate income tax incorrectly
- d) The tool vendor may go bankrupt

<details><summary>Show answer</summary>

**c)** (a) organizational, (b) people, (d) supplier → project risks.
</details>

**Q5.13 (FL-5.2.3, K2)** How can the results of product risk analysis be used?
- a) To decide the salaries of the test team
- b) To determine test techniques and the coverage to be achieved
- c) To replace the test plan
- d) To decide which developer caused each defect

<details><summary>Show answer</summary>

**b)** Also: test scope, test levels/types, effort estimates, prioritization, non-testing risk reduction activities.
</details>

**Q5.14 (FL-5.2.4, K2)** A company buys insurance to cover losses if its payment feature fails in production. Which risk response is this?
- a) Risk mitigation by testing
- b) Risk acceptance
- c) Risk transfer
- d) Risk monitoring

<details><summary>Show answer</summary>

**c)** Response options: mitigation by testing, acceptance, transfer, contingency plan.
</details>

**Q5.15 (FL-5.3.1, K1)** "Mean time to failure" is an example of which type of metric?
- a) Test progress metric
- b) Product quality metric
- c) Cost metric
- d) Coverage metric

<details><summary>Show answer</summary>

**b)** Product quality metrics: availability, response time, mean time to failure. Defect density / DDP = defect metrics.
</details>

**Q5.16 (FL-5.3.2, K2)** Which content belongs in a **test progress report** but NOT in a test completion report?
- a) Test metrics
- b) Impediments and workarounds
- c) Testing planned for the next period
- d) Lessons learned

<details><summary>Show answer</summary>

**c)** Lessons learned and unmitigated risks / unfixed defects are completion-report items; metrics and impediments appear in both.
</details>

**Q5.17 (FL-5.3, K2)** Which is an example of a **test control** directive?
- a) Counting the number of executed test cases
- b) Reprioritizing tests because an identified risk has become an issue
- c) Archiving testware at the end of the project
- d) Writing the test plan

<details><summary>Show answer</summary>

**b)** (a) is monitoring, (c) completion, (d) planning.
</details>

**Q5.18 (FL-5.4.1, K2)** How does configuration management support testing?
- a) It decides which tests to automate
- b) It ensures all configuration items are uniquely identified and version controlled, allowing a return to a previous baseline to reproduce test results
- c) It assigns severity to defects
- d) It replaces the need for traceability

<details><summary>Show answer</summary>

**b)**
</details>

**Q5.19 (FL-5.5.1, K3)** A tester writes this defect report: *"ID-77. Title: Checkout broken. Steps: add item, go to checkout, click Pay. Severity: High."* What is the MOST important information missing to help developers resolve it?
- a) The tester's favorite browser
- b) Expected result, actual result, and the test object version/test environment
- c) The name of the developer to blame
- d) The total number of defects in the project

<details><summary>Show answer</summary>

**b)** Without expected vs actual result and the environment/version, the defect is hard to reproduce and resolve.
</details>

**Q5.20 (FL-5.3.3, K2)** A team spread across Lahore and Toronto cannot meet face to face. Which is the MOST appropriate way to communicate test status?
- a) Only verbal hallway updates
- b) More formal communication, such as dashboards and formal test reports
- c) No status reporting until the end of the project
- d) Only informal chat messages

<details><summary>Show answer</summary>

**b)** More formal communication suits distributed teams due to distance and time differences.
</details>

### Chapter 5 – Quick-Fire Flashcards

| Question | Answer |
|---|---|
| 7 typical test plan contents? | Context, assumptions & constraints, stakeholders, communication, risk register, test approach, budget & schedule |
| Is running out of time a valid exit criterion? | **Yes**, if stakeholders **accept the risk** |
| 4 estimation techniques? | **Ratios, extrapolation** (metrics-based); **Wideband Delphi, three-point** (expert-based) |
| Three-point formula? | **E = (a + 4m + b) / 6**, **SD = (b − a) / 6** |
| 3 prioritization strategies? | **Risk-based, coverage-based** (incl. additional coverage), **requirements-based** |
| Who defined the testing quadrants? | **Brian Marick** |
| Q1 / Q2 / Q3 / Q4? | Component tests / functional & story tests / exploratory, usability, UAT / smoke & non-functional |
| Risk likelihood range? | **Greater than 0 and less than 1** |
| Risk analysis = ? Risk control = ? | Identification + assessment / mitigation + monitoring |
| 4 risk response options? | Mitigation by testing, acceptance, transfer, contingency plan |
| 4 categories of project risk? | Organizational, people, technical, supplier |
| 7 metric categories? | Project progress, test progress, product quality, defect, risk, coverage, cost |
| What does ISO 29119-3 call progress reports / defect reports? | **Test status reports** / **incident reports** |
| What is a baseline? | An approved configuration item, changeable only via **formal change control** |
| 3 objectives of a defect report? | Info to resolve; track work product quality; ideas for process improvement |

---

## Chapter 6 – Practice Questions

**Q6.1 (FL-6.1.1, K2)** Containerization tools and virtual machines belong to which tool category?
- a) Test management tools
- b) Tools supporting scalability and deployment standardization
- c) Static testing tools
- d) Collaboration tools

<details><summary>Show answer</summary>

**b)**
</details>

**Q6.2 (FL-6.1.1, K2)** Which statement is correct?
- a) Only commercial tools count as test tools
- b) A spreadsheet can be a test tool when used to assist testing
- c) Test management tools are used to execute performance tests
- d) DevOps tools support only manual testing

<details><summary>Show answer</summary>

**b)**
</details>

**Q6.3 (FL-6.2.1, K1)** Which is a potential **benefit** of test automation?
- a) Testers no longer need critical thinking
- b) More objective assessment, such as coverage, and measures too complicated for humans
- c) Automation tools never need maintenance
- d) All manual testing can be eliminated

<details><summary>Show answer</summary>

**b)**
</details>

**Q6.4 (FL-6.2.1, K1)** Which is a potential **risk** of test automation?
- a) Reduced test execution time
- b) Prevention of simple human errors
- c) Dependency on a tool vendor that may go out of business or provide poor support
- d) Easier access to test reporting information

<details><summary>Show answer</summary>

**c)** (a), (b), (d) are benefits.
</details>

**Q6.5 (FL-6.2.1, K1)** A team picks an open-source automation framework. Which risk is specific to this choice according to the syllabus?
- a) The tool may be abandoned, so no further updates are available
- b) The tool will execute tests too fast
- c) The tool will always comply with safety standards
- d) The tool will remove the need for test design

<details><summary>Show answer</summary>

**a)**
</details>

**Q6.6 (FL-6.1.1, K2)** Which tool type supports generating test cases, test data and test procedures?
- a) Test design and test implementation tools
- b) Collaboration tools
- c) Non-functional testing tools
- d) Static testing tools

<details><summary>Show answer</summary>

**a)**
</details>

### Chapter 6 – Quick-Fire Flashcards

| Question | Answer |
|---|---|
| Does buying a tool guarantee success? | **No** — introduction, maintenance and training effort needed |
| 9 tool categories? | Test management, static testing, test design & implementation, test execution & coverage, non-functional, DevOps, collaboration, scalability & deployment standardization, any other tool (e.g., spreadsheet) |
| 6 automation benefits? | Time saved, fewer human errors, objective assessment, easier info access, faster execution/feedback, more time for test design |
| 8 automation risks? | Unrealistic expectations, inaccurate estimates, tool used when manual is better, over-reliance, vendor dependency, abandoned open source, platform incompatibility, regulatory/safety non-compliance |

---

# PART E – MUST-KNOW LISTS (THE "MAGIC NUMBERS")

| Count | List |
|---|---|
| **9** | Typical test objectives |
| **3** | Debugging steps: reproduce, diagnose, fix |
| **7** | Testing principles |
| **7** | Test activity groups: planning, monitoring & control, analysis, design, implementation, execution, completion |
| **8** | Contextual factors affecting the test process |
| **2** | Test roles: test management role, testing role |
| **6** | Generic tester skills (testing knowledge; thoroughness…; communication…; analytical/critical thinking, creativity; technical knowledge; domain knowledge) |
| **4** | Levels of test independence |
| **5** | Things the SDLC impacts in testing |
| **4** | Good testing practices for any SDLC |
| **3** | Test-first approaches: TDD, ATDD, BDD |
| **5** | Shift-left practices |
| **5** | Test levels |
| **4** | Test types |
| **8** | ISO 25010 non-functional characteristics |
| **3** | Maintenance testing triggers; **3** factors for its scope |
| **5** | Review process activities |
| **6** | Review roles |
| **4** | Review types |
| **9** | Review success factors |
| **3** | Test technique categories |
| **4 + 2 + 3** | Black-box + white-box + experience-based techniques |
| **3** | State transition coverage criteria |
| **3** | C's of user stories; **6** INVEST letters |
| **5** | Uses of acceptance criteria; **2** common formats |
| **7** | Test plan content items |
| **4** | Estimation techniques |
| **3** | Test case prioritization strategies |
| **4** | Testing quadrants |
| **4** | Project risk categories |
| **6** | Ways to use product risk analysis results |
| **4** | Risk response options; **6** ways to mitigate by testing |
| **7** | Test metric categories |
| **6** | Test progress report contents; **7** test completion report contents |
| **5** | Ways to communicate test status |
| **11** | Defect report contents; **3** defect report objectives |
| **9** | Tool categories |
| **6** | Automation benefits; **8** automation risks |

## v3.1 → v4.0 Terminology Changes

Many free videos and old notes online still teach **v3.1 (retired)**. Watch for these differences:

| Old (v3.1) | New (v4.0 / v4.0.1) |
|---|---|
| Pesticide paradox | **Tests wear out** |
| 4 test levels (component, integration, system, acceptance) | **5 test levels** — integration split into **component integration** and **system integration** |
| Test types: functional, non-functional, white-box, **change-related** | Test types: functional, non-functional, **black-box**, white-box (confirmation & regression covered separately) |
| Decision coverage | **Branch coverage** |
| Use case testing | **Removed** |
| Test manager / tester as job titles | **Test management role / testing role** |
| General metrics-based & expert-based estimation | **4 named techniques**: ratios, extrapolation, Wideband Delphi, three-point |
| Tool selection, pilot projects, tool introduction | **Removed** — only tool types + automation benefits/risks |
| — | **New topics:** whole team approach, DevOps, shift left, retrospectives, test pyramid, testing quadrants, user stories (3 C's, INVEST), acceptance criteria, ATDD, 2-value & 3-value BVA, Each Choice coverage, test case prioritization |
| Usability / Portability (ISO 25010:2011) | Also called **interaction capability / flexibility**; **Safety** added (v4.0.1) |

## Exam-Day Strategy

1. **Time plan (60 min):** first pass — answer every K1/K2 question you know (~1 min each), **flag** the K3 and tricky ones. Second pass — solve flagged K3 questions (~3 min each). Keep 5 minutes to review flags.
2. **No negative marking** → **never leave an answer blank**.
3. **Read the stem twice.** Underline words like **NOT, BEST, MOST, LEAST, FIRST, TWO**.
4. **"Select TWO"** questions only score if **both** answers are right — read every option.
5. **Think in syllabus language**, not company language. The "real-world" answer you'd give at work is not always the syllabus answer.
6. Options with **absolute words** — *always, guarantees, proves, all defects, completely* — are usually wrong (testing can't prove absence of defects).
7. For K3 questions, **draw it** if scratch paper is allowed: partition line for EP/BVA, the decision table grid, the state diagram.
8. **Eliminate** clearly wrong options first; often two remain — pick the one that matches the syllabus wording most precisely.
9. Don't change an answer on review unless you find a **clear reason**.
10. Sleep well. Arrive early with your **CNIC/passport**.

## Last-Night Cheat Sheet

**Chapter 1**
- Error (human) → Defect (work product) → Failure (runtime). Root cause = fundamental reason.
- Testing ≠ debugging. Testing = product-oriented, corrective (QC). QA = process-oriented, preventive.
- 7 principles: **Presence · Exhaustive · Early · Defects cluster · Tests wear out · Context · Absence-of-defects fallacy**.
- Analysis = WHAT (test conditions). Design = HOW (test cases, coverage items, data & env **requirements**). Implementation = test **data**, procedures, suites, scripts, schedule, **build env**. Execution = run, compare, log, report. Completion = archive, shut down env, lessons, completion report.
- Independence: none → some → high → very high. Benefit: different defects. Drawback: isolation, devs lose responsibility, bottleneck.

**Chapter 2**
- TDD (test-code-refactor) · ATDD (from acceptance criteria) · BDD (Given/When/Then).
- 5 levels: component · component integration · system · system integration · acceptance.
- 4 types: functional · non-functional · black-box · white-box.
- Confirmation = was the fix OK? Regression = did the change break anything else? (impact analysis first)
- Maintenance triggers: **modification, migration/upgrade, retirement**.

**Chapter 3**
- Static = no execution; finds defects **directly**; works on non-executable products; measures maintainability.
- Review process: **Plan → Initiate → Individual review → Communicate & analyze → Fix & report**.
- Walkthrough = **author** leads. Technical = **moderator** leads, technical experts, decisions. Inspection = **most formal**, **metrics**, author ≠ leader/scribe, max anomalies.
- Never use reviews to evaluate people.

**Chapter 4**
- EP: one test per partition, invalid partitions count. Coverage = covered ÷ total.
- BVA: boundaries = min & max of **every** partition. 2-value = boundary + neighbor in next partition. 3-value = boundary ± 1.
- Decision table: 2ⁿ rules; coverage items = **feasible columns**.
- State transition: all states < valid transitions (0-switch) < all transitions. Invalid = empty cells in state table. One invalid per test.
- 100% branch ⇒ 100% statement (not vice versa). White-box can't find **omissions**.
- Error guessing / fault attacks · Exploratory (charter, time box, debrief) · Checklist (no automatable items).
- 3 C's: Card, Conversation, **Confirmation (= acceptance criteria)**. INVEST. Rule-oriented vs scenario-oriented. ATDD: positive → negative → non-functional.

**Chapter 5**
- Entry = DoR (resources, testware, smoke tests passed). Exit = DoD (coverage, defects, yes/no). Out of time OK if risk accepted.
- **E = (a + 4m + b) / 6 · SD = (b − a) / 6.** Ratio: watch dev:test direction.
- Prioritize by risk / coverage (additional coverage) / requirements — **dependencies first**.
- Pyramid: bottom = many, fast, isolated. Quadrants: Q1 unit · Q2 functional/story · Q3 exploratory/usability/UAT · Q4 smoke/non-functional.
- Risk level = likelihood × impact. Project risk (org, people, technical, supplier) vs product risk (quality).
- Responses: mitigate by testing, accept, transfer, contingency.
- Progress report = regular, includes "next period". Completion report = once, includes lessons learned & unmitigated risks.
- CM: unique ID, version control, baseline, revert to reproduce results.
- Defect report: ID, title, date/author, object & env, context, steps, **expected vs actual**, severity, priority, status, references.

**Chapter 6**
- Tools: management, static, design/implementation, execution/coverage, non-functional, DevOps, collaboration, VMs/containers, spreadsheets.
- Risks: unrealistic expectations, bad estimates, over-reliance, vendor dependency, abandoned open source, incompatible, non-compliant.

---

## 📚 Official References

- ISTQB® CTFL v4.0 page (syllabus, sample exams, exam structure): https://istqb.org/certifications/certified-tester-foundation-level-ctfl-v4-0/
- ISTQB® Glossary: https://glossary.istqb.org
- Find an exam provider: https://istqb.org/exam-providers/?directory_type=exam-providers&exam=CTFL%204.0
- Pakistan Software Testing Board (PSTB): https://pstb.pk
- Successful Candidate Register: https://scr.istqb.org
- Standards referenced in the syllabus: ISO/IEC/IEEE 29119-1/-2/-3/-4, ISO/IEC 20246 (reviews), ISO/IEC 25010 (quality model), ISO/IEC 14764 (maintenance), ISO 31000 (risk)

---

> **Disclaimer:** ISTQB® is a registered trademark of the International Software Testing Qualifications Board. These are personal, unofficial study notes summarizing the public CTFL Syllabus v4.0.1. The practice questions in Part D are original and are not official ISTQB® exam questions. Always confirm exam fees, dates and rules with your exam provider.

*Last updated: October 2026 · Syllabus v4.0.1*
