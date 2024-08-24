# LLM Project - DataTalks Zoomcamp Questions Answering
**The purpose of this project is to create a AI chatbot to answer courses-related questions from people who are interested in those three courses(data engineering, machine learning and mlops zoomcamps).**

**Step:**
1. Enter your question
2. Select a model
3. Select search type
4. Enter your questions
5. Click Ask

![Animation6](https://hackmd.io/_uploads/HJbqhS_qR.gif)


## Features
* Users can select the course they are interested in.
* Users can select the LLM model they want to use. There are 4 models provided including **phi3, gpt-3.5-turbo, gpt-4o and gpt-4o-mini**.
* Users can select one of the search types. One is text search and another is vector search.
* Users can give the bot a feedback about the answer by clicking +1(positive) or -1(negative) buttons.
* The bot also provides recent conversations for users to review.
* Feedback statistics

## Methodology
![LLM - Courses questions answering](https://hackmd.io/_uploads/BkAEsUuqR.jpg)


## Built With
* **Elasticsearch** - to search related data from the knowledge base
* **Open AI API** - use **gpt-4o, gpt-4o-mini, gpt-3.5-turbo** models to find the best answer based on the search result from Elasticsearch.
* **Ollama** - import **phi3** model.
* **Streamlit** - web app library
* **Grafana** - monitor the app running status including response time, feedback statistics, relevance distribution, model usage, token usage, cost of open ai api, 
* **Docker** - containerize all services
* **Language** - Python, SQL

## App monitoring dashboard
![image](https://hackmd.io/_uploads/ByLcYd_qR.png)



## Roadmap

- [x] Set up elasticsearch and index
- [x] Created a RAG
- [x] Imported 4 LLM models
- [x] Stored app running data in PostgreSQL
- [x] Created dashboard for monitoring


<!-- CONTACT -->
## Contact

Sean Liu - [LinkedIn](https://www.linkedin.com/in/sean-liu-65bbb8b2/) - sean.liu.job@gmail.com

Project Link: [https://github.com/Sean-Liu-GitHub/datatalks-courses-questions-answering-bot](https://github.com/Sean-Liu-GitHub/datatalks-courses-questions-answering-bot)

## Reference
* [DataTalks Club](https://datatalks.club/) - [LLM Zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp)
