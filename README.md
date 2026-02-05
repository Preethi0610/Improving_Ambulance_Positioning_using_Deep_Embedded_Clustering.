# Improving Ambulance Positioning Using Deep Embedded Clustering

## Project Overview
This project implements a data driven framework to optimize ambulance positioning by analyzing historical road accident data. Using Deep Embedded Clustering (DEC), the system learns meaningful representations of accident patterns and identifies high risk hotspots where ambulances can be strategically placed. The goal is to support faster emergency response, better resource allocation, and improved outcomes in real world emergency medical services.

## Motivation
Emergency response time is a critical factor in patient survival and recovery after road traffic accidents. Traditional ambulance deployment strategies are often static and do not adapt to dynamic accident patterns or geographical risk variations. This project explores machine learning-based clustering to identify optimal locations that minimize response times and maximize coverage of high accident areas, providing actionable insights for emergency planners and policymakers. 

## Key Concepts
- **Deep Embedded Clustering(DEC):** Combines deep representation learning with clustering to uncover latent structure in high dimensional accident data.  
- **Hotspot Identification:** Accident clusters indicate zones with high frequency or severity, useful for strategic ambulance placement. 
- **Data driven Insights:** Use spatial and temporal patterns from accident records to improve decision making. 

## Features
- Learns latent embeddings of accident data using autoencoder and deep clustering  
- Identifies meaningful clusters indicating high accident risk zones  
- Recommends optimal ambulance positioning based on learned clusters  
- Evaluation against traditional clustering baselines for robustness

## Workflow
1. **Data Preprocessing:** Clean, normalize, and encode spatial and temporal accident records.  
2. **Feature Representation:** Train autoencoder to learn a compact latent space capturing accident patterns.  
3. **Deep Embedded Clustering:** Apply DEC to cluster accidents based on learned embeddings.  
4. **Location Analysis:** Identify optimal ambulance positioning zones corresponding to cluster centers.  
5. **Result Interpretation:** Visualize clusters and analyze spatial patterns for deployment decisions.

## Technologies Used
- **Python** for data processing, modeling, and evaluation  
- **TensorFlow / Keras** for autoencoder and embedded clustering  
- **scikit-learn** for baseline clustering and evaluation metrics  
- **geospatial tools (optional)** for visualizing hotspots on maps  
- **Jupyter Notebooks / scripts** for step by step analysis

## How to Run
1. Clone the repository  
    ```
    git clone https://github.com/Preethi0610/Improving_Ambulance_Positioning_using_Deep_Embedded_Clustering.git
    ```
2. Set up environment (Python 3.8+ recommended)  
    ```
    python3 -m venv venv
    source venv/bin/activate
    ```
3. Install dependencies  
    ```
    pip install -r requirements.txt
    ```
4. Run notebooks or scripts to preprocess data and train models

## Results & Evaluation
The DEC based approach yields compact and meaningful clusters that highlight areas with high accident density, enabling more effective ambulance distribution planning compared to traditional unsupervised methods. 

## Future Work
Further enhancements may include real time modeling with live traffic and accident feeds, integration of optimization algorithms for dynamic ambulance dispatching, and comparison with advanced clustering variants.

## License
This project is released under the MIT License.

## Acknowledgements
Inspired by research on machine learning and emergency service optimization using Deep Embedded Clustering. 
