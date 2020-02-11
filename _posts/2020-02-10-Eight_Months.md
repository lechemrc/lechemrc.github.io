---
layout: post
title: <p style="color:orange">Eight Months</p>
image: /img/clarisse_croset_unsplash.jpg
bigimg: /img/clarisse_croset_unsplash.jpg
---

## Rapid Growth Over a Short Period of Time

Over the last several months, I've been so immersed in coding and other projects that I've barely updated my blog and portfolio. In fact, it's been 4 months. In my Lambda education we've gone quickly from using pandas and doing simple regressions and classfications, to using Neural Networks to classify and predict based on various sources of data. 

To sum up these months in two words, it's these: _productive struggle_

I have made it a goal to never just seek the simple solution. Even if it means spending hours and hours just working through setting up a workable virtual environment, or trying to figure out the correct shape of the data to feed into a neural net, I work through problems, challenges, and bugs for purpose of learning, not accomplishing the code (those that's always a nice secondary achievement). For that reason, it's felt that my education has been exponential as opposed to logarithmic, a rapidly increasing trajectory upward in terms of understanding and skill acquisition.

When I code, I code for generalization, avoiding hard coding whenever I can. It's in those moments that, where there may be a little front-loading in building the functions, it always pays off in the end when I can apply those functions to wide ranges of data easily. To me, that's one aspect of successful code. If it can be easily read, understandable and logical in its progression, and easily applied to different data, I've done my job. 

So far I have experience with:

_Pandas, numpy, recursive functions, linear algebra, various regression and classification models (inluding random forests, xgboost, etc.), statistical analysis and application, sklearn pipelines, designing and deploying packages and libraries, kaggle competitions, SQL databases, supervised and unsupervised learning, natural language processing, productization and cloud deployment, and even keras and tensorflow at this point only 8 months into my education._

It's been an absolute firehose of information in our Lambda education but set up in a way that we could digest, practice, and repeat everything in a way that it sticks with us. At the very least, that at least how _I_ feel. Each new subject now has an air of familiarity. Each new subject is an exciting new process in understanding data, both big and small. Each new project is a thrilling new opportunity to build something useful and purposeful. Each new day is a new or deepened skill. 

I love data science. I love cleaning data. I love approaching tough subjects and finding potential answers and hints of correlation. I love using technology to make sound predictions. I love the potential and power that this field has and I have no intention of ever letting up. 

```
import numpy as np
import matplotlib.pyplot as plt

def graph(func, x_range):
   x = np.arange(*x_range)
   y = func(x)
   plt.plot(x, y)

graph(lambda x: 100*(np.power(1.1, x)), (0,80))
```



photo credit: Clarisse Croset
