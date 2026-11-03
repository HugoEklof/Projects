## Project Overview
This repository contains some past (and present) projects with accompanying code.

1. **Bayesian inference in diffusion tensor imaging**  
   Group project where the goal was to implement and compare three different Bayesian inference methods to infer the underlying structure of white matter. I was responsible for implementing the Laplace approximation.

2. **Can one hear the area of a drum?**  
   My bachelor's thesis, focused on PDE analysis and variational calculus.

3. **Deep learning assignment**  
   Implementation of multi-layered fully-connected and convolutional neural networks for classifying hand-written digits. The PDF is not a formal report, but rather a showcase of how the model could be improved with better optimization and regularization. The code for the model is available in the appendix of the PDF.

4. **Do we need more bikes?**  
   Group project where the goal was to analyze temporal and meteorological data collected in a city to predict rental bike demand. I was responsible for implementing the Boosting algorithm.

---

## Remarks on Current Project(s)

- I am currently in a group project where we look for social cyber threats in TikTok data collected during the Swedish election period 2026.
- We have so far done a thorough literature study and have outlined 4 common strategic approaches to disrupt the political discourse:

  - **Normalization / Narrative Persistence**  
    Repeatedly reinforcing narratives, potentially making them seem more acceptable.  
    *Indicator:* Recurring claims and framing across accounts and over time.

  - **Amplification / Flooding**  
    Increasing the visibility of particular messages or narratives.  
    *Indicator:* Posting bursts, content repetition across accounts.

  - **Distraction / Hiding**  
    Potentially redirecting attention away from certain political events or topics.  
    *Indicator:* Sudden shifts in topic prevalence around events.

  - **Polarization**  
    Intensifying divisions through opposing political narratives.  
    *Indicator:* Divisive framing and contrasting political stances. Signs of coordination over these different stances.

- We are currently working with a smaller batch of test data (~28 000 TikTok posts, collected 1/6 - 10/6), but will have a sufficiently larger set (1/6 - 30/9).
- Algorithms for topic modeling (LDA and BERTopic are tested) and for detecting coordinated behavior are currently in progress.

