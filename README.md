# 5-Day Gen AI Intensive Course

## Overview

This repository is my personal workspace for the **5-Day Gen AI Intensive Course** by Google. This course (originally a live event) is now a self-paced learning guide covering the fundamental technologies and techniques behind Generative AI.

**Course Goals:**
- Explore Foundational Models, LLM evolution, and prompt engineering.
- Understand embeddings, vector stores, and their applications (e.g., RAG).
- Learn to build Generative AI Agents and understand their components.
- Delve into Domain-Specific LLMs like SecLM and Med-PaLM.
- Adapt MLOps practices for Generative AI and Vertex AI.
- Complete a capstone project.

---

## How to Use This Repo

### Daily Workflow

1.  **Listen** to the day's summary podcast episode(s).
2.  **Read** the complementary whitepaper(s) (Tip: Use NotebookLM).
3.  **Complete** the day's Kaggle codelab(s).
4.  **Download** the notebook: `File → Download .ipynb`.
5.  **Save it** in the corresponding `dayN_*/` folder.
6.  **Add notes** and key takeaways to the day's `notes.md` file.
7.  **Commit & push** to GitHub.

### Local Development Setup

```bash
# Clone this repository
git clone [https://github.com/yourusername/google-gen-ai-intensive-2025.git](https://github.com/yourusername/google-gen-ai-intensive-2025.git)
cd google-gen-ai-intensive-2025

# Open in VSCode or your preferred editor
code .
````

-----

## Security & API Keys

**IMPORTANT:** Never commit API keys or secrets to this repository.

  - Store your `GOOGLE_API_KEY` (from AI Studio) as a **Kaggle Secret** (Settings → Secrets) for use in the cloud.
  - Use environment variables locally (`.env` files are gitignored).
  - See `resources/setup_guide.md` for detailed instructions on Kaggle, AI Studio, and Discord setup.

-----

## Repository Structure

```
google-gen-ai-intensive-2025/
│
├── README.md                 # This file
├── LICENSE                   # MIT License
├── .gitignore                # Excludes secrets, cache, etc.
├── CONTRIBUTING.md           # (Optional) Contribution guidelines
│
├── resources/
│   ├── setup_guide.md        # Kaggle, AI Studio, & Discord setup steps
│   └── course_links.md       # All course URLs (podcasts, whitepapers, etc.)
│
├── day1_foundations_prompting/
│   ├── prompting_fundamentals.ipynb
│   ├── evaluation_structured_data.ipynb
│   └── notes.md                # Personal takeaways
│
├── day2_embeddings_vector_stores/
│   ├── RAG_question_answering.ipynb
│   ├── text_similarity_embeddings.ipynb
│   ├── neural_classification_keras.ipynb
│   └── notes.md                # Personal takeaways
│
├── day3_generative_ai_agents/
│   ├── function_calling_database.ipynb
│   ├── langgraph_ordering_system.ipynb
│   └── notes.md                # Personal takeaways
│
├── day4_domain_specific_llms/
│   ├── tune_gemini_model.ipynb
│   ├── google_search_data.ipynb
│   └── notes.md                # Personal takeaways
│
├── day5_mlops_for_gen_ai/
│   ├── agent_starter_pack_review.md # Notes on the google/agent-starter-pack
│   └── notes.md                # Day 5 notes (no codelab)
│
├── bonus_assignment/
│   ├── bonus_gemini_api_features.ipynb
│   └── notes.md
│
└── capstone_project/
    ├── project_notebook.ipynb    # (Placeholder)
    └── README.md               # Project details and goals
```

-----

## Daily Study Checklist

For each day's module:

  - [ ] Open [Kaggle Discord](https://www.google.com/search?q=) for community help
  - [ ] Review links for the day in `resources/course_links.md`
  - [ ] Listen to the day's **podcast(s)**
  - [ ] Read the day's **whitepaper(s)**
  - [ ] Complete the **Kaggle codelab(s)**
  - [ ] Download and save notebook(s) to repo
  - [ ] Update `notes.md` with key takeaways
  - [ ] Commit and push to GitHub
  - [ ] (Optional) Watch the day's original livestream recording

-----

## Resources

See `resources/course_links.md` for all official course podcasts, whitepapers, codelabs, and livestream recording links.

See `resources/setup_guide.md` for the initial setup steps.

-----

## License

This repository is licensed under the MIT License. See [LICENSE](https://www.google.com/search?q=LICENSE) for details.

-----

**Happy learning\!** 🚀

```
```