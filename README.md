# The Linguistic Signature of Hozier: A Computational Analysis
## Overview
What makes Hozier's lyrics feel "unusually poetic"? While listeners intuitively perceive his work as dense, symbolic, and visceral, this project seeks to answer one question: Is this difference measurable? Using tools from Computational Stylistics and Natural Language Processing (NLP), this project analyzes the lyrical language of Hozier’s Unreal Unearth (2023) against two distinct benchmarks:

1. Harry Styles (Harry’s House): representing the contemporary mainstream landscape.
2. Florence + The Machine (Dance Fever): a stylistic peer operating within similar folk-baroque and ritualistic aesthetics.

## Research Insights
The analysis confirms that Hozier occupies a distinct linguistic space characterized not just by what he says, but by what he omits.

- The "Love" Paradox: while "love" is a central theme, the word itself is statistically rare in Hozier’s lyrics. He replaces abstract emotional labels with sacred and anatomical metaphors.
- Body & Earth: Hozier shows a significantly higher density of semantic fields related to Geology (stone, earth, root) and Anatomy (flesh, bone, blood).
- Ritual Syntax: Florence + The Machine exhibits a unique signature of Imperative verbs, reflecting her "ritualistic" and performative lyrical framing.

## Methodology & Metrics
To avoid the biases of standard word counts, this pipeline implements:
- MTLD (Measure of Textual Lexical Diversity): a robust metric that evaluates vocabulary richness independent of text length.
- POS Tagging (Part-of-Speech): comparing the ratio of adjectives, adverbs, and imperatives across artists.
- Semantic Field Analysis: custom dictionaries mapping "Nature/Elements," "Body/Flesh," and "Domestic/Modern" imagery.
- PMI (Pointwise Mutual Information): identifying collocations - word pairs that uniquely define an artist's style (e.g., Hozier’s connection to Dantean and mythological terms).

## Project Structure
- `hozier_linguistic_analysis.ipynb`: the full Python pipeline (Data cleaning → Metrics → Visualization).
- `lyrics_dataset.csv`: the curated corpus of original compositions.

## Getting Started
- Clone the repo.
- Install dependencies.
- Run the Notebook: open `hozier_linguistic_analysis.ipynb` in Jupyter or Google Colab to reproduce the charts and metrics.

## Author's Note
I have always been fascinated by the power of words to transcend their literal definitions. This project is the first phase of an ongoing effort to bridge the gap between human intuition and computational evidence in musicology.
