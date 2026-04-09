# EPL_Quant_Analysis

The Premier League Tactical Analysis Prompt Flow is designed to automate the tactical evaluation of Premier League teams in the 2023–24 season by integrating real-world performance data with LLM-driven SWOT (Strengths, Weaknesses, Opportunities, Threats) analysis. It empowers coaches, analysts, and sports data enthusiasts to generate dynamic, data-informed tactical insights for any Premier League team in just a few seconds, through Azure AI Studio’s low-code interface.

The technical architecture is built around a cloud-native, agentic workflow that combines structured analytics with LLM-based reasoning. Player and team-level statistics are stored in Azure Blob Storage as .csv files. A Python node dynamically retrieves this dataset using secure account credentials and loads it into pandas for preprocessing and analysis. This node serves as the system's deterministic backbone, ensuring accurate metric computation before any AI interpretation occurs.
