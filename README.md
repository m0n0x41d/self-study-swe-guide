---
icon: hand-wave
cover: >-
  https://images.unsplash.com/photo-1617825013838-0c4109a96aca?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw3fHxheGV8ZW58MHx8fHwxNzMxNjgyNDIzfDA&ixlib=rb-4.0.3&q=85
coverY: -81
layout:
  width: default
  cover:
    visible: false
    size: hero
    mask: none
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# Hello friend, start here!

## About me

Hi, I'm Ivan Zakutnii. I'm a systems engineer, CTO at [Glentorion](https://glentorion.com/), co-founder of [Fusioncat](https://fusioncat.dev/), and creator of [Haft](https://haft.tools/). Earlier in my career, I worked as a Staff and Platform Engineer on fintech and production AI systems.

I am mentioning this just for context, not as a claim that I have found the one true way to learn. The relevant part is that I took a self-study route into professional engineering, spent years learning with an experienced mentor, and have kept testing these fundamentals in real work.&#x20;

My experience was such that it was thanks to self-education and a mentor that I learned much more than in an edu institution.&#x20;

I also write about systems engineering, software, and learning on [my blog](https://ivanzakutnii.com/). This guide is a step-by-step path for learning how to become a solid software engineer.

What this plan is **not** about

* "Ten best projects for your resume"
* Learning frameworks and other mainstream stuff you're already bombarded with everywhere
* Someone holding your hand through every step
* "Becoming a programmer in one month"

### Where did these materials come from?

This is how I learned programming and software engineering from my Mentor. It is mostly a rewritten version of the free plan he offers to self-taught programmers starting from zero.

I've spent years learning from him through internal materials.

### Who is my mentor?

I won't name names because our laboratory is kind of underground club and has rules I stick to.

In short: he has been programming since 1979. He has written more than a dozen books and programming courses, plus about a thousand articles on software engineering since 1995. He has trained thousands of people in programming and worked as a software engineer on many international projects. He is also a certified ICM (Institute of Consulting and Management) coach.

I'm sharing an adaptation of his guide with his permission, combined with what I learned while studying and working in the field.

> The tools and resources in this guide will keep changing. The core path is deliberately stable.

## Is this guide still relevant in the AI era?

I DO believe it is!

At the same time, **AI-assisted engineering is no longer optional. There is no going back to software engineering without it.** The pace of development has already increased, and it will not stop accelerating. This makes engineering fundamentals even more valuable, not obsolete. While following this guide, you should also start learning—right now, in parallel—how to create real projects with AI.

This guide will not teach you how to build projects with AI. That is deliberate: its job is to build the engineering foundation underneath that work. Treat these as two separate tracks and practice both:

* follow this guide to build programming fluency, engineering thinking, and the fundamentals;
* build separate projects with AI to learn AI-assisted engineering in practice.

Do not wait to finish one before starting the other. These tracks are complementary. Fundamentals let you direct, inspect, and remain responsible for AI-produced work. AI lets you build more, encounter larger problems, and learn faster.

AI can already produce some code quickly and cheaply. That is useful: a good engineer can test hypotheses, explore alternatives, and build working systems faster.&#x20;

But AI also amplifies the thinking and experience that is already present in its operator. Strong engineering judgment gains leverage; weak mental models let you produce confident mistakes at much greater speed.

How do we choose the right databases and design data models? How do we ensure that the AI-generated code is adequate for the business problems our system solves? How can we predict asymptotic bottlenecks at different system levels?

I think these are purely rhetorical questions.

AI can also help you study faster. If you genuinely study the topics and practice [thinking through writing](learning-path/learning-programming-basics.md#thinking-through-writing), use AI to ask questions, get explanations, generate examples and counterexamples, and review your understanding. It can shorten the feedback loop, but it cannot do the thinking through writing for you.

> In other words: Use AI to PROMPT YOURSELF. Get the idea – close the loop so your brain works as much as possible, especially when you're studying.

For language basics, writing code, and solving programming tasks, I still think you should rely on your own brain and hands. It is very, very hard to develop fluency in programming thinking if you only generate solutions with AI and read them.

At the extreme, yes: you probably can use AI throughout this guide if you genuinely study every topic, every algorithm, and every data structure, and can explain and reproduce what was generated. But I still think writing the code yourself will root the understanding and knowledge deeper in your head.

This is why the guide still asks you to write programs, debug them, study data structures, read code, work with databases, and explain ideas in your own words. The goal is not to compete with an AI model at typing syntax. The goal is to build enough of a model in your own head to understand a problem, inspect a solution, notice what is missing, and remain responsible for the result.&#x20;

By honestly following the path from this guide and making an effort, you will literally do one thing – **train** a software engineering **neural network** in your own head.

Use AI fully in the AI-assisted project track. In the foundations track, I still recommend using it as a teacher and reviewer before using it as the author of your solution. Inspect its answers, challenge them, and make sure you can reproduce and explain the result yourself. If the model completed an exercise and you cannot explain the solution, the learning step is still incomplete.

I think of this as augmented engineering: the human and the AI strengthen each other. You can delegate more execution as your judgment grows, but you cannot delegate the work of developing that judgment.&#x20;

I wrote a longer version of this position in [The Best Harness Is You and Your AI Agents](https://ivanzakutnii.com/en/blog/the-best-harness-is-you-and-your-ai-agents/).

## Who is this guide for?

This guide is for beginners and early-career software engineers who want to build a serious  engineering foundation before specializing.

You do not need to know your final specialization yet. You do need curiosity, patience, and a willingness to practice things that will not pay off immediately. We are building a solid house here, not a one-night shelter made from palm leaves.

There is a catch: this requires sustained effort. Fifteen distracted minutes once in a while will not build the skill. Regular focused practice matters more than occasional heroic sessions.

<figure><img src=".gitbook/assets/image (1).png" alt="Matrix choice: study programming deeply and become an engineer, or make things work somehow and spend a career copying from an LLM."><figcaption></figcaption></figure>

> Read the whole path before committing to it. The work is substantial, and it is better to choose it consciously.

***

This is not a job-placement plan, and completing it does not guarantee employment. Hiring depends on your market, specialization, portfolio, communication, interview skills, your personal brand, network and timing.

You will also need role-specific technologies and collaboration skills beyond this guide. Those change much faster than the foundation covered here.

> You get out what you put in, provided the effort is deliberate and aimed in the right direction.

If you do the work honestly, this path is designed to train your problem-solving ability and give you a foundation you can carry into many software engineering roles.

## How to use this book

First, read through it quickly to understand what it covers and how much work it will take.

You'll know pretty fast if it's for you or not.

[Basic Understanding](basic-understanding/good-to-have-in-your-mind.md) is for complete beginners who know little about programming or software jobs. If you already know what a variable is and are comfortable with a command line, skim it and continue.

The rest is the [Learning Path](learning-path/learning-programming-basics.md), focused on practical skills and how to develop them. The sequence matters, but some adjacent topics can be studied in parallel.

Do not advance only because you have finished reading a page. Move on when you can demonstrate the skill without copying a solution.

Good luck, and happy hacking.
