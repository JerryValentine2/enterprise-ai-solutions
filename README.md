# Jerry Valentine

## Production AI & Data Engineering Portfolio

I design and deploy production AI applications, data platforms, and cloud-native services using Python, Google Cloud, Large Language Models, APIs, and modern data engineering practices.

This portfolio highlights three systems demonstrating applied decision support, investment evaluation, and cloud-based vector data infrastructure.

---

## ODIN — Decision Support System

ODIN is a decision-support system that transforms raw data into actionable insights through a structured **ETL → DEP** process.

**ETL:** Extract → Transform → Load
**DEP:** Describe → Explain → Predict

ODIN prepares and analyzes data using reports, visualizations, summary statistics, correlation, regression, and machine-learning predictive models to help users understand what happened, why it happened, and what is likely to happen next.

The results of the DEP analysis are transmitted to AI, which interprets the analytical results and returns additional insights to help users understand their significance. ODIN also provides an interactive AI chat feature that allows users to ask questions and explore the results conversationally.

**Status:** User tested and ready for use.

* 🌐 **Application:** https://odin.agilesolutionsinc.org/
* 📖 **Instructions:** https://odin.instructions.agilesolutionsinc.org/
* 💻 **GitHub Code and Documentation:** https://github.com/JerryValentine2/odin

**Technologies:** Python, Google Cloud, Large Language Models, REST APIs, data analytics, machine learning

---

## ARES — Investment Evaluation System

ARES evaluates potential investments to determine whether an investment decision is financially sound. It analyzes expected costs, benefits, returns, risks, and financial performance to provide a structured evaluation of whether an investment makes economic sense.

After evaluating a decision in ODIN, a decision that leads to a potential investment can be evaluated further in ARES. ARES determines whether that investment is justified by the underlying financial analysis.

**Status:** UAT tested and validated; customer testing has not yet been completed.

* 🌐 **Application:** https://ares.agilesolutionsinc.org/
* 📖 **Instructions:** https://ares.instructions.agilesolutionsinc.org/
* 💻 **GitHub Code and Documentation:** https://github.com/JerryValentine2/ares-investor

**Technologies:** Python, Google Cloud, Large Language Models, REST APIs, financial analysis, data analytics

---

## Athena — Cloud Vector Database

Athena is a cloud-based vector database built on **Google Cloud Firestore**. A centralized vector database service deployed on **Cloud Run** provides a single API layer through which multiple applications can access the vector database.

This architecture allows applications to share vector-search capabilities through one reusable cloud service rather than implementing and maintaining separate vector database integrations.

**Status:** Core vector database and read-only retrieval service completed; full CRUD functionality is not yet implemented.

* 🌐 **Application:** https://athena.agilesolutionsinc.org/
* 📖 **Instructions:** https://athena-instructions-v1-927115364189.us-central1.run.app/
* 💻 **GitHub Code and Documentation:** https://github.com/JerryValentine2/athena

**Technologies:** Google Cloud, Firestore, Cloud Run, vector search, embeddings, REST APIs
