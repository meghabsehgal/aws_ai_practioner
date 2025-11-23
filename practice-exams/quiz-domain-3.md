# 📝 Domain 3: Application of Foundation Models Quiz (28% Weight)

Focus: Task 3.1 (Selection/Prompting), 3.2 (RAG/FT), 3.3 (Training), 3.4 (Evaluation)

---

**Q1. (D3.2) A financial services firm needs an FM to answer user queries using the company's proprietary, rapidly changing regulatory documents. Which customization method is most appropriate?**
A. Fine-Tuning the model on all regulatory documents.
B. Using Reinforcement Learning from Human Feedback (RLHF).
C. Implementing Retrieval Augmented Generation (RAG).
D. Using Zero-Shot Prompting.

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** C. Implementing Retrieval Augmented Generation (RAG).
**Explanation:** RAG is ideal for grounding the model with external, authoritative, and current data. Since the documents change rapidly, RAG is preferable to Fine-Tuning, which is costly and time-consuming to update frequently.
</details>

---

**Q2. (D3.1) A model is struggling with a complex, multi-step calculation. A data scientist modifies the prompt to include the instruction: "Explain your reasoning step-by-step before providing the final answer." Which technique is being applied?**
A. Few-Shot Prompting
B. Chain-of-Thought (CoT) Prompting
C. Instruction Tuning
D. Zero-Shot Prompting

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** B. Chain-of-Thought (CoT) Prompting
**Explanation:** CoT is used to elicit a structured thought process from the model, significantly improving its performance on reasoning and logical tasks.
</details>

---

**Q3. (D3.4) Which evaluation metric is most commonly used to assess the quality of a generated summary against a human-written reference summary?**
A. BLEU
B. Accuracy
C. ROUGE
D. F1 Score

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** C. ROUGE
**Explanation:** ROUGE (Recall-Oriented Understudy for Gisting Evaluation) is the standard metric for evaluating summarization tasks. BLEU is primarily for translation.
</details>

---

**Q4. (D3.3) During the Fine-Tuning process, what is the purpose of Reinforcement Learning from Human Feedback (RLHF)?**
A. To automatically clean and normalize the training data.
B. To collect human preference rankings (e.g., helpfulness, harmlessness) to further refine the model's weights.
C. To prevent model hallucination by integrating external documents.
D. To convert raw text into token embeddings.

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** B. To collect human preference rankings (e.g., helpfulness, harmlessness) to further refine the model's weights.
**Explanation:** RLHF is a critical post-training step that aligns the model's behavior with human values and preferences.
</details>
