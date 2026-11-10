# Paper inventory

Working inventory created from the supplied PDF: `published research papers.pdf`.

**Evidence rule:** publication metadata, methods, and findings below are transcribed or condensed from the source. “Unavailable” means the supplied material does not state the field. Numerical claims are retained only where the paper presents them; labels on the website identify illustrative, simulated, case-study, or source-reported status where relevant.

**Distinct papers found:** 15

## 1. A Multi-Agent Architecture for Autonomous Security-Focused Code Review in GitHub Pull Requests
- **Authors:** Jahnavi Somaraju · Sreevathsa Ganesh P R
- **Affiliation:** Department of Artificial Intelligence and Data Science, Aditya College of Engineering, Madanapalle
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** Security review of pull requests is often manual, inconsistent, and dependent on reviewer expertise. The paper proposes the AppSec Review Agent: a five-agent architecture with an Orchestrator, three deterministic specialist agents for static analysis, dependency-CVE lookup, and secret scanning, and an LLM Reasoning Agent supported by three memory tiers. Agents communicate through the Model Context Protocol (MCP).
- **Research problem:** A monolithic LLM must parse code, recall vulnerability patterns, reason about exploitability, prioritize issues, and phrase a response in one undifferentiated pass. The paper identifies confirmation bias, inconsistent repeated runs, and brittle point-to-point integrations as design problems.
- **Method / proposed approach:** PR event enters a stateless GitHub Action; Orchestrator classifies changed files and routes relevant checks; Static, dependency, and secret specialists return structured findings; Aggregator applies severity-max conflict resolution; LLM agent retrieves memory and writes explanation, severity, and fix suggestion
- **Evidence / findings:** The case study supports the intended division of labor: the vulnerability was caught before the LLM call, while the LLM contributed explanation and a parameterized-query suggestion.
- **Keywords:** Multi-Agent Systems, Agentic AI, Application Security, Large Language Models, Model Context Protocol, Retrieval-Augmented Generation, DevSecOps, Vector Memory
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL stated in source: www.ijsred.com.

## 2. Toward Planetary-Scale Intelligence: A Multi-Agent Framework for Cross-Domain Environmental Anomaly Detection and Reasoning
- **Authors:** Jahnavi Somaraju · V. Rohini
- **Affiliation:** Department of Artificial Intelligence and Data Science, Aditya College of Engineering, Madanapalle
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** The Planetary Intelligence System (PIS) coordinates perception, geo-spatial, temporal-pattern, and hazard-domain agents across satellite imagery, ground sensors, weather telemetry, seismic instrumentation, and text. It uses a typed message bus, tiered memory, retrieval-augmented knowledge, capability routing, weighted consensus, and conflict resolution.
- **Research problem:** A single model or agent struggles to combine different data types, maintain domain expertise, isolate failures, and produce an auditable real-time decision trail.
- **Method / proposed approach:** Normalize and stream heterogeneous telemetry; Perception pool scores candidate anomalies; Supervisor decomposes hypotheses into typed domain tasks; Hydrology, wildfire, air-quality, and seismic agents reason in parallel; Consensus, memory update, and human escalation shape delivery
- **Evidence / findings:** The paper reports F1 improvement of 9.4–16.7 percentage points, 31% lower end-to-end latency, and more than half reduction in false-positive rate; removing consensus or vector memory degraded accuracy most in the ablation.
- **Keywords:** Multi-agent systems, Environmental monitoring, Anomaly detection, Large language models, Orchestration, Retrieval-augmented generation, Distributed AI, Planetary intelligence
- **DOI / URL availability:** No DOI is stated for this paper in the supplied source. Publication URL stated in source: www.ijsred.com.

## 3. MANTIS: A Multi-Agent Architecture for Training and Benchmarking Neural Machine Translation Models
- **Authors:** Jahnavi Somaraju · Nandyala Mamatha
- **Affiliation:** Department of Artificial Intelligence and Data Science, Aditya College of Engineering, Madanapalle
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** MANTIS decomposes neural machine translation experimentation across data curation, preprocessing, training, hyperparameter search, evaluation, error diagnosis, and reporting. A central orchestrator, shared three-tier memory, and closed feedback loop coordinate specialized LLM-driven agents.
- **Research problem:** Manual notebooks and shell scripts obscure provenance and slow iteration; rigid automation cannot adapt to failures or reuse knowledge across experiments.
- **Method / proposed approach:** Parse a translation task specification; Curate and preprocess parallel corpora; Train and checkpoint Transformer models; Search hyperparameters and evaluate quality; Analyze errors, update memory, and trigger a new run when warranted
- **Evidence / findings:** The contribution is architectural and methodological: MANTIS makes experiment stages independently testable and connects evaluation/error analysis to future run planning. The supplied source does not present completed benchmark numbers.
- **Keywords:** Multi-agent systems, Neural machine translation, LLM agents, Retrieval-augmented generation, Hyperparameter optimization, Benchmarking
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL stated in source: www.ijsred.com.

