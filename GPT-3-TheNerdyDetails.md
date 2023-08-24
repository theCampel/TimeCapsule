# ChatGPT - The Nerdy Details:

Experts of specific fields realised that ChatGPT (GPT-3.5) was really just blowing hot air when it spoke about a topic. Too often it made up information (_hallucination_ - a problem I expect to be a thing of the past by 2030), broke past its guardrails (gave harmful information if prompted correctly) or even just forgot what was discussed almost immediately after it was said (short _context window_). 

A few months later, GPT-4 rolled around… for $20 a month. GPT-4 almost completely eradicated the first 2 main errors GPT-3.5 had (GPT-4 also had a much longer context window, about 25k words). The problem? Because it’s paid, very few consumers see it worth the investment when you can get “_good enough_” answers from GPT-3.5 for free (businesses use the GPT-3.5 fine-tuned models with great success).
 
ChatGPT works using a type of algorithm called a _Transformer_. By slightly optimising the original algorithm and feeding it _ungodly amounts of data and computational power_ (as well as getting real humans to rank the outputs), OpenAi was able to produce ChatGPT (after some promising successes from GPT-1 and GPT-2). 

The name of the game is just feeding transformers _more compute_ (computational power) (_Note: This has been somewhat of a bitter-sweet note for scientists in the field. They realised that you didn’t need the smartest people to design an even better architecture than the transformer. You just need to feed it more data, wayyyy more compute and reinforce the answers you like_). For the past 5 years, the amount of compute power used to train these models has increased _by a factor of 2 every 6 months_. In other words, we **_double_** the amount of **_computational power_** **_every 6 months_**. What’s most astonishing, it doesn’t look like it’s slowing down. So by 2030, we will have _2^14_ times the compute we have today to train our most advanced models. 

If we can already generate text well enough for a lot of use cases, why keep pumping resources into transformers? Cue the idea of _emergent properties_. This is the idea that we can teach a model the rules of something, not by feeding it the rules, but by feeding it enough examples. Imagine feeding GPT-5 enough examples of times-tables that it eventually learns the rules of multiplication. 

With GPT-2, we taught the transformer “basic” relationships between specific words using a “small” amount of training data (a bunch of books and ~8M webpages). The discovery was that though it was designed to predict the next word in a sentence, it was actually able to detect sentiment in a piece (think writing ‘the woman was’ and the transformer finished it with ‘happy’). Sentiment detection was an _emergent property_ they found in GPT-2. 

With GPT-4’s astonishing dataset, it’s learned (some) logic and reasoning, but it’s still not human levels of reasoning. The rules of maths say that at some point these properties will emerge, but it’s not exactly clear which property and at what point. 

It’s also not clear if it’ll be the Transformer architecture that gets us there. But with the rate at which advancements are happening, simple text dialogues like I described in the story are all but inevitable. 
