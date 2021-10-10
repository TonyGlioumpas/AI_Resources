 **Nominal data** :  
 is “labeled” or “named” data which can be divided into various groups that do not overlap.  
 Examples of nominal data include country, gender, race, hair color etc.

**Decision tree learning** :  
one of the predictive modelling approaches It uses a decision tree (as a predictive model) to go from observations about an item (represented in the branches) to conclusions about the item's target value (represented in the leaves)

**Classification trees** :  
Tree models where the target variable can take a discrete set of values

**Regression trees** :  
Decision trees where the target variable can take continuous values (typically real numbers).

**TDIDT** (class of algorithms) :  
Top-down induction of decision trees.  
Also known as *recursive partitioning* or *divide-and-conquer*. 

**Entropy**:  
How many binary(yes/no) questions do we need to ask, on average, to find the answer to some question?  
Given a variable V that can take values ![formula](https://render.githubusercontent.com/render/math?math=\color{white}\large\v_i), each with a probability ![formula](https://render.githubusercontent.com/render/math?math=\color{white}\large\p_i), the entropy of V is defined as:
 ![formula](https://render.githubusercontent.com/render/math?math=\color{white}\large\e=s_v=-\sum_{i=1}^{k}p_ilog_2(p_i))  
 
 
 **Information Gain**:  
 of a test t is the difference between the entropy of a set S and the average entropy of a partition S' that t induced:  
 ![formula](https://render.githubusercontent.com/render/math?math=\color{white}\large\IG(t,S)=CE(S)-CE(S'))
 
 **Impurity** :  
 The node impurity is a measure of the homogeneity of the labels at the node.  
 * Gini impurity index : measures the degree or probability of a particular variable being wrongly classified when it is randomly chosen
 * 
 
Sources :  
* https://en.wikipedia.org/wiki/Decision_tree_learning
* Machine Learning and Inductive Inference, H.Blockeel, Chapter 4
* https://www.analyticsvidhya.com/blog/2020/11/entropy-a-key-concept-for-all-data-science-beginners/