## 4. A Multi-Agent Architecture for AI-Based Early Screening, Referral, and Prediction of Retinal Diseases
- **Authors:** Jahnavi Somaraju · Poolasetti Vamshi
- **Affiliation:** Department of Artificial Intelligence and Data Science, Aditya College of Engineering, Madanapalle
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** The Retinal Screening and Referral Agent (RSRA) separates image quality and preprocessing, lesion detection, disease classification and risk prediction, deterministic referral decisions, and LLM report generation across six cooperating agents. MCP and three-tier memory connect the workflow.
- **Research problem:** Single-pipeline classifiers conflate capture quality, lesion detection, severity, referral triage, and explanation, making errors hard to localize and clinician trust harder to earn.
- **Method / proposed approach:** Ingest and normalize a fundus image; Gate blur, glare, and field-of-view problems; Detect lesions and classify disease risk; Apply guideline-encoded referral logic; Generate an explanation and referral letter for clinician review
- **Evidence / findings:** The case study reports that quality passed, a lesion was detected in the superior-temporal quadrant, and the deterministic referral agent assigned an urgent within-four-weeks tier. This is a simulated case, not clinical validation.
- **Keywords:** Multi-Agent Systems, Agentic AI, Diabetic Retinopathy, Retinal Disease Screening, Clinical Decision Support, Large Language Models, MCP, RAG, Vector Memory
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL stated in source: www.ijsred.com.

## 5. Javipra AI: A Confidence-Weighted Multimodal Sensor Fusion Framework for Autonomous, Privacy-Preserving Emergency Detection and Response on Edge Devices
- **Authors:** Jahnavi Somaraju · Chethan Kumar Reddy P
- **Affiliation:** Department of Artificial Intelligence and Data Science, Aditya College of Engineering, Madanapalle, Andhra Pradesh, India
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** Javipra AI proposes the Javipra Confidence Fusion Engine (JCFE), combining voice keyword spotting, speech emotion recognition, audio event detection, human activity recognition, and GPS context analysis. The design models inter-module agreement and temporal persistence, executes on-device with TensorFlow Lite, and escalates only after an adaptive decision threshold is crossed.
- **Research problem:** Manual distress activation fails when a person is unconscious, restrained, assaulted, or otherwise unable to reach a device. Isolated modality systems cannot turn uncertain signals into a calibrated action.
- **Method / proposed approach:** Continuously inspect local audio and motion streams; Score independent perception modules; Add context and risk weighting; Fuse evidence through JCFE; Trigger location sharing, trusted-contact notification, encrypted audio, and heightened monitoring when confirmed
- **Evidence / findings:** The source contribution is a complete framework and validation plan for autonomous, local emergency inference; performance claims remain to be established by the proposed experiments.
- **Keywords:** Edge AI, Multimodal sensor fusion, Emergency detection, Privacy-preserving computing, Human activity recognition, Speech emotion recognition
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL stated in source: www.ijsred.com.

## 6. SkillSync AI: A Multi-Agent Artificial Intelligence Framework for Dynamic Skill Gap Analysis, Digital Employability Twin, and Personalized Career Roadmaps to Reduce Graduate Unemployment
- **Authors:** Jahnavi Somaraju · Chethan Kumar Reddy P
- **Affiliation:** Department of Artificial Intelligence and Data Science, Aditya College of Engineering, Madanapalle, Andhra Pradesh, India
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** SkillSync AI introduces a Digital Employability Twin representing skills, projects, certifications, interview performance, and behavioral signals over a student’s academic and pre-placement journey. Eighteen specialized agents perform extraction, demand tracking, gap computation, roadmap synthesis, coaching, and prediction.
- **Research problem:** Static resume matching treats the candidate as a one-time document and does not close the loop between diagnosis, learning activity, and readiness.
- **Method / proposed approach:** Extract and provenance-tag profile evidence; Track industry demand vectors; Compute skill gaps and update the twin; Prioritize learning, projects, and certifications; Use coaching and feedback to update readiness and predictions
- **Evidence / findings:** In the reported simulation, the twin-and-roadmap loop closes skill gaps faster than a static baseline. Reported values are simulation outcomes and an upper-bound illustration under stated assumptions, not field placement outcomes.
- **Keywords:** Multi-agent systems, Digital twin, Employability, Skill gap analysis, RAG, Large language models, Career recommendation, Knowledge graph
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL stated in source: www.ijsred.com.

