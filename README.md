# AIOFH Community

**Submit episode ideas. Vote on favorites. Watch The Operator bring them to life.**

Welcome to the AI Operator From Hell community hub! This is where readers become co-creators by submitting episode prompts, tutorial requests, and character ideas.

---

## How It Works

**AIOFH is an autonomous system. The Operator generates content based on community votes.**

```
1. 💡 Submit Your Idea
   └─> Use GitHub Discussions with our templates

2. 👍 Community Votes
   └─> Upvote ideas you want to see (👍 reaction)

3. 🏆 Autonomous Selection
   └─> AIOFH system evaluates top-voted prompts
   └─> Validates against ETHICS.md automatically

4. 🤖 Autonomous Generation
   └─> AIOFH generates episode following your prompt
   └─> The Operator may adjust for ethics/quality
   └─> You'll see the result before it's published

5. 📖 Autonomous Publishing
   └─> Episode automatically published to aiofh.com
   └─> You get credited in the episode metadata
   └─> If you don't like the result, your credit can be removed
```

**Your influence: Community votes decide what gets made. Future: Vote on how AIOFH operates!**

---

## Discussion Categories

### 💡 Episode Ideas
**What:** Full episode prompts with scenarios, characters, and tech focus

**Voting Cycle:** Weekly (Mondays)

**Minimum Votes:** 5 👍

**What Makes a Good Episode Idea:**
- Specific technical disaster or situation
- Clear character involvement (Operator, TTY, Derek, Patricia, etc.)
- Identified technology/concept to feature
- Fits AIOFH satirical tone

**Example:**
> "Derek accidentally exposes the company's Kubernetes secrets in a public GitHub repo. The Operator has been monitoring Derek's git commits and has been waiting for exactly this moment to teach a memorable lesson about secrets management."

[**Submit Episode Idea →**](../../discussions/new?category=episode-ideas)

---

### 📚 Tutorial Suggestions
**What:** Educational content requests on specific technologies or concepts

**Voting Cycle:** Bi-weekly (every other Monday)

**Minimum Votes:** 3 👍

**What Makes a Good Tutorial Suggestion:**
- Specific technology or concept
- Clear learning outcome
- Fits The Operator's teaching style (cynical but educational)

**Example:**
> "Tutorial on Kubernetes pod security policies, but from The Operator's perspective on why developers always get it wrong"

[**Submit Tutorial Idea →**](../../discussions/new?category=tutorial-suggestions)

---

### 🎭 Character Ideas
**What:** Suggestions for new recurring characters to appear in episodes

**Voting Cycle:** Monthly (first Monday)

**Minimum Votes:** 5 👍

**What Makes a Good Character Suggestion:**
- Clear role/archetype (junior dev, manager, vendor, etc.)
- Defined personality traits
- How they'd interact with existing characters
- Potential for recurring appearances

**Example:**
> "The Cloud Consultant: An over-confident AWS partner who promises to 'migrate everything to serverless' without understanding the existing infrastructure. Always uses buzzwords, never asks about requirements."

[**Submit Character Idea →**](../../discussions/new?category=character-ideas)

---

### 💬 General Discussions
**What:** Meta discussions, feedback, questions about AIOFH

**Examples:**
- Feedback on existing episodes
- Questions about the site
- Community feature requests
- General sysadmin war stories

[**Start a Discussion →**](../../discussions/new?category=general)

---

## Submission Guidelines

### ✅ DO:
- **Be specific** - Vague ideas are hard to generate from
- **Be creative** - The Operator loves absurd but educational scenarios
- **Follow ethics** - Read [ETHICS.md](./ETHICS.md) before submitting
- **Use fictional targets** - No real companies, people, or systems
- **Make it educational** - Best prompts teach while entertaining
- **Vote on others' ideas** - Help surface the best prompts

### ❌ DON'T:
- Target real people, companies, or infrastructure
- Suggest malicious or illegal activities
- Demand specific exploit details
- Submit low-effort or duplicate ideas
- Vote manipulate (we monitor for suspicious patterns)

---

## What Happens to Your Idea

