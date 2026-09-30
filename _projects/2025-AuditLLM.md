---
title: "Large Language Model for Audit"
collection: projects
# type: "LLM for Audit"
# permalink: /projects/2025-AuditLLM
excerpt: |
    <div style="text-align: justify; font-size: 16px; color: inherit; margin: 0px 0px 0px 0px;">
        <p>
            The primary objective of this project is to design, fine-tune and deploy a secure, internally-facing Audit Large Language Model (ALLM) to empower auditors at <a href="https://sjt.henan.gov.cn/" style="text-decoration: none;">Henan Provincial Audit Department</a>. Built atop Qwen2.5-VL, ALLM need deliver intelligent support for audit Q&A, regulatory compliance and table-data analysis, improving audit efficiency and accuracy. In this project, I worked with Lutong Zhang and Haonan Zhang to finish:
        </p>
        <ul style="padding-left: 30px; margin-top: 0;">
            <li style="margin-bottom: 15px;">
                Data Collection: Aggregating amounts of audit documentation, historical audit reports, government financial regulations (national and provincial level), accounting standards (e.g., Chinese GAAP), policy directives, compliance manuals, and best practice guidelines.
            </li>
            <li style="margin-bottom: 15px;">
                Data Processing: Implementing data processing pipelines for heterogeneous audit sources, including: text extraction that applies PaddleOCR with regex-based digit correction for scanned documents, pdfplumber for layout-aware PDF, python-docx for DOCX files; spaCy + FinBERT for entity normalization of regulations/financial terms; DeepSeek-V2 classification for document categorization and UIE model for sensitivity tagging; LayoutLMv3 for context-aware semantic segmentation to preserve audit logic.
            </li>
            <li style="margin-bottom: 15px;">
                QA Generation and Expert Annotation: Using Qwen-72B-Chat to produce question-answer pairs reflecting common audit scenarios, enriching the fine-tuning dataset; collaborating with senior auditors to annotate real audit cases, identifying key entities, risks, compliance issues, and generating relevant queries/responses.
            </li>
        </ul>
    </div>
venue: "AITA and Henan Provincial Audit Department, China"
start-date: 2024-12-15
end-date: 2025-04-01
---