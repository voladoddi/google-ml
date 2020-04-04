1. ML concepts

[A] Framing ML 
- Labels : 
- Features : 
- Examples :
  - Labeled example
  - Unlabeled example 
- Models : 
  - Training a model
  - Inference
- Regression vs Classification :

[B] Descending into ML 
- Linear Regression : 
  - The line that models the relationship between input feature (x) and target (y). 
  - This can be represented as a line => y = mx + c , which in ML convention becomes y = b + wx.
  - There can be several input features x1, x2, and x3 ... in which case line => y' = b + wx1 + wx2 + ... wxn.
- Loss : 
  - L2 Loss : represents the squared error, where error is (y' - y) i.e. (predicted - target values).
  
[C] Reducing Loss
- An iterative approach to reduce loss while training models is 'Gradient descent'.
- Gradient is a rate of change of loss w.r.t every feature.
- The negative gradient represents the direction to step in to achieve the optimal loss value A.K.A
  local minimum of the cost function.
- The 'learning rate' parameter represents how far we go in the direction dictated by the negative gradient.
  (Note: A large learning rate may cause the loss to overshoot the initial loss)
- (Stochastic) Gradient Descent => Update gradients and loss for EVERY sample.
  (Mini-batch) SGD => Update gradients and losses to be the average of 10-1000 samples.

  
  


