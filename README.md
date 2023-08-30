# Problem: Challenges in Optimizing Usage for Energy-Intensive Buildings

Despite existing monitoring, energy-intensive buildings grapple with suboptimal energy optimization due to the complexity of consumption patterns. Inaccuracies in demand forecasting hinder proactive resource allocation and targeted efficiency enhancements. Enhanced methods for comprehending intricate energy usage are vital to enable precise optimization strategies, ensuring efficient resource distribution and cost-effective operations in these structures.

# Solution: Leveraging Machine Learning for Precise Energy Demand Forecasting

The goal of this project is to create a **machine learning model** based on reccurent neural networks (RNN) that can **forecast** energy demand of any building. The model will analyze historical data and external influences such as weather to predict the future energy consumption of the building.

# Data

The machine learning model can learn and predict the load demands of any building that provides historical load data. Presently, the model has been trained utilizing data sourced from the [DRYAD repository](https://datadryad.org/stash/dataset/doi:10.7941/D1N33Q). The building from DRYAD is a modern office building completed in 2015 and situated in Berkeley, California. The training dataset contains historical data encompassing heat and electrical energy consumption. Outdoor weather data is used as covariates to improve the model's accuracy.