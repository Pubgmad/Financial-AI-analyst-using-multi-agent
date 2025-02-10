FINANCIAL AI ANALYST

The code which I  have implemented is the financial_agent when we use multi agents to to specific tasks like web searching a specific agent is used, for financial analysis another agent is used.
POPULAR FRAMEWORK USED:PhiData
FOR EASY ACCESSING LLM:Groq
LLM:OpenAI

DuckDuckGo-agents can search ie web search can be done here .
yfinance-popular container for all financial information

STEPS:
1) Install athe requirements by the command:
   pip install -r requirements.txt

2) create a file named financial_agent.py and implement the coding part

3) create a file named playground.py and implement the coding part.Playground is nothing but ac as a interface to show on phidata web site itself instead of displaying the output in normal terminal.

4) Get all the api keys form the official we sites of Phidata.com , Groq.com ,openai.com

5) store all the keys in .env ,later while pushing in github the api key wont be displayed to the audiences.

6) in terminal type  as :
             setx GROQ_API_KEY "paste the api key of groq"
             setx OPEN_API_KEY "paste the api key of openai"
             setx PHI_API_KEY "paste the api key of phidata"

7) to view the output type the command as:
            
            py playground.py

8) in this you will get a localhost:7777 which is default, then go to phi data web site and enable the permissions of localhost 7777.

9) output will be displayed.
             




