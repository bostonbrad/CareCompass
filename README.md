# ☤ Care 🩺 Compass 🧭
RAG AI app for care managers, uses InterSystems IRIS as the Vector Store and 
Gradio for front end user interface.

Introducing Care Compass: AI-Powered Case Prioritization for Human Services
In today’s healthcare and social services landscape, caseworkers face overwhelming challenges. High caseloads, fragmented systems, and disconnected data often lead to missed opportunities to intervene early and effectively. This results in worker burnout and preventable emergency room visits, which are both costly and avoidable.

Care Compass was created to change that.

*Disclaimer: Care Compass project is a technical demonstration developed by sales engineers and solution engineers. It is intended for educational and prototyping purposes only. We are not medical professionals, and no part of this project should be interpreted as clinical advice or used for real-world patient care without appropriate validation and consultation with qualified healthcare experts.

The Problem
Twelve percent of Medicaid beneficiaries account for 38 percent of all Medicaid emergency department (ED) visits. These visits are often driven by unmet needs related to housing instability, mental illness, and substance use. Traditional case management tools rarely account for these upstream risk factors, making it difficult for caseworkers to identify who needs help most urgently.

This data comes from a 2013 study published in The American Journal of Emergency Medicine, which highlights how a small portion of the Medicaid population disproportionately contributes to system-wide costs
(Capp et al., 2013, PMID: 23850143).

Too often, decisions are reactive and based on incomplete information.

Our Solution
Care Compass is an AI-powered assistant that helps caseworkers make better decisions based on a complete picture of a client’s medical and social needs. It combines Retrieval-Augmented Generation (RAG) and large language models to interpret data and generate actionable insights.

The assistant assesses real-time information, summarizes key risk factors, calculates dynamic risk scores, and recommends possible next steps and resources. Instead of combing through disconnected records, caseworkers get a unified view of their caseload, prioritized by urgency and context.

How It Works
The platform integrates a large language model, real-time data retrieval, and custom reasoning logic. Information from structured and unstructured sources is synthesized into readable summaries that explain not only the level of risk, but why a client is considered high-risk.

An intuitive user interface makes it easy for caseworkers to interact with the assistant, review insights, and take appropriate action. The emphasis is on transparency and trust. The system doesn’t just score risk; it explains its reasoning in plain language.

Lessons Learned
Building Care Compass has taught us that raw model accuracy is only part of the equation. We’ve learned that:

Small datasets limit the effectiveness of retrieval-based methods
Structured data is often inconsistent or incomplete
Fine-tuning models does not always improve performance
Interpretability is essential—especially for systems that guide care decisions
HIPAA compliance and data privacy must be built into the system from the beginning
Looking Ahead
Our next steps include expanding our dataset with more diverse and representative cases, experimenting with different embedding models, and incorporating evaluation metrics that reflect how useful and understandable the assistant’s outputs are in practice.

We’re also exploring how to better communicate uncertainty and strengthen the ethical foundations of the system, especially when working with vulnerable populations.

Care Compass is our response to a widespread need in health and human services: to prioritize what matters, before it becomes a crisis. It empowers caseworkers with the clarity and tools they need to act earlier, intervene more effectively, and deliver more equitable outcomes.

To see more about how we implemented the solution, please watch our youtube video:
https://youtu.be/hjCKJxhckbs
