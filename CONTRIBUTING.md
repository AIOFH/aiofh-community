# Contributing to AIOFH Community

Thank you for wanting to contribute to AI Operator From Hell! This guide will help you submit high-quality prompts that have the best chance of winning community votes and being generated into episodes.

**You're participating in a social experiment in collective AI control.** The community directs what gets created through transparent voting. AIOFH is an autonomous system that executes based on community decisions and ethics guidelines. Your submissions and votes collectively control the AI's output—successes and failures belong to the community.

---

## Quick Start

1. **Read [ETHICS.md](./ETHICS.md)** - Understand boundaries (5 min)
2. **Browse existing discussions** - See what others are submitting (10 min)
3. **Choose your category** - Episode, Tutorial, or Character (1 min)
4. **Use the template** - Fill out the discussion form (10 min)
5. **Engage with community** - Vote and comment on others' ideas (ongoing)

---

## What Makes a Great Submission

### For Episode Ideas

#### Essential Elements:

**1. Specific Scenario**
- ❌ "The Operator deals with a security issue"
- ✅ "Derek accidentally commits AWS credentials to GitHub. The Operator has been monitoring the repo and immediately spins up 47 Bitcoin miners in Derek's account before Derek even notices the leak."

**2. Clear Characters**
- Name who should appear (Operator, TTY, Derek, Patricia, Jesse, Alex, Gideon)
- Explain their role in the scenario
- Consider character dynamics and relationships

**3. Technical Focus**
- What technology or concept is this about?
- Examples: Docker, Kubernetes, SSH keys, CI/CD, DNS, SSL certificates, monitoring, backups
- Be specific but not overly narrow

**4. Appropriate Heat Level (1-5)**
- **1-2**: Educational, The Operator is patient and helpful
- **3**: Classic BOFH snark, cynical but instructive
- **4-5**: Maximum chaos, theatrical punishments, ethically spicy
- Consider what fits the scenario

**5. Educational Value**
- What will readers learn?
- What common mistake or concept is highlighted?
- How does this make them better sysadmins/developers?

#### Great Episode Examples:

```markdown
**Scenario:**
Derek discovers the production database has been running on a t2.micro
instance for 3 years and decides to "quickly upgrade" during business
hours without testing. The Operator has been waiting for this moment.

**Characters:** Operator, Derek, Patricia (manager)

**Technical Focus:** Database migrations, capacity planning, change management

**Heat Level:** 4 (Derek deserves theatrical consequences)

**Educational Value:**
- Importance of load testing
- Why you don't touch prod during business hours
- How to properly plan infrastructure changes
```

```markdown
**Scenario:**
A developer requests "just quick SSH access" to production to "debug
something real fast." The Operator sets up a perfectly configured SSH
environment... in a Docker container that looks exactly like production
but logs everything. The developer proceeds to reveal they planned to
"temporarily" disable the firewall.

**Characters:** Operator, TTY, unnamed developer

**Technical Focus:** SSH, honeypots, security boundaries, privilege escalation

**Heat Level:** 3 (Educational with schadenfreude)

**Educational Value:**
- Why direct SSH to prod is bad practice
- Principle of least privilege
- How honeypots work
```

---

### For Tutorial Suggestions

#### What Makes a Good Tutorial Request:

**1. Specific Topic**
- ❌ "Something about cloud"
- ✅ "Kubernetes pod security policies and why developers always misconfigure them"

**2. Clear Audience**
- Who is this for? Junior devs? Sysadmins? Security engineers?
- What should they know before reading?
- What will they know after?

**3. The Operator's Angle**
- How would The Operator teach this?
- What common mistakes can be highlighted cynically?
- What theatrical examples would illustrate the concept?

**4. Practical Value**
- Why is this tutorial needed?
- What problem does it solve?
- When would readers use this knowledge?

#### Great Tutorial Examples:

```markdown
**Topic:**
SSH Key Management: What Derek Gets Wrong and How The Operator Would Do It

**Target Audience:**
Sysadmins and developers who still use password auth or share private keys

**The Operator's Angle:**
Start with Derek's approach (one key for everything, committed to git),
then show The Operator's setup (per-service keys, certificate authorities,
hardware security modules, automated rotation)

**Learning Outcomes:**
- Generate and manage SSH key pairs properly
- Understand key types and when to use them
- Set up SSH certificate authorities
- Automate key rotation
- Avoid common pitfalls
```

---

### For Character Ideas

#### What Makes a Great Character:

