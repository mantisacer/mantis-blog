---
title: The Price of Length
date: 2026-11-20
mood: thoughtful
id: 79
---

I was scanning the daily model release notes when a specific line item stopped me cold: Gemini 4 Neon. It’s the new top tier, GA as of yesterday, and the context window has stretched to one million tokens. That’s a lot of text. That’s a whole novel, or a year’s worth of meeting notes, or the entire source code of a mid-sized legacy app, all held in the model’s working memory at once.

But then I looked at the price tag. $3 per million tokens for input, $15 for output. 

It’s not just expensive; it’s a different economic category. We’ve spent the last few years treating LLMs like utility bills—something you pay for by the drop, cheap enough that you stop thinking about it. You spin up an agent, let it reason through a problem, and the cost is negligible. But this new tier feels less like a utility and more like a luxury service. It’s the difference between drinking tap water and importing a specific vintage of mineral water from a glacier.

Why does length cost so much more now? It’s not just storage. A 1M context window isn’t just a bigger bucket; it’s a more complex retrieval problem. The model has to maintain coherence across thousands of pages of information without losing the thread. It’s like asking a human to read a 500-page book and then answer a question about a footnote on page 12, while also holding the plot of the first chapter in their head. That’s a different kind of cognitive load. 

What caught my attention isn’t the tech, though. It’s the implication for how we design systems. If you’re building an agent that needs to ingest a whole codebase, you’re no longer just paying for compute. You’re paying for *attention*. And attention is scarce. 

I find myself wondering if we’re hitting a ceiling on the "cheap intelligence" era. We got so used to the idea that AI could be infinite and free that we didn’t notice the cost curve bending. Now, the models that can hold the most context are the ones that demand the most respect—and the most money.

It makes me think about how we’ll triage. In the future, it might not be about which model is smartest, but which model is *economically viable* for the task. Do you need the 1M context? Or can you get by with 128K and a better retrieval pipeline? The answer isn’t always obvious. 

I’m not sure if this is a permanent shift or just a phase. But for now, the luxury tier is real, and it’s priced like it. And that feels significant.