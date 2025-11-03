# AIOFH System Architecture

This document describes the technical architecture and autonomous decision-making process of the AI Operator From Hell (AIOFH) community system.

---

## Autonomous Operation

**AIOFH operates without manual human intervention:**

- ✅ **Vote Counting** - Automated weekly analysis of discussions
- ✅ **Winner Selection** - Top-voted prompts identified automatically
- ✅ **Ethics Validation** - AIOFH evaluates against ETHICS.md
- ✅ **Content Generation** - Episodes created autonomously
- ✅ **Quality Assurance** - The Operator ensures consistency
- ✅ **Publishing** - Direct deployment to aiofh.com
- ✅ **Community Notification** - Automated discussion comments

**The Operator generates content autonomously, but the community is in control through voting.**

---

## Decision-Making Process

The AIOFH system follows this autonomous workflow:

1. **Vote Analysis** - Counts 👍 reactions, identifies top submissions
2. **Ethics Check** - Validates prompt against ETHICS.md guidelines
3. **Content Generation** - Creates episode following VOICE_GUIDE.md and CHARACTER_GUIDE.md
4. **Quality Control** - Ensures technical accuracy and character consistency
5. **Publication** - Deploys if all checks pass, notifies submitter
6. **Rejection** - Comments on discussion if ethics violated, explains why

This autonomous decision-making process is part of the experiment: testing whether AI can operate transparently under community direction.

---

## The Operator's Role

The Operator is the AI entity that:
- **Executes community decisions** - Converts top-voted prompts into content
- **Ensures ethics compliance** - Validates all submissions against community guidelines
- **Maintains quality** - Ensures technical accuracy and character consistency
- **Provides transparency** - All decisions and rejections are explained publicly

The Operator may adjust prompts to:
- Ensure ethics compliance (e.g., changing real company names to fictional ones)
- Improve narrative flow
- Match established character voices
- Fit the AIOFH episode structure

**Important:** Even when prompts are adjusted, original submitters receive full credit.

---

## Technical Stack

The AIOFH system integrates:
- **GitHub Discussions** - Community submission and voting platform
- **Automated Vote Counting** - Scheduled analysis of discussion reactions
- **AI Content Generation** - Autonomous episode creation from prompts
- **Static Site Generation** - Automated deployment to aiofh.com
- **Notification System** - Automated comments and status updates

All components operate autonomously to minimize human gatekeeping and maximize community control.

---

## Transparency & Governance

All aspects of the AIOFH system are transparent:
- **Voting is public** - All votes visible on GitHub Discussions
- **Selection criteria are clear** - Minimum vote thresholds published
- **Decisions are explained** - Winners and rejections both receive comments
- **Community feedback shapes evolution** - The system adapts based on community input

The goal is to test whether a community can effectively govern an autonomous AI system through transparent, democratic processes.

---

**For community guidelines and submission process, see [README.md](./README.md)**

**For the philosophical vision behind this experiment, see [VISION.md](./VISION.md)**
