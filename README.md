The famous Black-Scholes model for options pricing assumes that the  volatility of an underlying asset is constant. But the implied volatility derived from  option prices in the market shows that the implied volatility changes across different strike prices. This phenomena is known in the market as the volatility smile/skew.
Different models have been suggested to model this phenomena and one of them is SABR model.\\The stochastic alpha, beta, rho model (SABR) is a stochastic volatility model with this formula:

![equation](https://latex.codecogs.com/svg.image?\large&space;\\&space;dF_{t}&space;=&space;(F_{t})^\beta&space;\&space;\sigma_{t}&space;\&space;\mathrm&space;dW_{t}\\d\sigma_{t}&space;=&space;\alpha&space;\&space;\sigma_{t}&space;\&space;\mathrm&space;dZ_{t}\\E[\mathrm&space;dZ_{t}&space;\&space;\mathrm&space;dW_{t}&space;]&space;=&space;\rho&space;\&space;\mathrm&space;dt&space;)

Where, $F_{t}$ is a forward price, $\sigma_{t}$ is a volatility of the process and $Z_{t}$ and $W_{t}$ are two correlated brownian motions.
The model has constant parameters  that need to be calibrated based on a market data. 
In contrast to Black-Scholes model, the implied volatility from the SABR model is able to capture the smile.\\
 This model is widely used by traders, since there is a very accurate closed-form formula for its implied volatility. This formula  became an
interesting tool for calibration purposes.
This project is devoted to the study of this model, and its calibration to real market data.
\vspace*{1cm}
