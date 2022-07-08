# KNN-experiments
## The results for changing the num_candidates in dbpedia_en_fr_15k_procrustes

Num set as 10,the response from ES Took  1
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num10.png" />
</p>

Num set as 100,the response from ES took 4
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num100.png" />
</p>
Num set as 1k,the response from ES took 11
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num1000.png" />
</p>
Num set as 100k,the response from ES took 21
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num10000.png" />
</p>

## The results for changing the num_candidates in dbpedia_en_de_100k_procrustes
Num set as 10,the response from ES took 60
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num10-100k.png" />
</p>
Num set as 100,the response from ES took 73
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num100-100k.png" />
</p>
Num set as 1000,the response from ES took 235
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num1000-100k.png" />
</p>
Num set as 10000,the response from ES took 400
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num10000-100k.png" />
</p>

## Summary
In this experiment, we defaulted the top k setting to 10.
When the data set is small as 15K we used, the top 10 candidates are selected when num changes from 10 to 100, but there is a slight difference.
When num changes from 100 to 10,000, there is no change in the top 10 candidates selected.
When the data set was larger as 100K we used, no change was found in the top10 candidates even when num changed from 10 to 10,000.

