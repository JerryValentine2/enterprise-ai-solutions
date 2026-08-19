# Jerry Valentine

## Production AI & Data Engineering Portfolio

I design and deploy production AI applications, data platforms, and cloud-native services using Python, Google Cloud, Large Language Models, APIs, and modern data engineering practices.

This portfolio highlights three systems demonstrating applied decision support, investment evaluation, and cloud-based vector data infrastructure.

Email: jerryevalentine@gmail.com

# Featured Applications

## ODIN — Decision Support System
[existing ODIN entry]

---

## ARES — Investment Evaluation System
[existing ARES entry]

---

## Kokopelli Trainer — Mathematics AI Trainer
[existing Kokopelli entry]

---

# Sandbox

Sandbox projects are deployed, functional systems that are actively being tested and refined. They demonstrate working engineering capabilities but should not be interpreted as completed products.

## Apollo — Document Knowledge & Retrieval Platform

- 🌐 **Application:** https://apollo.agilesolutionsinc.org/
- 📖 **Instructions:** https://apollo.instructions.agilesolutionsinc.org/
- 💻 **GitHub Code and Documentation:** *add Apollo repository link*

Apollo is a cloud-based document knowledge and semantic retrieval platform that allows users to upload PDF documents and search their contents using natural-language questions.

Documents are ingested, text is extracted and divided into searchable chunks, and vector embeddings are generated for semantic retrieval. Apollo returns relevant source passages with traceability information including the source document, page number, Document ID, and chunk ID.

The platform also provides document lifecycle capabilities for adding, loading, and deleting source documents and their associated vector data. Documents are organized using Product IDs, allowing related collections of knowledge to be searched within a defined scope.

Apollo uses deterministic validation and error handling rather than silently returning uncertain retrieval results. Current development is focused on improving multi-document retrieval and document-management usability based on hands-on UAT.

**Status:** Deployed and functional; active UAT and usability refinement in progress.

**Technologies:** Python, Google Cloud Run, Google Cloud Storage, Firestore vector search, Gemini embeddings, REST APIs, semantic search, vector embeddings, PDF document processing