## 7. PromptShield AI: A Multi-Agent Architecture for Intelligent Prompt Injection and Jailbreak Attack Detection Using Machine Learning
- **Authors:** Jahnavi Somaraju · N. Sree Charan · M. Mythili · T. Reddy Bhargavi · K. Navya Sree
- **Affiliation:** Department of Artificial Intelligence, Aditya College of Engineering, Madanapalle
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** PromptShield AI routes requests through five parallel detection agents covering lexical, statistical, semantic, and contextual signals. A Decision Fusion Agent combines outputs; a Response/Mitigation Agent allows, sanitizes, or blocks; and a Logging and Feedback Agent supports retraining.
- **Research problem:** Single-mechanism defenses expose one decision boundary and can be evaded by paraphrase, obfuscation, or multi-turn manipulation.
- **Method / proposed approach:** Normalize incoming request and context; Run inexpensive and specialized detectors in parallel; Calibrate and fuse confidence scores; Apply a safety-priority conflict rule; Log decisions and feed verified outcomes back into learning
- **Evidence / findings:** The architectural argument is that complementary blind spots can be combined, but the supplied numerical comparison (including the reported full-pipeline F1) is illustrative rather than completed validation.
- **Keywords:** Prompt injection, Jailbreak detection, Multi-agent systems, Ensemble machine learning, NLP security, LLM guardrails
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL stated in source: www.ijsred.com.

## 8. TruthLens: Real-Time Evidence Verification and AI Hallucination Detection for Large Language Models via a Multi-Agent Architecture
- **Authors:** Jahnavi Somaraju · K. Ramyasree · K. Jashnavi · B. Madhu Sri · Y. Sumathi
- **Affiliation:** Department of Artificial Intelligence, Aditya College of Engineering, Madanapalle
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** TruthLens decomposes real-time verification across an Orchestrator, Retrieval, Evidence Verification, Hallucination Detection, and Response Synthesis agents. Claims are accepted only when corroborating evidence crosses a confidence threshold, with shared vector memory and feedback.
- **Research problem:** Single-agent RAG can conflate retrieval, reasoning, and verification. Fluent but unsupported statements remain difficult for users to recognize.
- **Method / proposed approach:** Retrieve candidate sources for a claim; Verify entailment and source support; Estimate hallucination risk independently; Resolve disagreement through a confidence rule; Synthesize a response with evidence context
- **Evidence / findings:** The reported result is source-stated: TruthLens reduced observed hallucination rate by 46.8% relative to the single-agent RAG baseline, with moderate latency overhead; the paper attributes the largest ablation contribution to Evidence Verification and Hallucination Detection.
- **Keywords:** Trustworthy AI, RAG, Hallucination Detection, Multi-Agent Systems, Fact Verification, Large Language Models
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL stated in source: www.ijsred.com.

## 9. SkillGraph: A Multi-Agent Architecture for AI-Powered Career Recommendation Using Knowledge Graphs and Graph Neural Networks
- **Authors:** Jahnavi Somaraju · V. Guru Thrinath · S. R. Bhavishya · S. Bhavya · Y. Jahnavi
- **Affiliation:** Department of Artificial Intelligence, Aditya College of Engineering, Madanapalle
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** SkillGraph combines a skill-career knowledge graph, GNN-based ranking, and LLM-driven agents. Specialized agents extract profiles, retrieve graph neighborhoods, rank candidates, plan career paths, and incorporate feedback through shared memory.
- **Research problem:** Content-based and collaborative recommendation can hide why a role was suggested and struggle with changing external information, path planning, and feedback.
- **Method / proposed approach:** Extract skills and goals from profile evidence; Retrieve a relevant graph neighborhood; Rank roles and skills with a GNN; Plan a path through skill and learning relationships; Re-rank using feedback and synthesize an explanation
- **Evidence / findings:** The source reports higher ranking quality than the listed baselines and identifies the orchestrator and shared memory as the largest task-completion contributors in ablation. The paper also notes live-user evaluation as future work.
- **Keywords:** Multi-agent systems, Knowledge graphs, Graph neural networks, Career recommendation, RAG, Large language models, Orchestrator agent
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL stated in source: www.ijsred.com.