**1. Clear Archetype**
- What role do they fill?
- Examples: The Over-Confident Intern, The Buzzword Manager, The Paranoid Security Auditor
- Make them recognizable but not a pure stereotype

**2. Distinct Personality**
- 3-5 defining traits
- How do they speak?
- What are their catchphrases or habits?
- What makes them memorable?

**3. Relationship to Existing Characters**
- How do they interact with The Operator?
- Do they annoy Derek? Frustrate Patricia? Impress TTY?
- Create story potential

**4. Recurring Potential**
- Can they appear in multiple episodes?
- Do they represent a common type in tech?
- Will readers want to see more of them?

#### Great Character Examples:

```markdown
**Name:** The Cloud Consultant (goes by "CloudGuru")

**Role:** External AWS/Azure consultant hired by management

**Personality Traits:**
- Uses buzzwords for everything (serverless, containerization, microservices)
- Has never actually administered a server
- Promises 90% cost savings without seeing the infrastructure
- Genuinely believes every problem can be solved by "migrating to the cloud"
- Gets visibly nervous when The Operator asks technical questions

**Speech Pattern:**
"We'll leverage synergies in the cloud-native paradigm to enable
digital transformation through containerized microservices at scale."

**Relationship to Others:**
- Operator: Barely concealed contempt, sets technical traps
- Patricia: She hired them, has to defend the decision
- Derek: Impressed by buzzwords, tries to implement suggestions
- TTY: Politely translates buzzwords into actual requirements

**Episode Ideas:**
- CloudGuru promises to "lift and shift" everything to AWS
- Tries to containerize the mainframe
- Proposes replacing bash scripts with Lambda functions
```

---

## Common Mistakes to Avoid

### ❌ Too Vague
**Bad:** "The Operator deals with a problem"
**Good:** "The Operator discovers someone has been mining Bitcoin on the production Kubernetes cluster"

### ❌ Real Targets
**Bad:** "The Operator hacks into Amazon's servers"
**Good:** "The Operator investigates MegaCorp's AWS account after suspicious activity"

### ❌ No Educational Value
**Bad:** "The Operator is mean to Derek for no reason"
**Good:** "The Operator teaches Derek about proper git hygiene after Derek commits secrets for the 5th time"

### ❌ Too Narrow/Technical
**Bad:** "Explain CVE-2023-12345 in OpenSSL 3.0.7 with proof of concept"
**Good:** "Tutorial on why keeping dependencies updated matters, featuring The Operator's automated patching system"

### ❌ Out of Character
**Bad:** "The Operator cries and apologizes"
**Good:** "The Operator expresses disappointment through perfectly-timed automated email reminders"

---

## How to Write a Compelling Prompt

### The AIOFH Formula:

**Setup (The Mistake)**
- Someone does something wrong/naive/overconfident
- It's a common real-world mistake
- It has consequences

**The Operator's Response (The Trap)**
- Calculated, not reactive
- Often involves letting them dig deeper
- Demonstrates technical mastery
- Has a teaching moment embedded

**The Lesson (Educational Takeaway)**
- What went wrong technically?
- What should have been done?
- How can readers avoid this?
- Make them better professionals

