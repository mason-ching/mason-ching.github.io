---
title: "Development and Deployment of Audit Large Language Model"
collection: projects
# type: "LLM for Audit"
# permalink: /projects/2025-AuditLLM
excerpt: |
    <div style="text-align: justify; font-size: 16px; color: #666; margin: 5px 0 0 20px; margin-left: 0px;">
        <p>
            The primary objective of this project is to design, fine-tune and deploy a secure, internally-facing Audit Large Language Model (ALLM) to empower auditors at <a href="https://sjt.henan.gov.cn/" style="text-decoration: none;">Henan Provincial Audit Department</a>. Built atop Qwen foundation model, our ALLM need deliver intelligent support for audit Q&A, regulatory compliance and table-data analysis, improving audit efficiency and accuracy. In this project, I worked with Lutong Zhang and Haonan Zhang to finish the following tasks:
        </p>
        <ul style="padding-left: 30px; margin-top: 0;">
            <li style="margin-bottom: 15px;">
                Data Collection: Aggregating amounts of audit documentation, historical audit reports, government financial regulations (national and provincial level), accounting standards (e.g., Chinese GAAP), policy directives, compliance manuals, and best practice guidelines.
            </li>
            <li style="margin-bottom: 15px;">
                Data Processing: Implementing data processing pipelines for heterogeneous audit sources, including: text extraction that applies PaddleOCR with regex-based digit correction for scanned documents, pdfplumber for layout-aware PDF, python-docx for DOCX files; spaCy + FinBERT for entity normalization of regulations/financial terms; DeepSeek-V2 classification for document categorization and UIE model for sensitivity tagging; LayoutLMv3 for context-aware semantic segmentation to preserve audit logic.
            </li>
            <li style="margin-bottom: 15px;">
                Knowledge Vectorization: Utilizing BGE-M3 to transform textual knowledge into high-dimensional vectors indexed into Milvus with metadata filters, enabling efficient semantic search and retrieval.
            </li>
            <li style="margin-bottom: 15px;">
                Synthetic QA Generation: Using Qwen-72B-Chat to produce question-answer pairs reflecting common audit scenarios, enriching our fine-tuning dataset.
            </li>
            <li style="margin-bottom: 15px;">
                Expert Annotation: Collaborating with senior auditors to annotate real audit cases, identifying key entities, risks, compliance issues, and generating relevant queries/responses.
            </li>
            <li style="margin-bottom: 15px;">
                Instruction Tuning: Formulating diverse instructions covering typical audit tasks (e.g., "Identify potential fraud indicators in this transaction log," "Explain the relevant regulation for expense X," "Summarize the key findings from report Y").
            </li>
        </ul>
    </div>
venue: "AITA and Henan Provincial Audit Department, Henan, China"
start-date: 2024-12-15
end-date: 2025-04-01
---