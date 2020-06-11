# Active Learning

Active learning is a special kind of learning  where  the algorithm can interactively query an oracle to label data points based on the algorithm’s preferences. <br/>
This repository aims to target all the major concepts in Active Learning with help of a real life problem of **Handwritten Digits Labelling**. <br/>
The concepts covered are as follows: <br/><br/>
  ○ Distribution of data: _Train, Test, Unlabelled_ <br/><br/>
  ○ Uncertainty Sampling using: <br/>
    - Least Confidence<br/>
    - Margin<br/>
    - Entropy<br/><br/>
  ○ Query by Committee (QBC)/ Disagreement Sampling using:<br/>
    - Vote Entropy<br/>
    - KL Divergence<br/><br/>
  ○ Version Space and its minimization<br/><br/>
  ○ Comparisons:<br/>
    - All Sampling Techniques<br/>
    - Pool Based Scenario vs Stream Based Scanerio<br/>
    - Active Learning vs Random (Traditional) Learning<br/><br/>
  ○ How good is clustering for this task?<br/><br/>

Dataset used: **Digits Dataset** (sklearn)<br/>
  ○ Number of Samples: 1797<br/>
  ○ Number of Features: 64<br/>
  ○ Number of Classes: 10<br/><br/>
