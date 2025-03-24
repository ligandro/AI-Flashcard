# 📚 AI-Flashcard: Smart Flashcard Creator  

AI-Flashcard is a web-based tool that transforms YouTube videos and online articles into interactive flashcards using AI.

## ✨ Features  

- 📝 **Article Summarization** – Convert blog posts and articles into flashcards.  
- 🎥 **YouTube Video Support** – Extract key points from video transcripts and turn them into flashcards.  
- 🔄 **Flip Animation** – Smooth transition between questions and answers.  
- 🔢 **Custom Flashcard Count** – Generate any amount of flashcards per run.  
- ⚠️ **Error Handling** – Displays clear messages for invalid URLs or processing failures.  
- 📝 **Ollama** – Uses Ollama system and model used is Mistral  7B

## 🚀 Installation  

1. **Clone Repository**
```bash
git clone 
cd AI-Flashcard
```

2. **Install Dependencies**
```bash
pip install -r requirements.txt
```

3. **Config Ollama**

```
- ollama pull mistral
``` 

4. **Start** 

```bash
python app.py
```

![Flashcard Demo]()


## ✨ Note  

- Sometimes json error may show up on first try. Rerun to get correct output. 
- Some youtube videos and articles may not be suitable for this as they may not have captions or the article site may be in unprocessable format.
- You need to have ollama setup on your system
