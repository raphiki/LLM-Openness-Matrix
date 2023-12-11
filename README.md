# LLM Openness Matrix

> A **simple** approach and matrix to evluate the leven of openness of Large Language Models.

![LLM Artifacts](https://github.com/raphiki/LLM-Openness-Matrix/assets/3777259/398453b7-905a-4f39-9b76-13e2b8e29fe2)

The assessment approach and matrix come from the series of articles *[How Open is Generative AI?](https://dev.to/worldlinetech/how-open-is-generative-ai-part-1-7cp)*

## Assessment Framework

The main components and aspects of a LLM to check when assessing its openness are the following:
- The model and its weights
- The dataset used for pre-training
- The dataset used for fine-tuning (if not a foundational model)
- The reward model used for the RLHF phase (if not a foundational model)
- The data processing code

On each of these aspects we then evaluate the level of openness with one of the following scores:
- Score 0 - Closed: No access to any public information, data or asset
- Score 1 - Published research only: Research papers(s) published but with no more information, data or asset
- Score 2 - Restricted access: Access to asset is possible only with special agreement (commercial, research…)
- Score 3 - Open with limitations: Access and reuse of asset is possible but with certain limitations on usage (ex. Open RAIL license)
- Score 4 - Totally open: Access and reuse of asset is possible without restriction (ex. open source license)

## Assessment Matrix

This prodices the following matrix to assess a LLM.

| Description                                                                                 | Model<br>(weights) | Pre-training<br>Dataset | Fine-tuning<br>Dataset | Reward<br>model | Data Processing<br>Code |
| ------------------------------------------------------------------------------------------- | ------------------ | ----------------------- | ---------------------- | --------------- | ----------------------- |
| No access to any public information, data or asset                                          |                    |                         |                        |                 |                         |
| Research papers(s) published but with no more information, data or asset                    |                    |                         |                        |                 |                         |
| Access to asset is possible only with special agreement (commercial, research…)             |                    |                         |                        |                 |                         |
| Access and reuse of asset is possible but with certain limitations on usage (ex. Open RAIL) |                    |                         |                        |                 |                         |
| Access and reuse of asset is possible without restriction (ex. open source license)         |                    |                         |                        |                 |                         |

## Other existing methodologies

- [The Foundation Model Transparency Index](https://crfm.stanford.edu/fmti/) by Standford University
- [Opening up ChatGPT: tracking openness of instruction-tuned LLMs](https://opening-up-chatgpt.github.io/) by Radboud University
