# Explainable-Artificial-Intelligence

Explainable Artificial Intelligence (XAI) refers to the field of AI that focuses on making machine learning models and their decision-making processes more transparent and understandable to humans. XAI encompasses various approaches, including auto-explanation, which involves classifiers generating their own explanations, typically seen in models like linear models or small decision trees. However, these models are often constrained by their classification accuracy.

Another XAI approach is post hoc explanation, which distinguishes between prediction and explanation steps. For instance, it approximates the decision boundary of a complex model with a simpler one to provide insights into why a specific prediction was made.

XAI also considers agnosticism assumptions, which involve determining what knowledge is available for explanation. This includes information about the classifier, the type of classifier, training data, additional data, data distribution, and causal graphs associated with attributes. Some XAI methods are model-agnostic and data-agnostic, such as LORE and Growing Spheres, which offer flexibility while respecting data privacy but may carry the risk of less relevant explanations.

Additionally, XAI can provide both global and local explanations. Global explanations aim to provide insights into the overall behavior of the classifier, such as reasoning from cases and generating prototypes. On the other hand, local explanations, as demonstrated by techniques like LIME, focus on explaining specific predictions, offering insights into why a particular decision was reached for a given data point.
