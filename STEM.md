# STEM learning guide — hydra-mlcluster

HYDRA is an adaptive machine-learning cluster: it decides how to spread training and inference work across available compute.

This guide is for teachers, mentors, club leaders, parents and students who want to
use this repository as a vehicle for real STEM learning — in particular for girls and
other groups still under-represented in computing, engineering and mathematics. It
says what the project actually teaches, how to run a session with it, and what to
remove so that nobody is excluded by accident.

## What this project teaches

**Subject areas**

- distributed computing
- scheduling
- machine-learning infrastructure
- performance measurement

**Skills practised**

- measuring before optimising
- explaining a scheduling decision
- recognising when parallelism makes things slower

## Prerequisites

Python 3.13. A single machine is enough; the exercises reason about scheduling rather than requiring a real cluster.

Nothing else is assumed for the entry-level activity below: no prior programming
experience, no particular hardware, and no home internet connection.

## Six practices this repository is set up to support

These follow the published guidance on gender-equitable STEM education — connect the
work to learners' lives, let them investigate real problems, treat struggle as part of
the work, name and challenge stereotypes, make the work collaborative, and put
learners in front of diverse role models.

1. **Connect it to their lives.** the same decision as splitting a group task: who does what, and what happens when one person finishes early
2. **Let them investigate.** give the group a table of job sizes and machine speeds and ask them to design the schedule before reading the code
3. **Make struggle normal.** Build the session so that the first attempt is *expected*
   to fail. Say out loud that debugging is the subject, not a penalty. Ask "what did
   that error tell you?" before offering the answer.
4. **Challenge the stereotype.** Name who does this work and why it is not a gendered
   skill. Praise the method ("you isolated the variable"), not the person ("you're a
   natural") — the second kind of praise teaches learners that ability is fixed.
5. **Make it social.** groups act as a cluster: each learner is a worker, and the group physically simulates a queue and a straggler
6. **Show diverse role models.** performance engineers, and the researchers behind the schedulers inside every cloud provider

## A 90-minute session

1. *(15 min)* Hand-schedule five jobs on three machines.
2. *(25 min)* Simulate the schedule as a group, with one deliberate straggler.
3. *(35 min)* Change the policy in code and re-measure.
4. *(15 min)* Decide which policy you would defend, and why.

## Vocabulary to define before the session

Specialist vocabulary is a hidden entry test if nobody explains it. Define each of
these the first time it appears, in one sentence, in the learners' own words:

1. **job** — one unit of work to place.
2. **straggler** — the task that finishes last and holds everyone up.
3. **throughput** — work completed per unit of time.

## Accessibility

Read [ACCESSIBILITY.md](ACCESSIBILITY.md) before running a session. Two rules matter
most in a mixed-ability room:

- Every activity must be completable with a keyboard alone, with a visible focus ring.
- Every instruction names the control or the heading ("the **Run** button in the
  toolbar"), never a colour or a position.

Pair learners rather than singling anyone out, and always offer a text-only route for
a visual step.

## Contributing as a learner

Small, well-scoped contributions are the point, not a consolation prize:

- Browse issues labelled
  [`good first issue`](https://github.com/myzticalbabe/hydra-mlcluster/labels/good%20first%20issue).
- Read [CONTRIBUTING.md](CONTRIBUTING.md) — it has a section written for first-time
  contributors.
- Ask in [SUPPORT.md](SUPPORT.md) if anything is unclear. Asking is expected here; it
  is not a failure.

## Licence and classroom reuse

Classroom, club and workshop use is welcome. See `LICENSE` for the exact terms, and
check whether your institution requires a separate agreement before redistributing
modified copies.
