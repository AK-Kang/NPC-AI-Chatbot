# Generating Conversation for NPCs in Games

## Project Overview

This project aims to enhance player engagement and immersion in video games by enabling non-playable characters (NPCs) to engage in free-form text conversations using AI-generated content. 
The project focuses on three popular games: Genshin Impact, Final Fantasy 7 Remake, and GTA 5, leveraging the Llama 2-13B model hosted on Gradient.AI.

## Objectives

- Enable NPCs to respond dynamically to a broad range of player inputs while maintaining character integrity.
- Avoid inappropriate content through prompt engineering.
- Measure success through player satisfaction surveys and sentiment analysis.

## Games and NPCs

1. **Genshin Impact** - Character: Zhongli
2. **Final Fantasy 7 Remake** - Character: Cloud
3. **GTA 5** - Character: Trevor

## Data Sources

### Genshin Impact
- Main quest dialogues involving Zhongli from Kaggle.
- Companion dialogues from Project Amber.
- Event quest dialogues from Genshin Impact Wiki.

### Final Fantasy 7 Remake
- Entire scripts from Final Fantasy games, focusing on “ff7-remake-script.csv” from Kaggle.

### GTA 5
- Dialogue corpus from the GTA 5 Dialogue Wiki.

## Methodology

1. **Data Preparation**: Clean and filter dialogue data specific to each NPC.
2. **Exploratory Data Analysis (EDA)**: Analyze common words, bigrams, and trigrams to understand each character’s speech patterns.
3. **Model Training**: Use the Llama 2-13B model with prompt engineering to guide character responses.
4. **Evaluation**: Conduct player surveys and perform sentiment analysis on generated dialogues.

## Key Findings

- **Zhongli (Genshin Impact)**: High player satisfaction with an average score of 6.7 compared to 2.0 for the baseline model. The model effectively avoided sensitive content.
- **Cloud (Final Fantasy 7 Remake)**: Moderate improvement with an average satisfaction score of 6.46 versus 5.3 for the baseline. Challenges included Cloud's concise dialogue style.
- **Trevor (GTA 5)**: Effective in reflecting Trevor’s unpredictable and violent nature. Sentiment analysis indicated high polarity and subjectivity in responses.

## Future Work

1. **Enhance Response Authenticity**: Use multi-head attention mechanisms for better alignment with character speech patterns.
2. **Expand Data Sources**: Incorporate additional texts, such as literary works and fanfiction, to enrich the models.
3. **Improve Empathetic Interactions**: Train models to reciprocate user emotions more effectively.
4. **Refine Prompt Engineering**: Tailor prompts to capture character complexity better and provide more interactive experiences.

## Contributors

- **Anni Kang**: Project planning, Genshin Impact analysis, Final Report.
- **Mason Kim**: Final Fantasy analysis.
- **Yingyuan Lin**: GTA 5 analysis.

## References

1. [Inworld AI Report](https://inworld.ai/whitepapers/future-of-npcs)
2. [Llama 2-13B Model on Hugging Face](https://huggingface.co/meta-llama/Llama-2-13b-chat-hf)
3. [Gradient.AI](https://gradient.ai/)
4. [Convai](https://convai.com/)
