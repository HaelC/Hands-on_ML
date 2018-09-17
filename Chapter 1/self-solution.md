**1. How would you define Machine Learning?**  
Machine learning is the science and art of programming computers so they can learn from data.

**2. Can you name four types of problems where it shines?**  

- Problems for which existing solutions require a lot of hand-tuning or long lists of rules: one machine learning algorithm can often simplify code and perform better.
- Complex problems for which there is no good solution at all using traditional approach: the best machine learning techniques can find a solution.
- Fluctuating environments: a machine learning system can adapt to new data.
- Getting insights about complex problems and large amounts of data.

**3. What is a labeled training set?**  
A labeled training set is the training set with the desired solutions(i.e., labels).

**4. What are the two most common supervised tasks?**  
Classification and regression.

**5. Can you name four common unsupervised tasks?**  
Clustering, visualization, dimensionality reduction and association rule learning.

**6. What type of Machine Learning algorithm would you use to allow a robot to walk in various unknown terrains?**  
Reinforcement learning.

**7. What type of algorithm would you use to segment your customers into multiple groups?**  
Clustering algorithms. E.g., kNN, EM.

**8. Would you frame the problem of spam detection as a supervised learning problem or an unsupervised learning problem?**  
Supervised learning. Classification, in particular.

**9. What is an online learning system?**  
Online learning trains the system incrementally by feeding data instances sequentially, either individually or by small groups called mini-batches.

**10. What is out-of-core learning?**  
Online learning algorithms used to train systems on huge datasets that cannot fit in one machine's main memory, which loads part of the data, runs a training step on that data, and repeats the process until it has run on all of the data.

**11. What type of learning algorithm relies on a similarity measure to make predictions?**  
Instance learning, which learns the examples by heart, then generalizes to new cases using a similarity measure.

**12. What is the difference between a model parameter and a learning algorithm's hyperparameter?**  
A hyperparameter is not affected by the learning algorithm itself; it must be set prior to training and remains constant during training. While the parameter(s) will be updated to find the optimal during the training process.

**13. What do model-based learning algorithms search for? What is the most common strategy they use to succeed? How do they make predictions?**  
Model-based learning algorithms search for optimal parameters of the model so that the model would perform well on new instances.   
The most common strategy is to minimizing the cost function by e.g., gradient descent.  
To make predictions, we just feed the new instance's features into the model and use the parameters found by the learning algorithm.

**14. Can you name four of the main challenges in Machine Learning?**  
Quantity and quality of data, complexity of algorithms(resulting in overfitting or underfitting), feature engineering.

**15. If your model performs great on the training data but generalizes poorly to new instances, what is happening? Can you name three possible solutions?**  
Overfitting.

- To simplify the model by selecting one with fewer parameters
- To gather more training data
- To reduce the noise in the training data

**16. What is a test set and why would you want to use it?**  
A test set is separated from training set, and it's used to test the model to evaluate the model and get an estimation of generalization error.   
To know how well the model will perform on instances it has never seen before.


**17. What is the purpose of a validation set?**  
Compare different models with various hyperparameters and select the best model.

**18. What can go wrong if you tune hyperparameters using the test set?**  
The model and heperparameters perform well on the test set, but the model is unlikely to perform as well on new data.

**19. What is cross-validation and why would you prefer it to a validation set?**  
The training set is split into complementary subsets, and each model is trained against a different combination of these subsets and validated against the remaining parts.  
It helps to avoid wasting too much training data in validation sets.
