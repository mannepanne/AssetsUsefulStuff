Copied from a newsletter by Simon Willison, where he perfectly summed up how I feel about "vibe coding" in a much better way than I ever could.

In essence: treat your vibe coding project like *any* well structured project. Put as much time in to prepare as you would when not working with AI. 

Think of the AI as a human collaborator (assuming all the same strengths and flaws of a human, apply "trust but verify", etc) and it can be an amazing way of working.

From: https://simonw.substack.com/p/vibe-engineering

It’s also become clear to me that LLMs actively reward existing top tier software engineering practices:

- *Automated testing.* If your project has a robust, comprehensive and stable test suite agentic coding tools can fly with it. Without tests? Your agent might claim something works without having actually tested it at all, plus any new change could break an unrelated feature without you realizing it. Test-first development is particularly effective with agents that can iterate in a loop.

- *Planning in advance.* Sitting down to hack something together goes much better if you start with a high level plan. Working with an agent makes this even more important - you can iterate on the plan first, then hand it off to the agent to write the code.

- *Comprehensive documentation.* Just like human programmers, an LLM can only keep a subset of the codebase in its context at once. Being able to feed in relevant documentation lets it use APIs from other areas without reading the code first. Write good documentation first and the model may be able to build the matching implementation from that input alone.

- *Good version control habits.* Being able to undo mistakes and understand when and how something was changed is even more important when a coding agent might have made the changes. LLMs are also fiercely competent at Git - they can navigate the history themselves to track down the origin of bugs, and they’re better than most developers at using git bisect. Use that to your advantage.

- *Having effective automation in place.* Continuous integration, automated formatting and linting, continuous deployment to a preview environment - all things that agentic coding tools can benefit from too. LLMs make writing quick automation scripts easier as well, which can help them then repeat tasks accurately and consistently next time.

- *A culture of code review.* This one explains itself. If you’re fast and productive at code review you’re going to have a much better time working with LLMs than if you’d rather write code yourself than review the same thing written by someone (or something) else.

- *A very weird form of management.* Getting good results out of a coding agent feels uncomfortably close to getting good results out of a human collaborator. You need to provide clear instructions, ensure they have the necessary context and provide actionable feedback on what they produce. It’s a lot easier than working with actual people because you don’t have to worry about offending or discouraging them - but any existing management experience you have will prove surprisingly useful.

- *Really good manual QA (quality assurance).* Beyond automated tests, you need to be really good at manually testing software, including predicting and digging into edge-cases.

- *Strong research skills.* There are dozens of ways to solve any given coding problem. Figuring out the best options and proving an approach has always been important, and remains a blocker on unleashing an agent to write the actual code.

- *The ability to ship to a preview environment.* If an agent builds a feature, having a way to safely preview that feature (without deploying it straight to production) makes reviews much more productive and greatly reduces the risk of shipping something broken.

- *An instinct for what can be outsourced to AI and what you need to manually handle yourself.* This is constantly evolving as the models and tools become more effective. A big part of working effectively with LLMs is maintaining a strong intuition for when they can best be applied.

- *An updated sense of estimation.* Estimating how long a project will take has always been one of the hardest but most important parts of being a senior engineer, especially in organizations where budget and strategy decisions are made based on those estimates. AI-assisted coding makes this even harder - things that used to take a long time are much faster, but estimations now depend on new factors which we’re all still trying to figure out.

If you’re going to really exploit the capabilities of these new tools, you need to be operating at the top of your game. You’re not just responsible for writing the code - you’re researching approaches, deciding on high-level architecture, writing specifications, defining success criteria, designing agentic loops, planning QA, managing a growing army of weird digital interns who will absolutely cheat if you give them a chance, and spending so much time on code review.

Almost all of these are characteristics of senior software engineers already! (And senior product managers! // Magnus)

*AI tools amplify existing expertise.* The more skills and experience you have as a software engineer the faster and better the results you can get from working with LLMs and coding agents.
