---
title: Failure Claims Assessment
type: project
draft: false
featured_image: ""
summary: "Small Language Model fine-tuned for specialized tasks"
weight: 3
authors: []
show_authors: false
show_date: false
show_reading_time: false
show_related: false
show_comments: false
hide_image: true
---

AI-powered system that analyzes equipment failure claims and generates detailed assessments using a fine-tuned GPT-2 language model.

***Key Features***
- **Intelligent Analysis**: Fine-tuned GPT-2 Large model for specialized claim assessment
- **Efficient Architecture**: PEFT/LoRA adapters keep model size small (~10-20MB)
- **Rich Training Data**: 3,000 synthetic claims covering diverse equipment & failure scenarios
- **Production-Ready**: Deployed on Hugging Face Spaces with Docker

**Tech Stack** : Python • Transformers • PEFT/LoRA • Streamlit • Docker • Hugging Face Spaces

**Impact** : End-to-end ML workflow demonstrating data generation, model fine-tuning, and production deployment at scale.

**Demo** https://velagalasr-failure-claims-assessment.hf.space
<iframe
	src="https://velagalasr-failure-claims-assessment.hf.space"
	frameborder="0"
	width="950"
	height="850"
></iframe>
