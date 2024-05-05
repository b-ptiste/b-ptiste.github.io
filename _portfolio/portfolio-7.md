---
title: "Project details"
excerpt: " <b> New loss implementation in Pytorch : Soft-DTW </b> <br/> <b> Keys words </b> : <i> Time Series, DTW, Pytorch </i> <br/> <pre><code class="language-python">import torch
from tslearn.datasets import UCR_UEA_datasets
from DTWLoss_CUDA import DTWLoss

# load data
ucr = UCR_UEA_datasets()
X_train, y_train, X_test, y_test = ucr.load_dataset("SonyAIBORobotSurface2")

# convert to torch
X_train = torch.from_numpy(X_train).float().requires_grad_(True)
loss = DTWLoss(gamma=0.1)
optimizer = # your optimizer

##############
# your code ##
##############

value = loss(X_train[0].unsqueeze(0), X_train[1].unsqueeze(0))
optimizer.zero_grad()
value.backward()
optimizer.step()</code></pre>"
collection: portfolio
---

Sketch classification

Objective
======


Links
======

[<img src="/images/GitHub.png" alt="GitHub" width="37.5" height="12.5" />](https://github.com/b-ptiste/dtw-soft) [<img src="/images/report_icone.png" alt="Report" width="37.5" height="12.5" />](https://drive.google.com/file/d/1DLoEmERS7CLC-pVz2tVf6g5yopMTYnEZ/view?usp=drive_link) [<img src="/images/class_icone.png" alt="Report" width="37.5" height="12.5" />](http://www.laurentoudre.fr/ast.html)
