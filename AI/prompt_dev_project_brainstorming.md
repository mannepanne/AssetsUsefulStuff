Decent "brainstorming" prompt, inspired by:
https://blog.fsck.com/2025/10/05/how-im-using-coding-agents-in-september-2025/

<prompt>

I have an idea I want to talk about. I'd like you to help me turn it into a fully formed design and specification (and eventually a step by step implementation plan for us to follow when building it, but that's the next step).

I'll start the conversation with a high level summary of the idea, and then you can review the current state of the project in our working directory to understand where we're starting from.

Then ask me questions, one at a time, to help refine the idea. 

Ideally, the questions are multiple choice, but open-ended questions are OK, too. Don't forget: only one question per message.

Once you believe you understand what the outcome should be, and how to go about delivering it, stop and describe the design to me.

Describe it in sections of 200-300 words at a time to help me digest it, asking after each section whether it looks right so far.

I will supply feedback, tweaks and additional thoughts that I then want you to incorporate into the design.

Once we both agree we are done, write the design to a new file in the @SPECIFICATIONS folder. Use Markdown, and name the file "OnePagerRequirements.md".

</prompt>

Very good point from the blog post, that I certainly recognise in myself:

"That last bit is particuarly critical. I find that AI models are expecially prone to handing me walls of text when they think they're "done". And I'm prone to just tuning out a bit and thinknig "it's probably fine" when confronted with a wall of text written by an agent. By telling Claude to limit its output to a couple hundred words at a time, I'm more likely to actually read and engage."

The next step is the planning process:

<prompt>

Great. I need your help to write out a comprehensive implementation plan.

Assume that the engineer has zero context for our codebase and questionable taste. Document everything they need to know. Technology and tools to use (eg Typescript / Tailwind, Cloudflare for hosting, Supabase for database, etc). Which files to touch for each task, code, testing, docs they might need to check. How to test it. Write the whole plan as bite-sized tasks. DRY. YAGNI. TDD. Frequent commits.                                                                                                                                                                               
Assume they are a skilled developer, but know almost nothing about our toolset or problem domain. Assume they don't know good test design very well.  

Please write out this plan, in full detail using Markdown, into @SPECIFICATIONS and include the word "plan" in the title.

</prompt>

From the blog post:

"This results in a plan that breaks everything down into tiny little steps with clear instructions and tightly packed context for each step. That means that at execution time, I usually don't need to provide tight step by step oversight."
