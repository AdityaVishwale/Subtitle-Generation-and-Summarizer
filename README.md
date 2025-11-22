# Subtitle-Generation-and-Summarizer
Automated Subtitle Generation &amp; Video Lecture Summarization using Whisper + T5
- This project automates the end-to-end process of generating subtitles and concise summaries for educational video lectures. It is designed for ed-tech platforms that upload multiple videos every month and need fast, accurate, and scalable AI assistance for accessibility and student engagement.
- The system extracts audio from lecture videos using FFmpeg, performs high-accuracy speech-to-text transcription using Whisper (OpenAI), generates timestamped .srt subtitle files, and produces clean 3–5 sentence summaries using state-of-the-art NLP models such as BART or FLAN-T5. The solution includes evaluation metrics such as WER (Word Error Rate) for transcription quality and ROUGE for summary quality checks.
  
