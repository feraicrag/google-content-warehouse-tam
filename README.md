# Google Content Warehouse TAM

Public repository for TAM prompt with Content Warehouse leak signals.

## Files

- `TAM-PROMPT-V7.3-TROY.md` - TAM prompt with staged execution
- `signals-summary.md` - Key ranking signals extracted from Content Warehouse API

## Usage

1. Fill variables in the prompt
2. Provide sitemap URL or list
3. Execute stages in order
4. Output must include all sections 6.1 to 6.11

## Limitation

A prompt cannot force an LLM to verifiably read 5000+ lines. The staged execution forces sequential processing of signal groups, but full line-by-line reading is not guaranteed.
