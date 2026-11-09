# Beginner Plan — SQL & Python From Zero

**Starting point (honest, set 2026-11-09):** Treat SQL and Python as brand new.
The programming degree is from 2018 — 8 years ago — so nothing is assumed or skipped.
Work history still counts on a resume; it just doesn't shortcut learning the languages.

Daily rule: 45–60 min computer days, 30 min light days, 15 min phone minimum on busy days.
📱 = phone-doable · 💻 = computer best

**Core beginner resources (all free):**
- SQL: SQLBolt (interactive, browser/phone) · Alex The Analyst "Learn SQL Beginner to Advanced" (YouTube, from 0:00) · Khan Academy Intro to SQL
- Python: Programming with Mosh "Python in 1 Hour" (YouTube) · Kaggle Learn Python course · SoloLearn / Mimo app (phone)
- Pandas comes LATER (Weeks 9–12) — only after Python basics are solid

## Weeks 1–4: Absolute Basics (Nov 10 – Dec 7, 2026)

### Week 1: What things are + first lines
- [ ] Day 1 — Tue Nov 10 💻 Setup: VS Code check, clone this repo, `python --version`, open PROGRESS.md
- [ ] Day 2 — Wed Nov 11 📱/💻 SQL: What is a database / table / row / column. SQLBolt Lesson 1 (SELECT). Alex SQL video 0:00–21:00
- [ ] Day 3 — Thu Nov 12 📱/💻 Python: Mosh 0:00–30:00 — first program, variables, strings, receiving input
- [ ] Day 4 — Fri Nov 13 📱/💻 SQL: SQLBolt Lessons 2–3 — WHERE, AND/OR, filtering
- [ ] Day 5 — Sat Nov 14 📱/💻 Python: Mosh 30:00–end — numbers, if statements
- [ ] Day 6 — Sun Nov 15 💻 Build (light build): Save 5 SQL queries in `sql/week1.sql` and a `python/hello.py` that prints + uses a variable. Commit both
- [ ] Day 7 — Mon Nov 16 📱 Light: SoloLearn Python first module on phone. Re-read your week 1 notes

### Week 2: Sorting, counting, lists, loops
- [ ] Day 8 — Tue Nov 17 SQL: SQLBolt Lessons 4–5 — ORDER BY, LIMIT, simple math
- [ ] Day 9 — Wed Nov 18 Python: Kaggle Learn Python L1–2 — functions, booleans, conditionals
- [ ] Day 10 — Thu Nov 19 SQL: Alex SQL — Group By section. SQLBolt Lesson 10 intro to grouping
- [ ] Day 11 — Fri Nov 20 Python: Kaggle Learn Python L3 — Lists
- [ ] Day 12 — Sat Nov 21 SQL: Practice — 5 GROUP BY queries on a sample table, save to `sql/week2.sql`
- [ ] Day 13 — Sun Nov 22 💻 Build: Python script that loops over a list and prints each item with a number. Commit it
- [ ] Day 14 — Mon Nov 23 📱 Light: Phone drills — SoloLearn SQL + Python review

### Week 3: Joins (slowly) + dictionaries, loops in Python
- [ ] Day 15 — Tue Nov 24 SQL: What a JOIN is and why tables split data. Alex SQL — Joins section, first half only
- [ ] Day 16 — Wed Nov 25 Python: Kaggle Learn Python L4 — Loops and List Comprehensions
- [ ] Day 17 — Thu Nov 26 📱 Light (holiday-friendly): Phone only — rewatch the JOIN explainer, 2 SQLBolt review lessons
- [ ] Day 18 — Fri Nov 27 SQL: INNER JOIN practice — SQLBolt Lessons 6–7
- [ ] Day 19 — Sat Nov 28 Python: Kaggle Learn Python L5 — Strings and Dictionaries
- [ ] Day 20 — Sun Nov 29 💻 Build: 3 JOIN queries saved + a Python script using a dictionary (e.g. product -> price) that looks items up. Commit both
- [ ] Day 21 — Mon Nov 30 📱 Light: Review notes, redo 1 SQL lesson and 1 Python lesson you found hardest

### Week 4: Putting basics together + first self-test
- [ ] Day 22 — Tue Dec 1 SQL: LEFT JOIN + NULLs — SQLBolt Lessons 7–8
- [ ] Day 23 — Wed Dec 2 Python: Kaggle Learn Python L6 — Working with External Libraries intro + finish the Python course (certificate)
- [ ] Day 24 — Thu Dec 3 SQL: HAVING vs WHERE, CASE statements — Alex SQL sections
- [ ] Day 25 — Fri Dec 4 Python: Reading a file — Python's built-in `csv` module, count rows in a CSV (no pandas yet)
- [ ] Day 26 — Sat Dec 5 💻 Build: Script that reads a sample CSV with `csv`, prints row count + first 5 rows. Commit it
- [ ] Day 27 — Sun Dec 6 SQL+Python self-test (no videos, notes allowed): write a JOIN + GROUP BY query from scratch; write a Python loop + dictionary script from scratch
- [ ] Day 28 — Mon Dec 7 📱 Retro in `notes/`: what feels solid, what's still shaky. That decides Week 5 pacing

## Weeks 5–12: Still Foundations, Level 2
- **Weeks 5–8 — Intermediate SQL + more Python:** subqueries, CTEs, then window functions (they live here now, not Week 2); Python functions properly, error handling, `requests` / APIs at the end
- **Weeks 9–12 — Pandas from zero:** Kaggle Learn Pandas (now it fits), merging data, cleaning real CSVs, first SQL + Python combined mini-project
- **Pass mark to leave Phase 1:** Unaided, you can (1) write a JOIN/GROUP BY/CTE query, (2) write a Python script that reads, cleans, and summarizes a CSV in pandas

## After Phase 1 (unchanged destination, later start)
- Phase 2 — dbt + Snowflake + Prefect (starts ~Month 4; DataTalksClub Zoomcamp self-paced fits better here than the January live cohort now)
- Phase 3 — Two portfolio projects: e-commerce ELT pipeline, daily incremental pipeline
- Realistic job-ready window on this honest pacing: **9–12 months** to Junior Data Engineer / Analytics Engineer applications
