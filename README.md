# Scenario 
Online learning is suitalb for models which are deployed in a dynamic enviroment where the content set is changing over time.
Keeping the model up to date on the lastest post is important. Especially for the application where every post is short-lived. But how? One apporach is refresh our model frequently (for example, training a new model since the lastest fix window day.) However, more practicle and efficient way is to keep refreshing the model with the lastest few intervial (eg. 15/30 minuts etc). Online learning is here for solve this senario.

In this approach, we need to train a base model and keep adding the lastest data.

# Online Learining
