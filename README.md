📊 Marketing Campaigns — Causal Inference Analysis
A causal inference project that measures the true impact of marketing campaigns using observational sales data.

🎯 Objective
How much did the marketing campaigns actually drive sales? Rather than relying on simple correlation, this project applies three distinct causal methods to rigorously answer that question.

🔬 Methods
MethodDescriptionDifference-in-Differences (DiD)Compares pre/post dynamics between treatment and control groupsSynthetic ControlConstructs a counterfactual to answer "what would have happened without the campaign?"EconML Meta-LearnersIdentifies heterogeneous treatment effects (S-Learner, T-Learner, X-Learner)

🛠️ Libraries Used
EconML — Microsoft's causal ML library · scikit-learn — ML models · pandas / numpy — data manipulation · matplotlib / seaborn — visualization

📌 Key Takeaway
The attributable sales lift from the campaign is quantified across three independent causal methods, with cross-method comparison to validate robustness.
