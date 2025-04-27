# HydePHP Investigation Process

## Purpose of Investigations

Investigations are preliminary tasks used to gather information and make an informed decision about whether and how to proceed with a potential feature, improvement, or change.  
An Investigation should focus on answering:

- Is this worth pursuing?
- What would it involve?
- What potential risks, benefits, or alternatives exist?

Investigations are not meant to build or implement anything yet.

## How to Execute an Investigation

1. **Understand the Problem or Idea**  
   Clearly define what is being investigated. Frame the problem or opportunity in a few concise sentences.

2. **Gather Information**  
   Research relevant background information. This can include:
   - Reviewing existing HydePHP code and architecture
   - Checking documentation or specifications
   - Looking at how similar problems are solved elsewhere
   - Identifying available libraries, standards, or prior discussions

3. **Analyze Feasibility**  
   Evaluate the complexity and technical viability.  
   Key points to consider:
   - How well does it fit into the current architecture?
   - How difficult would implementation be?
   - What impact might it have on users, maintainability, or performance?

4. **Explore Alternatives**  
   If multiple approaches are possible, briefly compare them.  
   Summarize the pros and cons for each option.

5. **Identify Risks and Unknowns**  
   Note any significant uncertainties, technical debt, or possible future problems.

6. **Prepare a Recommendation**  
   Finish the investigation with a clear recommendation.  
   Structure the recommendation like this:
   - **Proceed**: If the task should move forward. Include a suggested rough outline for implementation.
   - **Postpone**: If it might be valuable later, but not now. Include what needs to change before it should be reconsidered.
   - **Discard**: If it’s not worth pursuing. Explain why (e.g., too complex, not enough benefit, conflicts with project goals).

## Writing the Investigation Report

Each Investigation should result in a short report, typically 1–2 pages at most, covering:

- Problem Summary
- Key Findings
- Alternatives Considered
- Risks and Unknowns
- Final Recommendation (Proceed / Postpone / Discard)

Keep the tone technical, neutral, and fact-driven. Avoid marketing language or unnecessary enthusiasm.

---

> Here is an example format for an investigation report

# Investigation Report

## Problem Summary
> Briefly describe the problem, idea, or feature request. Focus on what needs to be solved or decided.

## Key Findings
> Summarize relevant research, including:
> - Existing solutions (if any)
> - Related parts of HydePHP architecture
> - External libraries, tools, or specifications that could be relevant

## Alternatives Considered
> List and briefly describe different possible approaches.
> For each option, note key pros and cons.

## Risks and Unknowns
> Identify technical risks, uncertainties, or potential long-term issues.

## Final Recommendation
> Choose one:
> - **Proceed**: Describe a rough outline of how to implement it.
> - **Postpone**: Explain why it is better to delay, and under what conditions it should be reconsidered.
> - **Discard**: Explain why the idea should not be pursued.
