# minitorch
The full minitorch student suite. 


To access the autograder: 

* Module 0: https://classroom.github.com/a/qDYKZff9
* Module 1: https://classroom.github.com/a/6TiImUiy
* Module 2: https://classroom.github.com/a/0ZHJeTA0
* Module 3: https://classroom.github.com/a/U5CMJec1
* Module 4: https://classroom.github.com/a/04QA6HZK
* Quizzes: https://classroom.github.com/a/bGcGc12k

## Results
### Module 0 - Simple Classifier
<img src='images/module_0.png'/>

With parameters:
- linear.weight_0_0 = -1.51
- linear.weight_1_0 = -0.26
- linear.bias_0 = 0.77

### Module 1 - Autodiff

| Parameter         | Simple      | Diag         | Split       | XOR         |
| ----------------- | ----------- | ------------ | ----------- | ----------- |
| **Hidden Layers** | 4           | 3            | 5           | 5           |
| **Learning Rate** | 0.5         | 0.5          | 0.5         | 0.5         |
| **Epochs**        | 500         | 300          | 400         | 300         |
| **Final Loss**    | 1.2574      | 0.6139       | 6.5993      | 4.3938      |
| **Accuracy**      | 98% (49/50) | 100% (50/50) | 96% (48/50) | 96% (48/50) |

### Visual Results Table for Module 1

| Dataset  | Simple                                         | Diag                                       | Split                                        | XOR                                      |
| -------- | ---------------------------------------------- | ------------------------------------------ | -------------------------------------------- | ---------------------------------------- |
| **Data** | ![Simple Data](images/module_1_Simple.png)     | ![Diag Data](images/module_1_Diag.png)     | ![Split Data](images/module_1_Split.png)     | ![XOR Data](images/module_1_XOR.png)     |
| **Loss** | ![Simple Loss](images/module_1_SimpleLoss.png) | ![Diag Loss](images/module_1_DiagLoss.png) | ![Split Loss](images/module_1_SplitLoss.png) | ![XOR Loss](images/module_1_XORLoss.png) |


### Module 2 - Tensors

| Parameter         | Simple      | Diag         | Split       | XOR         | Circle      |
| ----------------- | ----------- | ------------ | ----------- | ----------- | ----------- |
| **Hidden Layers** | 2           | 3            | 5           | 6           | 6           |
| **Learning Rate** | 0.5         | 0.5          | 0.5         | 0.5         | 0.5         |
| **Epochs**        | 300         | 300          | 300         | 300         | 300         |
| **Final Loss**    | 0.9570      | 0.8367       | 2.6457      | 5.8473      | 6.2091      |
| **Accuracy**      |100% (50/50) | 100% (50/50) | 98% (49/50) | 96% (48/50) | 96% (48/50) |
| **Time/Epoch**    | 0.072s      | 0.109s       | 0.191s      | 0.254       | 0.269s      |


### Visual Results Table for Module 2

| Dataset  | **Data** | **Loss** |
| -------- | ------------------------------------------ | ---------------------------------------------- |
| Simple   | ![Simple Data](images/module_2_Simple.png) | ![Simple Loss](images/module_2_SimpleLoss.png) |
| Diag   | ![Diag Data](images/module_2_Diag.png) | ![Diag Loss](images/module_2_DiagLoss.png) |
| Split   | ![Split Data](images/module_2_Split.png) | ![Split Loss](images/module_2_SplitLoss.png) |
| XOR   | ![XOR Data](images/module_2_XOR.png) | ![XOR Loss](images/module_2_XORLoss.png) |
| Circle   | ![Circle Data](images/module_2_Circle.png) | ![Circle Loss](images/module_2_CircleLoss.png) |