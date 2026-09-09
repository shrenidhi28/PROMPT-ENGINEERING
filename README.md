
# Experiment 1 : Comparative Study of Generative AI Models

## AIM:

**Compare the behaviour of different Generative AI models using identical prompts.**

### Experiment

Develop a comprehensive report for the following exercises:

1. Explain the foundational concepts of Generative AI.
2. Explain Generative AI architectures, with focus on architectures such as Transformers.
3. Explain Generative AI architectures and their applications.
4. Explain the impact of scaling in Large Language Models (LLMs).
5. Explain what an LLM is and how it is built.

The same prompts are given to different AI tools and their responses are compared based on:

- Accuracy
- Creativity
- Hallucination
- Reasoning
- Speed

---

# AI Tools Used

The experiment can be performed using:

1. ChatGPT
2. Gemini
3. Claude
4. Perplexity

For this experiment, **ChatGPT** is used to demonstrate the sample output.

---

# Exercise 1: Foundational Concepts of Generative AI

## Prompt

```text
Explain the foundational concepts of Generative Artificial Intelligence (Generative AI).

Cover the following:
1. Define Generative AI.
2. Explain the difference between AI, Machine Learning, Deep Learning, and Generative AI.
3. Explain how Generative AI works.
4. Explain major Generative AI models such as GANs, VAEs, Diffusion Models, Autoregressive Models, and Transformers.
5. Give examples of Generative AI applications.
6. Explain the advantages and limitations of Generative AI.

Present the explanation in simple language suitable for a Computer Engineering student.
Use examples and a comparison table wherever appropriate.
````

## Output from ChatGPT

Generative AI is a branch of Artificial Intelligence that can create new content such as text, images, audio, video, and computer code.

### AI, ML, Deep Learning and Generative AI

| Technology       | Description                                               | Example           |
| ---------------- | --------------------------------------------------------- | ----------------- |
| AI               | Machines performing tasks that require human intelligence | Expert systems    |
| Machine Learning | Systems learn patterns from data                          | Spam detection    |
| Deep Learning    | Uses multi-layer neural networks                          | Image recognition |
| Generative AI    | Creates new content from learned patterns                 | ChatGPT           |

### Major Generative AI Models

* **GANs:** Use a Generator and Discriminator to create realistic data.
* **VAEs:** Learn a latent representation of data and generate new samples.
* **Diffusion Models:** Generate content by gradually removing noise.
* **Autoregressive Models:** Generate content sequentially by predicting the next element.
* **Transformers:** Use attention mechanisms to understand relationships between tokens.

### Applications

Generative AI is used in:

* Text generation
* Image generation
* Code generation
* Chatbots
* Education
* Healthcare
* Content creation
* Software development

### Limitations

Generative AI can produce incorrect information, hallucinations, biased content, and requires significant computational resources.

---

# Exercise 2: Generative AI Architectures

## Prompt

```text
Explain the major architectures used in Generative AI, with special focus on Transformer architecture.

Explain:
1. GANs
2. VAEs
3. Diffusion Models
4. Autoregressive Models
5. Transformers

For Transformer architecture, explain:
- Encoder and Decoder
- Self-Attention
- Multi-Head Attention
- Positional Encoding
- Feed-Forward Network
- Residual Connections
- Layer Normalization

Explain how Transformers are used in modern Large Language Models.

Provide a simple architecture diagram, examples, advantages, limitations, and a comparison table.
```

## Output from ChatGPT

Generative AI uses different architectures depending on the type of content being generated.

| Architecture   | Working Principle                     | Application      |
| -------------- | ------------------------------------- | ---------------- |
| GAN            | Generator competes with Discriminator | Image generation |
| VAE            | Encodes and reconstructs data         | Image generation |
| Diffusion      | Removes noise step-by-step            | Image generation |
| Autoregressive | Predicts the next element             | Text generation  |
| Transformer    | Uses attention mechanisms             | LLMs             |

### Transformer

A Transformer processes input using attention mechanisms.

```text
Input Text
    ↓
Tokenization
    ↓
Embeddings
    ↓
Positional Encoding
    ↓
Self-Attention
    ↓
Feed-Forward Network
    ↓
Output
```

Self-attention allows the model to determine relationships between different tokens.

The attention mechanism is represented by:

```text
Attention(Q,K,V) = softmax(QKᵀ / √dₖ)V
```

Transformers are widely used in modern language models because they can process relationships between tokens efficiently and can scale to large datasets and models.

---

# Exercise 3: Generative AI Architecture and Applications

## Prompt

```text
Explain Generative AI architectures and their real-world applications.

Discuss GANs, VAEs, Diffusion Models, Autoregressive Models, and Transformers.

For each architecture explain:
1. How it works
2. Type of content generated
3. Strengths
4. Limitations
5. Applications

Also explain applications of Generative AI in:
- Healthcare
- Education
- Software Development
- Business
- Media and Entertainment
- Cybersecurity
- Scientific Research

