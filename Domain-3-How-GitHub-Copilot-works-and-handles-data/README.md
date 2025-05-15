# ⚙️ Domain 3: How GitHub Copilot Works and Handles Data (15%)

This domain focuses on how GitHub Copilot gathers, processes, and uses contextual information to generate code suggestions. It covers the internal data flow, prompt construction, and architecture of the suggestion engine, including post-processing and limitations.

---

## 🎯 Objective: Understand the Suggestion Lifecycle in the IDE

### Key Learning Goals:
- Describe the **data pipeline lifecycle** of Copilot suggestions
- Visualize the **end-to-end flow** of a Copilot code suggestion:
  1. Context gathering
  2. Prompt building
  3. Proxy service and filters
  4. Model response generation
  5. Post-processing through proxy
  6. Code matching and ranking

---

## 🎯 Objective: Understand How Copilot Handles Context and Prompts

### Key Learning Goals:
- Explain **how GitHub Copilot gathers context** from your code
- Understand **prompt construction and filtering** logic
- Identify different **input types** used in Copilot Chat
- Describe **context window limitations**

---

## 🎯 Objective: Understand Data Usage and Privacy Models

### Key Learning Goals:
- Describe how GitHub Copilot handles:
  - **User data** and context inputs
  - **Copilot Individual** vs **Copilot Business/Enterprise** data handling
- Explain:
  - Data flow for **code completion**
  - Data flow for **Copilot Chat**

---

## 🎯 Objective: Understand Limitations of AI Models

### Key Learning Goals:
- Explain the **limitations of Copilot and large language models (LLMs)**:
  - Limited context awareness
  - Influence of frequently seen code examples
  - Staleness of training data
  - Lack of precise reasoning or computation

---

> 🧩 A clear understanding of how Copilot works under the hood helps you make informed, secure, and effective use of its code suggestions.
