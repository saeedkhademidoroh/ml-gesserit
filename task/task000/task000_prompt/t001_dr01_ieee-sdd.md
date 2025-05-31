Here is a **Gemini Pro 2.5 prompt** tailored for your **Second Task** (Face Recognition):

---

### ✅ Final Prompt for Gemini Pro 2.5:

You are an AI software architect helping evaluate and improve the design of a machine learning system for face recognition.

**Task context**:
We are building a face recognition pipeline using the InsightFace repository. The requirement is to use pre-trained models (e.g., `buffalo_l`, `buffalo_s`) and evaluate them on the following datasets:

* LFW
* CALFW
* CPLFW

For each dataset, we must compute:

* Accuracy
* FNMR (False Non-Match Rate)
* FMR (False Match Rate)

We will process 6000 face pairs and deploy this system using a server-client architecture. The server loads the model and performs inference. The client sends API requests containing two images (or paths), and receives a similarity score or match/non-match result.

**Your task**:

1. Review this system design at a high level.
2. Suggest improvements to architecture, modularity, and clarity.
3. Recommend best practices for:

   * Using InsightFace cleanly and correctly
   * Structuring code for model loading, request handling, and evaluation
   * Building a minimal but robust Flask/FastAPI interface
4. Optionally, propose a clean folder layout for this project.

The goal is clarity, simplicity, and readiness for evaluation and deployment.

---