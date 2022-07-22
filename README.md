# GoingHigher  
Going Deeper in Aiffel  
_22-07-06~_  

___Created by Jemu___

<img src='https://velog.velcdn.com/images/jujemu/post/ed8300f9-e42e-498a-8517-6186b8fb6129/image.jpg' width=40% height='auto'></img>

___

## [GD-2] ResNet  
_Implementation ResNet 34-Layer 50-Layer_
### Ablation study

_15 Epoch_

Test accuracy

||ResNet|Plain|
|:---:|:---:|:---:|
|34 Layer|87.04%|75.21%|
|50 Layer|85.98%|X|

Validation Accuracy

||ResNet|Plain|
|:---:|:---:|:---:|
|34 Layer|86.25%|75.33%|
|50 Layer|86.03%|X|

### Review
Figuring out ResNet is sucessful using layers block.  
For detail, Learning rate scheduling, momentum, appropriate batch size is used.  
And I've got familiar with tensorflow dataset. How to deal with, get into infomation, etc.  

Also, there is something to be improved not yet.  
I've knew regularization, weight decay is tough for me at now.  
Exploration for how batch size effects model fitting will be needed.

### Exploration
- Batchsize and Learning rate  
https://arxiv.org/pdf/1711.00489.pdf#:~:text=(2017)%20trained%20a%20ResNet%2D,a%20momentum%20coefficient%20of%200.9  
https://inhovation97.tistory.com/32

- Tensorflow dataset My summary  
https://velog.io/@jujemu/텐서플로우-데이터셋-도대체-뭐야  

