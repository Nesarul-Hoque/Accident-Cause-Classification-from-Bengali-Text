# Accident Cause from Bengali Text (ACBT) Corpus
Population density is strongly proportional to the rate of accidents. As a highly populated country, the number of accidental deaths is increasing day by day in Bangladesh. Various online news portals, such as Prothom Alo and The Daily Ittefaq in this country, represent an established and credible source for accident-related news dissemination. However, accidental news is not divided into more specific classes on those news portals. Therefore, the reader faces difficulty deciding which type of accident-related news he or she wants to read. Additionally, getting statistical information from the manual classification system about various types of accidents is a laborious job. Moreover, an automated classification system may help the government or other voluntary organizations raise awareness about the major types of accidents. In these regards, we have introduced a pioneer ACBT dataset for identifying accident news and detecting the causes with ten fine-grain classes: Traffic, Collapse of Object, Drown, Train Accident, Fires and/or Explosion, Electrocution, Intentional, Natural Disaster, Struck by Falling Object, and Others, from the Bengali text data.

### Task Formulation
The ACBT is divided into two levels using a hierarchical annotation schema: (A) Detect the text whether it is accidental or not and (B) If the text is accidental, then identify the cause of an accident. We formulate our problem into two subtasks, namely, Sub-task A, which is a binary classification (detect whether the text is accidental or not), and Sub-task B which is a multiclass classification (identify the cause of an accident).

### Data Statistics
We have shown the statistical information about the samples of the dataset as follows: where _samples_ indicates the number of samples, _words_ presents the number of words, _vocab_ is the vocabulary size, _minWord_ represents the minimum number of words in a sample, _maxWord_ is the maximum number of words in a sample, and _avg_ is the average number of words in a sample.

<table>
  <tr><th>Class</th><th><i>samples</i></th><th><i>words</th><th><i>vocab</th><th><i>minWord</th><th><i>maxWord</th><th><i>avg</th></tr>
  <tr><th colspan="7">Sub-task A</th></tr>
  <tr><td>Nonaccident</td><td>1099</td><td>38298</td><td>12657</td><td>3</td><td>528</td><td>34.848</td></tr>
  <tr><td>Accident</td><td>1949</td><td>38445</td><td>7850</td><td>3</td><td>86</td><td>19.725</td></tr>
  <tr><td><b>For Entire Dataset</td><td><b>3048</td><td><b>76743</td><td><b>17965</td><td><b>3</td><td><b>528</td><td><b>25.178</td></tr>
  <tr><th colspan="7">Sub-task B</th></tr>
  <tr><td>Traffic</td><td>641</td><td>14428</td><td>3167</td><td>4</td><td>62</td><td>22.508</td></tr>
  <tr><td>Collapse of Object</td><td>89</td><td>1662</td><td>774</td><td>4</td><td>53</td><td>18.674</td></tr>
  <tr><td>Drown</td><td>92</td><td>1936</td><td>718</td><td>6</td><td>36</td><td>21.043</td></tr>
  <tr><td>Train Accident</td><td>181</td><td>3438</td><td>1067</td><td>5</td><td>71</td><td>18.994</td></tr>
  <tr><td>Fire and/or Explosion</td><td>214</td><td>3766</td><td>1580</td><td>3</td><td>47</td><td>17.598</td></tr>
  <tr><td>Electrocution</td><td>193</td><td>2886</td><td>997</td><td>3</td><td>50</td><td>14.953</td></tr>
  <tr><td>Intentional</td><td>228</td><td>5995</td><td>2339</td><td>4</td><td>86</td><td>26.293</td></tr>
  <tr><td>Natural Disaster</td><td>88</td><td>1787</td><td>893</td><td>4</td><td>48</td><td>20.306</td></tr>
  <tr><td>Struck by Falling Object</td><td>120</td><td>1601</td><td>560</td><td>5</td><td>45</td><td>13.341</td></tr>
  <tr><td>Others</td><td>103</td><td>946</td><td>517</td><td>4</td><td>26</td><td>9.184</td></tr>
  <tr><td><b>For Entire Dataset</td><td><b>1949</td><td><b>38445</td><td><b>7850</td><td><b>3</td><td><b>86</td><td><b>19.725</td></tr>
</table>
