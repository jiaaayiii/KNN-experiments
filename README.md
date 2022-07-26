# KNN-experiments
## The results for changing the num_candidates in dbpedia_en_fr_15k_procrustes

The paramaters of num_candidates set as 10,the response from ES Took 1(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num10.png" />
</p>

The paramaters of num_candidates set as 100,the response from ES took 4(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num100.png" />
</p>
The paramaters of num_candidates set as 1000,the response from ES took 11(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num1000.png" />
</p>
The paramaters of num_candidates set as 10000,the response from ES took 21(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num10000.png" />
</p>

## The results for changing the num_candidates in dbpedia_en_de_100k_procrustes
The paramaters of num_candidates set as 10,the response from ES Took 60(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num10-100k.png" />
</p>
The paramaters of num_candidates set as 100,the response from ES took 73(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num100-100k.png" />
</p>
The paramaters of num_candidates set as 1000,the response from ES took 235(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num1000-100k.png" />
</p>
The paramaters of num_candidates set as 10000,the response from ES took 400(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/num10000-100k.png" />
</p>


## The results for changing the num_candidates in dbpedia_caligraph,we set Kaulu as the searching entity
The paramaters of num_candidates set as 10,the response from ES Took 5(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/cali10-1.png" />
</p>
The paramaters of num_candidates set as 100,the response from ES took 20(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/cali100-1.png" />
</p>
The paramaters of num_candidates set as 1000,the response from ES took 199(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/cali1000-1.png" />
</p>
The paramaters of num_candidates set as 10000,the response from ES took 518(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/cali10000-1.png" />
</p>


## The results for changing the num_candidates in dbpedia_caligraph,we set Marianne_Winslett as the searching entity
The paramaters of num_candidates set as 10,the response from ES Took 8(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/cali10-2.png" />
</p>
The paramaters of num_candidates set as 100,the response from ES took 15(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/cali100-2.png" />
</p>
The paramaters of num_candidates set as 1000,the response from ES took 54(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/cali1000-2.png" />
</p>
The paramaters of num_candidates set as 10000,the response from ES took 660(microsecond)
<p>
  <img width="50%" src="https://github.com/jiaaayiii/KNN-experiments/blob/main/cali10000-2.png" />
</p>



## Summary
In this experiment, we defaulted the top k setting to 10.
When the data set is small as 15K we used, the top 10 candidates are selected when num changes from 10 to 100, but there is a slight difference.
When num changes from 100 to 10,000, there is no change in the top 10 candidates selected.
When the data set was larger as 100K we used, no change was found in the top10 candidates even when num changed from 10 to 10,000.

