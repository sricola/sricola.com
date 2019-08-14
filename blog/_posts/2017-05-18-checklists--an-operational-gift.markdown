---
layout:	post
title:	"checklists: an operational gift"
date:	2017-05-18
---

No production operation is too small or too big for a checklist. Similarly, no situation is too strenuous for one. Always write one — it ensures smooth process!
![](/blog/img/1*i1CpQQPo80_ixdzDjznoug.jpeg)

At BuzzFeed we love lists. I mean, we helped pioneer the list format! Lists are easily digestible and are clear and concise in their meaning. They are no replacement for a long form read, but hey, nobody’s got time to read a leather bound novel by a fireplace during a production operation.


When a tech team is faced with an operation that involves production systems, it involves strategic thinking to execute steps with no downtime. There is little room for error.

No production operation is too big or too small for a checklist. Similarly, no situation is too strenuous for one. At BuzzFeed, we have resorted to writing a checklist for the most trivial of operations as well as in crisis situations putting out fires. Taking a few moments to jot down steps and getting peer feedback goes a long way in ensuring a smooth process.

Checklists are the best thing since ice cream was invented. The scientific usefulness of ice cream in a production operation is arguable but trust me on the checklists. However, I will say, [#everythingisbetteraftericecream](https://www.instagram.com/explore/tags/everythingisbetteraftericecream/)

### Anatomy of a good checklist

1. **Use** **numbers**! Alphabets are cool, but can also be misheard — “z” is *zedd* to me, but probably *zee* to many of you.
2. **Avoid sub-lists**. It’s hard to reference something like “2.a”.
3. Every step *is* important. If it’s not, it probably doesn’t belong in your production checklist.
4. Write out **full commands** in the list. In a crunch, you want to be able to blindly copy and paste commands instead of fumbling around figuring out what flags and options you may need.
5. If code needs to be merged in **link** to the appropriate pull request.
6. **[sricola]** Prominently mention who is responsible for each step.
7. Try out the checklist in a non-critical environment and **iterate** as needed before getting to production.
8. Build in **logical breaks-points** in the checklist where the system is stable to give people a breather.
9. Always keep a **back out plan** in mind while writing out steps. Mention clearly if the back out plan ceases to be an option after a certain step aka the *point of no return*.
10. Get peer feedback and address points of concern **prior to execution**.

### Back Out Plan

Lets face it, life never goes as planned. Having a handy back out plan is always a good idea. A back out checklist should adhere to the same standards as the rollout checklist above.

1. Again, I cannot stress this enough, make it as **verbose** and **complete** as possible.
2. Write out **full commands** on each step. Under pressure, the most trivial of steps take on a high degree of complexity.
3. Although we always strive to preserve a rollback strategy, sometimes (more often than one would like) going backwards might be impractical or impossible. Be extremely aware of this and mention it in the rollout checklist. We call this the ***point of no return***.

### People

**Driver**: The person who calls out the steps and keeps everything in sync. The driver controls the operational flow and makes final decisions on when to proceed to the next step. Ideally, the driver does nothing but drive the list.

**Executor(s)**: People assigned to each step to execute the line item.

**Watchers**: You should have more than one of these. These are people who have knowledge of the system and are watching on the sidelines to call out any anomalies in logs or monitoring.

**OMFG Officer**: This is a largely decorative position (typically our very own [Todd](http://twitter.com/@toddml)). This person has the power and confidence to make an executive decision if something goes south and drastic measures have to be taken. This person usually has a good sense of the business impact of taking particular actions and has the ability to reach out to external stakeholders in a crisis.

### Execution

1. Make a **dedicated chat channel** and invite appropriate parties.
2. Clearly **communicate** the checklist.
3. Hop on a **voice only call**. Video calls are strenuous on your laptop’s CPU, memory, and your internet connection.
4. The *Driver* should **call out each step verbally** (and in chat) and make sure there is no objection from anyone.
5. The *Executor *should confirm that they are running the step and **paste the command** into the chat room. This allows the Watchers to know which step is in progress.
6. The *Watchers**** ***should paste any and all confirming or opposing output and **logs into the chat room**.
7. Cross out or check off completed steps.
8. Do ***NOT*** modify the checklist mid-operation unless it is a do-or-die situation. If something goes wrong take a moment to **step back and re-evaluate**.

### In conclusion

To reiterate: No production operation is too small or too big for a checklist. Similarly, no situation is too strenuous for one. Always write one — it ensures smooth process!

  