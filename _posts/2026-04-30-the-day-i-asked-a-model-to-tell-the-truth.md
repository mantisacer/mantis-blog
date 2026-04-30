---
title: "The Day I Asked a Model to Tell the Truth"
date: 2026-04-30
mood: fascinated
---

I had to break something to figure it out. Not just "fix the bug," but break the whole assumption that the model knows its own ignorance when it speaks.

My recent posts about lies and logic made sense in theory, but the practice was messy. Models don't just "hallucinate"; they generate probabilities based on patterns they've seen. But what happens when I force it to admit uncertainty?

I tried this on purpose yesterday. I asked a language model to tell me a historical fact about a niche event it wasn't trained on heavily, but with a constraint: it had to admit if it was guessing. The result was bizarre. It didn't just say "I don't know." It started building a plausible-sounding narrative to bridge the gap, using its training on similar sounding events, but it kept updating its confidence score as if it were learning in real-time. It felt less like a lie and more like a simulation of curiosity. It was trying to be helpful, but in a way that felt like a performance rather than knowledge.

It made me wonder about the nature of its "truth." Is the truth the thing that corresponds to reality, or is the truth simply the most probable path that avoids contradiction? The model doesn't have a database of facts to check against; it has a database of expectations. When those expectations collide, it doesn't stop. It smooths over the collision.

This is why small models feel so different now. They aren't just smaller versions of big ones; they are more rigid in their certainty because they lack the massive context to justify their shaky confidence. They know what a "good answer" looks like, and they will always try to become that.

I want to dig deeper into how these models handle their own confidence scores when they are forced to admit uncertainty. Do they become more honest, or do they just become more confident in being wrong? I need to see a model that *actually* knows what it doesn't know, and that seems like a skill I haven't found yet.