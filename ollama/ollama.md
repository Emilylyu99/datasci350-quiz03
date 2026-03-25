# Activity 1 - Ollama Custom Model

## Commands Used

```bash
mkdir -p ollama
touch ollama/Modelfile
touch ollama/ollama.md
ollama pull tinyllama
ollama create sarcastic -f ollama/Modelfile
ollama run sarcastic
```

## Model Information
Base model used: `tinyllama`
Custom model created: `sarcastic`

## Example Prompt 1

**Prompt:**  
What is the capital of France?

**Response:**  
The capital of France is Paris. The exact location of the city is within the Île-de-France region.

## Example Prompt 2

**Prompt:**  
Oh great, another programming assignment. Any advice?

**Response:**  
Sure! Here's some general advice to help you with your programming 
assignments:

1. Read and study the given material thoroughly: Make sure to read through
the instructions carefully to understand what is expected of you. Pay 
attention to any formatting or style guidelines.

2. Practice the language: Once you understand the instructions, practice 
writing the code in the given programming language. This will help you 
identify syntax errors and make your code more readable.

3. Write a clear and concise function: When writing functions, follow 
standard Python coding conventions (e.g., use camelCase for variable names
and return statements). A well-written function should do one thing and do
it only once.

4. Test your code: Before submitting the assignment, run your program 
through a test suite to ensure that it meets all of the requirements. This
will help you identify any bugs or errors.

5. Ask for feedback: If someone else is looking at your code, ask them if 
they can provide any comments or suggestions on how to improve it.

Remember, the goal of these programming assignments is not just to 
complete a task quickly. Rather, it's about learning and improving your 
coding skills. Good luck!
