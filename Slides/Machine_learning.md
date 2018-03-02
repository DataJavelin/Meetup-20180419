### Supervised learning
* Tune model with a training set
* Apply tuned model to new inputs
* Widely used for classification


* Obtain training dataset with inputs $\mathbf{x}$ and labels $y$ (often most time consuming)
* Choose a mathematical model $f$, with parameters $\mathbf{w}$
* $y=f(\mathbf{x; w})$, *prediction function*
* learn $\mathbf{w}$ values that gives most correct answers in training set

Note:
* Highly dependent on quality of dataset
* The model or function $f$, should be chosen to match how we think $x$ depends on $y$, could be smoothness,
if we were modelling weather, we might want some perodic component to reflect the seasons..
* If you don't use appropriate knowledge in chosing function, then model must learn it independently, need a lot more 
data and a lot more computing power to tune 
* last stage is parameter estimation, those parameters are learnt under supervision


### Unsupervised learning
* Have inputs $\mathbf{x}$ but no outputs
* Learn structure from data
    * e.g. clustering
    * e.g. dimensionality reduction


### Reinforcement learning
* Model learns best way of achieving task through receiving awards/penalties
<iframe width="854" height="480" data-src="https://www.youtube.com/embed/lJzv3aUGiDU?autoplay=1"></iframe>


* Great for learning games e.g. AlphaGo, mario karts
* Not so good for self-driving car  

Note:
Not good for learning on the job in real world, but could learn from simulation
