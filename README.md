What is TOPSIS
Technique for Order Preference by Similarity to Ideal Solution (TOPSIS) originated in the 1980s as a multi-criteria decision making method. TOPSIS chooses the alternative of shortest Euclidean distance from the ideal solution, and greatest distance from the negative-ideal solution.

# How to use this package:
TOPSIS-Aneesh-101853025 can be run as in the following example:

## **In Command Prompt**

 **topsis data.csv "1,1,1,1" "+,+,-,+" result.csv**

## Sample Input

Model | Corr | Rseq | RMSE | Accuracy 
--- | --- | --- | --- |--- 
M1|0.79|0.62|1.25|60.89|
M2|0.66|0.44|2.89|63.07|
M3|0.56|0.31|1.57|62.87|
M4|0.82|0.67|2.68|70.19|
M5|0.75|0.56|1.3|80.39|

## Output
Model | Corr | Rseq | RMSE | Accuracy | TOPSIS Score | Rank
--- | --- | --- | --- | --- | --- | ---
M1|0.79|0.62|1.25|60.89|0.639133014|2
M2|0.66|0.44|2.89|63.07|0.21259183|5
M3|0.56|0.31|1.57|62.87|0.407845678|4
M4|0.82|0.67|2.68|70.19|0.51915324|3
M5|0.75|0.56|1.3|80.39|0.828266585|1



