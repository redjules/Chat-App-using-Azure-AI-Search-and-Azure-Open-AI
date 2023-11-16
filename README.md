# Chat App using Azure AI Search and Azure Open AI

Go to Azure AI Services and AI search:
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/3c3f6539-f197-40a3-a9c7-950646b19239)

Click create a search service

![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/0ac83bf4-6d4c-401f-8c79-f8100c8ce35c)

Go to Kaggle to download the dataset: Customer Support Ticket Dataset

![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/d1738e14-67ea-448d-a5c1-6f4f58bc9882)
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/84e43674-f051-407e-bb8d-4531fcc74361)


We go to Create Index, id to create TicketID, TicketType, TicketSubject, Ticket description:
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/4432b679-b16e-4039-84ab-68f7586dae4e)

![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/c2a8f53f-bff2-4cf4-ab1f-88651486c270)

![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/f71bba7a-69e0-4082-902a-ad60caa8f319)

In VS Code we create a python script called indexing.py:
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/e7d693ee-d605-43bf-902b-52796695a57f)
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/d68d6916-4650-4ad7-b603-b3e8d784db5a)

Activate langchain in the terminal:
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/d09d4555-46c0-4b68-9395-04be13927eb4)

we write a query in mydata_index:
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/d4e7a654-baab-4e57-826f-ee2ecb4e3475)
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/7d20f94b-5ca2-4ca1-8494-d69a5e7e18f5)

Go to Azure OpenAI:
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/bc4227f3-e5e4-4e1b-87a6-605068cdbf71)
and create a resource

Go to Azure AI Studio and deployments:
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/6aeb5e0e-456a-4b1b-95b3-86279371de67)

Go to Azure AI Studio and Chat playground and add a data source.

We test now the chat:
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/aa77d5be-ed0b-4b26-90c3-32d389febf36)

We deploy to a web app and launch web app:
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/f4470384-bb2e-4b0a-b471-5d74ee800deb)
![image](https://github.com/redjules/Chat-App-using-Azure-AI-Search-and-Azure-Open-AI/assets/106017493/b98e1259-0540-4e28-9d9d-3f86c73aa5d7)


and the Azure Chatbot works!

