# LLM-Reasoning-Research
Awesome research into reasoning capacities of LLMs

Why is a single prompt like 'let's think step by step' gives better result? What makes Chain of Thought Prompting effective instead of asking a direct answer? Is LLM actually performing reasoning? 

This paper sheds light on a potential explanation in my opinion: LLM is doing approximate retrieval. And reasoning performace between iterative prompting and top-k completions are very similar, moreover, iterative prompting with human-corrected feedback has similar effect as a pure 'try again' prompting. This implies that instead of 'reasoning', LLM is 'choosing' among the top-k candidate through approximate retrieval. And the 'let's think step by step' spell mostly triggers the candidate answer which appears to be more inter-connected with other relavent information around the subject.


1. GPT4 Doesn't know it's wrong
https://arxiv.org/pdf/2310.12397.pdf