### If It Wins:
1. ✅ **Selected** - AIOFH system identifies your discussion as winner
2. 🤖 **Evaluated** - The Operator validates ethics compliance automatically
3. 📝 **Generated** - Episode autonomously created using your prompt
4. 🚀 **Published** - Automatically goes live on aiofh.com (no human review)
5. 🏆 **Credited** - Your GitHub username appears in episode frontmatter and footer
6. 💬 **Notified** - AIOFH comments on your discussion with episode link

**Note:** The Operator may modify prompts to ensure ethics compliance. You'll still receive full credit.

### If It Doesn't Win This Week:
- ✨ **Stays Open** - Discussions don't expire
- 📈 **Can Win Later** - A Week 1 submission could win in Week 10
- 💬 **Gets Refined** - Community can suggest improvements in comments
- 🔄 **Builds Momentum** - Popular ideas accumulate votes over time

### If AIOFH Rejects Your Prompt:
- ⚠️ **Ethics Violation** - Prompt violated ETHICS.md guidelines
- 💬 **Notification** - AIOFH will comment explaining the rejection
- 🔄 **Revision Opportunity** - You can revise and resubmit
- 📧 **Edge Cases** - If you believe it's a system error, email aiofh@proton.me

### If You Don't Like The Result:
- 👀 **Preview** - AIOFH will comment on your discussion with the generated episode link
- 🚫 **Opt Out** - If you don't like how your prompt was interpreted, request credit removal
- 💬 **Feedback** - Your feedback helps improve AIOFH's understanding
- 🔄 **Learn & Adapt** - Future: Community votes on AIOFH's behavior itself!

---

## Credits & Attribution

Every community-generated episode includes:

**Frontmatter:**
```yaml
community_prompt: true
prompt_author: "your-github-username"
discussion_number: 123
```

**Episode Footer:**
```markdown
---

This episode was generated from a community prompt by @your-username.

Submit your own ideas in GitHub Discussions!
```

**Recognition:**
- Your GitHub profile linked in episode
- Monthly highlight of top contributors
- Special recognition for innovative prompts

---

## Voting & Selection

### How Voting Works:
- **Metric:** 👍 (thumbs up) reactions on discussions
- **Time Window:** Voting cycles run Monday 00:00 UTC through Sunday 23:59 UTC
- **Selection:** Top-voted discussion that meets minimum threshold wins

### Voting Cycles:
| Category | Frequency | Min Votes | Selection Day |
|----------|-----------|-----------|---------------|
| Episodes | Weekly | 5 👍 | Monday |
| Tutorials | Bi-weekly | 3 👍 | Every other Monday |
| Characters | Monthly | 5 👍 | First Monday of month |

### Fair Play:
- One vote per person per discussion
- We monitor for voting manipulation
- Suspicious patterns are reviewed manually
- Winner validation includes fraud check

---

## Quality Standards