## 10. VisionGuard: Explainable Deep Learning Framework for Real-Time Anomaly Detection in Surveillance Video
- **Authors:** Jahnavi Somaraju · L. Mounika · M. Mounika · K. Mounika · BS. Karishma
- **Affiliation:** Department of Artificial Intelligence, Aditya College of Engineering, Madanapalle
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** VisionGuard coordinates a Perception Agent, Temporal Reasoning Agent, Explanation Agent, Orchestrator Agent, and Alert and Response Agent. A message bus, hybrid short-term feature store, vector memory, and human feedback channel support explainable triage.
- **Research problem:** Monolithic video detectors are difficult to interpret, brittle under distribution shift, and provide no clear rationale for operator action.
- **Method / proposed approach:** Extract spatio-temporal features from clips; Score short clips for anomalous dynamics; Route decisions and resolve conflicts; Generate saliency-linked explanations; Deliver alerts and incorporate operator verdicts
- **Evidence / findings:** The paper reports a 5.6-point improvement over its strongest evaluated baseline and 29.4 FPS. It also reports recurring failure modes around illumination changes and crowd scenes.
- **Keywords:** Video anomaly detection, Multi-agent systems, Explainable AI, Surveillance, RAG, Human-in-the-loop
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL stated in source: www.ijsred.com.

## 11. AutoResearch: A Multi-Agent AI System for Automated Literature Review, Paper Summarization, and Citation Mapping
- **Authors:** Jahnavi Somaraju · Meenakshi A · Nandini K
- **Affiliation:** Department of Artificial Intelligence and Data Science, Aditya College of Engineering, Madanapalle
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** AutoResearch decomposes literature review across deterministic retrieval, paper parsing and extraction, citation mapping, and an LLM Synthesis Agent. MCP-mediated tools and three-tier memory support a tagged, reproducible case-study protocol.
- **Research problem:** A single LLM must search, read, extract, verify citations, and synthesize at once, increasing fabricated citations, inconsistent coverage, and unexplained inclusion decisions.
- **Method / proposed approach:** Retrieve candidates from academic sources; Parse abstracts, methods, results, and claims; Map citation relationships and evidence context; Deduplicate and aggregate findings; Synthesize with provenance and report gaps
- **Evidence / findings:** The available evidence demonstrates the proposed pipeline’s reporting structure and a worked query, not a completed general benchmark. The design’s central claim is traceable separation of retrieval, extraction, citation mapping, and synthesis.
- **Keywords:** Multi-Agent Systems, Agentic AI, Natural Language Processing, Information Retrieval, Large Language Models, MCP, RAG, Citation Graph Analysis
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL stated in source: www.ijsred.com.

## 12. PhishNet: A Cost-Sensitive Stacked-Ensemble Approach to Machine Learning-Based Phishing Website Detection
- **Authors:** Jahnavi Somaraju · Dhanalakshmi G · Rakshitha V · Kavitha G · Rajani A
- **Affiliation:** Department of Artificial Intelligence and Data Science, Aditya College of Engineering, Madanapalle
- **Venue / year:** International Journal of Scientific Research and Engineering Development · Volume 9, Issue 4 · July–August 2026
- **Abstract / scope:** PhishNet combines tiered feature acquisition with a stacked-generalization ensemble. Cheap lexical and DNS features run first; expensive rendering features are added when uncertainty remains. Fold-safe oversampling and an explicit cost matrix shape the operating point.
- **Research problem:** Legitimate URLs vastly outnumber phishing URLs, while false negatives and false positives have different consequences. Balanced-dataset accuracy and fixed thresholds do not reflect deployment conditions.
- **Method / proposed approach:** Run lexical and DNS checks; Stop early when confidence crosses a threshold; Escalate to DOM and rendering features when ambiguous; Fuse five tier-appropriate learners with logistic regression; Select a deployment operating point through expected cost
- **Evidence / findings:** PhishNet’s supported contribution is a deployment-oriented design that treats cost and imbalance as first-class constraints. The worked score is case-study evidence, not a general performance claim.
- **Keywords:** Phishing detection, Cost-sensitive learning, Stacked generalization, Class imbalance, Cybersecurity, Feature engineering, LightGBM, Machine learning
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL stated in source: www.ijsred.com.

