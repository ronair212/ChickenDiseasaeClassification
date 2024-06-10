# Chicken Disease Classification Project

## Overview
This repository contains a project focused on classifying poultry diseases using images of chicken feces. The dataset consists of annotated images collected from the Arusha and Kilimanjaro regions in Tanzania between September 2020 and February 2021. The images were captured using the Open Data Kit (ODK) app on mobile phones. The classification categories are "Coccidiosis" and "Healthy."

We have also created a demo HTML webpage where users can upload an image to receive a prediction on whether the chicken is diseased or not.

## Dataset Description
The annotated dataset of poultry disease diagnostics for small to medium-scale poultry farmers consists of poultry fecal images taken in the Arusha and Kilimanjaro regions in Tanzania between September 2020 and February 2021 using the Open Data Kit (ODK) app on mobile phones. The classes are:
- "Coccidiosis"
- "Healthy"

## Project Structure
1. **Configuration Files**
   - `config.yaml`
   - `secrets.yaml` [Optional]
   - `params.yaml`
2. **Source Code**
   - Configuration Manager (`src/config`)
   - Components
   - Pipeline
   - `main.py`
   - `dvc.yaml`

## Workflows
1. Update `config.yaml`
2. Update `secrets.yaml` (Optional)
3. Update `params.yaml`
4. Update the entity
5. Update the configuration manager in `src/config`
6. Update the components
7. Update the pipeline 
8. Update `main.py`
9. Update `dvc.yaml`

## How to Run

### Steps:
1. **Clone the Repository**
   ```bash
   git clone https://github.com/entbappy/Chicken-Disease-Classification--Project
    ```

2. **Create a Conda Environment**
   ```bash
   conda create -n cnncls python=3.8 -y
   conda activate cnncls
   ```
   

 3. **Install the Requirements**
    ```bash
    pip install -r requirements.txt
    
    ```

4. **Run the Application**
    ```bash
    python app.py    
    ```

5. **Access the Application** 
    Open your local host and port to access the application.