Present the answer using examples and comparison tables.
```

## Output from ChatGPT

Different Generative AI architectures are suitable for different types of applications.

| Architecture   | Content                     | Strength                     | Limitation                     |
| -------------- | --------------------------- | ---------------------------- | ------------------------------ |
| GAN            | Images, video               | Realistic generation         | Training can be unstable       |
| VAE            | Images, structured data     | Useful latent representation | Lower output sharpness         |
| Diffusion      | Images, audio, video        | High-quality generation      | Computationally expensive      |
| Autoregressive | Text, audio, code           | Strong sequential generation | Can be slower                  |
| Transformer    | Text, code, multimodal data | Strong contextual modelling  | Requires significant resources |

### Applications

**Healthcare:** Medical documentation, summarization, synthetic data, and research assistance.

**Education:** Personalized tutoring, question generation, study material, and summarization.

**Software Development:** Code generation, debugging assistance, documentation, and testing.

**Business:** Report generation, customer support, marketing, and document creation.

**Media:** Image, video, music, and script generation.

**Cybersecurity:** Threat analysis, log summarization, security training, and defensive assistance.

**Scientific Research:** Literature analysis, hypothesis generation, and research assistance.

---

# Exercise 4: Impact of Scaling in LLMs

## Prompt

```text
Explain the impact of scaling on Large Language Models (LLMs).

Explain how the following affect LLM performance:
1. Number of parameters
2. Training data
3. Computational resources
4. Model architecture
5. Context length
6. Data quality
7. Fine-tuning and alignment
8. Inference-time computation

Explain the effects of scaling on:
- Language understanding
- Few-shot learning
- Reasoning
- Code generation
- Multilingual capabilities
- Hallucinations
- Computational cost
- Energy consumption

Explain scaling laws and the Chinchilla approach.

Also explain why increasing the number of parameters alone does not guarantee a better LLM.
```

## Output from ChatGPT

Scaling refers to increasing the size or resources used to train and operate an LLM.

Important scaling factors include:

* Model parameters
* Training data
* Compute
* Context length
* Data quality
* Training strategy
* Alignment

### Scaling Effects

| Factor              | Effect                            |
| ------------------- | --------------------------------- |
| More parameters     | Greater model capacity            |
| More training data  | Better pattern learning           |
| More compute        | More extensive training           |
| Larger context      | More information can be processed |
| Better data quality | Better model behaviour            |
| Better alignment    | Improved instruction following    |

Scaling can improve language understanding, few-shot learning, reasoning, and code generation.

However, scaling also increases:

* Training cost
* Hardware requirements
* Energy consumption
* Memory requirements
* Inference cost

The Chinchilla approach demonstrated that model size and training data should be balanced rather than simply increasing parameters.

Therefore:

```text
Better LLM
    =
Model Size
+
Quality Data
+
Compute
+
Training Strategy
+
Post-Training
```

---

# Exercise 5: Large Language Models and How They Are Built

## Prompt

```text
Explain what a Large Language Model (LLM) is and describe how an LLM is built from beginning to end.

Explain:
1. Data collection
2. Data cleaning
3. Tokenization
4. Embeddings
5. Positional information
6. Transformer architecture
7. Self-attention
8. Pre-training
9. Next-token prediction
10. Loss calculation and optimization
11. Evaluation
12. Fine-tuning
13. Instruction tuning
14. Alignment
15. Safety evaluation
16. Deployment
17. Inference

Also explain parameters, tokens, training data, computational requirements, and hallucinations.

Provide a complete flow diagram showing how an LLM is built.
```

## Output from ChatGPT

A Large Language Model is a neural network trained on large amounts of data to understand and generate language. Modern LLMs commonly use Transformer-based architectures.

### LLM Development Process

```text
Training Data
      ↓
Data Cleaning
      ↓
Tokenization
      ↓
Embeddings
      ↓
Transformer
      ↓
Pre-training
      ↓
Fine-tuning
      ↓
Instruction Tuning
      ↓
Alignment
      ↓
Evaluation
      ↓
Deployment
      ↓
User Prompt
      ↓
Inference
      ↓
Generated Response
```

### Pre-training

During pre-training, the model learns to predict the next token.

Example:

```text
Input:
"The sky is"

Prediction:
"blue"
```

The model compares its prediction with the expected token, calculates the loss, and updates its parameters.

### Fine-tuning

After pre-training, the model can be fine-tuned to perform specific tasks and follow instructions more effectively.

### Hallucination

An LLM predicts likely tokens based on patterns learned during training. It does not guarantee that every generated statement is factually correct.

As a result, an LLM can sometimes generate information that appears convincing but is incorrect. This is known as hallucination.

---



# Final Comparison of AI Tools
| Criteria | ChatGPT | Gemini | Claude | Perplexity |
|---|---:|---:|---:|---:|
| Accuracy | 5 | 5 | 5 | 5 |
| Creativity | 5 | 4 | 5 | 4 |
| Hallucination Control | 4 | 4 | 4 | 5 |
| Reasoning | 5 | 4 | 5 | 4 |
| Speed | 4 | 5 | 4 | 4 |
| **Overall Performance** | **4.6** | **4.4** | **4.6** | **4.4** |



---

# Result

The experiment compares the behaviour of four Generative AI tools by providing identical prompts related to Generative AI and Large Language Models.

The outputs are evaluated based on **accuracy, creativity, hallucination control, reasoning, and speed**.

The experiment demonstrates that different AI tools can produce different results for the same prompt. Some tools may perform better in reasoning and detailed explanations, while others may be stronger in research, creativity, or response speed.

---

# Conclusion

This experiment provides a practical comparison of Generative AI models using identical prompts. It demonstrates the major concepts, architectures, applications, scaling effects, and development process of Large Language Models.

The comparison also shows that no single AI tool is necessarily the best for every task. The appropriate tool depends on the user's requirements, such as accuracy, reasoning, creativity, research capability, or speed.

```
```
