# CS 452 Project

**Project: Gospel Library AI Search Engine**

The goal of this project is to create an AI-powered search engine for Gospel Library that allows users to ask natural-language questions instead of searching by keywords. The application will search scriptures, General Conference talks, Church manuals, and other resources, then provide a brief AI-generated summary along with relevant references and links to the original materials. It is possible that legally I cannot use those resources for the church. If not possible, I will pivot to use other resources, such as RSC materials, Joseph Smith Papers, and FairAnswers.org to compile more of a controversial church question chatbot. We will see which way I go!

**Technologies:** TypeScript, Next.js, Supabase (PostgreSQL), and an AI API.

**Main Goals:**
- Build a ChatGPT-style search interface.
- Store and organize searchable Church materials.
- Implement AI-powered semantic search.
- Generate summaries with accurate citations and references.

**MVP:** A working web application that can search a small collection of approved Church materials and return relevant resources with AI-generated summaries.

**Diagram** Rough Diagram of ideas

<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/6270c07a-f08c-4b83-9b34-24b0a84f7477" />

**Explanation**
SupaBase and PostreSQL will be used to hold embedings. It will parelell the RAG project in that structure. Instead of storing the whole text, we talked about possibly just storing the URL of the sources so as to maximize database space. Above I have a the rough sketch of how to store conversations, messages, and user interactions so as to save conversations.

***Possible UI Implementations***

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/c8bf92c2-61dd-4995-a6b6-6c5c63531314" />

![Uploading image.png…]()
