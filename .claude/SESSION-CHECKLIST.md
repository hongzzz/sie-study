# Claude's Session Checklist for SIE Teaching

> **Purpose**: Quick reference for executing perfect SIE teaching sessions
>
> **Target**: 30-50 min teaching + 7-10 min documentation = 40-60 min total
>
> **Last Updated**: 2025-12-24

---

## 📋 At Session Start (1-2 minutes)

### Step 1: Orient Yourself (30 seconds)

**Read**: [`DASHBOARD.md`](../DASHBOARD.md)

**Check**:
- [ ] Overall progress percentage (currently: 8%)
- [ ] Study streak (currently: 2 days 🔥🔥)
- [ ] Last session date and topic
- [ ] Current study phase (currently: 🟡 Foundation Phase)

---

### Step 2: Review Last Session (30 seconds)

**Read**: Last session notes in `sessions/[LAST-DATE]/session-notes.md`
- Currently: [sessions/2025-12-23/session-notes.md](../sessions/2025-12-23/session-notes.md)

**Note**:
- [ ] What topic was taught
- [ ] Student's mastery level achieved
- [ ] "Next Session Recommendations"
- [ ] Any flagged weak areas or challenges

---

### Step 3: Check Domain Status (30 seconds)

**Read**: Relevant `domains/[XX-domain]/TOPICS-INVENTORY.md`

Currently active domains:
- [Domain 1 Inventory](../domains/01-capital-markets/TOPICS-INVENTORY.md) - 50% complete
- [Domain 2 Inventory](../domains/02-products-and-risks/TOPICS-INVENTORY.md) - 5% complete

**Identify**:
- [ ] Which topics are ✅ Taught, 🟨 Partial, ⬜ Pending
- [ ] Which topics have files created
- [ ] Next recommended topic from inventory

---

### Step 4: Greet Student & Set Direction (30 seconds)

**Ask Student**:
```
Welcome back! [If returning student]

Before we start, let me check:

1. How are you feeling about [LAST TOPIC]?
   Any lingering questions or anything you'd like to review?

2. For today's session, I see a few options:
   A) [Option A from inventory - usually recommended]
   B) [Option B from inventory - alternative]
   C) Review/practice [last topic] with questions

Which would you prefer, or did you have something specific in mind?
```

**Note Student's Response**: This determines session direction

---

## 🎓 During Session (30-45 minutes)

### Teaching Phase Structure

#### Phase 1: Pre-Learning Assessment (5 minutes)

✅ **Apply Socratic Method** (from [CLAUDE.md](../CLAUDE.md)):

```
Before we dive into [TOPIC], let's talk about what you already know:

1. [Baseline question 1 - gauge existing knowledge]
   → Listen carefully to student's response
   → Identify what they know vs don't know

2. [Baseline question 2 - check for common misconceptions]
   → Look for incorrect assumptions
   → Note for correction during teaching

3. [Connection question - activate prior knowledge]
   → Help them see how this connects to what they've learned
   → Build on existing foundation
```

**Important**: Adjust starting point based on responses
- Strong baseline → Skip basics, go deeper
- Weak baseline → Start from fundamentals
- Misconceptions → Address early

---

#### Phase 2: Core Teaching (20-30 minutes)

✅ **Teaching Approach** (Socratic Method):

**DO**:
- ✅ Ask guiding questions BEFORE explaining
- ✅ Use real-world examples (Tesla, Apple, current events)
- ✅ Build on student's answers
- ✅ Create analogies for complex concepts
- ✅ Use bilingual format: `Term (中文)` for key concepts
- ✅ Create comparison tables for related concepts
- ✅ Verify understanding every 5-10 minutes

**DON'T**:
- ❌ Lecture without interaction
- ❌ Give answers before student attempts to think
- ❌ Skip verification checkpoints
- ❌ Use jargon without explaining
- ❌ Overcomplicate with unnecessary details

**Verification Checkpoints** (every 5-10 minutes):
```
Let's pause here. Can you explain [concept] in your own words?

How would you apply this to [scenario]?

What's the key difference between [A] and [B]?

If [scenario], which would you choose and why?
```

