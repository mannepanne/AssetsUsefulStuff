# What is this

Template for prompting tools like Lovable, v0, Bolt to produce a wireframe / starting point of a design.

Lifted from:
https://newsletter.posthog.com/p/an-engineers-guide-to-vibe-design

Credits to: 
Lior Neu-ner, https://substack.com/@liorn

# Goal
You're helping me design a wireframe for an app/feature that 
<your single sentence on your job to be done>.
Example: 
You're helping me design a wireframe for an web app that lets users log a bug and assign it to a teammate in under 30 seconds.

## Target user
<Who is this feature for, and what mindset are they in when using it?>
Example: 
A software engineer or product tester reporting a bug mid-flow. They're in a rush and need to get the issue logged and handed off with minimal friction.

## Success criteria
<How you will know your user has achieved their job to be done>
Example: 
The user can within 30 seconds and 3–4 clicks:
- Open the app
- Enter a bug title and description
- Assign it to a teammate
- Save it

## Key screens
- <screen 1>
- <screen 2>
Example:
- Bug list (default view, sorted by status)
- New bug form
- Single bug detail view

## Requirements
- <What your app *must* do>
- <What your app *must not* do>
Example:
- Must support: bug title, description, status (open/in progress/done), assignee
- Must support: fast reassignment and status updates
- Must not require account switching, complex onboarding, or configuration before logging
- Should be desktop-first

## Design intent
The UI should feel: <clean, fast, minimal, playful, etc.>  
Prioritize: <clarity, speed, minimal steps, mobile-first, etc.>
Example:]
The UI should feel: fast, minimal, focused  
Prioritize: speed, clarity, zero-fat UX

## Tech stack
<Your preferred tech stack, component libraries, etc.>
Example:
- Next.js
- Tailwind
- Shadcn

## Inspiration from competitors

### <Competitor Name>
**What works well:**
- <list of patterns or layouts you like>

**What doesn't:**
- <list of things to avoid>

**Competitor screenshots**
- <description of first competitor screenshot>
- <description of second competitor screenshot>

## Inspiration example

### Linear
**What works well:**
- Clean, minimal layout
- Fast modal-based bug creation
- Keyboard shortcuts for power users

**What doesn't:**
- Abstract language
- Intimidating for non-technical users

## Jira
**What works well:**
- Customizable workflows

**What doesn't**
- Overly complex
- Too many clicks and screens
- Slow performance

### GitHub Issues
**What works well:**
- Familiar issue structure
- Good activity history

**What doesn't:**
- Too many fields upfront
- Slow to create quick entries

**Competitor screenshots**
- linear_bug_list.png - shows simple bug creation 
- jira.png - shows cluttered UI
- github_issue_form - show too many fields in bug creation