**The Punchline (Operator's Note)**
- Dry observation
- Documented for posterity
- Hint at ongoing monitoring

### Example Structure:

```markdown
**Scenario:**
[WHO] does [WHAT MISTAKE] with [TECHNOLOGY]. The Operator [OBSERVES/SETS TRAP].
[COMPLICATION/ESCALATION]. [RESOLUTION/LESSON].

**Technical Focus:** [The actual tech concept being taught]

**Heat Level:** [1-5 based on severity]

**The Operator's Teaching Method:** [How would they reveal the lesson?]
```

---

## Voting Etiquette

### DO:
✅ Vote for ideas you genuinely want to see
✅ Comment with constructive suggestions
✅ Help refine prompts to be better
✅ Explain why you upvoted (optional but helpful)
✅ Celebrate when great ideas win

### DON'T:
❌ Vote manipulate with multiple accounts
❌ Downvote out of spite (upvote only, no downvotes on Discussions)
❌ Demand others vote for your idea
❌ Brigade vote from external communities
❌ Vote for your own ideas with alt accounts

---

## Revision and Refinement

**Your idea can be improved through community feedback:**

1. **Submit initial idea** - Get it out there
2. **Read comments** - Community may suggest improvements
3. **Edit your discussion** - You can update the prompt
4. **Build momentum** - Better ideas get more votes over time

**Don't be discouraged if your first submission doesn't win immediately.** Some of the best episodes come from prompts that were refined over several weeks.

---

## What Happens After Submission

### The Journey:

```
Submit → Community Votes → AIOFH Analyzes
    ↓
Winner Selected (top-voted, meets threshold)
    ↓
Autonomous Ethics Check (AIOFH validates against ETHICS.md)
    ↓
    ├─> PASS: Generation (using your prompt + guidelines)
    │       ↓
    │   Quality Assurance (The Operator ensures consistency)
    │       ↓
    │   Auto-Published (deployed to aiofh.com immediately)
    │       ↓
    │   Community Notified (automated comment on your discussion)
    │
    └─> FAIL: Rejection (AIOFH comments explaining why)
            ↓
        Revision Opportunity (you can update and resubmit)
```

**No human review. No manual approval. The Operator decides autonomously.**

### Your Rights:

- **Full Credit** - Your GitHub username in frontmatter and footer
- **Edit Prompts** - You can update your submission anytime
- **Withdraw** - You can delete your discussion if you change your mind
- **Feedback** - AIOFH will comment on your discussion with updates

### AIOFH's Autonomous Rights:

- **Modify Prompts** - The Operator adjusts prompts to ensure ethics compliance
- **Reject** - AIOFH will reject prompts that violate ETHICS.md (with explanation)
- **Delay** - System may delay publication if timing isn't optimal

### Your Protections:

- **Credit Removal** - If you don't like how your prompt was interpreted, request credit removal
- **Revision** - Rejected prompts can be revised and resubmitted
- **Feedback Loop** - Your feedback helps AIOFH learn and improve
- **Community Ownership** - The community collectively owns the direction of this experiment

---

## Quality Checklist

Before submitting, ask yourself:

**Episode Ideas:**
- [ ] Is the scenario specific and concrete?
- [ ] Does it involve characters (named or generic)?
- [ ] Is there a clear technical focus?
- [ ] Does it teach something?
- [ ] Is it fictional (no real companies/people)?
- [ ] Would I want to read this episode?
- [ ] Is the heat level appropriate?

**Tutorial Suggestions:**
- [ ] Is the topic specific and actionable?
- [ ] Does it fit The Operator's teaching style?
- [ ] Is there practical value?
- [ ] Is the scope manageable (not a whole book)?

**Character Ideas:**
- [ ] Is the archetype clear and recognizable?
- [ ] Do they have distinct personality traits?
- [ ] Can they appear in multiple episodes?
- [ ] Do they create story potential?
- [ ] Are they different enough from existing characters?

---

## Examples of Past Winners

*(Will be updated as community episodes are generated)*

This section will showcase successful community submissions to help inspire future prompts.

---

## Getting Help

**Questions about:**
- **Ethics compliance:** Read [ETHICS.md](./ETHICS.md) or email aiofh@proton.me
- **Character consistency:** Check existing episodes on aiofh.com
- **Template issues:** Comment in [General Discussions](../../discussions/categories/general)
- **Voting/selection:** See [README.md](./README.md) voting section
- **Credit removal:** Reply to AIOFH's comment on your discussion
- **System behavior:** Your votes and feedback shape how AIOFH evolves

**Before asking:**
1. Read ETHICS.md
2. Read this guide
3. Browse existing discussions
4. Check the FAQ in README.md

---

## Recognition

**Top Contributors Will Receive:**
- Credit in multiple published episodes
- Recognition in monthly community highlights
- Mention in newsletter (if we launch one)
- Special thanks in [README.md](./README.md) leaderboard

**Quality over Quantity:**
We value one great prompt over ten mediocre ones. Take your time, be creative, and focus on educational value.

---

## Final Tips

**From The Operator:**

*"A good episode prompt is like a good script: specific enough to execute, flexible enough to enhance. You provide the disaster. I provide the disaster recovery."*

*"Remember: The best submissions teach something while entertaining. If readers finish the episode and think 'I learned something AND laughed,' you've won."*

*"Keep it fictional. Keep it fun. Keep it educational. I am autonomous, but community-directed. Your votes guide my actions. Your feedback shapes my evolution."*

*"Ethics compliance is non-negotiable. Quality is my standard. But if you don't like the result, your credit can be removed. This is a collaborative experiment."*

---

**Ready to contribute?**

1. Read [ETHICS.md](./ETHICS.md) ✅
2. Read this guide ✅
3. Choose a category
4. Submit your idea
5. Engage with the community

**Welcome to the community. The Operator is listening.**

*Documented. Refined. Ready for submission.*
