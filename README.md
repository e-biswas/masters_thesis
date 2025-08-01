# Leveraging Contextual Information for Spoiler Detection in Movie Reviews
The proliferation of user-generated content on online movie platforms has led to unintentional exposure to spoilers, significantly diminishing the viewing experience. To address this, this thesis presents an **enhanced model for spoiler identification** in movie reviews, leveraging a comprehensive dataset of **over 3 million English movie reviews** (until late 2020).  

### Key Contributions  
- Investigates the role of **contextual information** in spoiler detection using:  
  - **Transformer-based models**  
  - **Language Model (LLM)-based methods**  
  - **Conventional statistical learning models**  
- Achieves **85% accuracy** and an industry-leading **F1-score of 0.84**, outperforming benchmarks like **MSVD**.  
- Validated on a **300,000-sample test set**, with extended evaluations on **20 popular films (2022–2023)**—unseen during training.  
  - Maintains strong performance: **weighted precision (0.83), AUC (0.8256)** on ~55,000 new samples.  
  - Surpasses **Llama 3.1 8B Instruct** (F1: 0.71), demonstrating closer alignment with human judgment. (The chunk based spoiler detection was able to match the performance of GPT 4.0 (December 2024) during live demo). 

### Technological Advancements  
- Introduces a **state-of-the-art architecture** for spoiler detection, advancing NLP applications in deep learning.  
- Proposes a **novel dataset preprocessing** method and **decision visualization technique** for future research.  
- Establishes a **new performance benchmark**, highlighting the critical role of context in spoiler detection.  

This work underscores the adaptability of deep learning models in evolving data environments while setting a foundation for further innovation in the field.

> **Note:** Read the full report for the total understanding!
