# API Usage Justification

This project requires high API usage because each legal reasoning task involves multiple model calls.

Pipeline:
User Input → Persona Router → Legal Reasoning → Verification → QC → Output

Benchmark experiments run multiple agents on the same legal problems.