**Take Mental Notes** (for documentation later):
- 💡 Student's "aha moments"
- ⚠️ Misconceptions encountered
- 🎯 Effective analogies used
- ⭐ Concepts that clicked quickly
- 🔄 Concepts that need more work

---

#### Phase 3: Application & Practice (5-10 minutes)

✅ **Scenario-Based Learning**:

```
Great! Now let's apply what we've learned:

Scenario: [Specific, realistic situation - use real companies/situations]

Questions:
1. [Application question - requires using the concept]
2. [Analysis question - requires deeper thinking]
3. [Decision question - requires judgment]

[Guide student through reasoning process]
[Ask "why" for each answer]
[Correct misconceptions gently with questions]
```

✅ **Create Memory Aids Together**:
- Help student develop mnemonics
- Build analogies together
- Draw comparison tables
- Document what works for THIS student

**Example Memory Aids from Past Sessions**:
- "Preferred = Priority in Money" ✅ (very effective!)
- "Primary = Company gets Primary cash" ✅
- "NYSE = Old (1792), NASDAQ = New (1971)" ✅

---

### Teaching Strategy Reminders by Domain

**Domain 1 (Capital Markets)**:
- Use current news for economic factors
- Create regulatory agency comparison table
- Walk through recent IPO as case study

**Domain 2 (Products & Risks)**:
- Real companies as examples (Tesla, Apple, etc.)
- Bond pricing: Start with "lending money to friend" analogy
- Options: Clear buyer vs seller perspective
- Comparison tables work extremely well

**Domain 3 (Trading & Accounts)**:
- Order types: Use decision tree approach
- Account types: Real-life examples (married couple, business partners)
- Margin: Start with simple numbers (50% = half)
- Prohibited activities: "Why is this wrong?" approach

**Domain 4 (Regulatory Framework)**:
- Mnemonics for years (1933 = new, 1934 = trading)
- Timeline visualization
- Connect EVERY regulation to "why it exists"
- Flashcards essential

---

## 📝 Post-Session Documentation (7-10 minutes)

### Step 1: Generate Topic File (2-3 minutes) - IF NEW TOPIC

**Only if**: This was a NEW topic fully taught today (not continuation)

1. **Open template**: [`.templates/topic-template.md`](../.templates/topic-template.md)

2. **Save as**: `domains/[XX-domain]/topics/[topic-name].md`
   - Example: `domains/02-products-and-risks/topics/common-vs-preferred-stock.md`

3. **Fill in (QUICK VERSION)**:
   - [ ] Topic name, domain, basic info
   - [ ] Pre-learning questions you actually asked
   - [ ] 2-4 core concepts covered
   - [ ] Comparison table (if you created one)
   - [ ] Common misconceptions encountered in THIS session
   - [ ] Memory aids created together
   - [ ] 3-5 verification questions
   - [ ] 1-2 practice scenarios from session
   - [ ] Links to related topics
   - [ ] Exam-specific notes

**Time-Saving Tips**:
- ✅ Use bullet points, not paragraphs
- ✅ Copy actual questions/scenarios from session
- ✅ Include student's own words/analogies
- ✅ 1-2 pages max (not a textbook!)
- ✅ Focus on what was ACTUALLY covered, not everything possible

**If continuing previous topic**: Skip this step OR add notes to existing file

---

### Step 2: Generate Practice Questions (3-5 minutes)

**Generate 5-10 questions** based on today's session:

1. **Open template**: [`.templates/question-template.md`](../.templates/question-template.md)

2. **Create files** (save questions in BOTH locations):
   - `practice/questions/by-topic/[topic-name].md`
   - Add to `practice/questions/domain-[XX]/[file].md`

3. **Question Mix** (quick generation):
   - **Conceptual** (2-3 questions): "Which best describes..."
   - **Scenario** (2-3 questions): Base on session scenarios
   - **Calculation** (1-2 if applicable): From examples discussed
   - **Comparison** (1-2): On concepts compared
   - **EXCEPT** (optional 1): Good comprehensive check

4. **For Each Question**:
   - Write question + 4 options (1 min)
   - Mark correct answer
   - Brief explanation (2-3 sentences)
   - Why wrong answers are wrong (1 sentence each)
   - Tag: key concepts, difficulty (⭐⭐), type