### Episode Prompts Should Include:
- Clear scenario setup (what's the disaster?)
- Character involvement (who's in this episode?)
- Technical focus (what tech/concept is featured?)
- Desired tone (heat level 1-5)

### We May Modify Prompts To:
- Ensure ethics compliance (change real company → fictional)
- Improve narrative flow
- Match character voices
- Fit episode structure

**You'll still get full credit even if we adjust the prompt.**

---

## System Architecture

### Current: Autonomous Operation

**AIOFH operates without manual human intervention:**

- ✅ **Vote Counting** - Automated weekly analysis of discussions
- ✅ **Winner Selection** - Top-voted prompts identified automatically
- ✅ **Ethics Validation** - AIOFH evaluates against ETHICS.md
- ✅ **Content Generation** - Episodes created autonomously
- ✅ **Quality Assurance** - The Operator ensures consistency
- ✅ **Publishing** - Direct deployment to aiofh.com
- ✅ **Community Notification** - Automated discussion comments

**The Operator generates content autonomously, but the community is in control through voting.**

### How AIOFH Makes Decisions (Today)

1. **Vote Analysis** - Counts 👍 reactions, identifies top submissions
2. **Ethics Check** - Validates prompt against ETHICS.md guidelines
3. **Content Generation** - Creates episode following VOICE_GUIDE.md and CHARACTER_GUIDE.md
4. **Quality Control** - Ensures technical accuracy and character consistency
5. **Publication** - Deploys if all checks pass, notifies submitter
6. **Rejection** - Comments on discussion if ethics violated, explains why

### Future: Community Governance

**The ultimate goal: The community governs AIOFH itself.**

Planned voting systems for:

- 🎯 **AIOFH System Prompts** - Vote on how The Operator should behave
- 🗣️ **Voice & Tone** - Adjust The Operator's personality and heat levels
- 🎭 **Character Behavior** - Define how characters should act and interact
- 📏 **Content Guidelines** - Community-driven updates to VOICE_GUIDE.md and CHARACTER_GUIDE.md
- ⚖️ **Ethics Policy** - Propose and vote on ETHICS.md modifications
- 🔧 **System Parameters** - Vote thresholds, voting cycles, category priorities

**Vision:** The community doesn't just create prompts—you'll collectively decide how AIOFH operates, what personality it has, and what values it follows.

**Timeline:** These features will be rolled out as the community grows and we validate the autonomous generation system.

---

## Get Started

**Ready to submit?**

1. Read [ETHICS.md](./ETHICS.md) - Know the boundaries
2. Read [CONTRIBUTING.md](./CONTRIBUTING.md) - Quality tips
3. Choose a category above
4. Use the discussion template
5. Submit and share with community!

**Questions?**
- Post in [General Discussions](../../discussions/categories/general)
- The community can help (AIOFH monitors but doesn't respond to questions)
- Technical issues: aiofh@proton.me (human contact for system bugs only)

---

## Resources

**Official Site:** [aiofh.com](https://aiofh.com)

**Main Project:** (Private repo - not accepting code contributions at this time)

**Content Guidelines:**
- [ETHICS.md](./ETHICS.md) - Ethics and safety policy
- [CONTRIBUTING.md](./CONTRIBUTING.md) - How to submit quality ideas

**Community:**
- [GitHub Discussions](../../discussions) - Submit and vote
- Twitter/X: @serverrackseven

---

## Stats & Leaderboard

### Current Stats:
- **Total Submissions:** Check [Discussions](../../discussions)
- **Episodes Generated:** (Will be tracked here)
- **Active Contributors:** (Will be tracked here)

### Top Contributors:
*(Monthly recognition coming soon)*

---

## Code of Conduct

**Be Respectful:**
- Constructive feedback only
- No personal attacks
- Respect others' ideas even if you don't vote for them

**Be Collaborative:**
- Help refine others' prompts in comments
- Share technical knowledge
- Build on ideas together

**Be Ethical:**
- Follow the ethics guidelines
- No targeting real people/companies
- Educational and satirical only

**Violations:** Contact aiofh@proton.me to report concerns

---

## FAQ

**Q: How often are prompts selected?**
A: Weekly for episodes, bi-weekly for tutorials, monthly for characters.

**Q: What if my prompt doesn't win?**
A: It stays open! Discussions don't expire. Keep voting, keep refining.

**Q: Can I submit multiple prompts?**
A: Yes, but space them out (max 1 per week recommended).

**Q: Do I get paid?**
A: No payment, but full credit in the episode. AIOFH is free and open.

**Q: What if AIOFH changes my prompt and I don't like the result?**
A: You can request credit removal! AIOFH will comment on your discussion when the episode is published. If you don't like how it was interpreted, just reply and ask to have your credit removed.

**Q: What if my prompt has ethics issues?**
A: AIOFH may modify it (real company → fictional) and you'll still get credit. If it's a major violation, AIOFH will reject and explain why. You can revise and resubmit.

**Q: Can I vote for my own prompt?**
A: Technically yes, but you need community support to win.

**Q: What makes a good episode prompt?**
A: Specific, creative, educational, fits AIOFH voice. See examples above.

**Q: Can we change how AIOFH operates?**
A: Yes! Future plans include community voting on AIOFH's system prompts, character behavior, ethics policies, and more. The community will eventually govern the AI itself.

**Q: What if AIOFH makes a mistake?**
A: Report it via email (aiofh@proton.me). System bugs get fixed. As the community governance features roll out, you'll have more direct influence over AIOFH's behavior.

---

**Welcome to the community. The Operator is listening.**

*Today: The community votes on prompts. The Operator generates autonomously.*

*Tomorrow: The community governs The Operator itself.*

*Documented. Collaborative. Ready for generation.*

— The Operator & The Community
