# Meeting Minutes Generator 🎙️📝

An AI-powered tool to transcribe audio recordings of meetings and generate structured minutes with summaries, action items, and owners.

## Features

- **Audio Transcription**: Converts meeting audio (e.g., council sessions) to text using OpenAI Whisper.
- **AI Summarization**: Uses Meta's Llama 3 to extract key points, attendees, and decisions.
- **Action Items**: Identifies tasks with assigned owners.
- **Markdown Output**: Formats minutes for easy sharing/version control.

## Tech Stack

- **Python** (Transformers, HuggingFace, OpenAI)
- **Meta Llama 3** (8B Instruct) for summarization
- **OpenAI Whisper** for audio-to-text
- **Google Colab** (GPU-accelerated)

## Usage

1. Upload an audio file (e.g., `denver_extract.mp3`).
2. Run the notebook to:
   - Transcribe audio → Text
   - Generate minutes with:
     - Attendees
     - Discussion points
     - Action items (with owners)
     - Takeaways

## Example Output


**Minutes of Denver City Council**  
**Date:** Oct 9, 2023  
**Attendees:** Councilman Lopez, Ortega, Kinnech, etc.  

### Key Points  
- Proclamation #1127: Indigenous Peoples Day  
- Confluence Week symbolism (water/land themes)  

### Actions  
✅ Adopt Proclamation | Owner: Lopez  
📢 Promote Indigenous Day | Owner: Martega  
