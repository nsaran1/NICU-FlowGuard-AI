# NICU-FlowGuard-AI
NICU FlowGuard AI: An Exception-Aware Command Center for Clinical Workflows Using Dragon Copilot

1. Project title
2. One-paragraph overview
3. Problem statement
4. Project objectives
5. MVP exception types
6. Architecture overview
7. Dataset summary
8. Models used
9. Project phases
10. Repository structure
11. Installation instructions
12. How to run the project
13. Demo workflow
14. Results summary
15. Safety and governance disclaimer
16. Contributors and references


```text
FlowGuard-AI/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── raw/
│   │   └── synthetic_workflow_events.csv
│   ├── processed/
│   │   └── flowguard_model_dataset.csv
│   └── data_dictionary.csv
│
├── notebooks/
│   ├── 01_data_generation.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_data_preprocessing.ipynb
│   ├── 04_exception_rule_analysis.ipynb
│   ├── 05_model_training.ipynb
│   └── 06_model_evaluation.ipynb
│
├── src/
│   ├── generate_data.py
│   ├── preprocess.py
│   ├── exception_rules.py
│   ├── train_models.py
│   ├── risk_scoring.py
│   ├── explanation_generator.py
│   ├── routing_engine.py
│   └── audit_logger.py
│
├── app/
│   ├── streamlit_app.py
│   └── components/
│
├── models/
│   ├── logistic_regression.pkl
│   ├── decision_tree.pkl
│   └── random_forest.pkl
│
├── docs/
│   ├── 01_project_proposal.md
│   ├── 02_dataset_documentation.md
│   ├── 03_architecture.md
│   ├── 04_exception_rules.md
│   ├── 05_model_methodology.md
│   ├── 06_dragon_copilot_integration.md
│   ├── 07_governance_and_safety.md
│   └── 08_results_and_evaluation.md
│
├── tests/
│   ├── test_exception_rules.py
│   ├── test_risk_scoring.py
│   └── test_audit_logger.py
│
└── presentation/
    ├── FlowGuard_AI_Final_Presentation.pptx
    └── demo_script.md
```


