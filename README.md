# tricks-in-deeplearning
Using different tricks to improve performance of resetnet by Keras

Paper：https://arxiv.org/abs/1812.01187

Resnet model and other CNN models implemented by keras can be found from: https://github.com/BIGBALLON/cifar-10-cnn

Train baseline Resnet model （done)  accuracy: 91.64%

Adding warmup LR (done) accracy:92.32%(+0.68%)

Adding cosine decay（done) accuracy:93.01%（+0.69%）

Adding cosine decay based on batch (done). But it does not improve for accuracy:92.93%

Adding mixup(done) accuracy:94.10%(+1.09%)

I tried label smoothing but it does not improve. According to Empirical study on label smoothing in neural
networks, cifar10 is not suitable for label smoothing.

Using smaller batch size :accuracy 94.38%(+0.28%)

Using resnet110: accuracy 95.21%(+0.83%)
