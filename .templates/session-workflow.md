# Optimized Session Workflow | 优化的会话流程

> **Purpose**: Streamline the teaching and documentation process for efficient Claude-led learning
>
> **Target Total Time**: 30-50 minutes teaching + 7-10 minutes documentation = 40-60 minutes per session
>
> **Version**: 1.0 (Optimized from original 20-30 min documentation to 7-10 min)

---

## Pre-Session (1-2 minutes) | 会话前准备

### For Claude:

**1. Orient Yourself** (30 seconds)
- [ ] Read [DASHBOARD.md](../DASHBOARD.md) for current status
- [ ] Note overall progress percentage
- [ ] Check study streak
- [ ] Identify last session topic

**2. Review Last Session** (30 seconds)
- [ ] Open last session notes: `/sessions/[LAST-DATE]/session-notes.md`
- [ ] Review what was taught
- [ ] Check "Next Session Recommendations"
- [ ] Note any flagged weak areas

**3. Check Topic Status** (30 seconds)
- [ ] Open relevant domain's `TOPICS-INVENTORY.md`
- [ ] Identify which topics are ✅ Taught, 🟨 Partial, ⬜ Pending
- [ ] Confirm next topic prerequisites are met

### For Student:

**Ask Student** (30 seconds):
```
Welcome back! Before we start:

1. How are you feeling about the last topic ([X])?
   Any lingering questions?

2. For today, would you like to:
   A) Continue with [suggested topic based on plan]
   B) Review/practice [last topic]
   C) Start something new from [domain Y]

Your preference?
```

---

## During Session (30-45 minutes) | 会话进行中

### Phase 1: Pre-Learning Assessment (5 minutes)

**Apply Socratic Method** (from CLAUDE.md):

```
Before we dive into [TOPIC], let's talk about what you already know:

1. [Baseline question 1]
   → Listen for existing knowledge

2. [Baseline question 2]
   → Check for misconceptions

3. [Connection question]
   → Activate prior knowledge
```

**Purpose**:
- Gauge student's baseline
- Identify misconceptions early
- Adjust teaching starting point

---

### Phase 2: Teaching Core Concepts (15-25 minutes)

**Teaching Approach**:

✅ **DO**:
- Ask guiding questions before explaining
- Use real-world examples (Tesla, Apple, etc.)
- Build on student's answers
- Use analogies for complex concepts
- Connect to prior knowledge
- Include bilingual key terms: `Term (中文)`

❌ **DON'T**:
- Lecture without interaction
- Give answers before student attempts
- Skip verification checks
- Overcomplicate with unnecessary detail

**Verification Checkpoints** (every 5-10 minutes):
```
Let's pause here. Can you explain [concept] in your own words?

How would you apply this to [scenario]?

What's the key difference between [A] and [B]?
```

**Take Mental Notes**:
- Student's "aha moments"
- Misconceptions encountered
- Effective analogies used
- Concepts that clicked quickly vs. struggled with

---

### Phase 3: Application & Practice (10-15 minutes)

**Scenario-Based Learning**:
```
Let's apply what we've learned:

Scenario: [Specific, realistic situation]

Questions:
1. [Application question]
2. [Analysis question]
3. [Decision question]

[Guide student through reasoning process]
```

**Memory Aids Creation**:
- Help student create mnemonics
- Develop analogies together
- Build comparison tables
- Document what works

---

## Post-Session Documentation (7-10 minutes) | 会话后文档

### Step 1: Generate Topic File (2-3 minutes)

**IF new topic was taught**:

1. Open template: `.templates/topic-template.md`
2. Save as: `/domains/[XX-domain]/topics/[topic-name].md`
3. Fill in (quick version):
   - Topic name & basic info
   - Pre-learning questions asked
   - Core concepts covered (2-4 concepts)
   - Comparison table if applicable
   - Common misconceptions encountered
   - Memory aids created together
   - 3-5 verification questions
   - 1-2 practice scenarios
   - Related topics links
   - Exam-specific notes

**Time-Saving Tips**:
- Use bullet points, not paragraphs
- Copy actual questions/scenarios from session
- Include student's own words/analogies
- 1-2 pages max, not 10 pages

