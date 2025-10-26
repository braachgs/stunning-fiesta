# stunning-fiesta
CARVE-Markov Engine: Carbon Risk Valuation Engine
📊 Quantifying Financial Risk in Voluntary Carbon Offtake Agreements
The CARVE-Markov Engine (Carbon Risk Valuation Engine) is a proprietary, data-driven framework and simulation tool designed to transform qualitative carbon project risk into a quantifiable financial metric: Value at Risk (VaR).
Traditional carbon risk ratings are static. CARVE utilizes a dynamic, probabilistic Markov Chain Model to forecast the likelihood of project failure (Default or Underperformance) over the multi-year term of an offtake agreement, providing CFOs and portfolio managers with actionable financial intelligence.
💡 The Problem: Bridging the Gap Between Climate Science and Finance
When a long-term carbon offtake agreement fails, the loss is purely financial. The VCM needs tools that speak the language of finance.
The CARVE Engine addresses this need by quantifying the three fundamental tiers of project risk:
Financial Risk: The potential loss (VaR) associated with non-delivery, overpayment, and forward liability.
Execution Risk: The dynamic probability of project operational failure (e.g., issuance delays, methodological weaknesses, developer performance).
External Risk: Systemic country-level and political instability factors (leveraging data like the INFORM Risk Index).
✨ How the CARVE Engine Works
The engine operates in two core phases:
Phase 1: Weighted Scoring (CARVE Score)
The framework assesses over a dozen factors, weighting the Project-Level Execution Risk most heavily. These factors generate a single, normalized CARVE Score (0-100), where a higher score indicates a lower systemic risk.
Phase 2: Probabilistic Forecasting (Markov Chain)
The CARVE Score is used to dynamically adjust the transition probabilities within a Markov Chain model. This model simulates the project's state year-over-year across three possible states:
P (Performing)
U (Under-delivering)
D (Default/Collapse)
The final output is a clear Probability of Total Collapse over the contract term and the resulting Cumulative Value at Risk (VaR) for the specified financial commitment.
🛠️ Technology Stack
This project is deployed as a single-page application (SPA) for speed, security, and portability:
Front-End: Pure HTML, Tailwind CSS (via CDN)
Core Engine: Vanilla JavaScript (<script type="module"> for security and performance)
Report Generation: Integrated with the Google Gemini API to translate raw numerical results into polished, narrative financial risk reports.
Hosting: Currently deployed via GitHub Pages.
🚀 Status and Usage
The CARVE Engine is currently in its pre-commercial rollout phase, demonstrating its immediate value in portfolio triage and long-term risk modeling.
The application allows users to:
Input core project and financial data (including streamlined input for manual scores).
Calculate the CARVE Score and Markov Chain probabilities instantly.
Generate a professional, narrative Risk Assessment Report in seconds.
Access the Live Demo (Deployed via GitHub Pages):
(Insert your final GitHub Pages URL here)
