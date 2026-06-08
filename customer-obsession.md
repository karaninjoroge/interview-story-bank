# Customer Obsession Stories

---

## Story 1: Designing for the User Nobody Interviewed

**Question This Answers:** "Tell me about a time you advocated for the user."
**Competency:** Customer obsession, Empathy, Advocacy

---

**Situation:**
During synthesis of my hospital queue research, I noticed a gap in my participant set. All three patients I interviewed were relatively comfortable navigating unfamiliar situations and had access to at least one smartphone (their own or a family member's). I had not spoken to older patients with feature phones only, or patients with low literacy.

**Task:**
I needed to ensure the product did not inadvertently exclude the most vulnerable segment of the patient population — exactly the people who suffer most from the current system.

**Action:**
I went back to the interview notes from Joseph (58, retired, Kisumu) — the closest I had to an older, less tech-forward user. His comment about his grandson checking the phone for him became a design insight rather than an edge case. I called this "proxy digital behavior" — using a family member's smartphone to access a service you cannot access directly.

I added this pattern explicitly to the personas document and made it a design constraint: the system must work for users who interact through proxies, not just direct users. This meant the SMS reference number had to be shareable and the status check had to work on any phone, not just the one that registered.

**Result:**
The product now has an explicit design requirement that emerged from one overlooked participant note. The "STATUS [queue number]" SMS command exists because of that design insight. Any phone can check any queue position — the registering phone does not need to be present.

**PM Skills This Demonstrates:**
User advocacy · Inclusive design thinking · Finding signal in overlooked data

---

## Story 2: The Abandonment Rate Nobody Was Counting

**Question This Answers:** "Tell me about a time you identified a problem others had missed."
**Competency:** Customer obsession, Insight, Problem identification

---

**Situation:**
In my interview with Dr. Wanjiku (Clinical Officer, Thika Level 5), she mentioned offhand that administration measured throughput — patients served per day — but never asked about abandonment. Patients who left were simply not counted.

**Task:**
As the PM, I needed to evaluate whether this was a product problem or a reporting problem — and whether it was significant enough to build for.

**Action:**
I calculated the impact. At a 400-patient-per-day facility with a 25% abandonment rate, 100 patients per day were leaving without care. These patients were invisible in every metric the administration used. The facility appeared to be running at capacity. In reality, it was losing a quarter of its potential impact.

I added abandonment tracking as a P0 feature — not just a nice-to-have reporting field. In the PRD, I defined it precisely: a patient who registers but is not marked as served within the grace window is counted as abandoned, not dropped. This distinction makes abandonment visible in daily summaries and forces administration to confront a number they previously ignored.

**Result:**
The daily summary report now surfaces abandonment rate alongside throughput. For the first time, facility administrators will have data showing the gap between registered patients and served patients. This creates accountability for a problem that previously had no measurement.

**PM Skills This Demonstrates:**
Problem identification from research · Translating insight into requirements · Metrics design · Advocacy for unmeasured outcomes
