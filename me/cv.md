# CV -- Avigya Paudel

**Location:** Schenectady, NY (Union College)
**Email:** avigyapaudel045@gmail.com
**LinkedIn:** linkedin.com/in/avigya-paudel-531119306
**Portfolio:** avigya.vercel.app
**GitHub:** github.com/Avi161

## Professional Summary

CS & Math sophomore at Union College (4.0 CS GPA, 3.98 cumulative) splitting time between two tracks: ML / AI safety research (NeurIPS 2025 Workshop paper as co-first-author, two research fellowships, ongoing departmental research role) and software engineering (full-stack projects, hackathons, web-dev internship). I keep doing both because the research forces me to reason carefully about what models are actually doing, and shipping working systems keeps me from getting lost in abstractions. Looking for ML/AI research fellowships or software engineering internships — I will take a strong offer from either side.

## Recent research (last 12 months)

- Trained linear probes on Qwen3-4B residual stream activations across all 36 layers. Hit 99.2% test accuracy at Layer 26, showing the model linearly encodes temporal horizon without any explicit time cues in the prompt. SPAR / AI Safety Camp, ongoing.
- Co-first-authored *Mitigating Sycophancy in Language Models via Sparse Activation Fusion and Multi-Layer Activation Steering*, accepted at the **NeurIPS 2025 Workshop on Mechanistic Interpretability**. Reduced sycophancy in Gemma-2-2b-it from 78% to 0% with only a 3.75% average accuracy trade-off.
- Contrastive Activation Addition (CAA) experiments steering model outputs toward short- or long-term reasoning on neutral prompts, with Layer 22 identified as the optimal injection point via a forced-choice logprob sweep across layers and steering coefficients.

## Work & Research Experience

### SPAR & AI Safety Camp -- Remote
**AI Safety Research Fellow**
Jan 2026 -- Present

- Trained linear probes on residual stream activations of Qwen3-4B across all 36 layers, achieving 99.2% test accuracy at Layer 26, confirming the model linearly encodes temporal horizon even without explicit time cues.
- Steered model outputs toward short-term or long-term reasoning on neutral prompts using Contrastive Activation Addition (CAA); identified Layer 22 as the optimal injection point via a forced-choice logprob sweep across layers and steering coefficients.
- Built a dataset of 800 prompt pairs (300 implicit, 500 explicit) spanning 10 semantic categories to study temporal horizon representations without surface temporal cues. Used Claude Opus 4.6 and Gemini 3 Pro as validation agents.

### Algoverse -- Remote
**Machine Learning Researcher**
May 2025 -- Sept 2025

- Implemented Multi-Layer Activation Steering (MLAS) on Gemma-2-2b-it using TransformerLens hooks across 26 residual layers, computing anti-sycophancy directions via PyTorch tensor operations. Reduced sycophancy from 78% to 0% while restoring accuracy from 45% to 68%. Team of 4.
- Co-engineered a Sparse Activation Fusion pipeline by integrating HuggingFace Transformers with custom Sparse Autoencoders, applying prompt-conditioned bias subtraction in latent feature space. Reduced sycophancy from 63% to 39% and doubled accuracy when users held incorrect opinions.
- Built an inference-time intervention framework with custom PyTorch hooks, batch processing, and evaluation on StrategyQA, GSM8K, MMLU, and SVAMP. Training-free bias mitigation with a 3.75% average accuracy trade-off.
- Work accepted at NeurIPS 2025 Workshop on Mechanistic Interpretability (co-first author).

### Union College -- Schenectady, NY
**Undergraduate Research Assistant, Department of Computer Science**
Jan 2025 -- Present

- Implemented Strassen's algorithm in Python using recursive divide-and-conquer. 8% empirical runtime improvement; theoretical complexity reduced from O(n^3) to O(n^2.81).
- Modeled 3×3 matrix multiplication as a SAT problem by translating ~729 Brent equations into ~130,000 CNF clauses. Re-derived Laderman's 23-product algorithm using a custom NumPy-based tensor framework.
- Built a testing harness using Python's multiprocessing module to analyze solver performance through randomized exclusion experiments, logging unique solutions to JSON for validation.

### Nobel Navigators -- Remote
**Web Development & Leadership Intern**
June 2024 -- Aug 2024

- Co-developed a WordPress site on the AI revolution, presented during a bi-weekly EXPO showcase to 65+ members.
- Co-facilitated 12 training sessions for 40+ interns on leadership and introductory web development. Every intern presented their own website at the end of the program.

## Publications

