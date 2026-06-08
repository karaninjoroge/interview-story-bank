# Failure & Learning Stories

---

## Story 1: The Assumption I Did Not Question

**Question This Answers:** "Tell me about a time you failed or made a mistake. What did you learn?"
**Competency:** Self-awareness, Learning mindset, Intellectual honesty
**Context:** Hospital Queue Management discovery phase

---

**Situation:**
When I began the hospital queue management project, I spent the first two days designing a product before talking to any users. I built a detailed feature list, sketched a user flow, and was genuinely excited about the solution. The product was focused on throughput optimization — faster processing, better triage algorithms, routing patients to less-busy doctors.

**Task:**
My task was to design a PM case study that demonstrated rigorous discovery. The problem was that I had skipped the discovery entirely and gone straight to solution design.

**Action:**
When I eventually forced myself to write out my assumptions before starting interviews, I realized I had made a fundamental error: I had assumed I understood the problem without evidence. The list of assumptions I wrote down was embarrassing — eight claims about user behavior that I had treated as facts.

I ran the interviews anyway, specifically designed to challenge those assumptions. By interview three, the core assumption — that patients wanted faster service — had been clearly invalidated. What patients wanted was information about their wait, not reduction of it.

I deleted my initial feature list and started over from the research findings.

**Result:**
The final product direction was meaningfully different from where I started. More importantly, I now have a discipline I did not have before: I write out assumptions before starting any research, and I design questions specifically to challenge them. The most dangerous assumption is the one you do not know you are making.

**What I Would Do Differently:**
Start with the assumption log before any solution thinking. The two days I spent designing before talking to users was not wasted — it made my assumptions explicit enough to test — but the sequence was wrong. Discovery first, always.

**PM Skills This Demonstrates:**
Intellectual honesty · Research discipline · Willingness to be wrong · Learning from failure

---

## Story 2: Scoping Failure — Wanting to Build Everything

**Question This Answers:** "Tell me about a time your plan didn't work out."
**Competency:** Scope discipline, Judgment, Learning

---

**Situation:**
When I first drafted the MVP definition for the hospital queue platform, my "MVP" contained eleven major features. Appointment scheduling, AI wait time prediction, multi-facility management, USSD fallback, patient ratings for facilities, and more. It was not an MVP. It was a roadmap dressed up as a launch.

**Task:**
I needed to define an MVP that was genuinely minimal while still solving the core problem.

**Action:**
I went back to the research and asked one question for each feature: "Does the product fail to solve the core problem without this?" If the answer was no, the feature moved out of MVP.

Appointment scheduling: removes the core problem of showing up and waiting — but requires patient behavior change that has not been validated. Out.
AI wait time prediction: improves accuracy of updates — but we have no training data pre-launch. Out.
USSD fallback: important for feature phone users — but SMS alone covers 80%+ of the target market in v1. Into v1.1.

By the time I finished this process, the MVP had four features instead of eleven.

**Result:**
The MVP I defined is genuinely launchable by a small team in a realistic timeframe. The features I removed all went into a prioritized backlog, not the bin — they are P1 and P2 items waiting for validation of the core system.

**PM Skills This Demonstrates:**
MVP thinking · Scope discipline · Evidence-based decision making · Backlog management
