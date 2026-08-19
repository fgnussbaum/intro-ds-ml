> **Navigation:** [Part Index](00-index.md) | [Main Index](../index.md) | [Pitching a Data-Science Idea -->](02-pitching-a-ds-idea.md)

---

# CRISP-DM Retrospective: From Coursework to Real Projects

**Requires**: [CRISP-DM](../part-01-the-big-picture/04-crisp-dm.md) · [Working as a Team on a DS Project](../part-02-ds-projects/03-team-project-basics.md)

**Motivation**: Across this course, CRISP-DM was the guiding process. We considered various techniques and process phases. Now, what changes when the CRISP-DM process leaves the classroom and enters an organization with real stakeholders, budgets, and consequences?

> Here we'll zoom out to the whole course arc, map every part back onto the CRISP-DM phases, and name what shifts when moving from personal/student projects to professional data-science work: more stakeholders, negotiated expectations, and genuine accountability.

## Table of Contents

- [The Course Arc in One Map: CRISP-DM Revisited](#the-course-arc-in-one-map-crisp-dm-revisited)
- [What Changes with Multiple Stakeholders: Roles, Expectations, Accountability](#what-changes-with-multiple-stakeholders-roles-expectations-accountability)
- [Plan, Pitch, Perform: From Data Science Idea to Funded Project](#plan-pitch-perform-from-data-science-idea-to-funded-project)
- [Summary](#summary)

## The Course Arc in One Map: CRISP-DM Revisited

We introduced CRISP-DM in [🖝 CRISP-DM](../part-01-the-big-picture/04-crisp-dm.md) as a live orientation tool for the major parts of the course. Let's sum up the whole arc:

| CRISP-DM phase | Where you practiced it |
|---|---|
| Business Understanding | [🖝 Part I: The Big Picture](../part-01-the-big-picture/00-index.md), [🖝 Part II: Data-Science Projects](../part-02-ds-projects/00-index.md) |
| Data Understanding | [🖝 Part III: Data Understanding](../part-03-data-understanding/00-index.md) |
| Data Preparation | [🖝 Part IV: Data Preparation](../part-04-data-preparation/00-index.md) |
| Modeling | [🖝 Part V: Supervised Learning](../part-05-supervised-learning/00-index.md), [🖝 Part VII: Unsupervised Learning](../part-07-unsupervised-learning/00-index.md), [🖝 Part VIII: Deep Learning](../part-08-deep-learning/00-index.md) |
| Evaluation | Parts V-VIII, and the principles in [🖝 Part VI: Principles That Transfer (Reflection)](../part-06-reflection/00-index.md) |
| Deployment | This part |

You have traversed the "inner loop" (Data Understanding, Preparation, Modeling, Evaluation) many times, but **Deployment** was not much of a topic yet. However, most value of a solution can only unfold when it gets deployed and does actual work. Therefore, deployment is where a model or a system stops being something you own alone and becomes something other people rely on.

---

## What Changes with Multiple Stakeholders: Roles, Expectations, Accountability

For small personal project, you set the goal and own everything from idea to solution. In this spirit, [🖝 Part II: Data-Science Projects](../part-02-ds-projects/00-index.md) was a deliberately light pass at Business Understanding. Real projects widen this:

- **More stakeholders, more interests.** Beyond project-internal functions as we discussed in [🖝 Working as a Team on a DS Project](../part-02-ds-projects/03-team-project-basics.md), real projects depend on outside people: funding sponsors, end users who must adopt it, the people affected by its decisions, and functions like IT, compliance, and finance. Each has different interests, and some may resist the outcome.

- **Expectations must be negotiated.** In [🖝 Academia vs. Business Data Science](../part-01-the-big-picture/05-academia-vs-business-ds.md) you saw that business success means value for someone, and that the success metric has to be agreed with stakeholders. A recurring obstacle is that stakeholders often carry misconceptions about what AI can and cannot do. [(Nussbaum, 2023)](../references.md#nussbaum2023aimyths) contains some of the most common myths: that AI is always accurate, that it learns on its own, that it needs no maintenance. Surfacing and clarifying these upfront is usually helpful.

- **Accountability rises with the stakes.** In coursework, a wrong model costs little. In production, it can cost money, safety, or someone's rights: recall the deployed-system asymmetry from [🖝 AI Ethics: A Primer](../part-01-the-big-picture/03-ethics-and-responsibility.md). Someone needs to be accountable for what the system does. We return to this in [🖝 Ethics and Accountability in Production](../part-09-projects-in-practice/07-ethics-accountability.md).

> **Discussion:** When a deployed model produces a bad decision, who should be accountable, and how should that be decided *before* anything goes wrong?

---

## Plan, Pitch, Perform: From Data Science Idea to Funded Project

This part draws from the "Plan, Pitch, Perform" report [(Nussbaum, 2025)](../references.md#nussbaum2025planpitch). This is some of my own work which serves a framing on top of CRISP-DM, aiming at the organizational reality of getting a project funded and kept alive. It groups the procedure into three acts:

| Act | What it does | Course connection |
|---|---|---|
| **Plan** | Understand the business context and estimate value cheaply, filtering weak ideas early | [🖝 Part II: Data-Science Projects](../part-02-ds-projects/00-index.md), plus a feasibility pass through Parts III-V |
| **Pitch** | Win support and resources with a business case | [🖝 Pitching a Data-Science Idea](../part-09-projects-in-practice/02-pitching-a-ds-idea.md) |
| **Perform** | Execute, iterate, deploy, and maintain the funded project | surfaced in this part |

> The guiding principle behind the framework is: **Keep investments low while uncertainty is high**.

Especially during planning, cheap research and small experiments make sure that money and time are committed only once a project looks feasible and worthwhile. This is essentially [🖝 Reality-Checking Your Idea](../part-02-ds-projects/04-reality-checking-your-idea.md), scaled up from a "ten-minute check".

The pitch is covered in the next nugget [🖝 Pitching a Data-Science Idea](../part-09-projects-in-practice/02-pitching-a-ds-idea.md). From there, we move into Perform: taking a working model out of a notebook and keeping it trustworthy over time.

---

## Summary

- The prior course parts trace the CRISP-DM phases from Business Understanding to Evaluation. In this part, we also consider deployment.
- Aspects of real projects: more stakeholders with divergent interests, success criteria that must be negotiated, and accountability that scales with the stakes.
- Non-technical stakeholders often hold misconceptions about AI. Aligning expectations early is part of the job.
- The Plan-Pitch-Perform framing wraps CRISP-DM's early phases and keeps investment low while uncertainty is high, extending the reality-check habit from Part II.

As always: Happy learning, happy life! 🫶


---

> **Navigation:** [Part Index](00-index.md) | [Main Index](../index.md) | [Pitching a Data-Science Idea -->](02-pitching-a-ds-idea.md)

Script v1.8 (2026-08-19) · FGN
