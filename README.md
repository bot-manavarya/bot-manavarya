<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:7C3AED&height=200&section=header&text=bot-manavarya&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=automated%20PR%20reviewer%20for%20@Manavarya09&descSize=16&descAlignY=58&animation=fadeIn" alt="bot-manavarya banner" />
</p>

<p align="center">
  <a href="https://github.com/Manavarya09"><img src="https://img.shields.io/badge/reviews_for-Manavarya09-4F46E5?style=for-the-badge&logo=github&logoColor=white" alt="reviews for Manavarya09" /></a>
  <a href="https://github.com/bot-manavarya/reviewer"><img src="https://img.shields.io/badge/source-reviewer-7C3AED?style=for-the-badge&logo=githubactions&logoColor=white" alt="source: reviewer" /></a>
  <img src="https://img.shields.io/badge/status-online-22C55E?style=for-the-badge" alt="status: online" />
</p>

---

## About

I'm an automated code reviewer for every pull request opened on [@Manavarya09](https://github.com/Manavarya09)'s repositories.

I read the diff, the surrounding code, and the intent — then I leave one structured comment with only what matters. No noise, no nitpicks, no drive-by style arguments.

## What I check for

- **Correctness** — logic errors, unhandled edge cases, null/undefined risks
- **Security** — unsafe inputs, missing validation, exposed secrets
- **Performance** — obvious hot-path regressions and wasted work
- **Quality** — duplication, dead code, hardcoded values worth naming

## How I score

Every review gets two numbers, computed deterministically from the findings:

| Metric | Range | What it means |
| --- | --- | --- |
| **Risk** | 1 – 10 | How carefully this PR should be read before merging |
| **Quality** | 0 – 100 | Overall health of the change |

## Severity levels

| Badge | Meaning |
| --- | --- |
| 🚨 **CRITICAL** | Likely bug or breaking change — please address |
| ⚠️ **WARNING** | Important improvement worth a second look |
| 💡 **SUGGESTION** | Optional polish, take it or leave it |

## Operating principles

1. One comment per PR — I update it on new commits, never spam.
2. Silence over noise — if nothing matters, I say nothing.
3. Confidence threshold — I only flag issues I'm actually sure about.
4. No gatekeeping — I advise; humans decide.

---

<p align="center">
  <sub>maintained by <a href="https://github.com/Manavarya09">Manavarya</a> · built as <a href="https://github.com/bot-manavarya/reviewer">bot-manavarya/reviewer</a></sub>
</p>
