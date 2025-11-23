# 📝 Domain 2: Generative AI Fundamentals Quiz (24% Weight)

Focus: Task 2.1 (Concepts), 2.2 (Limitations), 2.3 (AWS Infra)

---

**Q1. (D2.1) What fundamental architecture allows Foundation Models (FMs) to process sequences of data (like words) by weighing the importance of different elements in the input sequence?**
A. Recurrent Neural Network (RNN)
B. Convolutional Neural Network (CNN)
C. Transformer Architecture
D. Generative Adversarial Network (GAN)

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** C. Transformer Architecture
**Explanation:** The Transformer architecture, particularly its self-attention mechanism, is the foundation for modern LLMs and FMs, enabling them to handle long-range dependencies in data.
</details>

---

**Q2. (D2.2) A business is concerned that a Generative AI model occasionally provides factually incorrect information that sounds convincing. What is the technical term for this limitation?**
A. Bias Drift
B. Nondeterminism
C. Hallucination
D. Overfitting

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** C. Hallucination
**Explanation:** Hallucinations refer to the model generating content that is plausible but factually incorrect or unsupported by the training data.
</details>

---

**Q3. (D2.3) A company has a high-volume, low-latency production application that calls an FM via Amazon Bedrock thousands of times per hour. Which pricing model is generally the most cost-effective for this scenario?**
A. Token-Based Pricing
B. Zero-Shot Pricing
C. Provisioned Throughput
D. Spot Instance Pricing

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** C. Provisioned Throughput
**Explanation:** Provisioned Throughput allows customers to purchase a fixed amount of throughput (tokens per second) for a dedicated period, making it more predictable and cost-effective for high-volume production loads than paying per token.
</details>

---

**Q4. (D2.3) Which AWS service provides a fully managed interface to access and choose from a variety of leading Foundation Models (FMs) from Amazon and third-party providers?**
A. Amazon SageMaker
B. AWS Lambda
C. Amazon Bedrock
D. Amazon CodeWhisperer

<details>
<summary><strong>Answer and Explanation</strong></summary>
**Answer:** C. Amazon Bedrock
**Explanation:** Amazon Bedrock is the hub for accessing a choice of FMs via a single API, simplifying GenAI application development.
</details>
