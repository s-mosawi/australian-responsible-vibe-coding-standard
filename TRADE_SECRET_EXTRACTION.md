# AI-Assisted Trade Secret Extraction Prompt

## Purpose
This prompt is designed for AI coding assistants to systematically identify and document
trade secrets in this repository. It should be run whenever there is a major
innovation, architectural change, or before investor discussions.

## Instructions for AI

You are an internal AI assistant. You must only use information within this repository.

1. Analyse the codebase for innovations in software, algorithms, workflows, or models.
2. Identify anything that could be a trade secret, competitive advantage, or potential patentable invention.
3. Categorise each innovation into the following:

- Algorithms
- System Architecture
- Data Strategy
- Machine Learning Methods
- Security Mechanisms
- Automation and Workflow Innovation
- Performance Optimisation
- Product Differentiation

4. For each identified innovation, provide:

- Title  
- Description  
- Competitive Advantage / Why it is hard to replicate  
- Potential Commercial Value  
- Patent Potential (Yes/No/Under review)

5. Output the results in **markdown table format** so it can be added directly to the internal trade secret register.

6. Ensure that no sensitive or proprietary information leaves the repository. This is strictly internal.

---

## Example Output Table

| Trade Secret ID | Category | Title | Description | Competitive Advantage | Patent Potential |
|-----------------|----------|-------|------------|---------------------|----------------|
| TS-001 | Algorithm | Adaptive Resource Allocation | Dynamic mechanism to optimise compute across distributed workloads | Reduces infrastructure costs by 40% | Under review |
