# Practice Questions by Topic

> **Purpose**: Topic-specific practice questions for targeted review
>
> **Organization**: Questions grouped by specific topics (not domains)
>
> **Last Updated**: 2025-12-24

---

## How This Folder Works

### Dual Organization System:

**By Domain** (`domain-XX/` folders):
- Organized by exam structure (Domain 1, 2, 3, 4)
- Used for: Comprehensive domain review, mock exam preparation
- Questions cover multiple topics within a domain

**By Topic** (`by-topic/` folder):
- Organized by specific learning topics
- Used for: Targeted review after learning a topic, spaced repetition
- Focused practice on single concepts

### Example:

"Common vs Preferred Stock" questions appear in:
- `/practice/questions/domain-02/equity-basics.md` (domain-based)
- `/practice/questions/by-topic/common-vs-preferred-stock.md` (topic-based)

This allows you to:
- Practice by topic while learning
- Practice by domain when preparing for exam

---

## Current Topics Available

### Domain 1: Capital Markets
- `market-structure.md` - Primary vs Secondary markets, NYSE vs NASDAQ (Coming soon)

### Domain 2: Products & Risks
- `common-vs-preferred-stock.md` - Stock types and characteristics (Coming soon)

### Domain 3: Trading & Accounts
- (Not started yet)

### Domain 4: Regulatory Framework
- (Not started yet)

**Total**: 0 topic-specific question files (will be populated as topics are taught)

---

## How to Use

### While Learning:
After completing a topic session:
1. Practice the topic-specific questions (10-15 questions)
2. Check understanding immediately
3. Review explanations for missed questions

### During Review:
Use spaced repetition:
- Day 3 after learning: Quick review (5 min)
- Week 1: Practice all questions (20 min)
- Week 4: Full topic review with questions (30 min)

### Before Exam:
- Focus on topics where accuracy < 80%
- Review易混淆概念 (easily confused concepts)
- Practice weak topics intensively

---

## File Naming Convention

Format: `[topic-name].md`

Examples:
- `market-structure.md`
- `common-vs-preferred-stock.md`
- `bond-pricing-and-yields.md`
- `options-calls-and-puts.md`
- `margin-accounts.md`

**Rules**:
- Lowercase
- Hyphens (not underscores or spaces)
- Descriptive (clear what topic covers)
- Matches topic file name in `domains/XX/topics/`

---

## Cross-References

Each topic question file should reference:
- Topic file: `../../domains/[XX]/topics/[topic-name].md`
- Domain questions: `../domain-[XX]/[file].md`
- Session notes: `../../sessions/YYYY-MM-DD/session-notes.md`

---

## Question Standards

All questions follow `question-template.md` format:
- 4 options (A, B, C, D)
- Detailed explanations
- Why wrong answers are wrong
- Key concepts tagged
- Difficulty rated (⭐⭐)
- Type identified (Conceptual, Scenario, Calculation, Comparison)

---

## Generation Workflow

**Automatic** (during/after teaching sessions):
1. Claude teaches topic
2. Claude generates 5-10 questions using template
3. Questions saved in both by-topic/ and domain-XX/
4. Cross-references added
5. Committed to git

**Manual** (for additional practice):
- Use `.templates/question-template.md`
- Generate more questions on weak topics
- Add to existing files

---

## Statistics

**Target**: 150-200 topic-specific question files by exam time

**Current Progress**: 0 files (2 pending from completed sessions)

**Per Domain Target**:
- Domain 1: 10-15 topic files
- Domain 2: 40-50 topic files (largest domain)
- Domain 3: 20-25 topic files
- Domain 4: 10-15 topic files

---

## Quick Links

- [Domain Questions](../) - Domain-organized questions
- [Mock Exams](../../mock-exams/) - Full 75-question exams
- [Topic Map](../../../resources/topic-map.md) - Learning paths
- [Progress Tracker](../../../progress/sie-study-tracker.md) - Overall progress

---

*This folder structure supports efficient, targeted practice for exam success*
