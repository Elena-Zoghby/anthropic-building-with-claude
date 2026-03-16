# anthropic-building-with-claude
Exercises from the course Building With Claude by Anthropic Academy

# Exercise 1 - Chatbot
Using the multiturn conversation code, we were able to build a basic chatbot using the API key for claude agent sonnet.

# Exercise 2 - System Prompt
We showed how important it is to include a system prompt to the chatbot effectively.

# Exercise 3 - Temperature Effect
Temperature defines the randomness of the model. Try increasing and decreasing the temperature to visualize the model's output in each case.

# Exercise 4 - Streaming
Streaming enhances user's experience by streaming data chunk by chunk rather than as a whole. It hides the delay that usually happens when we request a response from the AI.

# Exercise 5 - Control Model Output
Did you know that you can control an AI's output message by providing it with prefilled messages or stop sequences? By controlling the provided output, you can make the model's response biased or of consistent length.

# Exercise 6 - Prompt Evaluation
Just because your prompt worked once, doesn't mean it's going to work always. Check out the different techniques used to evaluate a prompt (code based, model based..) in the notebooks provided.

# Exercise 7 - Prompt Engineering
Prompt engineering is a technique used to refine prompts to generate better outputs. To do this, we can provide input-output examples (one-shot, multi-shot), be clear and direct, and include XML tags in our prompts. 

# Exercise 8 - Tool Use
What seperates an AI agent from a chatbot is its ability to handle dynamic data. By importing tool functions, we allow our model to retrieve live information (weather, browsing websites,...) making it a dynamic model or agent.

# Exercise 9 - RAG
To be able to analyze 1000 pages in a document, Claude uses the RAG technique. This technique consists of splitting the document into multiple chunks, rather than taking it as a whole, using different techniques. Check out the scripts to learn more!

# Exercise 10 - Features in Claude
Claude has multiple features: extended thinking, images and pdf processing, prompt caching and citations. Discover the code snippets to learn more about how we implement such features in our code.
