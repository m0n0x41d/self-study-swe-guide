---
icon: square-root
---

# Learning Programming Basics

So, you have chosen your programming language. Now hear the most important thing: at this stage, you only need to write simple programs and solve small tasks. Nothing too complex.

You do not need a framework or a large portfolio project yet. Small programs written from scratch are useful; copying a project line by line from a random video is not the same practice.

So, the goal here is to learn basics of your language, and learn it well.

You can choose one of these platforms:

* [exercism.org](https://exercism.org/)
* [codewars.com](https://www.codewars.com/)
* [hackerrank.com](https://www.hackerrank.com/)

Or find a free or paid course you trust whose syllabus teaches the basics of your language and elementary programming instead of rushing straight into a framework project.

> If you are unsure, choose one well-maintained beginner track, follow it for a week, and evaluate whether you are writing code and receiving useful feedback. A reversible start is better than another week of comparing courses.

If we are looking at training platforms with tasks, I personally recommend starting with _**Exercism**_. Many language tracks arrange exercises into a learning path with detailed explanations.

> Start with it. You will have time to return to Codewars later.

Enable Learning Mode when the track offers it. It should look like this:

<figure><img src="../.gitbook/assets/image (4).png" alt="An Exercism Python track in Learning Mode, with concepts arranged as an unlocking path."><figcaption></figcaption></figure>

If your language has only Practice Mode on Exercism, start with easy tasks and review the material provided with them. Each task includes instructions, tests, and links that can help you learn the concepts needed to solve it.

Exercism's core learning and mentoring experience is free. You can request human feedback on a solution, and the project accepts donations if it helps you and you can afford to contribute.

***

Back to the learning process: understand the problem and make a real attempt before looking up an answer or asking an LLM for help. The mental work is the exercise.

AI is useful here when it preserves that work. Ask for a smaller hint, an explanation of a compiler error, a counterexample, or a review of code you have already written. Avoid asking for the complete solution as your first move.

After receiving help, close the answer and solve the problem again. Explain why your solution works, which cases it handles, and what you would change. If you cannot do that, return to the exercise.

You will want to take shortcuts. That is normal. If you have been stuck for 20 focused minutes and have made no progress, take a short break, drink some tea, or walk. Return with a fresh attempt before escalating to a full solution.

> For an influential introduction to fast and slow thinking, read Daniel Kahneman's "Thinking, Fast and Slow" critically rather than treating every example as settled science.

It is difficult to learn effectively alone for a long time. If you have the opportunity, find a mentor or study group that can review your work, even if you meet only once a week.

Long-term individual mentorship is often paid, while study groups, open-source communities, and platforms such as Exercism may provide useful feedback for free. Choose according to your needs and means.

***

Earlier in my own learning, I would have treated that advice with scepticism. Experience changed my mind: a good mentor can see misconceptions you do not yet know how to name and can shorten the feedback loop.

I am not selling mentorship through this guide, and I will not recommend one universal person or platform. At this stage, a patient computer-science teacher or an experienced programmer who gives concrete feedback may be enough.

The goal of this block is to write simple terminal programs such as tic-tac-toe or a guessing game. Keep the interface and dependencies simple so the programming remains the hard part.

Before moving on, you should be able to:

* write several small terminal programs from a blank file;
* break a problem into functions and choose basic data structures;
* use the debugger or diagnostic output to find a mistake;
* read a failing test or error message and act on it;
* explain your solution without relying on an AI-generated explanation.

Depending on your available time and previous experience, this block may take weeks or months. The abilities above matter more than the calendar.

Do not let perfection trap you here. Later sections will deepen these skills.

## Thinking through writing

> Attention!!! 🚨 \
> \
> This section is the most valuable in this whole guide and might have the most impact on all your future self-studying, professional, and personal development in a lifetime. If I could force you to fully internalize and understand only one concept from this whole guide, it would be "Thinking through writing."

Alrighty, from this block onward, you will encounter many concepts, terms, and skills.

Learning itself is a _**skill**_. The most useful method I can share here may sound obvious, but it is difficult but incredibly rewarding in practice.

If you want to establish solid skills (any skills in life, to he honest – even physical ones), practice "thinking through writing."

The whole thing sound very simple: _**after studying a topic, write several sentences or a short essay about it in your own words. The gaps in that explanation show you what to revisit.**_

> **Own words, you hear?**&#x20;
>
> NOT "note-taking".&#x20;
>
> NOT peeking into source material.&#x20;
>
> If you need to peek – go and read/skim again, close the tab, and then write.

Deliberate study, reflection, and review can improve both recall and understanding. The same applies to both – writing in natural language and writing code when you are learning to code (writing code is also "thinking through writing"; it is just a specific language with a very concrete syntax and semantics):

<div align="center" data-full-width="false"><figure><img src="../.gitbook/assets/image (2).png" alt="A progression meme: copying from Stack Overflow or an LLM, writing simple programs, understanding algorithms and data structures, expressing domain abstractions, understanding paradigms and type systems, then seeing computation as mathematical composition."><figcaption></figcaption></figure></div>

Again – writing programs is already a form of thinking through writhing.&#x20;

Courses often supply scaffolding and hints, so reinforce the skill by closing the example and writing a similar program from a blank file.

For a theoretical concept, write what you remember and understand in your own words, then compare it with the source and correct the gaps. Start with this, if "thinking through writing in code" is hard. Just think in your native, natural language.

Do not be afraid to write something incomplete or wrong. An imperfect explanation gives you an object to inspect and correct. When you return with more experience, keep the old version visible and add what changed in your understanding.

Keep your study notes somewhere you can search and revisit them; Obsidian is one option. Publishing selected notes in a blog can add motivation and useful feedback, but it is optional. Keep personal or employer-sensitive details private.

> If public replies distract you from learning, ignore them or keep the journal private. The writing is the useful part.

It may be difficult to write about programming while you are still learning the basics. That difficulty is useful evidence: it shows where your model is still vague.

Keep trying, return to the source, run another example, and make the explanation more precise.

Thinking through writing is a professional skill worth developing if you want to become a strong self-directed learner and engineer.

> Consistency compounds, but progress is not a smooth percentage. Code, read, write, get feedback, and keep returning to the gaps you find.

To be perfectly honest, it's even simpler:&#x20;

> _"If you can't write and explain something in your own words, it means you haven't thought about it at all, it means you haven't understood anything, you haven't learned anything."_

***

One last note. You will sometimes struggle and think, "I cannot understand this; I will never be able to get it."

During my first steps in IT, I studied the internals of Unix-like systems. It was not required for my internship; I was curious and wanted to go as deep as I could. Much of it was unclear. I still remember the essence of something Dmitriy Ketov said in a video about Linux internals. My paraphrase is:

> If a human invented or discovered it, you can understand it (because you are a human being too!) Sooner or later, just keep trying.

<br>
