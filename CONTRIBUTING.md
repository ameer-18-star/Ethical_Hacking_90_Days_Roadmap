# 🤝 Contributing to 90 Days of Ethical Hacking

Thank you for taking the time to contribute! This roadmap is a **living document** built by and for the ethical hacking community. Every improvement — no matter how small — helps someone get their first job, pass their first cert, or find their first bug bounty.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [What We're Looking For](#what-were-looking-for)
- [What We're NOT Looking For](#what-were-not-looking-for)
- [How to Contribute](#how-to-contribute)
  - [Reporting Issues](#reporting-issues)
  - [Submitting a Pull Request](#submitting-a-pull-request)
- [Contribution Categories](#contribution-categories)
  - [📖 Learning Resources](#-learning-resources)
  - [🛠️ Practice Labs & Machines](#️-practice-labs--machines)
  - [💡 Professional Tips](#-professional-tips)
  - [🐛 Fixing Broken Links](#-fixing-broken-links)
  - [🌐 Translations](#-translations)
  - [🧪 Quizzes & Knowledge Checks](#-quizzes--knowledge-checks)
- [Style Guide](#style-guide)
- [Quality Standards](#quality-standards)
- [Review Process](#review-process)
- [Recognition](#recognition)

---

## 🧭 Code of Conduct

This project follows a simple rule: **be excellent to each other**.

- Treat all contributors and learners with respect — regardless of experience level.
- This roadmap is for **ethical, legal** security research and career development. Content that promotes illegal activity, unethical hacking, or harm to others will be rejected immediately and permanently.
- Constructive criticism is welcome. Personal attacks are not.
- Assume good intent. Everyone here is learning.

Violations can be reported by opening an issue tagged `[conduct]`.

---

## ✅ What We're Looking For

| Type | Examples |
|---|---|
| Better resources | A newer course, a clearer explanation, a free alternative to a paid resource |
| Additional labs | A new TryHackMe room, a VulnHub machine, a PortSwigger lab that fits a specific day |
| Updated content | Replacing deprecated tools, correcting outdated techniques, refreshing links |
| Pro tips | Real-world experience from pentesters, bug bounty hunters, red teamers, blue teamers |
| Translations | Full or partial translations into other languages |
| Quiz content | Multiple-choice or practical questions that test understanding per phase |
| Structural improvements | Better ordering, clearer explanations, added context for complex topics |
| Accessibility | Clearer language for non-native English speakers, more beginner-friendly phrasing |

---

## ❌ What We're NOT Looking For

- **Offensive tool tutorials** that have no clear defensive or educational purpose
- **Paid resource links** unless the resource is genuinely exceptional and a free alternative doesn't exist
- **Affiliate links** of any kind
- **Promotional content** for commercial products or services
- **Outdated certifications** no longer recognized in the industry
- **Platform-specific content** that only works on one OS without noting this
- **Vague contributions** — "This section could be better" is not a PR, it's a comment

---

## 🚀 How to Contribute

### Reporting Issues

Found a broken link? An outdated resource? A missing lab? Open an issue using the appropriate label:

| Label | Use for |
|---|---|
| `broken-link` | A URL that no longer works |
| `outdated-content` | A resource, tool, or technique that is no longer current |
| `missing-resource` | A gap in coverage — a topic that needs a better resource |
| `typo` | Spelling, grammar, or formatting errors |
| `suggestion` | Ideas for new content or structural changes |
| `conduct` | Code of conduct violations |

**Issue template — please include:**
- Which day/phase the issue is in
- What the current content says
- What the problem is
- What you'd suggest instead (if applicable)

---

### Submitting a Pull Request

1. **Fork** this repository
2. **Create a branch** with a descriptive name:
   ```
   git checkout -b fix/day-12-broken-link
   git checkout -b add/phase3-wireshark-resource
   git checkout -b translate/spanish-phase1
   ```
3. **Make your changes** following the [Style Guide](#style-guide) below
4. **Test all links** before submitting — dead links on arrival will be closed without review
5. **Write a clear PR description** that explains:
   - What phase/day you changed
   - What you added, removed, or updated
   - Why this improves the roadmap
6. **Submit your PR** against the `main` branch

PRs that touch multiple unrelated sections should be split into separate PRs. Focused changes are reviewed faster.

---

## 📂 Contribution Categories

### 📖 Learning Resources

When suggesting a new learning resource, it must meet **all** of the following:

- **Free or freemium preferred.** If paid, it must be significantly better than any free alternative and must be clearly labeled as paid.
- **Current.** Content must reflect tools and techniques relevant in the current year. A video tutorial using deprecated syntax or EOL tools is worse than nothing.
- **Specific.** A resource should map to a specific day or topic. "A great general hacking course" is not a contribution — "A better explanation of Kerberoasting for Day 78–80" is.
- **Verifiable.** The resource must be from a reputable creator, platform, or institution. Unknown YouTube channels with no community validation will not be merged.

**Format to use:**
```markdown
- [Resource Title](URL) — Brief one-line description of what it covers and why it's useful
```

---

### 🛠️ Practice Labs & Machines

Lab recommendations should specify:

- **Platform** (TryHackMe, HackTheBox, VulnHub, PortSwigger, etc.)
- **Difficulty** (Beginner / Intermediate / Advanced)
- **Which day(s) it supports**
- **Whether it requires a paid subscription** (label it clearly)
- **What specific skills it reinforces**

Machines from HackTheBox should be **retired** before being added, so walkthroughs are available for learners who get stuck.

---

### 💡 Professional Tips

Pro tips are one of the most valued parts of this roadmap. They must:

- Come from **real-world experience** — not rephrased documentation
- Be **specific and actionable** — not generic motivation
- Be **honest about context** — a tip that applies to bug bounty may not apply to pentesting engagements, and vice versa
- Be attributed in a general way (e.g., "Senior Pentester, consulting firm" or "Bug Bounty Hunter, top 100 on HackerOne") — **no full names or personal details unless you are personally submitting your own tip and consent to attribution**

**Format to use:**
```markdown
**💡 Pro Tip:** *"Your tip here."* — Role, context (e.g., Red Team Operator, enterprise)
```

---

### 🐛 Fixing Broken Links

If you find a broken link:

1. Search for the most current, equivalent resource
2. Prefer the **official source** over a mirror or aggregator
3. If no equivalent exists, note this in your PR — the section may need to be rewritten rather than just re-linked

Do not replace a quality resource with a lower-quality one just because the original URL broke.

---

### 🌐 Translations

Translations are welcome and encouraged. Guidelines:

- Create a new file named `README.[language-code].md` (e.g., `README.es.md` for Spanish)
- Translate the full document — partial translations create confusion and should be submitted as draft PRs
- Keep all URLs, tool names, platform names, and code examples in their original form — do not translate these
- Pro tips may be lightly adapted for cultural clarity, but should not change meaning
- Add yourself to the translation credits section at the bottom of the translated file

**Actively seeking translations in:** Arabic, Spanish, French, Portuguese, Hindi, Turkish, German, Mandarin

---

### 🧪 Quizzes & Knowledge Checks

Each phase should eventually have a short knowledge check. If you're contributing quiz content:

- Questions should test **conceptual understanding**, not rote memorization
- Include **4 answer choices** with one clearly correct answer and a brief explanation
- Questions should map to **specific days or topics** within the phase
- Format as a separate file: `quizzes/phase-[number]-quiz.md`

---

## ✍️ Style Guide

Consistency matters. Please follow these conventions:

### Headings
- Phase titles use `###`
- Day ranges use `####`
- Sub-sections within days use `**bold text**` as a label, not additional heading levels

### Time Estimates
- Always expressed as a range: `2–3 hours/day`
- Use an en dash (`–`), not a hyphen (`-`)

### Links
- Link text should be descriptive: `[Nmap Official Book](url)` not `[click here](url)`
- Do not shorten URLs — use the full canonical URL
- All external links should open correctly — test before submitting

### Tools and Commands
- Inline code for tool names and commands: `nmap`, `tcpdump`, `burpsuite`
- Code blocks for multi-line commands or scripts

### Pro Tips
- Always wrapped in a blockquote using `**💡 Pro Tip:**` prefix
- Attribution in italics at the end, separated by `—`
- Do not attribute to named individuals without their explicit consent

### Tables
- Use the existing table format for consistency
- Keep column headers short and clear

---

## 🔍 Quality Standards

Before submitting any PR, run through this checklist:

- [ ] All links tested and working
- [ ] Content is specific to a day or phase — not generic
- [ ] Free resources preferred; paid resources clearly labeled
- [ ] No affiliate links included
- [ ] Follows the style guide above
- [ ] PR description clearly explains what changed and why
- [ ] No duplicate content already covered in the roadmap
- [ ] Content promotes legal, ethical security research only

PRs that don't meet these standards will be returned with feedback before review.

---

## 🔄 Review Process

1. PRs are reviewed on a **rolling basis** — typically within 7 days
2. Every PR gets at least one review from a maintainer
3. Feedback will be given as inline comments on the PR
4. If changes are requested, the contributor has **14 days** to respond before the PR is closed (it can be reopened)
5. Approved PRs are merged to `main` directly — there is no staging branch

Maintainers reserve the right to edit contributions for style consistency before merging, without changing the substance of the content.

---

## 🏅 Recognition

Contributors who submit accepted PRs will be:

- Added to the `CONTRIBUTORS.md` file (name or GitHub handle, your choice)
- Credited inline on translated files they authored
- Credited in the changelog entry for their contribution

This project is volunteer-maintained. There is no monetary compensation — only the satisfaction of knowing your contribution helped someone get their start in security.

---

## 📬 Questions?

If you're unsure whether a contribution fits, **open an issue first** and ask. It's faster than submitting a PR that gets rejected.

For general discussion, join the community on [TCM Security Discord](https://discord.gg/tcm) or post in [r/netsec](https://reddit.com/r/netsec).

---

*This CONTRIBUTING.md was written to match the structure, tone, and standards of the 90 Days of Ethical Hacking roadmap. It is covered under the same MIT License.*
