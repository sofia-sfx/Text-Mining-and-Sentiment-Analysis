# Text-Mining-and-Sentiment-Analysis

Explain you opinion (P7)

Born Classifier is a text classification algorithm inspired by the notion of superposition of states in quantum physics. Born provides good classification performance, explainability, and computational efficiency. In this project, the goal is to exploit the Born explanation in order to use it for Aspect Based Sentiment Analysis. In particular, the main idea to to proceed as follows:
1. Perform sentiment analysis classification of documents using Born
2. Extract the explanation features for each pair of documents and predicted labels
3. Analyze the explanatory features in order to group them in candidate aspects
4. Associate each aspect to a specific sentence or portion of the text
5. Predict the sentiment for the sentence or text portion usingthetrainedBornclassifier
6. Associate the (potentially different) sentiment to each sentence or text portion according to the aspect
Finally, evaluate the quality of the results for each aspect.
