# S6
## Part 1
![Excel Output](https://github.com/PRIYE/S6/assets/7592375/b28beca5-92d0-44c6-bd70-1176715473c3)

### Steps
1. Write output of each neuron with respect to incoming weight and connected input layer.
2. Find derivative of total Error with respect to activation function of output dEtotal/da_01 ,  dEtotal/da_02
3. Find derivative of Error with respect to incoming weights in output layer w5, w5, w8 and w7 using chain rule
4. Find derivative of total Error with respect to activation function function in hidden layer.
5. Using  formuale from step 4, calculate derivative of total error with respect to weights in hidden layer w1, w2, w3
6. Using the above all derivatives, update the weights in subsequent iterations until model convergence using learning rate as a hyperparameter.

###Error Comparison
![Error 0.1](https://github.com/PRIYE/S6/assets/7592375/e7451234-2024-47fd-9ccf-bcfeb8829af0)
![Error 0.2](https://github.com/PRIYE/S6/assets/7592375/e7199710-4a76-4806-858d-ec6a4ef45c22)
![Error 0.5](https://github.com/PRIYE/S6/assets/7592375/fe59d67d-fde4-4e6e-8833-f190181e5697)
![Error 0.8](https://github.com/PRIYE/S6/assets/7592375/4bd0c1c8-ef84-4348-ad8b-75d9e47e3c7c)
![Error 1](https://github.com/PRIYE/S6/assets/7592375/5aa5e3e9-7d5a-4c47-a247-b6b614a05167)
![Error 2](https://github.com/PRIYE/S6/assets/7592375/c6cc0718-c17e-4043-bd0f-2ee5842e8a05)

As the learning rate increases the, the rate of model converges increases at lower iterations

    
