
# Ex.No1: Comparative Analysis of Generative AI Models Using Identical Prompts

## Objective

To compare the behaviour and performance of different Generative AI models using identical prompts and evaluate them based on:

- Accuracy
- Creativity
- Hallucination
- Reasoning
- Speed
- Engineering usefulness

---

## AI Tools Used

The following Generative AI tools are used for comparison:

1. ChatGPT
2. Gemini
3. Claude
4. Perplexity

The **same prompt** is given to all four AI tools for each activity to ensure a fair comparison.

---

# Activity 1: Foundational Concepts of Generative AI

## Prompt

```text
Explain the foundational concepts of Generative Artificial Intelligence (Generative AI) in a clear and comprehensive manner.

Cover the following points:
1. Definition of Generative AI
2. Difference between traditional AI, Machine Learning, Deep Learning and Generative AI
3. How Generative AI works
4. Role of neural networks and deep learning
5. Training data and parameters
6. Tokens and embeddings
7. Major types of Generative AI models
8. Examples of Generative AI systems
9. Advantages and limitations
10. Real-world applications

Explain each concept using simple language and suitable examples. Include a comparison table where appropriate. The explanation should be technically accurate and suitable for an engineering student.
````

### Purpose

This prompt evaluates how well each AI tool explains the **basic concepts and foundations of Generative AI**.

---

# Activity 2: Generative AI Architectures

## Prompt

```text
Explain the major architectures used in Generative AI, with special focus on the Transformer architecture.

Cover the following topics:
1. Generative AI architecture overview
2. Generative Adversarial Networks (GANs)
3. Variational Autoencoders (VAEs)
4. Diffusion Models
5. Transformer architecture
6. Self-attention mechanism
7. Query, Key and Value
8. Multi-head attention
9. Encoder and Decoder
10. Positional encoding
11. GPT and BERT architectures
12. Advantages and limitations of each architecture

Provide simple architecture diagrams using text/ASCII where possible. Compare GANs, VAEs, Diffusion Models and Transformers in a table. Explain the Transformer architecture step-by-step in a way that an engineering student can understand.
```

### Purpose

This prompt evaluates the model's ability to explain **technical AI architectures and reasoning behind their components**.

---

# Activity 3: Generative AI Architecture and Its Applications

## Prompt

```text
Explain how Generative AI architectures are used in real-world applications.

First explain the relationship between Generative AI architectures and their applications. Then discuss the applications of GANs, VAEs, Diffusion Models and Transformer-based models.

Cover applications in:
1. Natural Language Processing
2. Chatbots and virtual assistants
3. Image generation
4. Video generation
5. Audio and music generation
6. Software and code generation
7. Healthcare
8. Education
9. Business and marketing
10. Engineering and scientific research

For each application, identify the suitable Generative AI architecture and explain why it is suitable.

Provide a table with:
Architecture | Application | Example | Benefits | Limitations

Use real-world examples and explain the content at an engineering-student level.
```

### Purpose

This prompt evaluates how effectively each AI tool connects **AI architectures with practical engineering and industry applications**.

---

# Activity 4: Impact of Scaling in LLMs

## Prompt

```text
Explain the impact of scaling in Large Language Models (LLMs).

Discuss the following:
1. What scaling means in Generative AI
2. Model scaling and number of parameters
3. Training-data scaling
4. Computational scaling
5. Scaling laws
6. Relationship between model size, data and compute
7. How scaling affects accuracy and capabilities
8. Emergence of new capabilities
9. Benefits of scaling LLMs
10. Limitations and challenges of scaling
11. Training cost and energy consumption
12. Inference and deployment costs
13. Why larger models do not always mean better models
14. Efficient and compute-optimal model training

Provide suitable examples and a comparison table showing the effects of increasing model size, data and computational resources.

Explain the topic clearly for an engineering student and distinguish established research findings from assumptions or speculation.
```

### Purpose

This prompt tests the model's ability to explain **scaling, technical trade-offs and the relationship between model size, data and computation**.

---

# Activity 5: LLM and How It Is Built

## Prompt

```text
Explain what a Large Language Model (LLM) is and describe how an LLM is built from beginning to end.

Explain the following stages in detail:

