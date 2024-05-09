# Topsis
TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) is a multi-criteria decision-making method used to determine the best alternative among a set of options based on their proximity to the ideal solution. It involves comparing alternatives against both positive (ideal) and negative (anti-ideal) reference points. The ideal solution represents the highest benefit, while the anti-ideal solution represents the lowest benefit or highest cost. By calculating the distance between each alternative and these reference points, TOPSIS ranks the alternatives by their relative closeness to the ideal solution, aiding decision-makers in selecting the most desirable option.

# Steps 
1. Define Criteria: Identify the criteria or attributes relevant to the decision-making problem. These criteria should be measurable and directly related to the alternatives being evaluated.

2. Normalize the Decision Matrix: Create a decision matrix where rows represent alternatives and columns represent criteria. Normalize the matrix to ensure that all criteria are on the same scale, typically between 0 and 1, to remove any bias caused by different units or scales.

3. Determine Weighted Normalized Decision Matrix: Assign weights to each criterion based on their relative importance in the decision-making process. Multiply each normalized value in the decision matrix by its corresponding weight to obtain the weighted normalized decision matrix.

4. Identify Positive Ideal Solution (PIS) and Negative Ideal Solution (NIS): Determine the ideal solution (highest value for each criterion) and the anti-ideal solution (lowest value for each criterion) by considering all alternatives.

5. Calculate Distance: Calculate the Euclidean distance between each alternative and the PIS and NIS. The distance from the PIS indicates how close an alternative is to the ideal solution, while the distance from the NIS indicates how far it is from the worst solution.

6. Calculate Proximity to Ideal Solution: Determine the proximity of each alternative to the ideal solution by dividing the distance to the NIS by the sum of the distances to the PIS and NIS.
Rank the Alternatives: Rank the alternatives based on their proximity to the ideal solution. The alternative with the highest proximity value is considered the best choice.
