# Stickiness

* It is possible to implement stickiness so that the same client is always redirected to the same
instance behind a load balancer
* Works for Classic and Application Load Balancers
* The "cookie" used for stickiness has an expiration date you control
* Use case: make sure the user doesn't lose his session data
* Enabling stickiness may bring imbalance to the load over the backend EC2 instances
