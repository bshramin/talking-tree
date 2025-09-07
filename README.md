# talking-tree
Leveraging LLMs to generate decision trees that explain their decisions in a transparent and human-readable manner.


## Problem
Despite the hype around deep learning and advanced AI, industries like banking and insurance still rely heavily on tree-based models. Their data is mostly structured and tabular, making gradient-boosted trees consistently outperform more complex neural networks in these contexts. Additionally, strict regulations demand explainability. It’s far easier to justify a loan rejection or a flagged claim with a tree model than with a black-box neural network.

However, even though tree predictions can be explained, they usually require a technical layer, ML engineers, interpreting results before product managers, analysts, or customer support teams can understand them. This creates a communication gap between models and decision-makers.

Tree-based models are powerful but not directly interpretable by non-technical stakeholders.
Business teams depend on ML engineers to translate predictions into human-friendly explanations.
This slows down workflows and reduces trust in AI-powered decisions.


## Solution

This solution will save hours of ML team time by reducing the need to answer questions from product managers and stakeholders. It will also improve customer service by providing clearer explanations of why the model makes certain decisions.

We use SHAP test to explain the predictions of a tree-based models.
We use LLMs to translate SHAP explanations into plain, human-readable language.
This allows tree-based models to effectively “talk” to humans and explain their decisions without requiring a technical intermediary.
