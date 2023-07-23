# Text-Similarity-Quantifier
PROBLEM STATEMENT

The data contains a pair of paragraphs. These text paragraphs are
randomly sampled from a raw dataset. Each pair of sentences may or may not be semantically
similar. The candidate is to predict a value between 0-1 indicating the similarity between the pair of
text paras. A sample of a similar dataset will be used as test data, therefore it’s crucial to the model
solution using provided dataset.

Part A
Build an algorithm/model that can quantify the degree of similarity between the two text-based on
Semantic similarity. Semantic Textual Similarity (STS) assesses the degree to which two sentences
are semantically equivalent to each other.
1 means highly similar
0 means highly dissimilar

Part B
Deploy the Algorithm/Model built-in Part A in any cloud service provider. Your final algorithm should
be exposed as a Server API Endpoint. In order to test this API make sure you hit a request to the
server to get the result as a response to the API. The request-response body should be in the
following format:
Request body: {“text1”: ”nuclear body seeks new tech …....”, ”text2”: ”terror suspects face arrest ……”}
Response body: {“similarity score”: 0.2 }
Note: “text1”, “text2”, and “similarity score” keys should be kept as it is, without any change.
