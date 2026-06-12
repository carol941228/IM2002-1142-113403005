# Peer Review Report

> **Instructions:** Complete this form **individually and independently**.
> Do not discuss your ratings with teammates before submitting.
> Submit via EEClass as a **separate, confidential submission** — not in the shared team repo.
> Your teammates will not see this report.
>
> Reference the team's `WORK_ALLOCATION_TEMPLATE.md` when completing this form.

---

## Your Details

| Field | Your answer |
|-------|------------|
| Full Name |卓少筠 |
| Student ID |113403005 |
| Team ID |45 |
| Date submitted |2026/6/12 |

---

## Rating Scale

| Rating | Meaning |
|--------|---------|
| **5** | Exceeded expectations — delivered more than agreed; helped teammates; consistently high quality |
| **4** | Met expectations fully — delivered exactly what was agreed; on time; good quality |
| **3** | Mostly met expectations — minor shortfalls; one or two items completed late or with help |
| **2** | Partially met expectations — noticeable gaps; teammates had to cover some tasks |
| **1** | Did not meet expectations — significant tasks left incomplete; very limited contribution |

---

## Section A — Self-Assessment

### A1. What did you personally implement?

List the specific tasks, functions, files, or document sections that you were the primary author of.
Be specific (e.g., "I designed all 12 tables in schema.sql and implemented query_national_rail_availability and execute_booking").

> I focused on database security and integrity enforcement, I implemented Argon2id password hashing and moved passwords out of the user table, added
  missing Foreign Keys between bookings and payments tables to prevent ghost bookings and data corruption, and enforced CHECK constraints on status
  columns to replace open strings and eliminate data entry typos.

---

### A2. What challenges did you face?

Describe any technical or collaboration difficulties you personally encountered and how you resolved them.

> Ensuring the password protection, the new foreign key and CHECK constraints did not conflict with existing database records or break any functions.
  To solve the problem, I created the branch every time before using AI to generate the code and check the database in pgAdmin to see if there is
  anything going wrong. In addition , I also use self-learning resources on ee-class to learn the basic knowledge of database to avoid depending on
  AI.

---

### A3. Self-rating

| Criterion | Rating (1–5) | Justification (1–2 sentences) |
|-----------|-------------|-------------------------------|
| I delivered the tasks assigned to me in the work allocation |5|I do everything in my part of the work allocation. |
| The quality of my work was satisfactory |4|The problem in the oringinal database is corrected. |
| I communicated well and kept the team informed |3|After I modified the file, I would tell my partner what I did. |
| I met deadlines agreed within the team |5|I did my job before the deadline my team dicided. |
| **Overall self-rating** |3|Most of the works are not finished by me, I just try to find if there is anything that can be improved and modified it. |

---

### A4. Estimated contribution percentage

What percentage of the total team effort do you estimate you personally contributed?

> My estimated contribution: **_10_%**

---

## Section B — Peer Assessments

Complete one subsection per teammate. Add or remove subsections to match your team size.
If your team has 2 members, complete B1 only. If 3 members, complete B1 and B2.

---

### B1. Assessment of Teammate 1

| Field | Your answer |
|-------|------------|
| Teammate's full name |林楷崋 |
| Teammate's student ID |113403018|

#### What did this teammate deliver?

List the tasks, functions, files, or document sections that this teammate was the primary author of,
based on what you observed during the project (compare against the work allocation).

> Optimizing system performance such as adding efficient shortest-path queries by Dijkstra's Algorithm, preventing connection exhaustion
  by Singleton and Connection Pool, and so on. In addition, he also add annotation of the codes and other thing belonging to the bonus item.

#### Did their actual contribution match the agreed work allocation?

> Yes, no more and no less.

#### Peer rating for this teammate

| Criterion | Rating (1–5) | Justification (1–2 sentences) |
|-----------|-------------|-------------------------------|
| Delivered the tasks assigned in the work allocation |5|do everything in his part|
| Quality of their work was satisfactory |5|All the function has no problem.|
| Communicated well and kept the team informed |4|ask whether we can have a meeting or if there is anything he can help actively|
| Met deadlines agreed within the team |4|after one day of the deadline. |
| **Overall rating for this teammate** |4|successfully enhance the database|

#### Estimated contribution percentage for this teammate

> My estimate of their contribution: **_25_%**

---

### B2. Assessment of Teammate 2

| Field | Your answer |
|-------|------------|
| Teammate's full name |郭明儒 |
| Teammate's student ID |114423010|

#### What did this teammate deliver?

> All the task the teacher requested and md file of document and work allocation.

#### Did their actual contribution match the agreed work allocation?

> Yes, no more and no less.

#### Peer rating for this teammate

| Criterion | Rating (1–5) | Justification (1–2 sentences) |
|-----------|-------------|-------------------------------|
| Delivered the tasks assigned in the work allocation |5|do everything in his part|
| Quality of their work was satisfactory |4|still have something that can be improved|
| Communicated well and kept the team informed |3|don't respond to the message quickly|
| Met deadlines agreed within the team |5|do all the job very early|
| **Overall rating for this teammate** |4|finish the whole task and can run successfully|

#### Estimated contribution percentage for this teammate

> My estimate of their contribution: **_65_%**

---

## Section C — Contribution Percentage Summary

All members (including yourself) must sum to 100%.

| Member | Your estimated % | Notes |
|--------|----------------|-------|
| Yourself |10% | |
| Teammate 1 |25% | |
| Teammate 2 |65% |  |
| **Total** | **100%** | |

---

## Section D — Overall Team Reflection

### D1. What went well in the team's collaboration?

> Actually, I think we almost don't have enough discussion about the project, we only have a meeting, and didn't decide the work allocation. We just found out what part
 we can add something and send the finish message after modifying it. Furthermore, I send mail to my partner and he responded to me almost one week later, and told me he
 had finished the whole task and ask us whether we would keep working with it or make a new project from the beginning(5/23), finally we decided to continue with it and
 that is the only thing we decide in the meeting(5/31). 

---

### D2. What would you do differently if you did this project again?

> I would ask for making a new project from the beginning.

---

### D3. Is there anything else the markers should know about team dynamics or individual contributions?

This is optional. Use it only if there is important context that the ratings above do not capture
(e.g., a member had a documented personal emergency, or a member was unresponsive for a significant period).

> Nothing to add

---

## Declaration

I confirm that this peer review reflects my honest and independent assessment.
I understand it will be kept confidential from my teammates.

**Signed:** _____________卓少筠____________________ **Date:** _____2026/6/12__________
