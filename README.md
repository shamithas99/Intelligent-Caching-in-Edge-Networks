Caching is done to store any data so that future requests for that data is served faster.
Caching of web pages, media and files by making use of machine learning techniques to increase the hit rate of the cache.
Caching is done to store requests such as web pages, media, files so that the future requests can be served faster.
Caching is done to decrease load on core networks
Maximum utilization of the space and time.

We are aiming to implement our model in edge networks and   near gateways router.
The dataset was collected from Wireshark open source tool
The packets were captured over WLAN
Dataset consists of FTP and HTTP requests.

Reinforcement Learning
It is a subset of Artificial Intelligence in which the model takes actions to maximise rewards
Using Q-learning algorithm
Goal: Reduce miss rate

CONCLUSION
We observed the performance of caching algorithms on FTP and HTTP packets from which we can conclude that our dataset is suitable for small size caches.
MLP was giving a very high hit rate due to small size of dataset and was over-fitting while Multiple Regression was predicting an id when real id was given as input instead of evicting id’s when cache was full.
Using supervised or unsupervised algorithms for classification or popularity prediction along with standard caching algorithm adds an overhead. 
So, the algorithm most suitable for our project is Reinforcement Learning(RL). RL has the ability to learn and adapt to the environment. We have used Q-tables, which is a way to implement RL.
Applying RL for huge files FTP along with HTTP request packets is used to compensate the computational time and cost involved.

Thus we can conclude that the RL along with parameters like unique id,  frequency and size for caching was a novel technique and its performance was comparable to the other algorithms more commonly used. 













