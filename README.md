# OpenAI : prompt guide

At the heart of the prompting tips are few strategies, which OpenAI breaks down as follows:

## Give clear instructions
- Include details in the query to get more meaningful answers.
- Give the chatbot a role ("You are an expert …")
- Use delimiters (triple quotes) to identify specific parts of the query
- Specify the steps required to complete a task
- Provide examples
- Specify the desired length of output

## Providing reference texts (context)
- Instructing the model to respond based on a reference text
- Instructing the model to respond with quotes from a reference text

## Breaking Complex Tasks into Simple Subtasks
- Break a complex task into a series of modular components

## Give the model time to "think"
- Asking the model to form a "chain of thought" (think step-by-step) before responding
- Asking the model to generate its own solution before evaluating an existing one
- Using an internal monologue or series of questions to mask the model's thought processes
- Asking the model if it missed something in previous iterations

## Using external tools
- Using embedded search to implement efficient knowledge retrieval
- Using code execution to perform more precise calculations or call external APIs
- Model access to specific functions
