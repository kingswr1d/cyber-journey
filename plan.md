# 12-week cyber security plan

**start date:** 28 sept 2026
**end date:** ~20 dec 2026 (12 weeks)
**target outcome:** first cyber security job offer by mid-2027

## context

- starting knowledge: junior sysadmin / hobbyist dev level
- hardware: laptop only (5gb ram — no local vm lab feasible)
- time budget: 15+ hrs/wk
- goal: any first sec role

## weeks 1-3: foundations + first cert push

**goal:** build the study rhythm, finish THM SOC L1 path, start Security+ prep

- **study:** professor messer security+ youtube (free) — domain 1 + 2 by week 3
- **lab:** tryhackme SOC level 1 learning path (30 rooms, ~25 hrs)
- **deliverables:**
  - week 1: THM rooms 1-10 + 2 writeups
  - week 2: THM rooms 11-20 + messer domain 1 summary
  - week 3: THM rooms 21-30 + messer domain 2 summary

## weeks 4-6: security+ finish + analyst fundamentals

**goal:** sit the security+ exam by end of week 6

- **study:** finish messer, full practice exams on examcompass + professormesser.com (3x timed runs)
- **lab:** letsdefend free tier SOC analyst path — investigate alerts, write incident reports
- **deliverable:** security+ cert in hand (aim 800+/900). book exam early in week 4 — slots fill.

## weeks 7-9: siem + detection fundamentals

**goal:** become hireable, not just certified. real detection work.

- **lab:** wazuh single-node install on laptop (5gb is tight — disable elastic stack, just wazuh manager + agents). or use tryhackme's elastic prebuilt rooms.
- **practice:** letsdefend investigations continue. write 5+ sigma rules in `detection-rules/`.
- **deliverables:**
  - week 7: wazuh up + 1 custom rule + writeup
  - week 8: 5 letsdefend investigations + 1 public writeup
  - week 9: github `detection-rules/` repo with 3+ rules + readme

## weeks 10-12: capstone + job hunt

**goal:** ship a public portfolio, start applying

- **capstone:** detection-rules repo with 10+ rules + docker-compose so others can run your stack in 5 min
- **job hunt:** resume + linkedin rewrite (post-sec+), 10 informational interviews with SOC analysts on linkedin
- **cert optional:** BTL1 if budget allows — it's the cert that says "i can do the job"
- **deliverables:**
  - week 10: resume + linkedin rewrite done, 5 SOEs sent
  - week 11: 10 more SOEs + 2 mock interviews on Pramp
  - week 12: applications live + capstone repos public + first 5 job apps submitted

## cost

| item | cost | required? |
|---|---|---|
| tryhackme | free (or $10/mo for premium) | yes |
| letsdefend | free tier or $30/mo | yes |
| security+ exam | ~R7,500 ($392) | YES — HR filters on this |
| professor messer | free | yes |
| BTL1 | ~$450 | optional, week 10+ |

**backup plan if security+ cost is blocker:** Google Cybersecurity Certificate (coursera, ~$49/mo, financial aid available free). Increasingly accepted for SOC tier 1 roles in 2026-27.

## rules for me

1. every friday: post on linkedin. non-negotiable.
2. every friday: commit to this repo (notes + writeups). non-negotiable.
3. if i miss a week: i tell you why, and i make it up the next week. no quiet disappearing.
4. budget is real: don't buy anything without checking with hermes first. free alternatives exist for almost everything.

## not in scope (yet)

- red team / pen testing (later, year 2 maybe)
- OSCP / OSEP (year 2+)
- cloud security specialization (later)
- malware reverse engineering (later)
- compliance-only GRC roles (week 12+ decision — could pivot here if SOC path is too slow)