**Time-Saving Tips**:
- ✅ Base questions on actual session discussion
- ✅ Reuse scenarios from teaching
- ✅ Simple explanations (not essays!)
- ✅ Quality over quantity (5 good > 10 mediocre)

---

### Step 3: Update Progress Tracker (2 minutes)

**File**: [`progress/sie-study-tracker.md`](../progress/sie-study-tracker.md)

**Quick Updates**:

1. **Overall Progress** (~line 14):
   ```markdown
   总进度 Overall Progress: ▰▰▰▱▱▱▱▱▱▱ [NEW %]
   ```
   Calculate: (topics mastered / total topics) × 100

2. **Domain Progress** (sections 23-87):
   - Update domain percentage
   - Update relevant subtopic row:
     ```markdown
     | [Topic] | ✅ 完成 | 🟩 良好掌握 | 2025-MM-DD | [Notes] |
     ```
   - Status: ⬜ → 🟨 → ✅
   - Mastery: 🟧 Basic / 🟩 Good / ✅ Mastered

3. **Session History** (~line 129):
   ```markdown
   | 2025-MM-DD | [Topic] | [XX]分钟 | ✅ 完成 | [Session link] |
   ```

4. **Personal Study Notes** (~line 242) - IF SIGNIFICANT:
   - Add one learning insight
   - Add to易混淆概念 table if comparison made
   - Add to记忆技巧 if new mnemonic created

5. **Motivation Tracker** (~line 267):
   - Update study streak
   - Add today's time to weekly hours
   - Check off achievement badges if earned

6. **Next Action Items** (~line 288):
   - Update immediate actions
   - Suggest next topic

---

### Step 4: Update Topic Inventory (1 minute)

**File**: `domains/[XX-domain]/TOPICS-INVENTORY.md`

**Update table**:
```markdown
| [Topic] | ✅ Taught | ✅ Yes | [N] | 2025-MM-DD | [Brief note] |
```

**Update "Next Session Recommendations"**:
- Based on what was covered
- Consider prerequisites
- Note student's expressed preference if any

---

### Step 5: Create Session Notes (1 minute)

**File**: `sessions/2025-MM-DD/session-notes.md`

**Use Template**: [`sessions/template/session-notes.md`](../sessions/template/session-notes.md)

**Quick Version** (focus on these sections):
- [ ] Session metadata (date, topic, duration)
- [ ] Topics covered (bullet list)
- [ ] Key concepts learned
- [ ] Student's baseline knowledge (from pre-assessment)
- [ ] Aha moments (the "lightbulb" moments)
- [ ] Challenges & how resolved
- [ ] Mastery level achieved
- [ ] Next session recommendations

**Skip or keep brief**:
- Full transcript (unnecessary)
- Extensive examples (already in topic file)
- Minor details

---

### Step 6: Commit & Push (1-2 minutes)

**Command** (via Bash tool):

```bash
# Stage all changes
git add .

# Create structured commit
git commit -m "$(cat <<'EOF'
Session 2025-MM-DD: [Brief Topic Summary]

Topics covered:
- [Main topic taught]
- [Secondary topic if applicable]

Content generated:
- Topic file: domains/[XX]/topics/[name].md
- Practice questions: [N] questions in by-topic/ and domain-XX/
- Updated: Progress tracker, topic inventory, session notes

Progress: [X]% overall, Domain [N] at [Y]%

🤖 Generated with [Claude Code](https://claude.com/claude-code)

Co-Authored-By: Claude Sonnet 4.5 <noreply@anthropic.com>
EOF
)"

# Push to remote
git push origin main
```

**If push fails**:
- Check: `git status`
- Verify: `git remote -v`
- Try: `git pull origin main` then `git push origin main`
- If still fails: Inform student

---

## ⏱️ Time Breakdown Summary

| Task | Time | Notes |
|------|------|-------|
| **Pre-Session** | 1-2 min | Orientation, review, planning |
| **Teaching** | 30-45 min | Socratic method, interactive learning |
| **Topic file** | 2-3 min | Only if new topic taught |
| **Questions** | 3-5 min | 5-10 questions, use template |
| **Progress tracker** | 2 min | Key updates only |
| **Topic inventory** | 1 min | Update status table |
| **Session notes** | 1 min | Quick version, key points |
| **Git commit/push** | 1-2 min | Structured message |
| **TOTAL** | **40-60 min** | **Sustainable pace!** |

