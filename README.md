# Whisper Fine-tuning for Hindi-English Code-Switched Speech

Fine-tuning OpenAI's Whisper ASR model on Hindi-English (Hinglish) 
code-switched speech to improve transcription accuracy on mixed-language audio.

## Problem
Whisper's pretrained model shows degraded accuracy on Hindi-English 
code-switched speech, since its training data is dominated by monolingual 
audio. This limits its usefulness for real-world Indian speech, where 
code-switching is common.

## Approach
Fine-tune whisper-small on a small Hindi-English code-switched audio 
dataset, and measure the Word Error Rate (WER) improvement compared to 
the baseline (unmodified) model.

## Results
(training ke baad yahan before/after WER numbers aayenge)

## License
MIT
