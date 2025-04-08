# evaluating-the-environmental-impacts-of-stone-quarrying
# Quarry Impact Assessment Using GIS, Remote Sensing, and Deep Learning

## Overview
This project investigates the environmental and socio-economic impacts of small-scale building stone quarrying activities in Central Imenti, Meru County, Kenya. Using multi-temporal satellite imagery, GIS spatial analysis, and a Convolutional Neural Network (CNN) model, the study characterizes historical changes (2000–2023) and predicts potential quarrying impacts for the year 2030.

## Objectives
- **Spatial Analysis:** Map and quantify the spatial extent and temporal changes of quarrying activities from 2000 to 2023.
- **Impact Assessment:** Evaluate the associated environmental and socio-economic impacts using deep learning (CNN).
- **Predictive Modeling:** Forecast future impacts of quarrying activities for the year 2030.

## Data Sources
- **Satellite Imagery:** Landsat 7, 8, and 9; Sentinel-2 datasets.
- **Ancillary Data:** Population datasets, soil datasets, and land use/land cover (LULC) maps.

## Tools and Technologies
- **GIS Software:** ArcGIS Pro, QGIS
- **Remote Sensing Platform:** Google Earth Engine (GEE)
- **Programming Environment:** Google Colab (Python)
- **Deep Learning Framework:** TensorFlow / Keras

## Methodology
1. **Data Collection and Preprocessing:**  
   - Downloaded and preprocessed satellite imagery from 2000 to 2023.
   - Corrected atmospheric and radiometric distortions.
2. **Classification and Mapping:**  
   - Conducted supervised classification for LULC mapping.
   - Extracted quarry locations and quantified area changes.
3. **Impact Assessment Using CNN:**  
   - Built and trained a CNN model to analyze quarry-induced land changes.
   - Validated model performance with ground-truth data.
4. **Prediction of Future Impacts:**  
   - Modeled and visualized potential quarrying impacts for 2030.

## Repository Structure
```plaintext
📂 data/         # Sample datasets (if any)
📂 notebooks/    # Python notebooks for processing and analysis
📂 scripts/      # Preprocessing and CNN model scripts
📂 outputs/      # Maps, graphs, and prediction outputs
README.md        # Project overview and instructions
requirements.txt # Required Python libraries

## Results
Temporal maps of quarry expansion (2000–2023).

Quantified environmental impacts including vegetation loss and land degradation.

Predictive map highlighting vulnerable areas for future quarrying impacts (2030).

How to Run
Clone the repository.

Install the required dependencies using pip install -r requirements.txt.

Open the notebooks in Google Colab or your local environment.

Follow the notebook instructions for data preprocessing, training, and prediction.

License
This project is licensed under the MIT License — see the LICENSE file for details.

Contact
For questions, collaborations, or further information, feel free to contact:

Name: [Brian Mukaria]

Email: [mukariabrian83@gmail.com]

LinkedIn: [https://www.linkedin.com/in/brian-mukaria-503084291/]
