# 2401PTDS_Regression_Project


## Table of Contents
* [1. Project Overview](#project-overview)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. Instructions to Set Up Environment](#instructions-to-set-up-environment)
* [6. Team Members](#team-members)

## 1. Project Overview <a name="project-overview"></a>
This project aims to analyze and predict the effect of CO2 emissions on climate change from the agri-food sector. The goal is to understand the impact of agricultural activities on climate change and develop strategies for sustainable practices. 

Utilizing a dataset compiled from the **Food and Agriculture Organization (FAO)** and the **Intergovernmental Panel on Climate Change (IPCC)**, the project explores various emission sources and applies regression analysis to predict temperature variations. Insights and actionable recommendations will be provided to stakeholders, including policymakers and agricultural businesses.

## 2. Dataset <a name="dataset"></a>
The dataset contains emissions data from the agri-food sector, with features representing various sources of emissions such as:
- **Savanna Fires**, **Forest Fires**, **Crop Residues**, **Rice Cultivation**
- **Food Transport**, **Fertilizers Manufacturing**, **Manure Management**, **Food Processing**
- **Average Temperature (°C)** as the target variable for prediction.

The features include CO2 emissions (in kilotonnes) and other relevant indicators, such as rural and urban populations, that influence the agri-food sector's impact on climate change.

## 3. Packages <a name="packages"></a>
The following packages are required for this project:
- **Pandas** 2.2.2: Data manipulation and analysis
- **Numpy** 1.26: Numerical computing
- **Matplotlib** 3.8.4: Data visualization
- **Scikit-learn**: Machine learning tools (for regression analysis)
- **Seaborn**: Data visualization (for advanced plotting)

## 4. Environment <a name="environment"></a>
It is recommended to use a **virtual environment** to manage dependencies. If you're using Anaconda, we have provided instructions to set up the environment.

## 5. Instructions to Set Up Environment <a name="instructions-to-set-up-environment"></a>

### **Step 1: Install Anaconda**
If Anaconda is not installed, you can download it from the [official website](https://www.anaconda.com/products/individual).

### **Step 2: Clone the Repository**
Clone the project repository by running:
```bash
git clone https://github.com/mpho004/2401PTDS_Regression_Project.git
cd 2401PTDS_Regression_Project
```

### **Step 3: Create the Conda Environment**
To create a new environment for the project, run:
```bash
conda create --name <env_name> python=3.8
```

### **Step 4: Activate the Environment**
Activate your environment using:
```bash
conda activate <env_name>
```

### **Step 5: Install Dependencies**
Once the environment is activated, install the necessary dependencies:
```bash
pip install -r requirements.txt
```

### **Step 6: Verify the Installation**
To verify that all dependencies are correctly installed, use:
```bash
conda list
```

## 6. Team Members <a name="team-members"></a>
- **Name** - Mpho Mathebula
- **Team Member 1** - Davhana,Tshiwela

---

