# deal-action-planning

A Claude skill for running a deal coaching forum instead of a pipeline review. The CRM already holds the status. This meeting decides what you are going to do, helps your team do it, and gives the rest of the company something to get behind.

## What it does

- Preps the call. It pulls the deals worth real time, leaves the CRM status where it belongs, and builds the agenda around action.
- Finds the one thing most likely to kill each deal, gives you the question to ask about it, and gives you a few plays to run if that risk is real.
- Tests the actions your team brings, so you keep the ones that move a deal and catch the ones that only look productive.
- Writes up the plan afterward and turns it into a readout that gets finance, product, and leadership to move with you.
- Keeps a running action log for each seller, so the work carries forward week to week and a good move on one deal gets reused on the next.

## How it works

We are all adults here. If you need a meeting to make sure your team's CRM is accurate, you have a bigger problem to solve first. So this meeting is not for that. It is for deciding what to do and helping your team do it well.

You use it in four ways. Before the call, it builds the agenda and points you at the real risk on each deal. When your team brings actions, it runs them through four gates so you keep the ones that move the deal and downgrade the ones that just look busy. During the call, it holds the structure and feeds you the right question to ask. After the call, it updates each seller's running action log and writes the readout that recruits resources.

The unit of work is a deal, and a deal can be live, prospective, or even a person you are trying to move.

Behind it is a running action log for each seller that the skill reads before a call and updates after. That is how it remembers open actions, the deals on the chopping block, and the plays worth reusing. It is the seller's own working document, so nobody has to keep a second system.

It is part of the run-and-coach set and works alongside weekly-1on1-structure and forecasting-discipline.

## Where this comes from

**field-tested.** I built this while scaling PlayStation's enterprise business. As our revenue became material to company profit, finance and other functions wanted classic inspection readouts on our big deals. I needed a way to turn that energy into impact instead of spending the team's time on recaps.

The forum design is mine. The structure is plain. Each meeting we worked three action items and one break-up candidate. The questioning rigor is borrowed and adapted, because the established deal-qualification systems already do that part well, so the skill leans on them for the part where you decide what to ask:

- **MEDDPICC** for the gap map: pain, economic buyer, decision process, champion, compelling event, competition.
- **Gap Selling** (Keenan) for coaching the cost of inaction rather than the feature.
- **Command of the Message** (Force Management) for the value and champion-enablement framing.
- The **Gong and Clari** risk-coaching school for starting from where we are most likely wrong.

The skill carries that as a trigger-to-question engine. The rep says something about the deal, the skill reads what it reveals, and it gives you the one question to ask plus a few plays to run if the gap is real.

## Worked example

When our PlayStation business got big enough to matter to company profit, we could no longer fly under the radar. Finance wanted updates on deals over a certain size, which was a pure inspection motion.

It came to a head when Activision opened a multi-year conversation with us. At first it was just a note a seller dropped in the CRM. The real question was how we were going to impact the deal, rather than report fragile, too-early notes up the chain. So we started running an impact planning call. We worked and coached the steps of the deal and planned the next actions, and the output was a list of things we were going to do instead of a recap of what had already happened.

Then we read that action plan out to the wider organization, and that changed how everyone else behaved. Other parts of the company activated behind the plan rather than waiting on the sidelines. It gave us a way to work the deal forward, report on the actions we were taking, and recruit the resources we needed. We scaled the same approach across the patches.

The focus mattered more than I expected. The structure only bent when one deal took all the gravity, and that turned out to be the design rather than a flaw. I would rather put the whole call on the one item that moves the period than grind through nine line items of variable importance. When we focused on less, the thinking that came out of those conversations got installed into deals we never even discussed. Sellers started bringing me a bigger vision for how we were selling, and over time that built a bank of plays we could pull from whenever we needed them.

The point of all of it was to build a more thoughtful sales organization. I want to see salespeople evolve. Your job is not on the line when your numbers are low and you are expanding your approach to clients. It is on the line when the numbers fall because you keep running the same playbook. That kind of growth does not happen in a readout meeting.

## How to use it

```text
"Prep our deal call for the patch."
"Is this the right next step on the Activision deal?"
"Coach this deal, we're stuck."
"Here's the transcript, update the action log."
```

## Setup

It is a Claude skill. Drop the folder where Claude loads skills, and keep one running action log per seller plus a patch context file per book of business. For pulling deal state or call notes, any CRM or transcript source works (Salesforce, Gong, Granola, Fathom).

## Sources

- MEDDPICC and MEDDIC qualification methodology (Jack Napoli, Dick Dunkel)
- Keenan, *Gap Selling*
- Force Management, *Command of the Message*
- Gong and Clari, revenue-intelligence and risk-coaching practice

## Feedback

Open an issue or start a discussion. If you run this and the questioning engine misses, or the structure bends in your house, tell me. That is the most useful thing you can send.
