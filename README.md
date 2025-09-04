Purpose of this project: Creating my own version of ChatGPT Copilot or Amazon Q equivalent

## How it works:

1. Accepts a coding task (e.g. "strings aren't splitting in my app.. Please fix")
2. Chooses from a set of predefined functions to work on the task.
   - Scan the files in a directory
   - Readd a file's contents
   - Overwrite a file's contents
   - Execute a python interpreter on a file
3. Repeat step 2 until the task is complete (or it fails miserably, which is possible)

## Description:

1. Multi-directory Python project
2. Understand how the AI tools that I'll most certainly use on the job actually work under the hood
3. Practice Python and functional programming skills
4. Not simply a response from trained data, but provide responses in live by either via API call or web browsing.

## Takeaways:

1. Make sure to write good (readable) error messages because LLM is also learning from it.
2. System prompt sets the tone for the conversation, and can be used to set the personality of the AI, set the "rules" for the conversation, etc.
3. LLM doesn't call a function I've created in functions folder. Rather, we tell LLM which functions are available. LLM is a decision-making engine, but I'm still the one running the code.