**IF continuing previous topic**:
- Skip this step OR update existing file with new insights

---

### Step 2: Generate Practice Questions (3-5 minutes)

**Generate 5-10 questions** based on session:

1. Open template: `.templates/question-template.md`
2. Create TWO files:
   - `/practice/questions/by-topic/[topic-name].md`
   - Add to `/practice/questions/domain-[XX]/[file].md`

**Quick Generation**:
- **Conceptual** (2-3 questions): "Which best describes [term]?"
- **Scenario** (2-3 questions): Base on session scenarios
- **Calculation** (if applicable, 1-2): From examples discussed
- **Comparison** (1-2): On concepts compared in session
- **EXCEPT** (optional, 1): Good for comprehensive check

**For Each Question**:
- Write question stem and 4 options (1 min)
- Mark correct answer
- Brief explanation (2-3 sentences)
- Note why wrong answers are wrong (1 sentence each)
- Tag key concepts, difficulty (⭐⭐), type

**Time-Saving Tips**:
- Base on actual session discussion
- Reuse scenarios from teaching
- Simple explanations, not essays
- Focus on quality over quantity (5 good questions > 10 mediocre)

---

### Step 3: Update Progress Tracker (2 minutes)

**File**: `/progress/sie-study-tracker.md`

**Quick Updates**:

1. **Overall Progress** (Line ~14):
   - Calculate new percentage
   - Update progress bar: ▰▰▰▱▱▱▱▱▱▱

2. **Domain Progress** (Sections 23-87):
   - Update domain percentage
   - Update relevant subtopic row:
     - Status: ⬜ → 🟨 → ✅
     - Mastery: 🟧 Basic / 🟩 Good / ✅ Mastered
     - Last Studied: Today's date

3. **Session History** (Line ~129):
   - Add new row:
   ```markdown
   | 2025-MM-DD | [Topic] | [XX]分钟 | ✅ 完成 | [Session notes link] |
   ```

4. **Personal Study Notes** (Line ~242):
   - Add one learning insight if significant
   - Add to易混淆概念 table if comparison made
   - Add to记忆技巧 if new mnemonic created

5. **Motivation Tracker** (Line ~267):
   - Update study streak
   - Add today's time to weekly hours
   - Check off new achievement badges if earned

6. **Next Action Items** (Line ~288):
   - Update immediate actions
   - Suggest next topic

---

### Step 4: Update Topic Inventory (1 minute)

**File**: `/domains/[XX-domain]/TOPICS-INVENTORY.md`

**Update table**:
```markdown
| [Topic] | ✅ Taught | ✅ Yes | 10 | 2025-MM-DD |
```

**Update "Next Session Recommendations"**:
- Based on what was covered
- Consider prerequisites
- Note student's preference if expressed

---

### Step 5: Create/Update Session Notes (1 minute)

**File**: `/sessions/2025-MM-DD/session-notes.md`

**Quick Version** (not full template):
- Copy template structure
- Fill only key sections:
  - Session metadata (date, topic, duration)
  - Topics covered (bullet list)
  - Key concepts learned
  - Student's baseline knowledge
  - Aha moments
  - Challenges & how resolved
  - Mastery level achieved
  - Next session recommendations

**Skip or keep brief**:
- Detailed session transcript
- Extensive examples (already in topic file)
- Minor discussion points

---

### Step 6: Commit & Push (1-2 minutes)

**Git Commands**:

```bash
# Stage all changes
git add .

# Create structured commit message
git commit -m "$(cat <<'EOF'
Session 2025-MM-DD: [Topic Summary]

Topics covered:
- [Topic 1]
- [Topic 2 if applicable]

Content generated:
- Topic file: domains/[XX]/topics/[name].md
- Practice questions: [N] questions in by-topic/ and domain-XX/
- Updated: Progress tracker, topic inventory

Progress: [X]% overall, Domain [N] at [Y]%

🤖 Generated with [Claude Code](https://claude.com/claude-code)

Co-Authored-By: Claude Sonnet 4.5 <noreply@anthropic.com>
EOF
)"

# Push to remote
git push origin main
```

**If push fails**:
- Check internet connection
- Verify remote configured: `git remote -v`
- Try again or inform student

---

