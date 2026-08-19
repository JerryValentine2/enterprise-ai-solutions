# Jerry Valentine

## Production AI & Data Engineering Portfolio

I design and deploy production AI applications, data platforms, and cloud-native services using Python, Google Cloud, Large Language Models, APIs, and modern data engineering practices.

This portfolio highlights three systems demonstrating applied decision support, investment evaluation, and cloud-based vector data infrastructure.

Email: jerryevalentine@gmail.com


# Featured Applications

## ODIN — Decision Support System

* 🌐 **Application:** https://odin.agilesolutionsinc.org/
* 📖 **Instructions:** https://odin.instructions.agilesolutionsinc.org/
* 💻 **GitHub Code and Documentation:** https://github.com/JerryValentine2/odin

ODIN is a decision-support system that transforms raw data into actionable insights through a structured **ETL → DEP** process.

**ETL:** Extract → Transform → Load
**DEP:** Describe → Explain → Predict

ODIN prepares and analyzes data using reports, visualizations, summary statistics, correlation, regression, and machine-learning predictive models to help users understand what happened, why it happened, and what is likely to happen next.

The results of the DEP analysis are transmitted to AI, which interprets the analytical results and returns additional insights to help users understand their significance. ODIN also provides an interactive AI chat feature that allows users to ask questions and explore the results conversationally.

**Status:** User tested and ready for use. Independent user testing found the workflow easy to use, the AI analysis clear and useful, and the discussion feature helpful for exploring specific findings.

**Upcoming Features:**
* Expanded user customization of analysis and visualizations.
* Metadata upload for defining dataset columns and providing additional context for analysis.

**Technologies:** Python, Google Cloud, Large Language Models, REST APIs, data analytics, machine learning

--- 

## ARES — Investment Evaluation System

* 🌐 **Application:** https://ares.agilesolutionsinc.org/
* 📖 **Instructions:** https://ares.instructions.agilesolutionsinc.org/
* 💻 **GitHub Code and Documentation:** https://github.com/JerryValentine2/ares-investor

**Usage Note:** Ares performs an in-depth analysis using seven independent investor perspectives followed by a synthesized investor-readiness assessment. Analysis may take 30–60 seconds to complete.

ARES evaluates potential investments to determine whether an investment decision is financially sound. It analyzes expected costs, benefits, returns, risks, and financial performance to provide a structured evaluation of whether an investment makes economic sense.

After evaluating a decision in ODIN, a decision that leads to a potential investment can be evaluated further in ARES. ARES determines whether that investment is justified by the underlying financial analysis.

**Status:** UAT tested and validated; customer testing has not yet been completed.

**Technologies:** Python, Google Cloud, Large Language Models, REST APIs, financial analysis, data analytics

---

## Kokopelli Trainer — Mathematics AI Trainer

- 🌐 **Application:** https://kokopelli.math.agilesolutionsinc.org
- 📖 **Instructions:** [soon]
- 💻 **GitHub Code and Documentation:** https://github.com/JerryValentine2/kokopelli-math
  
Kokopelli Trainer is an AI-powered mathematics learning application that provides adaptive, Socratic instruction while validating AI responses against explicit behavioral requirements.

The application separates the learning behavior from the conventional application code. A structured **Mathematics AI Program** defines the instructional behavior, while the Mercury runtime executes the program through Google Vertex AI and validates the resulting AI responses before they are presented to the learner.

The trainer introduces mathematical concepts in plain language, explains essential terminology, provides concrete examples, and guides the learner through Socratic questions. It evaluates learner responses, adapts subsequent instruction, identifies misconceptions, and requires evidence of understanding before completing a learning session.

The application uses a deliberately minimal Python web architecture, separating the web application layer, AI execution runtime, and behavioral AI Program.

**Status:** Development.


**Technologies:** Python, Google Cloud Vertex AI, Gemini, JSON, REST/HTTP, behavioral validation, AI program execution


# Sandbox Applications

## Apollo — Document Knowledge & Retrieval Platform

* 🌐 **Application:** https://apollo.agilesolutionsinc.org/
* 📖 **Instructions:** https://apollo.instructions.agilesolutionsinc.org/
* 💻 **GitHub Code and Documentation:** *add Apollo repository link*
  
Apollo is a cloud-based document knowledge and semantic retrieval platform that allows users to upload PDF documents and search their contents using natural-language questions.

Documents are ingested, text is extracted and divided into searchable chunks, and vector embeddings are generated for semantic retrieval. Apollo returns relevant source passages with traceability information including the source document, page number, Document ID, and chunk ID.

The platform also provides document lifecycle capabilities for adding, loading, and deleting source documents and their associated vector data. Documents are organized using Product IDs, allowing related collections of knowledge to be searched within a defined scope.

Apollo uses deterministic validation and error handling rather than silently returning uncertain retrieval results. Current development is focused on improving multi-document retrieval and document-management usability based on hands-on UAT.

**Status:** Sandbox — deployed and functional; active UAT and usability refinement in progress.

**Technologies:** Python, Google Cloud Run, Google Cloud Storage, Firestore vector search, Gemini embeddings, REST APIs, semantic search, vector embeddings, PDF document processing
