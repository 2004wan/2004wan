# Hi, I'm Yiran (Emily) Wang 👋

### Data Science Graduate | Machine Learning Explorer | AI-Assisted Builder

I recently completed my Master of Data Science at the University of British Columbia.

My interests go beyond traditional data analysis. I enjoy exploring machine learning, computer vision, data-driven applications, and the engineering behind intelligent systems. I am also currently strengthening my foundations in algorithms, data structures, and problem-solving.

As AI continues to reshape the way we work and learn, I actively explore tools such as ChatGPT, Codex, Gemini, and DeepSeek to support coding, research, debugging, and idea development. At the same time, I believe AI-generated results should always be reviewed, tested, and improved through human judgment.

What makes me happiest is not only building something that works, but also discussing ideas, collaborating with people, and turning technical results into explanations that others can understand.

---

## 🧭 What I'm Currently Exploring

- Machine learning and computer vision
- Algorithms and data structures
- AI-assisted software development
- Data analytics and visualization
- Practical applications of large language models
- Communicating technical insights to non-technical audiences

---

## 🤖 Machine Learning & AI

### VLM-Based Security Action Detection

A real-time video monitoring system for detecting security-relevant actions with vision-language models and limited labeled data.

This project turns raw surveillance-style videos into an end-to-end action recognition workflow: video clipping, CVAT annotation alignment, model training/evaluation, and webcam-based inference. We compared CLIP, X-CLIP, ViCLIP, Qwen-VL, prototype-based methods, and CoOp prompt tuning across both model quality and deployment practicality.

**Highlights**
- Built a full video action detection pipeline from raw videos to real-time inference
- Processed annotated video data into fixed-length clips aligned with CVAT labels
- Evaluated VLM-based methods across accuracy, Macro-F1, latency, prompt sensitivity, and reliability
- Combined a CoOp-tuned X-CLIP detector with a lightweight Qwen-VL verifier for uncertain cases
- Achieved **0.858 Macro-F1** on multi-class security action recognition
- Supported actions including fence jumping, vault jumping, falling down, kicking, and punching

**Tech Stack:** Python, PyTorch, CLIP, X-CLIP, ViCLIP, Qwen-VL, CoOp, CVAT

