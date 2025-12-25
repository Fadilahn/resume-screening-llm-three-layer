# Resume Screening System with LLMs

Sistem otomatis untuk screening resume menggunakan Large Language Models (LLMs). Sistem ini mengevaluasi kesesuaian kandidat terhadap job description menggunakan pipeline multi-layer.

## Fitur Utama
- Ekstraksi informasi terstruktur dari resume dan job description
- Evaluasi multi-aspek (skill match, experience, domain fit, dll.)
- Pipeline modular dengan 3 layer (Extraction → Evaluation → Decision)

## Arsitektur
- Layer 1: LLM Extraction (resume & JD)
- Layer 2: Multi-Aspect Scoring
- Layer 3: Weighted Aggregation + Decision Rules

## Instalasi

```bash
# Clone repository
git clone https://github.com/username/resume-screening-llm.git
cd resume-screening-llm

# Install dependencies
pip install -r requirements.txt

# Setup HuggingFace token
export HUGGINGFACE_TOKEN="[token]"
