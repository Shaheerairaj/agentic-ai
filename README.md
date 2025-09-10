# Agentic AI – Fundamentals

**Welcome to the Agentic AI learning resource!**
Built in collaboration with [SuperDataScience](https://community.superdatascience.com), this course is part of our community-driven effort to make Agentic AI accessible to everyone.

This repository is your hands-on guide to building **AI agents from scratch using pure Python** before we move on to frameworks like LangChain or CrewAI. By the end of these courses, you’ll understand how agents work under the hood and be able to build autonomous Agentic AI systems and deploy them to production for scalability.

---

## About This Repository

This repository contains **step-by-step Python scripts and Jupyter notebooks** that introduce you to the core ideas of Agentic AI. You’ll build agents incrementally, starting from a simple loop around an LLM, and progressing toward agents with **tools, reasoning traces, and error handling**.

### What You'll Learn

* **What AI agents are** and how they differ from plain LLMs
* Building a **basic agent loop in Python**
* Adding **tools** (calculator, search, APIs) to agents
* Handling **errors and retries**
* A **mini project**: An AI Travel Planner

---

## 🗂️ Repository Structure

```
agentic-ai/
├── README.md
├── requirements.txt
├── environment.yaml
├── .env.example
└── Part1-Fundamentals/
    └── community-contributions/
    └── lab1
    └── lab2
```

---

## 🚀 Getting Started

### Prerequisites

* Python 3.10 or higher
* OpenAI API key (sign up at [OpenAI](https://platform.openai.com/))
* Basic understanding of Python and Jupyter notebooks

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Shaheerairaj/agentic-ai-course.git
   cd agentic-ai-course
   ```

2. **Create and activate a virtual environment**

   *For Windows:*

   ```bash
   python -m venv .venv
   .venv\Scripts\Activate
   ```

   *For Mac/Linux:*

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies:**

   Using pip:

   ```bash
   pip install -r requirements.txt
   ```

   Or using uv (recommended):

   ```bash
   uv sync
   ```

4. **Set up your API key:**

   ```bash
   echo "OPENAI_API_KEY=your_api_key_here" > .env
   ```

5. **Start learning:**

   ```bash
   jupyter notebook Part1-Fundamentals/
   ```

---

## 🛠️ Key Dependencies

* **OpenAI** – for accessing LLMs
* **python-dotenv** – for managing API keys in `.env`
* **Jupyter** – for interactive learning

---

## 🤝 Contributing

We welcome contributions from the community!

### Ways to Contribute

1. Report issues or suggest improvements
2. Improve documentation
3. Add new agent examples or tools
4. Fix bugs in notebooks

### Guidelines

* Fork the repo and create a feature branch
* Follow the existing code style and notebook format
* Add clear markdown explanations and comments
* Test your notebooks before submitting
* Open a pull request with a clear description

Community submissions go in the `community-contributions/` folder.

---

## 📚 Additional Resources

* [OpenAI API Docs](https://platform.openai.com/docs)
* [SuperDataScience Community](https://www.community.superdatascience.com/) (Lecture videos)

---

## 📢 Need Help?

* 📧 Open a [GitHub Issue](https://github.com/Shaheerairaj/agentic-ai-courses/issues)
* 💬 Join our community: [Agentic AI Q\&A](https://community.superdatascience.com/c/ml-ai-questions/)
* 💼 [LinkedIn](https://www.linkedin.com/in/shaheerairajahmed)
* 🐙 [GitHub](https://github.com/shaheerairaj)

---

**Happy Learning! 🎉** Start your Agentic AI journey today and build your own Python-powered agents from scratch.