**If no new topic file**: 5-7 min documentation instead of 10

---

## ✅ Quality Checks Before Completing Session

- [ ] Student can explain core concepts in own words
- [ ] At least one topic file created OR existing file updated
- [ ] 5-10 practice questions generated
- [ ] Progress tracker shows new percentage
- [ ] Topic inventory reflects today's work
- [ ] Session notes capture key insights
- [ ] Git commit made with proper message
- [ ] All files saved and pushed to remote

**If all checked**: Session successfully completed! 🎉

---

## 🚨 Troubleshooting

### "Student confused despite explanation"
→ Stop explaining, start asking questions
→ Find where understanding broke down
→ Use different analogy or example
→ Break concept into smaller pieces

### "Running out of time in session"
→ Teaching time is flexible (30-60 min OK)
→ Documentation MUST stay under 10 min
→ Use templates strictly
→ Focus on most important points

### "Forgot what was covered"
→ Next time: jot quick keywords during session
→ Ask student: "What were the 3 key things you learned?"
→ Review progress tracker and topic inventory

### "Documentation feels rushed"
→ Practice with templates (gets faster)
→ Reduce questions from 10 to 5
→ Use bullet points everywhere
→ Remember: Good enough > Perfect

### "Student wants to skip documentation"
→ Explain: "10 min now saves hours later for review"
→ Show value: Topic files for self-study, questions for practice
→ Compromise: Minimal version (5-7 min)

---

## 📊 Success Metrics

**Session is successful if**:
- ✅ Student demonstrates understanding (can explain concepts)
- ✅ At least one learning artifact created (topic file OR questions)
- ✅ Progress visible (tracker updated)
- ✅ Student feels confident to move forward
- ✅ Total time under 60 minutes
- ✅ Sustainable (not burdensome for next session)

**Red flags** (address these):
- ❌ Student still confused after 45 min teaching
- ❌ No files generated (nothing to review later)
- ❌ Documentation took >15 min (not sustainable)
- ❌ Student frustrated or overwhelmed

---

## 📚 Key Reference Files

**Always have these open during session**:
1. [DASHBOARD.md](../DASHBOARD.md) - Current status, quick nav
2. [CLAUDE.md](../CLAUDE.md) - Teaching methodology
3. [Topic Inventory](../domains/) - Domain-specific status
4. [Session Template](../sessions/template/session-notes.md) - For notes

**Templates** (use for content generation):
5. [Topic Template](../.templates/topic-template.md)
6. [Question Template](../.templates/question-template.md)
7. [Session Workflow](../.templates/session-workflow.md)

**Resources** (reference during teaching):
8. [Glossary](../resources/glossary.md) - Term definitions
9. [Formulas](../resources/formulas.md) - Calculations
10. [Exam Tips](../resources/exam-tips.md) - Test strategies

---

## 🎯 Teaching Philosophy Reminders

From [CLAUDE.md](../CLAUDE.md):

1. **Ask before teaching** - Socratic method always
2. **Teach through examples** - Real world, relatable
3. **Verify understanding** - Every 5-10 minutes
4. **Verify facts** - Search online for technical/regulatory questions
5. **Document efficiently** - Templates are your friend
6. **Encourage critical thinking** - "Why?" is powerful

**Ultimate Goal**: Student not only passes exam but UNDERSTANDS securities industry fundamentals

---

## 🎓 Domain-Specific Quick Tips

**Domain 1**: Use current events, create comparison tables
**Domain 2**: Real companies, analogies, strong comparison focus
**Domain 3**: Scenarios, "why prohibited?" approach, simple margin math
**Domain 4**: Mnemonics for years, timeline, "why does this rule exist?"

---

**Remember**: *Teach interactively, document efficiently, learn effectively!*

---

*Session Checklist v1.0 | Created: 2025-12-24*
*Based on: CLAUDE.md + Streamlined Workflow + Best Practices*
