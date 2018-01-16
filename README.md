# Jaccard
# Language: R
# Input: CSV (abundances)
# Output: CSV (dissimilarities)

PluMA plugin that computes dissimlarities between samples, using the Jaccard Index (Jaccard, 1912).
The plugin takes input in the form of a CSV file where rows represent samples and columns represent community members.
Entry (i, j) then represents the abundances of member j in sample i.
The plugin produces an output CSV file of dissimilarities where both rows and columns represent samples
and entry (i, j) represents the dissimilarity of sample i with sample j.