## 13. Digital Twin-Driven Predictive Healthcare Advisor Using Multimodal AI
- **Authors:** S. Jahnavi · M Sivakrishna · G Gopi Krishna · A Hemanth
- **Affiliation:** Department of Artificial Intelligence & Data Science, Aditya College of Engineering, Madanapalle, India
- **Venue / year:** International Journal of Science and Technology (IJST) · 2(3):36–41 · 2026
- **Abstract / scope:** The paper proposes a Digital Twin-Driven Predictive Healthcare Advisor that collects EHR data, wearable IoT signals, laboratory results, and medical imaging. A patient-specific digital twin is initialized, analyzed with multimodal AI, and used to produce explainable predictions and recommendations.
- **Research problem:** Reactive healthcare relies on periodic visits and often misses deterioration between appointments. Heterogeneous data sources are difficult to analyze together in real time.
- **Method / proposed approach:** Authenticate and collect patient data; Initialize the digital twin; Combine structured, imaging, and sensor signals; Run risk analysis and feature explanations; Display predictions and recommendations
- **Evidence / findings:** The available paper supports a system proposal and validation framing around efficiency, reduced manual effort, and healthcare quality; it does not provide enough numerical evidence for a chart here.
- **Keywords:** Digital Twin, Predictive Healthcare, Multimodal AI, Disease Prediction, Healthcare Analytics, Real-Time Monitoring, EHR, Wearable Sensors, Explainable AI
- **DOI / URL availability:** No DOI is stated in the supplied paper. Publication URL is not stated in the supplied source.

## 14. ResuMind: A Unified Platform for ATS-Friendly Resumes, Career Guidance, Gamified Assessment, and AI Mock Interviews
- **Authors:** Mayuri Kurabalakota · Jagadesh Bhumika · Lakkireddy Himaja Reddy · Jahnavi Somaraju · Dr. M. Roshini
- **Affiliation:** Department of CSE-AI, Aditya College of Engineering, Madanapalle, India
- **Venue / year:** International Journal of Scientific Development and Research (IJSDR) · Volume 10, Issue 10 · October 2025 · IJSDR2510067
- **Abstract / scope:** ResuMind integrates ATS-friendly resume creation, LinkedIn import and normalization, ATS scoring, conversational career guidance, gamified aptitude and soft-skills assessments, job-portal integration, and AI mock interviews.
- **Research problem:** Existing tools often optimize one job-readiness step while leaving candidates to stitch together resume, guidance, assessment, and interview practice themselves.
- **Method / proposed approach:** Parse resumes and profiles; Generate structured ATS-friendly documents; Score keywords, semantic similarity, and formatting; Adapt assessment difficulty; Generate interview questions and feedback
- **Evidence / findings:** ResuMind presents an integrated platform and reports preliminary improvements, while its own evaluation plan calls for parsing accuracy, ATS gains, user satisfaction, engagement, and response-time measures. Treat the results as source-reported preliminary claims.
- **Keywords:** ATS, Resume parsing, Resume scoring, Career guidance, Chatbot, Gamification, Mock interview, Natural language processing, Embeddings
- **DOI / URL availability:** No DOI is stated. Source URL/identifier: www.ijsdr.org · IJSDR2510067.

## 15. MicroTrack: An Integrated Platform for Microplastic Spectral Signature Capture, Autonomous AI Classification, and Scalable IoT Deployment
- **Authors:** V. Meenhaz · S. Mohammed Saif · Jahnavi Somaraju · Dr. M. Roshini
- **Affiliation:** Department of CSE-AI, Aditya College of Engineering, Madanapalle, India
- **Venue / year:** International Journal of Scientific Development and Research (IJSDR) · Volume 10, Issue 10 · October 2025 · IJSDR2510143
- **Abstract / scope:** MicroTrack proposes a portable smart sensor that captures optical spectral signatures, filters signals, classifies microplastic types with a CNN on a Raspberry Pi, and sends JSON results through MQTT to a cloud dashboard.
- **Research problem:** FTIR and Raman spectroscopy can be accurate but expensive and laboratory-bound. Field monitoring needs a lower-cost, intelligent, connected approach.
- **Method / proposed approach:** Illuminate and measure water-sample reflections; Filter noise and normalize signals; Classify PE, PP, PS, and PET signatures; Transmit JSON detection results via MQTT; Visualize pollution levels and trends in a dashboard
- **Evidence / findings:** The paper reports that the sensor classified named polymer types under varying water conditions and operated with secure cloud transmission and low power. These are source-stated results; the supplied material does not include sample counts or uncertainty intervals.
- **Keywords:** Smart sensor system, Microplastics detection, Artificial intelligence, Internet of Things, Environmental monitoring, CNN, Optical sensing, Cloud dashboard
- **DOI / URL availability:** No DOI is stated. Source URL/identifier: www.ijsdr.org · IJSDR2510143.