🔗 [View the project on GitHub](https://github.com/2004wan/VLM-Security-Action-Detection)


### FoodVision Transfer Learning Studio

A GUI-first transfer learning workspace for image classification experiments, built around Food-101 and extensible model customization workflows.

This project combines a PySide6 desktop interface with reproducible PyTorch training pipelines, checkpoint management, prediction tools, robustness evaluation, Grad-CAM visualization, and structured custom model generation. It supports comparing baseline fine-tuning strategies with PEFT-style methods such as LoRA, DoRA, TSA, BN tuning, and full fine-tuning.

**Highlights**
- Built an end-to-end desktop studio for training, prediction, evaluation, and experiment analysis
- Implemented reusable PyTorch pipelines for image classification and checkpoint-based inference
- Designed a custom model canvas for generating structured model variants from JSON specs
- Added robustness evaluation across curated test splits and visual comparison tools
- Integrated experiment logs, accuracy curves, confusion matrices, efficiency plots, and Grad-CAM previews

**Tech Stack:** Python, PyTorch, Torchvision, PySide6, Pillow, Matplotlib, JSON-based model specs

🔗 [View the project on GitHub](https://github.com/2004wan/ModelCraft-Studio)


---

## 📊 Data Analytics & Visualization

### VanCrime Lens ###
An interactive geospatial dashboard for exploring Vancouver crime patterns across neighbourhoods, time periods, and crime categories.

This project turns public Vancouver crime records into an end-to-end visual analytics workflow: data cleaning, coordinate transformation, neighbourhood-level GeoJSON mapping, interactive filtering, linked statistical charts, and cloud deployment. The dashboard helps users investigate how crime patterns vary by year, time of day, location, and incident type through coordinated map and chart interactions.

**Highlights**

- Built an end-to-end geospatial crime analytics dashboard from raw public records to a deployed web application
- Processed large-scale Vancouver crime data and converted projected coordinates into map-ready latitude/longitude values
- Aligned incident records with neighbourhood GeoJSON boundaries to support choropleth mapping and spatial drilldown
- Implemented coordinated interactions across filters, maps, summary statistics, and analytical charts
- Added neighbourhood click-to-zoom exploration with point-level incident visualization and dynamic map updates
- Designed time-based analysis views for yearly trends, monthly patterns, hourly distributions, and volatility changes
- Deployed the dashboard with a production-ready Dash, Gunicorn, and Render workflow

**Tech Stack:** Python, Dash, Plotly, Pandas, GeoJSON, PyProj, Gunicorn, Render  

🔗 [View the live dashboard](https://data-551-group8-project.onrender.com/)


### Traffic Accident Analysis
Analyzed approximately **209,000 traffic accident records** across 24 variables.

- Investigated relationships among accident frequency, severity, weather, road conditions, and time
- Cleaned, categorized, and visualized large-scale accident data
- Translated analytical findings into accessible visual explanations

### Agentic PR Testing Analysis ###  
A data-driven software engineering study on how AI coding agents contribute tests in pull requests using the AIDev dataset.

This project analyzes large-scale pull request data to understand testing behavior in agent-generated software changes. It detects test-related PRs from commit files, messages, and review comments, classifies test types such as unit, integration, and end-to-end tests, compares test-code churn with regular code churn across programming ecosystems, and investigates whether human developers intervene when agentic PRs lack tests.

**Highlights**

Built an analysis workflow for detecting test-related changes in AI-generated pull requests  
Processed pull request, commit, review, and timeline data from the AIDev dataset  
Classified test contributions by keyword-based signals from filenames, commit messages, and comments  
Measured test-to-code churn ratios across programming language ecosystems  
Analyzed human follow-up behavior through later commits and review comments  
Generated result tables, visualizations, and final research reports for reproducible analysis  

**Tech Stack:** Python, Pandas, Jupyter Notebook, Matplotlib, Hugging Face Datasets, Parquet

🔗 [View the project on GitHub](https://github.com/2004wan/agentic-pr-testing-analysis)

---

## 💻 Applications & Software Projects

### Python Quizzing Application
Developed components of a Python-based educational quiz application.

- Worked on backend logic and application functionality
- Practiced modular programming, debugging, and collaborative development

### Interactive Data Applications
Built interactive analytical tools using Dash and Plotly.

- Converted raw datasets into accessible user-facing applications
- Focused on usability, filtering logic, visual clarity, and communication of results

---

## 🛠️ Technical Toolkit

**Programming**

`Python` `SQL` `R`

**Machine Learning & AI**

`PyTorch` `scikit-learn` `XGBoost` `Transfer Learning`  
`Computer Vision` `CLIP` `Vision-Language Models`

**Data Analysis & Visualization**

`Pandas` `NumPy` `Excel` `Plotly` `Dash` `Tableau`

**Development & Cloud**

`Git` `GitHub` `VS Code` `AWS`

**AI-Assisted Workflow**

`ChatGPT` `Codex` `Gemini` `DeepSeek`

---

## 🌱 Beyond the Code

I enjoy working in collaborative and international environments. During my undergraduate and graduate studies, I regularly worked with teammates and professors from different cultural and academic backgrounds.

I particularly enjoy:

- Discussing ideas and learning from others
- Presenting technical work in a clear and natural way
- Connecting technical findings with practical needs
- Helping teams organize information and move projects forward

I believe strong technical work becomes more valuable when it can be clearly communicated and effectively applied.

---

## 📫 Connect with Me

- **LinkedIn:** [Add your LinkedIn URL]
- **Email:** [Add your email address]
