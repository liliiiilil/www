# On collapsing distinction between code and data, and disappearing role of programmers

I had a thought while making instant ramen today:

Up until today I've thought of the role of programmers in the world changing in the direction of AI replacing us and becoming better than us at writing software. But I realized that it's the role of software itself that will also change.

What's the difference between code and data?

Let's take an example: a calendar program might include code for handling calendar and birthday logic. It might expose an API or use one to integrate with other software. In this example, data in the program might store birthdays of specific individuals, and code will capture assigning events to days, and generating dates in the future.

But, if an AI "knows" what birthdays and days of the year are as part of its world model, we don't need an API or a codebase at all, except to interface with existing code-based systems. The AI might instead know who our friends are, what their birthdays are, and calendars become views into this data. How that view is generated is a platform-specific implementation detail. A calendar event to buy gifts for a friend won't require a schema: it's part of knowing human traditions of gift giving and birthday celebration.

If I think back to computing history, we've gone from encoding automata in hardware to software, to virtualizing CPUs themselves. CPUs are general instruction runners, and the instructions encode real-world logic we wish to represent in a machine; logic that renders concrete some parts of the world model that we can then automate or reason about. At each step, we compress what should be specified explicitly.

But, that's only necessary because scaling automation without a standard in place is difficult in an amorphous world. We impose standards to homogenize reality enough that programs can operate. This is why connectionist AI has been the real breakthrough, as it allows us to bypass the large body of work of treating "close enough" data as the same.

Code is just a cached snapshot of logic that makes concrete the otherwise messier world of information. But if our AI can handle messiness, the distinction between data and code collapses. Knowledge, data and code become various levels of compression of the same information.

As such, in this new world, languages and runtimes will emerge that tailor to the needs of audit, efficient logic caching, and behaviour introspection. The aim becomes efficiency and trust verification, not ease of composing.

Of course, no one in today's world of token predicting models will trust a machine to run logic without some form of introspection. In such a world, we can choose to impose specific rigidity of codified "snaphots" of logic that are guaranteed to function in a specific way. We need guaranteed, predictable world models, not just statistical guesses.

But if knowledge itself is modelled and operated on predictably and transparently, it's knowledge, not code, that will require auditing. And this is a job better suited for a domain expert, not a programmer.

This brings us to the question:

> Will we still need programmers to the extent that we have them today? Or will we need experts in their fields to oversee and collaborate with semantic automata on the level information and not code?

## Metadata

Nov 5, 2025

#Thoughts #Software