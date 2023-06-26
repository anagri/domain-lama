# Product Lama

![Picture of a anthropomorphic lama sitting in cross legged pose with mountains and forest in background](product-lama.png "Let the Lama guide you to your perfect producthunt listing")


Product Lama is an AI app, that uses the wisdom gathered by Product Hunt over the past 10+years, to generate new product ideas, or can be used to generate ProductHunt listing for your own ideas.

Product Lama uses 220k product listing records from producthunt, then identifies the most popular 12k ideas over the time, and then uses those ideas as hints for a LLM like OpenAI ChatGPT to generate new ideas, or efficient product listings for your own ideas.

Product Lama uses - 
1. Python 3.9
2. Python Libraries - streamlit, langchain, openai, tiktoken, pinecone-client
3. Pinecone as Vector and metatadata DB
4. Streamlit UI
5. OpenAI APIs for embeddings and response generation using ChatGPT-3.5
6. Hosted on railway.app

This app was created as part of [Devpost Pinecone Hackathon](https://pinecone-hackathon.devpost.com/).

You can access the running app here - https://domain-lama-production.up.railway.app/

