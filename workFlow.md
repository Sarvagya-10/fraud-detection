# 🕵️ Real-Time Fraud Detection Model

**Team:** Sarvagya, Pritish, Daksh  
**Duration:** 20 Days  

---

## 🎯 Objective
To simulate an end-to-end workflow where team members individually develop models and then collaborate to integrate them into a single, unified prediction service.

---

## 👥 Team Roles & Parallel Focus

- **All:** Develop, tune, and evaluate a unique fraud detection model individually.  
- **Sarvagya:** Focus on Tree-Based Models; *designs* final model integration and ensemble logic.  
- **Pritish:** Focus on Linear/Classical Models; *builds* the unified prediction script (the “frontend” backend).  
- **Daksh:** Focus on Anomaly Detection; *manages* shared EDA and consolidated documentation.

---

## 🗓️ Project Timeline

---

### **Week 1: Project Setup & Common Foundation**

**Day 1: Kick-off & Environment Setup**
- All: Project kick-off, finalize scope, agree on validation metrics.  
- Sarvagya: Set up Git repository (main, dev, feat/sarvagya-model, etc.).  
- Pritish: Add initial code base, data, and notebooks.  
- Daksh: Create initial `README.md` and folder structure (`data/`, `notebooks/`, `src/`, `docs/`).

**Day 2: Data Ingestion & Shared Review**
- Pritish: Ingest synthetic dataset.  
- Daksh: Run initial EDA notebook and share data profile.  
- All: Review dependencies (`requirements.txt`) for potential models.

**Day 3: Common Preprocessing & Individual EDA**
- Pritish: Refine `preprocessing.py` (common pipeline).  
- Daksh & Sarvagya: Fork EDA notebook to explore relevant features.  
- All: Sync meeting to finalize preprocessing.

**Day 4: Individual Script Setup**
- All: Finalize validation strategy (split, random seed).  
- All: Set up individual training scripts (`train_model_sarvagya.py`, etc.).  
- Daksh: Document data pipeline in `docs/data_pipeline.md`.

**Day 5: Week 1 Review & Baseline Models**
- All: Run baseline models and record metrics (Precision, Recall, F1).  
- Pritish: Containerize base environment (`Dockerfile`).  
- All: Weekly sync to review baselines and plan tuning strategies.

---

### **Week 2: Parallel Model Tuning & Experimentation**

**Day 6: Hyperparameter Tuning**
- All: Experiment with hyperparameters and update shared results doc.

**Day 7: Feature Engineering**
- Daksh: Propose new features from EDA.  
- Pritish: Implement agreed features into preprocessing script.  
- Sarvagya: Update model to handle new features.

**Day 8: Individual Model Refinement**
- All: Tune and re-run models with new features.  
- All: Discuss bugs/findings via chat or call.

**Day 9: Mid-Week Model Sync**
- All: Present current SOTA performance and discuss trade-offs.  
- Daksh: Start drafting “Model Comparison” section in final report.

**Day 10: Week 2 Review & Integration Plan**
- All: Review tuned models and decide integration approach (best model vs. ensemble).  
- Pritish: Start designing `predict.py` for multi-model input.

---

### **Week 3: Integration & Deployment Prep**

**Day 11: Freezing Models**
- All: Conduct code reviews and save final trained models (`model_S.pkl`, etc.).  
- Daksh: Update `README.md` with “How to Run” instructions.

**Day 12: Unified Prediction Script**
- Pritish: Develop `predict.py` to load all models.  
- Sarvagya: Implement ensemble logic (majority vote/averaging).  
- Daksh: Document API input/output for ensemble predictions.

**Day 13: Testing the Ensemble Service**
- Pritish: Test `predict.py` with sample inputs.  
- Sarvagya: Debug ensemble logic.  
- Daksh: Begin final presentation slides (Title, Intro, Problem Statement).

**Day 14: Finalizing Dockerfile**
- Pritish: Finalize Dockerfile with models and `predict.py`.  
- Sarvagya: Test Docker image and local run.  
- Daksh: Add “Methodology” and “Model Comparison” slides.

**Day 15: Week 3 Review & Documentation Sprint**
- All: Confirm final code integration in `dev` branch.  
- Daksh: Draft project report (Comparative Analysis).  
- Sarvagya & Pritish: Add detailed comments/docstrings to training scripts.

---

### **Week 4: Final Deliverables & Wrap-up**

**Day 16: Report Finalization**
- Sarvagya & Pritish: Review and edit report for accuracy.  
- Daksh: Finalize visualizations and charts.

**Day 17: Presentation Build-out**
- Daksh: Complete slide deck highlighting ensemble solution.  
- Sarvagya: Provide ensemble logic talking points.  
- Pritish: Prepare demo using `predict.py`.

**Day 18: Rehearsal & Feedback**
- All: Conduct full rehearsal and peer feedback.  
- Daksh: Adjust slides per feedback.

**Day 19: Final Code & Repo Cleanup**
- Pritish: Sanitize repo (clean notebooks, .gitignore, merge dev → main).  
- Sarvagya: Final check of main branch.  
- Daksh: Polish `README.md` as the single source of truth.

**Day 20: Final Submission & Debrief**
- All: Submit final project (Git repo, report, slides).  
- All: Team debrief on learnings and outcomes.  
- All: Archive the project.

---

✅ **Deliverables**
- Final GitHub Repository  
- Project Report (PDF)  
- Presentation Slide Deck  
- Dockerized Ensemble Prediction Service
