# tricks-in-deeplearning
Using different tricks to improve performance of resetnet50 by Keras

Paper：https://arxiv.org/abs/1812.01187

Resnet50 model and other CNN models implemented by keras can be found from: https://github.com/BIGBALLON/cifar-10-cnn

Train baseline Resnet50 model （done)  accuracy: 91.64%

Adding warmup LR (done) accracy:92.32%(+0.68%)

Adding cosine decay（done) accuracy:93.01%（+0.69%）

Adding cosine decay based on batch (done). But it does not improve for accuracy:92.93%

Adding mixup(done) accuracy:94.10%(+1.09%)

Adding label smoothing(on progress)
