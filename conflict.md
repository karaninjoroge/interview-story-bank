# Conflict Stories

---

## Story 1: When the Data and the Instinct Disagreed

**Question This Answers:** "Tell me about a time you dealt with a disagreement or conflict."
**Competency:** Conflict resolution, data-driven thinking, intellectual honesty

---

**Situation:**
During the prioritization phase of the hospital queue management project, I had a tension between two approaches that felt like a genuine conflict — not with another person, but between what my RICE scores were telling me and what my research instinct was saying.

The RICE scores ranked the patient SMS system significantly higher than the staff dashboard. On pure numbers, the patient system should be built first. But the research told me something different: without staff adoption, the patient system has no operational context to function within. A patient who texts in gets a queue number — but if the nurse isn't using the dashboard to manage the queue, that number means nothing.

**Task:**
I needed to resolve this conflict with a documented decision I could defend, not just a gut call.

**Action:**
I went back to first principles: what is RICE actually measuring? It measures reach, impact, confidence, and effort at a feature level. It does not capture dependencies between features. The staff dashboard wasn't a lower-priority feature — it was a prerequisite.

I added a "dependency flag" to my prioritization table and documented explicitly: the staff dashboard has lower RICE scores but unlocks the value of every patient-facing feature. It is not P1 — it is P0-dependency. This reframing resolved the conflict by exposing the limitation of the framework in this specific context.

**Result:**
Both features entered the MVP with the staff dashboard sequenced first in development. The prioritization document now has an explicit note explaining why a lower-scoring feature takes sequence priority. Anyone reading it can understand the decision without having been in the room.

**PM Skills This Demonstrates:**
Navigating framework limitations · Documenting decisions under uncertainty · Honest trade-off reasoning
