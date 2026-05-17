# brsr-forensic-audit-nlp
NLP-driven forensic audit pipeline for detecting inconsistencies between BRSR disclosures and external regulatory evidence across selected NIFTY 50 companies.
This project presents an NLP-driven forensic audit pipeline designed to evaluate the consistency between Business Responsibility and Sustainability Report (BRSR) disclosures and independently retrieved external regulatory evidence.

The system applies Natural Language Processing (NLP), Natural Language Inference (NLI), and automated evidence retrieval techniques to identify disclosure inconsistencies, strategic silence, and transparency risks among selected NIFTY 50 companies.

The project was developed as part of my MSc Analytics dissertation at Tata Institute of Social Sciences (TISS), Mumbai.

Problem Statement- Corporate ESG disclosures are largely self-reported and often lack systematic external verification.

While the BRSR framework introduced by SEBI standardizes sustainability reporting in India, there remains a significant verification gap between disclosed claims and real-world regulatory actions.

This project attempts to bridge that gap through an automated NLP-based forensic audit framework capable of:
- Extracting disclosure claims from BRSR reports
- Retrieving external regulatory evidence
- Performing semantic consistency checks
- Generating transparency risk indicators

- ## Objectives

- Build a modular NLP-driven forensic audit pipeline
- Extract penalty-related disclosure claims from BRSR PDFs
- Retrieve external regulatory and media evidence
- Apply RoBERTa-based Natural Language Inference (NLI)
- Classify disclosure consistency outcomes
- Generate structured audit outputs and transparency risk metrics

- ## Methodology

The pipeline consists of four major stages:

1. Disclosure Claim Extraction
   - PDF parsing
   - Rule-based extraction hierarchy
   - Penalty disclosure detection

2. External Evidence Retrieval
   - Tavily AI search integration
   - Regulatory notice retrieval
   - News evidence collection

3. NLI-Based Consistency Classification
   - Cross-encoder RoBERTa model
   - Semantic contradiction detection
   - Entailment and neutrality scoring

4. Structured Output Generation
   - Excel audit reports
   - Risk classification tables
   - Transparency Risk Rate (TRR) calculation
  
   - ## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- HuggingFace Transformers
- RoBERTa
- NLP / NLI
- OpenPyXL
- PDF Processing
- ESG Analytics

- ## Key Findings

- 51.2% of observations showed Insufficient Disclosure
- 12.2% exhibited semantic contradiction with external evidence
- Banking sector firms demonstrated comparatively higher disclosure consistency
- The overall Transparency Risk Rate (TRR) was 63.4%
- Pipeline achieved ~87.8% validation accuracy after manual verification

- ## Research Contribution

This work contributes to:
- Computational ESG analytics
- AI-assisted forensic auditing
- Automated sustainability disclosure verification
- NLP applications in governance analytics
- BRSR transparency assessment in India

- ## Future Improvements

- Domain-specific fine-tuning for ESG NLI tasks
- Improved table extraction from BRSR PDFs
- Scalable entity disambiguation system
- Real-time regulatory monitoring integration
- Expansion to full NIFTY 50 coverage

- 
