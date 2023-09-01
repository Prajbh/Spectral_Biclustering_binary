# Spectral_Biclustering_binary

An attempt to use Spectral Biclustering on a binary dataset that I have but I cannot share the dataset here!
The dataset has rows as the sample ids and the columns as function names. 

The consensus score the program gave me on my dataset was in negative. 

ChatGPT says: "A consensus score can indeed be negative. The consensus score measures the similarity between the biclusters found by the biclustering algorithm and the original data. A negative consensus score indicates that the biclusters found by the algorithm are dissimilar or not well-matched to the original data.
A positive consensus score indicates a higher degree of similarity between the biclusters and the data. A score close to 1 suggests strong agreement among the biclusters, while a score close to 0 indicates little agreement.
A negative consensus score might mean that the biclustering algorithm did not perform well on your shuffled data or that the underlying structure of the data does not align well with the biclustering assumptions."

Reference Link: https://scikit-learn.org/stable/auto_examples/bicluster/plot_spectral_biclustering.html
