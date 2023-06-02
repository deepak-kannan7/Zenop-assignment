# Token-Healing-in-Python

My Work Flow in the 12 hours given: 

Hour 0-1: Deciding on which question to attempt, read through the problem statements and decided to take up token healing because it is an NLP project which is my field of interest. 

Hour 1-2: After getting a basic idea of the concept of token healing, I tried to implement a very simple version of token healing which is TokenHealingTry.ipynb. A brute force version where just the wrong words are replaced by the correct ones directly because the input is known.

Hours 2-4: Opened Microsoft Guidance documentation and read through it. I read through how neural networks like BERT were used in embedding to capture syntactic and semantic properties of token. 

Hours 4-6: Tried to code using NLTK with corpus and tokenize. Got a pretty decent level of accuracy with different type of texts. Solved most of the spell errors in tokens. Put my code on chatgpt and told it to try optimizing it. This code is in TokenHealingNLTK.ipynb. 

Hour 6-7: Tried running the optimized chatgpt code using fuzzywuzzy, accuracy was pretty decent and was similar to my original code. When prompted again to use a different library, it used language-tool-python and gave a code which gave very erratic outputs. Decided to go ahead with my original NLTK code, after all humans also have a good brain.

Hours 7-9: Queried chatgpt about what Hugging Face and transformers were because I had no idea, got it to write token healing codes using transformers, it gave very erroneous codes so I had to keep asking it to rectify the errors I was getting, one of the code took 30 minutes to run so I asked it to give optimized solutions. These codes are in TokenHealingTransformers.ipynb but most of the codes did not give the desired outputs. Overall, the attempt using transformers was not going well because I did not get correct outputs even for simple spell errors unlike the NLTK method. 

Hour 9-11: Searched on how to handle grammatical errors and how it was done in GUIDANCE. Read about the GECToR model used by Grammarly and saw their GitHub repo. I queried chatgpt to write a code using GECToR after cloning the Grammarly repo but still it didnt work because of some error. I learnt about some other methods to handle grammatical errors like Statistical Machine Translation, Neural Machine Translation and Sequence Labeling. I tried implementing these but my efforts were only in vain. The codes are available in GrammaticalErrorHandling.ipynb. 

Hour 11-12: Uploaded code on my GitHub repo, wrote this report, setting up the PR and submission. 

I would like to thank Mr.Anurag Bisoyi and openAgent(Zenop) for selecting me in the first round and giving me the opportunity to do this project. NLP was a domain I really wanted to explore and I have learnt so much about this domain in only 12 hours, thanks to this project. Now that the 12 hours are over, I am motivated to improve upon this project, rectify all the errors and create a good model for token healing to solve all types of errors.
