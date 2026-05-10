# Responsible AI

**Source:** [IBM - What is responsible AI?  ](https://www.ibm.com/think/topics/responsible-ai)

## Summary
A framework of ethical principles designed to guide the lifecycle of AI—from design to deployment. Its core mission is to align technology with human values, legal standards, and societal well-being.

* It builds trust in AI solutions and avoid unwanted outputs
* Must be clear about who train the AI systems, which data were used in training and what when into the insights/recommendations

---

## Take-away

### Trust
* **Explanability:** Ability to explain the reasoning behind AI decisions.
* **Prediction accuracy:** Running simulations by AI and comparing output to the true results in training dataset. Use LIME technique to explain prediction of classifiers by ML.
* **Traceability:** Allow users to document and track back to data, code and how it is processed by models, also enable debugging AI system.
* **Decision understanding:** Able to understand how and why AI derives conclusions → understand the business really well.

### Fairness
ML is a form of statistical discrimination, it can place privilege groups at advantages and reverse, because it train on the realistic data which might already had the prejudice or, under/over sampling.

**Solutions:**
* Use diverse and representative data.
* Regularly assess training data for biases.
* Use tools (open source framework of IBM, Microsoft, Google) to identify and correct biases before training.
* **Bias-aware algorithms:** Integrate fairness metrics and algorithmic constraints throughout the model lifecycle to actively monitor and minimize predictive disparities across demographic subgroups.
* **Bias mitigation techniques:** Resampling, reweighting, adversarial training.
* **Diverse development teams:** Bring different perspective to identify biases.
* **Ethical AI review Boards:** Evaluate and provide guidance on ethical consideration at managing level.

### Robustness
* Handle exceptional conditions (abnormalities in input or malicious attacks).
* Protect against exposed vulnerability, attack and security risk.

### Transparency
* Users must be able to see then evaluate its functionality, strengths, limitations.
* Then able to determine whether it is good for a given use case, or to know how/why an AI produced inaccurate or biased conclusion.

### Privacy
* To comply with frameworks like GDPR, organizations must protect AI models from malicious extraction of sensitive data (e.g, from malicious third party).
* Implement strict input controls and privacy-preserving techniques.