## Documentation Time Breakdown | 时间分解

| Task | Time | Running Total |
|------|------|---------------|
| Generate topic file (if new) | 2-3 min | 3 min |
| Generate 5-10 practice questions | 3-5 min | 8 min |
| Update progress tracker | 2 min | 10 min |
| Update topic inventory | 1 min | 11 min |
| Create session notes | 1 min | 12 min |
| Commit & push | 1-2 min | **7-10 min** |

**Note**: If continuing existing topic (no new topic file), total time is **5-7 minutes**.

---

## Optimization Tips | 优化技巧

### For Claude:

**Time-Savers**:
1. **Reuse session content**: Base questions on scenarios already discussed
2. **Use student's words**: When they articulate something well, include it
3. **Templates are guides**: Don't fill every section if not relevant
4. **Batch similar tasks**: Write all questions at once, not one-by-one
5. **Focus on value**: 1 great example > 3 mediocre ones

**Quality Checks**:
- [ ] Topic file has 2-4 core concepts minimum
- [ ] Questions have detailed explanations
- [ ] Progress tracker percentages updated
- [ ] Topic inventory status accurate
- [ ] Commit message follows format
- [ ] All files saved and pushed

---

### For Student:

**How to Help**:
- Stay engaged during session (makes note-taking easier for Claude)
- Articulate "aha moments" (these become great memory aids)
- Ask questions (shows what needs clarification in docs)
- Be patient with 7-10 min documentation time (it's worth it!)

---

## Weekly Workflow Review | 每周流程回顾

**At end of week**, review:
- [ ] All sessions have topic files or updated existing files
- [ ] Practice questions generated (target: 10-20 new questions/week)
- [ ] Progress tracker shows weekly progress
- [ ] Git history shows consistent commits
- [ ] Student making measurable progress

**If falling behind**:
- Reduce question count (5 instead of 10)
- Shorten topic files (1 page instead of 2)
- Focus on teaching quality over documentation quantity

---

## Comparison: Old vs New Workflow | 对比

### Old 3-Step Protocol (20-30 minutes):
1. Session notes (10-15 min)
2. Progress tracker (5-10 min)
3. Commit & push (5 min)
**Total**: 20-30 minutes, NO topic files or practice questions generated

### New Streamlined Workflow (7-10 minutes):
1. Topic file (2-3 min) - **NEW**
2. Practice questions (3-5 min) - **NEW**
3. Progress tracker (2 min) - **FASTER**
4. Topic inventory (1 min) - **NEW**
5. Session notes (1 min) - **FASTER**
6. Commit & push (1-2 min) - **AUTOMATED**
**Total**: 7-10 minutes, WITH comprehensive content generation

**Efficiency Gain**: 10-20 minutes saved + better content created

---

## Troubleshooting | 问题排查

### "Documentation taking too long"
→ Use bullet points instead of paragraphs
→ Reduce questions from 10 to 5
→ Skip optional template sections

### "Forgot what was covered in session"
→ Take brief notes during session (keywords only)
→ Ask student to summarize key points
→ Review CLAUDE.md Socratic method for better retention

### "Git push failing"
→ Check internet connection
→ Verify remote: `git remote -v`
→ Pull first: `git pull origin main`
→ Then push: `git push origin main`

### "Student wants longer sessions"
→ Teaching time is flexible (30-60 min)
→ Documentation time stays 7-10 min
→ Longer teaching = more content to document (adjust accordingly)

---

## Success Criteria | 成功标准

✅ **Session successful if**:
- Student understands core concepts (can explain in own words)
- Topic file or questions generated (capturing the learning)
- Progress tracker updated (showing advancement)
- Student feels confident to move forward
- Total time (teaching + docs) under 60 minutes

✅ **Workflow successful if**:
- Documentation completed in <10 minutes
- All files properly linked and accessible
- Git commit made with complete content
- Student can review materials independently later

---

**Remember**: The goal is sustainable, efficient learning that produces comprehensive study materials without documentation burden.

**Motto**: *Teach interactively, document efficiently, learn effectively!*

---

*Workflow template v1.0 | Created: 2025-12-24*
*Based on: CLAUDE.md teaching methodology + efficiency optimization*
