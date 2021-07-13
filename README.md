# Loan-Prediction
In this project I'm trying to predict wheter a customer should receive a Loan from a bank or not.
I'm using Python with Pandas, Matplotlib, PyTorch and Tensorflow

1. I'm using linear regression trying to find out if a store has increased it's sales in the past. If not this shop is rejected.
2. Later on I'm focusing only on shops that weren't declined in the first step. For those I'm trying to predict their future with LSTM Neural Net. 
Those two steps should be sufficient enough to recognize wheter a store should receive a loan. Please consider that those predictions are based only on a combined sales of a 
single store at a particular time.
3. This step is only for optimalization of a prediction. As we hve another dataset with multiple stores features such as their surroundings we will now do something that is 
not recommended to do at homes. We will use Predictions from first two steps and use it as our desired output so we are now turning unsupervised learning problem to supervised
but please remember that it is made only for speeding up future predictions and ideally we would have some data where we would be able to check our predictions.

