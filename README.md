## Abstract
The famous Black-Scholes model for options pricing assumes that the  volatility of an underlying asset is constant. But the implied volatility derived from  option prices in the market shows that the implied volatility changes across different strike prices. This phenomena is known in the market as the volatility smile/skew.  
Different models have been suggested to model this phenomena and one of them is SABR model.  
The stochastic alpha, beta, rho model (SABR) is a stochastic volatility model with this formula:

![equation](https://latex.codecogs.com/svg.image?%5Clarge%20%5C%5C%20dF_%7Bt%7D%20=%20(F_%7Bt%7D)%5E%5Cbeta%20%5C%20%5Csigma_%7Bt%7D%20%5C%20%5Cmathrm%20dW_%7Bt%7D%5C%5Cd%5Csigma_%7Bt%7D%20=%20%5Calpha%20%5C%20%5Csigma_%7Bt%7D%20%5C%20%5Cmathrm%20dZ_%7Bt%7D%5C%5CE%5B%5Cmathrm%20dZ_%7Bt%7D%20%5C%20%5Cmathrm%20dW_%7Bt%7D%20%5D%20=%20%5Crho%20%5C%20%5Cmathrm%20dt)

Where, $F_{t}$ is a forward price, $\sigma_{t}$ is a volatility of the process and $Z_{t}$ and $W_{t}$ are two correlated brownian motions.
The model has constant parameters  that need to be calibrated based on a market data. 
In contrast to Black-Scholes model, the implied volatility from the SABR model is able to capture the smile.\\
 This model is widely used by traders, since there is a very accurate closed-form formula for its implied volatility. This formula  became an
interesting tool for calibration purposes.
This project is devoted to the study of this model, and its calibration to real market data.

## Note on the data:
We decided not to disclose data files, therefore, in case you want to replicate results please contact authors of the thesis:  
[Galymzhan Tazhibayev](mailto:galymzhan.tazhibayev@bse.eu?subject=[GitHub]%20Source%20Master%20Thesis)
[Seyed Ebrahim Ayatollahi](mailto:seyed.ayatollahi@bse.eu?subject=[GitHub]%20Source%20Master%20Thesis)
