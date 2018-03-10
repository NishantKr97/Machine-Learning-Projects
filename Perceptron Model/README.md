# Perceptron Model
In machine learning, the perceptron is an algorithm for supervised learning of binary classifiers 
(functions that can decide whether an input, represented by a vector of numbers, belongs to some specific class or not).
<br>It is a type of linear classifier, i.e. a classification algorithm that makes its predictions based on a linear predictor 
function combining a set of weights with the feature vector.
<br>
In the modern sense, the perceptron is an algorithm for learning a binary classifier: a function that maps its input x (a real-valued vector) to an output value f ( x ) {\displaystyle f(x)} f(x) (a single binary value):
<br><br>
    f ( x ) = { 1 if    w ⋅ x + b > 0
    <br>{0 otherwise 
    <br>{\displaystyle f(x)={\begin{cases}1&{\text{if }}\ w\cdot x+b>0\\0&{\text{otherwise}}\end{cases}}} {\displaystyle f(x)={\begin{cases}1&{\text{if }}\ w\cdot x+b>0\\0&{\text{otherwise}}\end{cases}}}

where w is a vector of real-valued weights, w ⋅ x {\displaystyle w\cdot x} w\cdot x is the dot product ∑ i = 1 m w i x i {\displaystyle \sum _{i=1}^{m}w_{i}x_{i}} {\displaystyle \sum _{i=1}^{m}w_{i}x_{i}}, where m is the number of inputs to the perceptron and b is the bias. The bias shifts the decision boundary away from the origin and does not depend on any input value.
