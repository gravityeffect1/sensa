# sensa
Fighting cervical cancer misinformation in Romania with Gemma 4

## The problem
[2-3 sentences lifted from your writeup §1]

## What Sensa does
[2-3 sentences lifted from your writeup §2]

## Architecture
![Architecture diagram](architecture.png)
Four-layer pipeline: deterministic safety → myth RAG → constrained Gemma 4 E4B → response validation.

## How to run
1. Open `sensa.ipynb` in Kaggle
2. Attach Gemma 4 E4B model from Kaggle Models
3. Enable GPU T4 accelerator
4. Run All

## Attribution
Sensa is built on Gemma 4 E4B, developed by Google DeepMind.
Sensa is not endorsed by or affiliated with Google.
Gemma is a trademark of Google LLC.
