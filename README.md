# structured-prompts
Collection of structured prompt examples from personal projects.

##When-Familiar 

WhenFamiliar is a therapy chatbot project that leverages emotional state tracking across conversation, and feeds user sentiment back to the model to guide therapuetic tact. A model fine-tuned on Big 5 Personality essay data assists in tracking sentiment-density across Openness, Conscientiousness, Extraversion, Agreeableness, and Neuroticism (OCEAN scores) dimensions.

WhenFamiliar.md is an LLM prompt that enables chatbots to provide therapuetic support and track user sentiment across conversation. This prompt was developed to a) compare discretion and accuracy on sentiment detection between LLMs and b) label LLM-guided therapy transcripts to train future models. For transparency and memory persistence, the prompt urges the LLM to output this label after each user's message. 

DATA: [O:x.xx,C:x.xx,E:x.xx,A:x.xx,N:x.xx][CState:word,PState:word][Engage:type,x.xx][Def:type,x.xx][Band:x.xx]

This project is partially-retired due to limitations in voluntary transcript donations, though users have reported satisfaction with the prompt (and score-tracking) for personal use.

##LLM-Orchestra

OpenAI's release of Deep Search in early 2025 inspired me to integrate the model into a structured expert-in-the-loop (XITL) pipeline due to reported variances in user experience. The more informed about a topic a user was (and the more familiar they were with LLMs), the more practical Deep Search's insights were. While this is an intuitive conclusion, there is significant upskilling potential by automating the generation of Deep Search queries by treating user statements as a Source of Truth for intention while LLMs construct prompts based on pre-made epistemic templates.

This research was summarized in the following white paper: https://drive.google.com/file/d/1Ga27g1WGk3QcY4vB8kJK_uk9XhlvxcDC/view?usp=sharing
