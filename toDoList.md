## Neural Network with Rust
- OOP
- without any external library (except for image I/O)

## Class and Methods

### Layers
- Fully connected layer

  - params : <unsigned int input node number, unsigned int output node number)
  - attribute : weight and bias for nodes
  - method : forward (<input>, <output> ){inner product and return}
  - method : exception관리를 위해서 input output숫자가 맞는지 확인해 주는 게 필요
  - sub Class : Node
    - params : weight, bias
    - 

  

### DataSet

- getData(int idx, int batchSize, )

### Module

- Network의 최상위 클래스
- constructor

- initializer
- forward(self, <input>)

### Optimizer

![img](https://blog.paperspace.com/content/images/2018/06/adam.png)

- ADAM
  - params : lr, eps, gt, nut, st, beta1, beta2
  - methods : step? 아무튼, loss받아서 update하는 것.

### Loss

- L2 loss
- parmas (output, label)
- return L2 loss double

### Activation

- ReLU (x)



### Basic Array

- numpy array나 torch의 tensor같은 것.
- shape, view, concat 등 구현 필요



### Functional

- softmax (arr)
