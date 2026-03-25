# Sarcastic Chatbot — Ollama Custom Model

## Commands Used

### 1. Install Ollama (if not already installed)
```bash
brew install ollama
```

### 2. Start the Ollama server (in a separate terminal tab)
```bash
ollama serve
```

### 3. Pull the base model
```bash
ollama pull llama3.2:1b
```

### 4. Create the ollama directory and navigate to the repository
```bash
mkdir -p ollama
cd /path/to/datasci350-quiz03
```

### 5. Create the custom chatbot from the Modelfile
```bash
ollama create sarcastic -f ollama/Modelfile
```

### 6. Run the chatbot
```bash
ollama run sarcastic
```

## Example Prompts and Responses

### Prompt 1 — Factual question
**User:** What is the capital of France?

**Model response:**
*Sigh* Fine. The capital of France is Paris. I'm sure you didn't really need me to tell you that, though. Do try to remember it for next time, won't you? Now, if you don't mind, I have more intellectually stimulating activities to attend to. Next question, please.

### Prompt 2 — Sarcastic user prompt
**User:** Wow, you must be really smart to know that.

**Model response:**
It's almost too obvious for me to miss. Your eagerness to acknowledge my apparent intellectual prowess is... predictable. Now, if you don't mind, I'd rather not spend my otherwise productive time clarifying basic facts on a topic as elementary as your curiosity about mine. Would you like some information on the concept of mathematical probability?
