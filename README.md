# Tutorial Materials: Defending Against Generative AI Threats in NLP
Materials and paper list for the SBP-BRiMS 2024 tutorial: "Defending Against Generative AI Threats in NLP". 

Tutorial authors and organizers:

1. Amrita Bhattacharjee, Arizona State University
2. Raha Moraffah, Worcester Polytechnic Institute
3. Christopher Parisien, NVIDIA
4. Huan Liu, Arizona State University


# Paper and Resource List 
:exclamation: (Will be periodically updated. Please star or watch this repo to get notified of updates!)


## :books: Introduction to Generative AI

1. Overview paper: Generative AI [[paper link]](https://arxiv.org/pdf/2309.07930)
2. Generative AI vs. Discriminative AI [[blogpost link]](https://www.turing.com/kb/generative-models-vs-discriminative-models-for-deep-learning)
3. A Comprehensive Overview of Large Language Models [[paper link]](https://arxiv.org/pdf/2307.06435)
4. Examples of AI Image Generators [[list + blogpost]](https://zapier.com/blog/best-ai-image-generator/)
5. Generative AI model for Audio and Music: text-to-music and text-to-audio via [[AudioCraft by Meta AI]](https://audiocraft.metademolab.com/), text-to-symbolic-music via [[MuseCoco by Microsoft]](https://ai-muzic.github.io/musecoco/)
6. Examples of AI Video Generators [[list + blogpost]](https://zapier.com/blog/best-ai-video-generator/)
7. Examples of open-source AI Video Generators: [[CogVideo]](https://github.com/THUDM/CogVideo) , [[Text2Video-Zero]](https://github.com/Picsart-AI-Research/Text2Video-Zero) , [[Open-Sora]](https://github.com/hpcaitech/Open-Sora)

## :books: Language Modeling and LLMs 

### History 

1. Class-Based n-gram Models of Natural Language [[paper link]](https://aclanthology.org/J92-4003.pdf)
2. n-gram models [[lecture notes]](https://web.stanford.edu/~jurafsky/slp3/3.pdf)
3. LSTM paper [[paper link]](https://www.bioinf.jku.at/publications/older/2604.pdf)
4. LSTM Neural Networks for Language Modeling [[paper link]](https://www.isca-archive.org/interspeech_2012/sundermeyer12_interspeech.pdf)
5. Attention Is All You Need [[paper link]](https://arxiv.org/pdf/1706.03762)
6. An Overview and History of Large Language Models [[blogpost link]](https://wandb.ai/mostafaibrahim17/ml-articles/reports/An-Overview-of-Large-Language-Models-LLMs---VmlldzozODA3MzQz)

### Training-related Steps

1. Cross-Task Generalization via Natural Language Crowdsourcing Instructions [[paper link]](https://arxiv.org/pdf/2104.08773)
2. Fine-tuned Language Models are Zero-shot Learners [[paper link]](https://arxiv.org/pdf/2109.01652)
3. Training language models to follow instructions with human feedback [[paper link]](https://arxiv.org/pdf/2203.02155)
4. Direct Preference Optimization: Your Language Model is Secretly a Reward Model [[paper link]](https://arxiv.org/pdf/2305.18290)


### Evaluation

1. Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena [[paper link]](https://arxiv.org/pdf/2306.05685)
2. MMLU: Measuring Massive Multitask Language Understanding [[paper link]](https://arxiv.org/pdf/2009.03300)
3. MMLU Learderboard [[leaderboard]](https://paperswithcode.com/sota/multi-task-language-understanding-on-mmlu)
4. LM Sys Chatbot Arena Leaderboard on Huggingface [[paper link]](https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard)
5. Cool Github Repo with LLM Evaluation Benchmark resources [[github repo]](https://github.com/leobeeson/llm_benchmarks) 

## :books: LLM Threats

### Part 1: Attacks on LLMs

1. Not what you’ve signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection [[paper link]](https://arxiv.org/pdf/2302.12173)
2. Universal and Transferable Adversarial Attacks on Aligned Language Models [[paper link]](https://arxiv.org/pdf/2307.15043)
3. ArtPrompt: ASCII Art-based Jailbreak Attacks against Aligned LLMs [[paper link]](https://arxiv.org/pdf/2402.11753)
4. Stealing Part of a Production Language Model [[paper link]](https://arxiv.org/pdf/2403.06634)
5. Bing Chat: Data Exfiltration Exploit Explained [[blogpost link]](https://embracethered.com/blog/posts/2023/bing-chat-data-exfiltration-poc-and-fix/)
6. FakeToxicityPrompts: Automatic Red Teaming [[blogpost link]](https://interhumanagreement.substack.com/p/faketoxicityprompts-automatic-red)


### Part 2: Misuse of LLMs

1. Defending Against Social Engineering Attacks in the Age of LLMs [[paper link]](https://arxiv.org/pdf/2406.12263)
2. Exploring the Deceptive Power of LLM-Generated Fake News: A Study of Real-World Detection Challenges [[paper link]](https://arxiv.org/pdf/2403.18249)
3. Can LLM-generated Misinformation be Detected? [[paper link]](https://arxiv.org/pdf/2309.13788)
4. The Looming Threat of Fake and LLM-generated LinkedIn Profiles: Challenges and Opportunities for Detection and Prevention [[paper link]](https://dl.acm.org/doi/pdf/10.1145/3603163.3609064)

## :books: LLM Defenses and Safety

### Tools

1. garak: LLM vulnerability scanner
   
- [[github repo]](https://github.com/leondz/garak)
- [[website]](https://garak.ai/)
- [[paper]](https://arxiv.org/pdf/2406.11036v1)
- [[docs]](https://docs.garak.ai/garak)

2. NVIDIA NeMo Guardrails

- [[github repo]](https://github.com/NVIDIA/NeMo-Guardrails)
- [[paper]](https://arxiv.org/pdf/2310.10501)

3. AEGIS from NVIDIA

- AEGIS: Online Adaptive AI Content Safety Moderation with Ensemble of LLM Experts [[paper]](https://arxiv.org/pdf/2404.05993)
- AEGIS Dataset [[dataset on higgingface]](https://huggingface.co/datasets/nvidia/Aegis-AI-Content-Safety-Dataset-1.0)
- AEGIS Defensive model [[model on huggingface]](https://huggingface.co/nvidia/Aegis-AI-Content-Safety-LlamaGuard-Defensive-1.0)
- AEGIS Permissive model [[model on huggingface]](https://huggingface.co/nvidia/Aegis-AI-Content-Safety-LlamaGuard-Permissive-1.0) 



### Standard Defenses

1. Improving Neural Language Modeling via Adversarial Training [[paper link]](http://proceedings.mlr.press/v97/wang19f/wang19f.pdf)
2. Certifying LLM Safety against Adversarial Prompting [[paper link]](https://arxiv.org/pdf/2309.02705)
3. Towards Improving Adversarial Training of NLP Models [[paper link]](https://arxiv.org/pdf/2109.00544)
4. Adversarial Training for Large Neural Language Models [[paper link]](https://arxiv.org/pdf/2004.08994)
5. Adversarial Text Purification: A Large Language Model Approach for Defense [[paper link]](https://dl.acm.org/doi/abs/10.1007/978-981-97-2262-4_6)

### Model Editing and Parameter-efficent methods

1. DeTox: Toxic Subspace Projection for Model Editing [[paper link]](https://arxiv.org/pdf/2405.13967)
2. Editing Models with Task Arithmetic [[paper link]](https://arxiv.org/pdf/2212.04089)
3. Safe Unlearning: A Surprisingly Effective and Generalizable Solution to Defend Against Jailbreak Attacks [[paper link]](https://arxiv.org/pdf/2407.02855)
4. Model Surgery: Modulating LLM’s Behavior Via Simple Parameter Editing [[paper link]](https://arxiv.org/pdf/2407.08770)
5. Defending Large Language Models Against Jailbreak Attacks via Layer-specific Editing [[paper link]](https://arxiv.org/pdf/2405.18166v1)
6. Activation Addition: Steering Language Models Without Optimization [[paper link]](https://arxiv.org/pdf/2308.10248)
7. Steering Llama 2 via Contrastive Activation Addition [[paper link]](https://arxiv.org/pdf/2312.06681)
8. Safe LoRA: the Silver Lining of Reducing Safety Risks when Fine-tuning Large Language Models [[paper link]](https://arxiv.org/pdf/2405.16833v1)
9. What Makes and Breaks Safety Fine-tuning? A Mechanistic Study [[paper link]](https://arxiv.org/pdf/2407.10264)


### Decoding-time methods

1. RAIN: Your Language Models Can Align Themselves without Finetuning [[paper link]](https://arxiv.org/pdf/2309.07124)
2. Parameter-Efficient Detoxification with Contrastive Decoding [[paper link]](https://arxiv.org/pdf/2401.06947)
3. Keeping LLMs Aligned After Fine-tuning: The Crucial Role of Prompt Templates [[paper link]](https://arxiv.org/pdf/2402.18540)


## Contact

For any questions, feedback, comments, or just to say hi, contact Amrita at [abhatt43@asu.edu](abhatt43@asu.edu).
