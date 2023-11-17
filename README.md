# Accident Cause from Bengali Text (ACBT) Corpus
Population density is strongly proportional to the rate of accidents. As a highly populated country, the number of accidental deaths is increasing day by day in Bangladesh. Various online news portals, such as Prothom Alo and The Daily Ittefaq in this country, represent an established and credible source for accident-related news dissemination. However, accidental news is not divided into more specific classes on those news portals. Therefore, the reader faces difficulty deciding which type of accident-related news he or she wants to read. Additionally, getting statistical information from the manual classification system about various types of accidents is a laborious job. Moreover, an automated classification system may help the government or other voluntary organizations to provide consciousness about the major types of accidents. In these regards, we have introduced a pioneer ACBT dataset for identifying accident news and detecting the causes with ten classes from the Bengali text data.

### Task Formulation
The ACBT is divided into two levels using a hierarchical annotation schema: (A) Detect the text whether it is accidental or not (B) If the text is accidental then identify the cause of an accident. We formulate our problem into two subtasks namely, Sub-task A which is a binary classification (detect whether the text is accidental or not), and Sub-task B which is a multiclass classification (identify the cause of an accident).

### Data Statistics
We have shown the statistical information about the samples of the dataset as follows, where _samples_ indicates the number of samples, _words_ presents the number of words, _vocab_ is the vocabulary size, _minWord_ represents minimum number of words in a sample, _maxWord_ is the maximum number of words in a sample, and _avg_ is the average number of words in a sample.

|Class|_samples_|_words_|_vocab_|_minWord_|_maxWord_|_avg_|
|-------|-------|-------|-------|-------|-------|-------|
|**Sub-task A**|
|Non-accidental|1099|38298|12657|528|3|34.848|
|Traffic|641|14428|3167|62|4|22.508|
|Collapse of Object|89|1662|774|53|4|18.674|
|Drown|92|1936|718|36|6|21.043|
|Train Accident|181|3438|1067|71|5|18.994|
|Fires and/or Explosion|214|3766|1580|47|3|17.598|
|Electrocution|193|2886|997|50|3|14.953|
|Intentional|228|5995|2339|86|4|26.293|
|Natural Disaster|88|1787|893|48|4|20.306|
|Struck by Falling Object|120|1601|560|45|5|13.341|
|Others|103|946|517|26|4|9.184|
|**For Entire Dataset**|**3048**|**76743**|**17965**|**528**|**3**|**25.178**|

<table>
  <tr>
    <td>One</td>
    <td>Two</td>
  </tr>
  <tr>
    <td colspan="2">Three</td>
  </tr>
</table>

| One    | Two | Three | Four    | Five  | Six 
| -
| Span <td colspan=3>triple</td>  <td colspan=2>double</td>
