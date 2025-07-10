# Hybrid-Time-Series-Modeling
![ alt text ](https://img.shields.io/badge/license-MIT-green?style=&logo=)
![ alt text ](https://img.shields.io/badge/-Jupyter-F37626?logo=Jupyter&logoColor=white)
![ alt text ](https://img.shields.io/badge/-pandas-150458?logo=pandas&logoColor=white)
![ alt text ](https://img.shields.io/badge/-NumPy-013243?logo=Numpy&logoColor=white)
![ alt text ](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=TensorFlow&logoColor=white)
![ alt text ](https://img.shields.io/badge/-Keras-D00000?logo=Keras&logoColor=white)
![ alt text ](https://img.shields.io/badge/-Google_Colab-F9AB00?logo=googlecolab&logoColor=white)

Time series prediction with hybridization approachs, combining LSTM and XGBoost.


|                        |   **RMSE**  |    **R²**  |
|------------------------|-------------|------------|
| **LSTM (Baseline)**    |   301.7562  |   0.9280   |
| **Feature Stacking**   |   102.2692  |   0.9917   |
| **Residual Learning**  | **70.4254** | **0.9961** |
| **Ensemble Averaging** |   140.3238  |   0.9844   |
