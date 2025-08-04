# ensemble
Ensemble of AI agents.

In the intial phase of development, the agent would be able to look at your codebase and operate on certain aspects of it. 
For example, it would be able to generate a coherent documentation (inline or external) for the codebase.

Thereafter, it would be able to look incrementally at the git commits and review them, update documentation, and its own understanding
of your codebase.

It would initially integrate two bots:

CRAB - Code Review and Aggregation Bot (Reviews code and generates a review summary)
COMB - Commenting Bot (For adding documentation to the code). Optionally, linting would be supported as well.

Standalone operation with git, or integration with a gitlab instance would be supported.
