# Whisper Fine-tuning for Hindi-English Code-Switched Speech

Fine-tuning OpenAI's Whisper ASR model on Hindi-English (Hinglish) 
code-switched speech to improve transcription accuracy on mixed-language audio.
### Dataset: 
Prototype trained on the Hinglish (code-switched) subset of 
`addyo07/noisy-hinglish-asr` (Hugging Face, Apache 2.0) 

Dataset have: 28,681 audio recordings, 36.6 hours total

1. 4 categories are labeled: Hindi (hi), English (en), Hinglish code-switched (hinglish), and silence/noise
2. The Hinglish subset alone contains 6,028 training samples — meaning it is directly usable for your project
3. It is already divided into training/validation/test sets — you do not need to split the data yourself
4. Apache 2.0 license — free to use, including for research

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
Wait 

## License
MIT