- Adityo, N.\*, Min, P. P.\*, **Paudel, A.\***, Rufail, A.\*, Zhu, A.\*, Blondin, C., Zhu, K., Dev, S., & O'Brien, S. (2025). *Mitigating Sycophancy in Language Models via Sparse Activation Fusion and Multi-Layer Activation Steering.* **NeurIPS 2025 Workshop on Mechanistic Interpretability.** \*Equal contribution. [[PDF]](https://openreview.net/pdf?id=BCS7HHInC2)

## Projects

- **FloodNet: Multi-Modal Disaster Prediction** ([GitHub](https://github.com/Avi161/AI4ALL-5A)) -- PyTorch. Multi-modal deep learning model fusing Sentinel-1 (SAR) and Sentinel-2 (optical) satellite imagery for flood detection. 91.5% accuracy, 0.979 AUC, 92.7% recall on SEN12-FLOOD. 3-layer CNN with dropout, Adam, and a custom preprocessing pipeline (log-scale SAR + min-max optical) for robust detection in cloud-covered regions.
- **CreateStory** ([GitHub](https://github.com/Avi161/CreateStory) · [Live](https://createstory.onrender.com/)) -- Node.js, Express, MongoDB, EJS, Socket.IO. Full-stack storytelling web app: draft, edit, publish. REST API wired to an EJS front-end with live updates via Socket.IO, <200ms latency for 10 concurrent editors. Deployed on Render with CI/CD and MongoDB Atlas, session-based auth, 75+ stories shared in public beta.
- **WriteLight** ([GitHub](https://github.com/freeCodeCamp-2025-Summer-Hackathon/purple-array) · [Demo](https://imgur.com/a/Fuy2W5k)) -- freeCodeCamp 2025 Summer Hackathon, 10-person team. Designed backend architecture for coin-based reward tracking and in-app item purchases using MongoDB schemas and RESTful API routes for user auth. Resolved frontend/backend data flow issues across the team.
- **AI Summarizer & Translator** ([GitHub](https://github.com/Avi161/AI-Summariser-and-Translator) · [Demo](https://imgur.com/a/VJN8MFo)) -- Chrome extension using the GPT-4o API to summarize and translate web content across 10 languages. Secure token handling, client-side rate limiting, Tailwind CSS UI.

## Education

### Union College -- Schenectady, NY
**BS Computer Science & Mathematics, Minor in Statistics**
Sept 2024 -- June 2028 (expected)

- GPA: **3.98/4.0** cumulative · **4.0/4.0** Computer Science · **3.96/4.0** Mathematics
- Honors: Generation Google Scholar, Union Scholar, Dean's List, Uber Career Prep Fellow
- CS coursework: Object-Oriented Programming, Data Structures, Algorithm Design & Analysis
- Math coursework: Probability Theory, Linear Algebra, Discrete Mathematics, Enriched Differential Vector Calculus (Honors), Integral Vector Calculus, Differential Equations, Logic and Set Theory, Geometry, Abstract Algebra, Numerical Analysis, Mathematical Statistics
- Activities: ICPC Team Member, ACM Member, Mathematics Club

## Teaching & Leadership

### Union College Calculus Help Center -- Schenectady, NY
**Calculus Tutor** · Sept 2025 -- Present

- Led weekly study sessions for 200+ students across pre-calculus algebra, single-variable calculus, and vector calculus, tailoring explanations to individual learning styles.
- Created visual aids and step-by-step breakdowns for integration techniques, partial derivatives, and multivariable optimization.

### Union College Badminton Club -- Schenectady, NY
**President** · Jan 2025 -- Present

- Grew the club to 30+ active members through weekly practices and termly sign-up events.
- Ran on-campus tournaments and mixed-doubles games for players of all levels.

## Presentations

- **Poster:** *Finding Tensor Rank.* Union College Undergraduate Summer Research Poster Session, Lally Reading Room (Schaffer Library), Schenectady, NY. July 24, 2024. Co-authors: Shravani Kulkarni, Brodie Flaherty. Adviser: Dr. Matthew Anderson.

## Skills

**ML / AI research:** PyTorch, TransformerLens, HuggingFace Transformers, Sparse Autoencoders, activation steering (CAA, MLAS), linear probes, inference-time interventions. NumPy, Pandas, scikit-learn, TensorFlow, Matplotlib. Eval benchmarks I've actually worked with: StrategyQA, GSM8K, MMLU, SVAMP.

**Software engineering:** Python (daily), C/C++, Java, JavaScript/TypeScript, Swift, SQL. React, Node.js, Express, Flask, Tailwind CSS, HTML/CSS. REST APIs, Socket.IO. MongoDB, MySQL, PostgreSQL. Git/GitHub, Docker, Arduino, Claude Code. CI/CD on Render with MongoDB Atlas.

**Math & tooling:** Linear algebra, probability theory, abstract algebra, numerical analysis, mathematical statistics. SAT solvers / CNF encoding (PySAT). Python multiprocessing.