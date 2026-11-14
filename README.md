# Tutorials

Step-by-step lessons for building every tool on [Pink Bourbon Estate](https://pink-bourbon-estate.github.io) yourself, written for someone who has never written code.

**Status: planned. Nothing here is built yet.** This repository holds the plan until the first lessons exist. Read the reasoning in the essay [Beyond open: owning how it works](https://pink-bourbon-estate.github.io/articles/beyond-open-owning-how-it-works/).

## Why
Open code is only half of ownership. If you cannot follow it, you still depend on whoever (or whatever) wrote it. The point of these tutorials is that the knowledge of how to create, use and change each tool does not disappear if any one AI service does.

## The plan
- Every project on the site links to its own tutorial.
- Each lesson is step by step, in the browser, with an editor you can type into, and says how and why at every step.
- Every tutorial assumes **zero knowledge**. Toggles give intermediate and advanced readers less explanation.
- The path starts before any tool: making a GitHub account, making a website, building this exact website with all its features, submitting it to Google and Bing, and where `robots.txt` goes and what to say in it about AI.
- Then, one by one, every tool.
- Later, and with no guarantees: a helper that takes a tool you plug in and writes a tutorial to help you build and edit it.

## Rules for the lessons
- Plain language first; the jargon is introduced when it is needed and explained once.
- Every lesson is checked by building it from scratch, following only what is written.
- No accounts, no tracking, nothing loaded from other sites, like the rest of the estate.
- If a lesson has not been tested, it says so at the top.

## Layout (proposed)
```
tutorials/
  00-start-here/        accounts, tools, how to read a lesson
  01-your-website/      build the site
  02-publishing/        search engines, robots.txt
  tools/<tool-name>/    one folder per tool, linked from its project page
```

## Licence
Lessons: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Code samples: MIT.
