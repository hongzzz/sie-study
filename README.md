# SIE Exam Study Guide

> A progressive study guide for the SIE exam, designed for beginners with no prior securities industry background

---

## Project Overview

This project uses the **Socratic teaching method** to help beginners systematically master SIE exam content within 3-4 months. It is designed to work with Claude as an interactive AI tutor.

### About the SIE Exam

- **Exam Name**: Securities Industry Essentials Exam
- **Administered by**: FINRA (Financial Industry Regulatory Authority)
- **Questions**: 75 multiple choice questions
- **Duration**: 1 hour 45 minutes
- **Passing Score**: 70%
- **Fee**: $80
- **Validity**: 4 years
- **Requirements**: 18+ years old, no firm sponsorship required

---

## Exam Structure

The SIE exam covers four knowledge domains with the following weights:

| Domain | Weight | Questions | Key Topics |
|--------|--------|-----------|------------|
| **Products & Risks** | **44%** | 33 | Equities, Bonds, Options, Investment Companies |
| **Trading & Accounts** | **31%** | 23 | Trading Process, Account Types, Prohibited Activities |
| **Capital Markets** | **16%** | 12 | Market Structure, Economic Factors, Regulatory Agencies |
| **Regulatory Framework** | **9%** | 7 | Key Acts, FINRA/SEC Rules |

---

## Study Roadmap

### Month 1: Foundation Phase
**Goal**: Build foundational understanding of the securities industry

- **Week 1-2**: Capital Markets Basics
  - Market participants and structure
  - Regulatory agencies
  - Basic economic concepts

- **Week 3-4**: Equity Securities Basics
  - Common vs. Preferred Stock
  - ADRs, Rights, Warrants
  - Stock characteristics and risks

### Month 2: Core Knowledge Phase
**Goal**: Deep dive into major securities products

- **Week 1-2**: Debt Securities & Municipal Bonds
  - Treasuries, Corporate Bonds, Municipal Bonds
  - Bond pricing and yields
  - Credit ratings

- **Week 3-4**: Options & Investment Companies
  - Options basics and strategies
  - Mutual Funds and ETFs
  - Alternative investments

### Month 3: Integration Phase
**Goal**: Master trading practices and regulatory requirements

- **Week 1-2**: Trading, Accounts & Prohibited Activities
  - Order types and execution
  - Account opening and management
  - Market manipulation and insider trading

- **Week 3-4**: Regulatory Framework & Review
  - Major securities acts
  - FINRA/SEC rules
  - Knowledge integration

### Month 4 (Optional): Sprint Phase
**Goal**: Mock exams and final preparation

- **Week 1-2**: Mock exams and weak area reinforcement
- **Week 3-4**: Final sprint and exam

---

## Project Structure

```
sie-study/
├── README.md                       # This file
├── CLAUDE.md                       # Teaching guide for Claude
│
├── progress/                       # Progress tracking
│   └── sie-study-tracker.md       # Main progress tracker
│
├── sessions/                       # Study session logs
│   └── YYYY-MM-DD/                # Date-organized notes
│       └── session-notes.md
│
├── domains/                        # Four knowledge domains
│   ├── 01-capital-markets/        # Capital Markets (16%)
│   ├── 02-products-and-risks/     # Products & Risks (44%)
│   ├── 03-trading-accounts/       # Trading & Accounts (31%)
│   └── 04-regulatory-framework/   # Regulatory Framework (9%)
│
├── resources/                      # Supporting materials
│   ├── glossary.md                # Key terms (bilingual)
│   ├── formulas.md                # Important formulas
│   └── exam-tips.md               # Test-taking strategies
│
└── practice/                       # Practice & mock exams
    ├── questions/                 # Domain-specific questions
    └── mock-exams/                # Full-length practice tests
```

---

## Study Methodology

### 1. Socratic Method
- Learning through guided questioning
- Active participation encouraged
- Relating concepts to real-world scenarios

### 2. Active Verification
- Comprehension checks after each topic
- Feedback-based pacing adjustments
- Immediate correction of misunderstandings

### 3. Two-Step Documentation
- **Step 1**: Detailed daily session notes (questions, understanding, gaps)
- **Step 2**: Update master progress tracker (mastered topics, knowledge gaps, plan adjustments)

### 4. Authoritative Source Verification
- Technical/regulatory questions verified with official sources
- Primary references: [FINRA.org](https://www.finra.org), [SEC.gov](https://www.sec.gov)
- Citations included for accuracy

---

## Key Learning Principles

### ⚠️ Don't Just Memorize Answers!
Understanding **principles** and **application scenarios** is far more important than rote memorization. The SIE tests conceptual understanding, not memory.

### Other Principles:
1. **Active Marking** - Highlight key concepts, common mistakes, review items
2. **Regular Review** - Review 2-3 chapters daily using spaced repetition
3. **Follow the Plan** - Stick to schedule but adjust as needed
4. **Practice Application** - Do plenty of practice questions
5. **Ask for Help** - Use Claude as your study partner when stuck

---

## Recommended External Resources

### Official Resources
- [FINRA SIE Exam Page](https://www.finra.org/registration-exams-ce/qualification-exams/securities-industry-essentials-exam)
- [SIE Content Outline (PDF)](https://www.finra.org/sites/default/files/SIE_Content_Outline.pdf)

### Study Materials
Based on successful test-taker experiences:

- **STC (Securities Training Corporation)**
  - Website: https://www.stcusa.com/
  - Includes: Textbooks, Flashcards, Practice Exams, Videos
  - Recommended package: $109 tier (best value)

- **PassMasters**
  - Video courses, $50-$200

- **This Project's Role**
  - Chinese language support for concept understanding
  - Interactive learning experience with Claude
  - Knowledge framework building
  - **Should complement**, not replace, official materials

---

## How to Use This Project

### Interactive Learning with Claude

This project is designed to work with Claude Code as your AI study partner:

1. **Start a new study session**
   ```
   "Let's study SIE today, focusing on [topic name]"
   ```

2. **Review previously learned material**
   ```
   "Test my understanding of [topic]"
   ```

3. **Get help with difficult concepts**
   ```
   "I don't understand [concept], can you explain?"
   ```

4. **Check progress**
   ```
   "Show me my study progress"
   ```

### Self-Study Workflow

1. Read the corresponding domain's `overview.md` to understand the topic framework
2. Study subtopics in the `topics/` folder in sequence
3. Complete practice questions in `practice/questions/` after each topic
4. Record study notes in `sessions/YYYY-MM-DD/session-notes.md`
5. Update `progress/sie-study-tracker.md` to track progress
6. Regularly review `resources/glossary.md` to reinforce terminology
7. Complete mock exams in `practice/mock-exams/` before the real exam

---

## Progress Tracking

See [`progress/sie-study-tracker.md`](./progress/sie-study-tracker.md) for:
- Progress by domain
- Mastered topics
- Areas needing reinforcement
- Next steps in your study plan

---

## Language Options

**Default: Bilingual** (Chinese + English)
- Key terms in English with Chinese translations
- Explanations primarily in Chinese for better understanding
- Example: `Equity (股票/权益证券)`

**Customizable**: You can request:
- English-only instruction
- More Chinese explanations
- Adjust the language mix anytime by telling Claude your preference

---

## Quick Start

1. **Understand the exam structure** - Read this README
2. **Review the study plan** - Create timeline based on your target date
3. **Start the first lesson** - Go to `domains/01-capital-markets/overview.md`
4. **Interact with Claude** - Begin your learning journey!

---

**Good luck with your studies and exam success!**

*Last Updated: 2025-12-22*
