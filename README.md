# Yardstick
Task 1: Managing Conversation History with Summarization
1. Maintain a running conversation history of user–assistant chats.
2. Implement summarization of conversation history to keep it concise.
3. Allow customization options for truncation:
a. Limit by number of conversation turns (e.g., last n messages).
b. Limit by character/word length.

4. Add periodic summarization:
a. Perform summarization after every k-th run of the conversation.
b. Store/replace the summarized version in the conversation history.

5. Demonstrate the functionality by:
a. Feeding multiple conversation samples.
b. Showing outputs at different truncation settings.
c. Showing how summarization happens after every k-th run (e.g., after every 3rd run).

Task 2: JSON Schema Classification & Information Extraction

1. Create a JSON schema to extract 5 details from chats related to information collection (e.g., name, email, phone, location, age).

2. Use OpenAI function calling with Groq API for structured outputs.

3. Demonstrate:
a. Parsing of at least 3 sample chats.
b. Validation of outputs against the schema.
