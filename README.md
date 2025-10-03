# Writing ADRs

Architectural Decision Records are documents, stored in source control,
which capture context and outcome of decisions made about a systems architectural design.

## What
Created by Michael Nygard in 2011, they have become more utilised in industry.  
[See blog post](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions)

## How

The documents consist of a standard template, which capture the necessary information, including
whether a decision is "Proposed", "Accepted" or "Rejected".

The documents are stored in source control.

A company should use a consistent template.

### Template Examples

Simple [simple.md](templates/simple.md)  
Specific Considerations [consideration_breakdown.md](templates/consideration_breakdown.md)  
Analysis Focused [analysis_focused.md](templates/analysis_focused.md)  

Find more templates at: https://github.com/joelparkerhenderson/architecture-decision-record?tab=readme-ov-file
or make your own.

### Tools
There are tools which can generate templates:
[TO DO]


## Why
- Capture decisions – Record architectural choices and their rationale for future reference.

- Improve transparency – Make decision-making visible to the whole team.

- Support knowledge transfer – Help new team members understand past decisions.

- Enable accountability – Show why a path was chosen (and what was rejected).

- Avoid re-discussion – Prevent teams from repeatedly debating the same issues.

- Aid compliance & audits – Provide documented justification for regulatory or security reviews.

- Support evolution – Track when decisions are superseded or deprecated as systems grow.



## Beyond ADRs

General "Decision Records" are an expansion on the more specific ADR, and might capture code level decisions,
like choosing a logging framework or design pattern.

Request for Comment documents can be similar, be really should be used as living design documents, 
whereas an ADR or DR captures a summary of the context, options and decisions after the fact.

## Before ADRs
ADRs are not the only way design decisions have been captured. Check out this article on the making 
of Arch Decisions: https://www.ozimmer.ch/practices/2020/04/27/ArchitectureDecisionMaking.html

