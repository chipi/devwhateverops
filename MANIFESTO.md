# DevWhateverOps Manifesto

*A set of principles for engineers who build end to end — written as the AI hype begins to settle.*

-----

## Breaking things carefully is how you go faster.

The fastest engineering teams break things more often than the slow ones. Not because they are reckless — because they built systems where breaking things is safe, observable, and cheap.

Fear of breaking things is the real bottleneck. Not process, not tooling, not headcount. Every gate in a pipeline, every approval step, every handoff between teams — most of them exist because somebody was afraid. Afraid of blame, afraid of production, afraid of the unknown.

This manifesto is about building the kind of system where that fear has nowhere to live.

-----

## I. Culture

*Own the full loop. No gates, no handoffs, no role hiding.*

DevOps was never a role. It was a direction. Every “-Ops” suffix we invented since — SecOps, AIOps, DocOps, FinOps — was an attempt to name a culture shift. Most of the time it became a job title instead. A new silo built to solve the problem of silos.

The baseline for any engineer is understanding the full system they work in. Not just the code they write — how it is tested, how it is deployed, how it behaves in production, and what happens when it breaks. Specialization on top of that foundation is a multiplier. Specialization instead of it is a liability.

End-to-end ownership is not a senior bar. It is the entry bar. Hiring should reflect that. Can you write it, test it, pipeline it, deploy it, instrument it, and close the loop with metrics and observability? Are you ready for partial rollout, A/B, and gradual promotion to full deployment? That is the question — for any engineer, at any level.

Requirements and specifications belong in the pipeline, not beside it. RFCs, PRDs, ADRs are not side artifacts. They are first-class inputs. Code, tests, and pipeline stages should be able to reference them, trace back to them, and validate against them. The loop from specification to deployment to observation should be closed, not scattered across tools and folders nobody reads.

-----

## II. Pipeline

*Automate everything. Smooth is fast, fast is smooth.*

Automation is not about replacing people. It is about removing every ceiling on how fast and safely people can move. Every manual step in a pipeline is a speed limit. Every approval gate that exists because nobody automated the check is a tax on momentum.

Ops must be invisible. Not because it does not matter — because it matters so much it cannot depend on human intervention. The goal of Ops is to disappear into the system. The teams that move fastest are not the ones with the best engineers. They are the ones where the infrastructure gets out of the way.

CD over CI. The real signal comes after deployment, not before. Smaller deployments, early metrics, real user behavior. You do not build confidence in a pipeline by running more tests. You build it by shipping smaller and observing more.

Old quality is still there. It does not go away because AI arrived. Static analysis, dependency scanning, test coverage, security in the pipeline — these are not legacy concerns. They are the foundation. AI evaluation is the new layer on top. You cannot build the new layer on a broken foundation.

-----

## III. Experiments

*Every change is a hypothesis. Ship small, observe, decide.*

It is okay to break things. That is why we have controlled rollouts.

A/B testing and gradual rollouts are not just risk management tools. They are permission structures. They change what “safe to ship” means — from “we tested everything” to “we can observe and roll back.” That shift unlocks a completely different engineering culture. You stop optimising for not shipping and start optimising for learning fast.

An experiment is an experiment regardless of what you are changing. A new UI button observed against click behaviour. A copy change measured against conversion. An AI model swap validated against a baseline dataset. A feature rolled to five percent of traffic. The discipline is identical — hypothesis, controlled change, observation, decision. The tooling varies. The culture does not.

Evaluation, dataset versioning, experiment tracking, and baseline comparisons are not exotic ML infrastructure. They are what CI/CD looks like when your system has a probabilistic component. AIOps is a variation on the theme, not a separate practice. Teams that already had solid pipelines, good observability, and a deployment culture find it relatively natural. Teams that did not are struggling with both at once.

Every change is an experiment. The pipeline should treat it that way.

-----

## The Enemies

The cost of fragmentation is invisible. Nobody budgets for the deployment that required three teams and a ticket. Nobody measures the speed lost to a gate that exists because the test was never automated. The real cost of the current way of working is consistently underestimated — which means the investment required to change it is consistently underfunded.

Beyond cost: most organisations have people with rational reasons to resist this direction. Specialists who built careers inside a narrow lane. Managers who built teams around a function. Change that threatens identity moves slowly. Automation costs now and pays later — which is the wrong shape for most quarterly plans.

These are not excuses. They are the terrain.

-----

## From Here

*The principles don’t change. The articles will.*

This is not a new movement. It is the original one, still completing itself.

The principles here are intended to age well. The specific articles, tools, and examples that follow will evolve — and that is the point. This manifesto is the anchor. Everything else is the elaboration.

If you build end to end, you are already here. If you are trying to get there, you are in the right place.

-----

*More specific, hands-on writing coming.*  
*Follow along at [devwhateverops.com](https://www.devwhateverops.com)*

-----

**Version history and contributions:** [github.com/devwhateverops](https://github.com/devwhateverops)  
**Author:** Marko Dragoljevic · [LinkedIn](https://www.linkedin.com/in/markodragoljevic)
