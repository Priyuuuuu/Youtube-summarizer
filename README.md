# YouTube Summarizer

## Project Overview

The **YouTube Summarizer** project is a Streamlit-based application designed to provide users with an efficient way to understand a topic by summarizing content from YouTube videos. Users can input a topic or keyword, and the AI-powered system retrieves the transcripts of the top 5 related YouTube videos, combines their content, and generates a concise and informative summary.

---

## Features

- **Topic-Based Search**
  - Users can enter a topic or keyword to search for related YouTube videos.

- **Transcript Retrieval**
  - Fetches the transcripts of the top 5 YouTube videos relevant to the input topic.

- **Content Summarization**
  - Combines the transcripts and generates a single cohesive summary using advanced AI summarization techniques.

---

## Technologies Used

- **Frontend**: Streamlit
- **Backend**: Python
- **APIs**: YouTube Data API, YouTube Transcript API
- **AI Tools**: Google Generative AI (Gemini), Natural Language Processing (NLP) 

---

## Project Workflow

1. **Input Topic**:
   - User provides a topic or keyword in the Streamlit interface.

2. **Fetch YouTube Transcripts**:
   - Retrieves the transcripts of the top 5 relevant YouTube videos using the YouTube Transcript API.

3. **Combine Transcripts**:
   - Merges the transcripts into a single document.

4. **Summarize Content**:
   - Uses AI-powered NLP models to generate a concise summary of the combined transcripts.

5. **Display Results**:
   - Presents the summary and optionally the individual video transcripts in the Streamlit interface.

---

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Priyuuuuu/Youtube-summarizer
   ```
   
2. **Install dependencies**

3. **Run the application**:
   ```bash
   streamlit run app.py
   ```
   
---

