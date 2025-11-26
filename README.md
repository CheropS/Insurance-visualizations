# Insurance Survey Data Visualization

This project analyzes insurance survey data and creates visualizations to understand customer demographics and preferences.

## Setup

1. **Create virtual environment:**
   ```bash
   python3 -m venv venv
   ```

2. **Activate virtual environment:**
   ```bash
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Running the Notebook

1. **Activate the virtual environment:**
   ```bash
   source venv/bin/activate
   ```

2. **Start Jupyter:**
   ```bash
   jupyter notebook
   ```

3. **Open `index.ipynb` in your browser**

## Data

The project uses survey data from `INSURGENCE FORM RESPONSES - Sheet1.csv` containing:
- Demographics (age, gender, location, disability status)
- Digital financial tools usage
- Insurance preferences and types
- Payment methods

## Visualizations

Current visualizations include:
- Gender distribution (pie chart)
- Disability status distribution (pie chart)

## Dependencies

- pandas==2.1.4
- numpy==1.26.2
- matplotlib==3.8.2
- seaborn==0.13.0
- jupyter==1.0.0
- ipykernel==6.27.1
