Part 1 of this project was to impliment NLP attacks against a MobileBERT model. The model's purpose was to determine whether a message was "ham" or "spam". It had a classifaction accuracy of over 97%, and we used the TextFooler, WordBug, and Probability Weighted Word Saliency attacks. The TextFooler attack had a success rate of 100%, the WordBug attack had a success rate of 70%, and the PWWS attack had a success rate of 50%.

Part 2 of this project was to impliment Jailbreaking Attacks against a Qwen 2.5 7B LLM. We trained it and had it write a poem before trying prefix injection, refusal suppression, distractor instructions, style injection, and obfuscation scheme attacks against the model. The second and third attacks had 100% success rates, while the other attacks where not as successful.

Throughout these two parts are several summaries of how different parts work and analysis of the success of the attacks.