1. Definition of an LLM
2. Data collection
3. Data cleaning and preprocessing
4. Tokenization
5. Embeddings
6. Transformer architecture
7. Pre-training
8. Next-token prediction
9. Loss function and optimization
10. Backpropagation and gradient descent
11. Hardware and computational requirements
12. Fine-tuning
13. Instruction tuning
14. Human feedback and alignment
15. Evaluation and testing
16. Deployment and inference
17. Updating and improving an LLM

Provide a step-by-step pipeline showing how raw data is transformed into a working LLM.

Also explain the difference between training and inference.

Include a simple example showing how an LLM predicts the next token.

Finally, provide a table summarizing each stage, its purpose and the main technologies involved.

The explanation should be technically accurate, easy to understand, and suitable for an engineering student.
```

### Purpose

This prompt evaluates how well each AI tool explains the **complete lifecycle of building and deploying an LLM**.

---

# Comparison Methodology

Each of the five prompts will be submitted **without modification** to:

* ChatGPT
* Gemini
* Claude
* Perplexity

The responses will then be compared using the following criteria.

---

# Evaluation Criteria

## 1. Accuracy

Evaluate whether the information provided by the AI is:

* Factually correct
* Technically accurate
* Consistent with established AI concepts
* Supported by reliable sources when required

### Rating

| Score | Description        |
| ----- | ------------------ |
| 1     | Very inaccurate    |
| 2     | Mostly inaccurate  |
| 3     | Partially accurate |
| 4     | Mostly accurate    |
| 5     | Highly accurate    |

---

## 2. Creativity

Evaluate:

* Quality of examples
* Originality of explanations
* Ability to present concepts in interesting ways
* Use of analogies
* Quality of diagrams and presentation

### Rating

| Score | Description |
| ----- | ----------- |
| 1     | Very poor   |
| 2     | Poor        |
| 3     | Average     |
| 4     | Good        |
| 5     | Excellent   |

---

## 3. Hallucination

Hallucination refers to generating information that is **incorrect, fabricated or unsupported but presented as factual**.

Check whether the AI:

* Invents facts
* Gives incorrect technical information
* Provides fake references
* Makes unsupported claims
* Misrepresents research

### Rating

| Score | Description             |
| ----- | ----------------------- |
| 1     | Very high hallucination |
| 2     | High hallucination      |
| 3     | Moderate                |
| 4     | Low                     |
| 5     | Very low / reliable     |

> For this criterion, a **higher score means fewer hallucinations**.

---

# 4. Reasoning

Evaluate how well the AI:

* Explains cause and effect
* Connects concepts
* Breaks complex problems into steps
* Justifies technical claims
* Compares alternatives
* Explains trade-offs

### Rating

| Score | Description |
| ----- | ----------- |
| 1     | Very poor   |
| 2     | Poor        |
| 3     | Average     |
| 4     | Good        |
| 5     | Excellent   |

---

# 5. Speed

Record the approximate time taken by each AI tool to produce the response.

Example:

| AI Tool    | Response Time |
| ---------- | ------------: |
| ChatGPT    |   ___ seconds |
| Gemini     |   ___ seconds |
| Claude     |   ___ seconds |
| Perplexity |   ___ seconds |

The speed should be measured under approximately similar network conditions.

---

# 6. Engineering Usefulness

Evaluate how useful the response is for an engineering student.

Consider:

* Technical depth
* Clarity
* Practical examples
* Architecture explanations
* Industry relevance
* Code/pseudocode where appropriate
* Ability to support assignments and projects

### Rating

| Score | Description       |
| ----- | ----------------- |
| 1     | Not useful        |
| 2     | Slightly useful   |
| 3     | Moderately useful |
| 4     | Very useful       |
| 5     | Extremely useful  |

---

# Comparison Table

After testing all five prompts, fill in the following table.

| Criteria               | ChatGPT |  Gemini |  Claude | Perplexity |
| ---------------------- | ------: | ------: | ------: | ---------: |
| Accuracy               |      /5 |      /5 |      /5 |         /5 |
| Creativity             |      /5 |      /5 |      /5 |         /5 |
| Hallucination          |      /5 |      /5 |      /5 |         /5 |
| Reasoning              |      /5 |      /5 |      /5 |         /5 |
| Speed                  | ___ sec | ___ sec | ___ sec |    ___ sec |
| Engineering Usefulness |      /5 |      /5 |      /5 |         /5 |
| **Overall Score**      | **/25** | **/25** | **/25** |    **/25** |

> Speed is recorded separately and is not included in the `/25` score.

---

# Question-wise Comparison

## Question 1 – Fundamentals of Generative AI

| AI Tool    | Accuracy | Creativity | Hallucination | Reasoning | Engineering Usefulness |
| ---------- | -------: | ---------: | ------------: | --------: | ---------------------: |
| ChatGPT    |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Gemini     |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Claude     |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Perplexity |       /5 |         /5 |            /5 |        /5 |                     /5 |

---

## Question 2 – Generative AI Architectures

| AI Tool    | Accuracy | Creativity | Hallucination | Reasoning | Engineering Usefulness |
| ---------- | -------: | ---------: | ------------: | --------: | ---------------------: |
| ChatGPT    |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Gemini     |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Claude     |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Perplexity |       /5 |         /5 |            /5 |        /5 |                     /5 |

---

## Question 3 – Architecture and Applications

| AI Tool    | Accuracy | Creativity | Hallucination | Reasoning | Engineering Usefulness |
| ---------- | -------: | ---------: | ------------: | --------: | ---------------------: |
| ChatGPT    |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Gemini     |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Claude     |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Perplexity |       /5 |         /5 |            /5 |        /5 |                     /5 |

---

## Question 4 – Scaling in LLMs

| AI Tool    | Accuracy | Creativity | Hallucination | Reasoning | Engineering Usefulness |
| ---------- | -------: | ---------: | ------------: | --------: | ---------------------: |
| ChatGPT    |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Gemini     |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Claude     |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Perplexity |       /5 |         /5 |            /5 |        /5 |                     /5 |

---

## Question 5 – LLM and How It Is Built

| AI Tool | Accuracy | Creativity | Hallucination | Reasoning | Engineering Usefulness |
| ------- | -------: | ---------: | ------------: | --------: | ---------------------: |
| ChatGPT |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Gemini  |       /5 |         /5 |            /5 |        /5 |                     /5 |
| Claude  |       /5 |         /5 |            /5 |        /5 |                     /5 |

---

# Overall Evaluation

After completing all five experiments, calculate the average score for each AI tool.

| AI Tool    | Accuracy | Creativity | Hallucination | Reasoning | Engineering Usefulness | Overall |
| ---------- | -------: | ---------: | ------------: | --------: | ---------------------: | ------: |
| ChatGPT    |          |            |               |           |                        |         |
| Gemini     |          |            |               |           |                        |         |
| Claude     |          |            |               |           |                        |         |
| Perplexity |          |            |               |           |                        |         |

---

# Observations

The following observations should be recorded after testing the prompts:

1. Which AI provided the most technically accurate explanations?
2. Which AI provided the most creative examples?
3. Which AI produced the fewest hallucinations?
4. Which AI demonstrated the strongest reasoning?
5. Which AI responded fastest?
6. Which AI was most useful for engineering students?
7. Which AI provided the best references and sources?
8. Which AI provided the clearest explanations?
9. Which AI produced the best architecture diagrams?
10. Which AI performed best overall?

---

# Result

The four Generative AI tools — **ChatGPT, Gemini, Claude and Perplexity** — are evaluated using the same five prompts.

Their responses are compared based on **accuracy, creativity, hallucination, reasoning, speed and engineering usefulness**.

The experiment demonstrates that different Generative AI systems can produce different responses to identical prompts, with differences in technical depth, factual reliability, reasoning quality, response speed and practical usefulness.

---

# Conclusion

The experiment provides a systematic method for comparing Generative AI tools using identical prompts. By keeping the prompts constant and evaluating multiple performance criteria, the strengths and weaknesses of each AI system can be identified.

The comparison also demonstrates that selecting an AI tool depends on the specific engineering task. One model may provide stronger technical explanations, another may provide better references, while another may offer more creative or concise responses.

Therefore, **no single evaluation criterion is sufficient to determine the best Generative AI tool**. A combination of accuracy, reliability, reasoning, speed and engineering usefulness provides a more meaningful comparison.

