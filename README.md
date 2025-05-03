# THE COURSE PAPER IN ANALYTICAL CHEMISTRY: PREDICTION OF RETENTION TIME IN HILIC USING THE MACHINE LEARNING METHODS. 

 *In this Jupiter Notebook I'd like to introduce you to my scientific work in Analytical Chemistry (2024-2025), yet in Russian but soon you'll see English desctiption of this particulal notebook.*

## Description

I've taken the dataset of biological substances from this [research](https://pubmed.ncbi.nlm.nih.gov/32390414/) and their `Experimental Retention Times` for building the new ML models and features analysis which are the key for RT modeling.
- I used ensemble and linear models for RT prediction. The `LightGBM` was the best ($MAE = 0.92, RMSE = 1.43, R^2= 0.75$) 

![image](https://github.com/user-attachments/assets/6cad8f56-3b39-48fa-9fe7-55cf32242444)

  
- I've received the Ridge-regresion equation for the TOP-5 desctiptors by their importance:

![image](https://github.com/user-attachments/assets/993509be-1ce7-412e-8030-a6e55bd040a2)

- I've described the Descriptors.

### See more in `Coursepaper_finale` notebook and have a nice day!!!


