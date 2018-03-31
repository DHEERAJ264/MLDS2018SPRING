# MLDS2018SPRING/hw1
There are three parts in HW1.
# 1. Deep vs Shallow:
* Simulate a funtion.
    1. SINC
    ```
    cd hw1/hw1_1/SINC
    python3 sinc0.py
    python3 sinc1.py
    python3 sinc2.py
    python3 PLOT.py
    ```
    ![SINC_LOSS.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_1/SINC/SINC_LOSS.png)
    
    ![SINC_Predict.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_1/SINC/SINC_Predict.png)
    
    2. SGN
    ```
    cd hw1/hw1_1/SGN
    python3 sgn0.py
    python3 sgn1.py
    python3 sgn2.py
    python3 sgn_PLOT.py
    ```
    ![SGN_LOSS.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_1/SGN/SGN_LOSS.png)
    
    ![SGN_Predict.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_1/SGN/SGN_Predict.png)
    
* Train on actual task using shallow and deep models.
    1. MNIST
    ```
    cd hw1/hw1_1/MNIST
    python3 CNN_mnist_model0.py
    python3 CNN_mnist_model1.py
    python3 CNN_mnist_model2.py
    python3 CNN_MNIST_PLOT.py
    ```
    ![CNN_MNIST_ACC.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_1/MNIST/CNN_MNIST_ACC.png)
    
    ![CNN_MNIST_LOSS.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_1/MNIST/CNN_MNIST_LOSS.png)
    
    2. CIFAR-10
    ```
    cd hw1/hw1_1/CIFAR-10
    python3 CNN_model0.py
    python3 CNN_model1.py
    python3 CNN_model2.py
    python3 CNN_CIFAR10_PLOT.py
    ```
    ![CNN_CIFAR10_ACC.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_1/CIFAR-10/CNN_CIFAR10_ACC.png)
    
    ![CNN_CIFAR10_LOSS.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_1/CIFAR-10/CNN_CIFAR10_LOSS.png)
    
# 2. Optimization:
* Visualize the optimization process.
    1. SINC
    ```
    cd hw1/hw1_2/Observe_Gradient_Norm_During_Training/SINC
    python3 gradient_epoch.py
    python3 Plot.py
    ```
    ![gradientNorm.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_2/Observe_Gradient_Norm_During_Training/SINC/gradientNorm.png)
    
    2. MNIST
    ```
    cd hw1/hw1_2/Observe_Gradient_Norm_During_Training/MNIST
    python3 gradientNorm.py
    python3 Plot.py
    ```
    ![gradientNorm.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_2/Observe_Gradient_Norm_During_Training/MNIST/gradientNorm.png)
    
* Observe gradient norm during training.
    ```
    Todo.
    ```
* What happens when gradient is almost zero?
    ```
    Todo.
    ```
# 3. Generalization
* Can network fit random labels?
    ```
    cd hw1/hw1_3/1_Random_Label
    python3 MNIST.py
    python3 Plot.py
    ```
    ![MNIST_ACC.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_3/1_Random_Label/MNIST_ACC.png)
    
    ![MNIST_LOSS.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_3/1_Random_Label/MNIST_LOSS.png)
    
* Number of parameters v.s. Generalization
    ```
    cd hw1/hw1_3/2_Parameters/
    python3 MNIST.py
    python3 Plot.py
    ```
    ![MNIST_ACC.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_3/2_Parameters/MNIST_ACC.png)
    
    ![MNIST_LOSS.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_3/2_Parameters/MNIST_LOSS.png)
    
* Flatness v.s. Generalization
    * Part 1
        1. Batch size 64 v.s. batch size 1024
            ```
            cd hw1/hw1_3/3.1.1_BatchSize/
            python3 MNIST_64.py
            python3 MNIST_1024.py
            python3 interpolation.py
            python3 Plot.py
            ```
            ![BatchSize.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_3/3.1.1_BatchSize/BatchSize.png)
            
        2. Learning rate 1e-3 v.s. 1e-2
            ```
            cd hw1/hw1_3/3.1.2_LearningRate/
            python3 MNIST_1e-3.py
            python3 MNIST_1e-2.py
            python3 interpolation.py
            python3 Plot.py
            ```
            ![LearningRate.png](https://github.com/JasonYao81000/MLDS2018SPRING/blob/master/hw1/hw1_3/3.1.2_LearningRate/LearningRate.png)
            
    * Part 2
        ```
        cd hw1/hw1_3/3.2_sensitivity/
        Todo.        
        ```