# baqapp - Accident Prediction in Barranquilla

## Project Overview

This project is an investigation into traffic accidents in Barranquilla, Colombia, with the aim of developing predictive models to identify accident hotspots and contributing factors. By analyzing a dataset of 25,610 accident records, this research seeks to provide insights that can guide urban planning and road safety interventions.

## Project Structure

The project is organized as a Quarto website, with the following structure:

```text
accident-prediction/
├── index.qmd
├── 01-introduction.qmd
├── 02-data-exploration.qmd
├── 03-methodology.qmd
├── 04-results.qmd
├── 05-conclusion.qmd
└── _quarto.yml
```

### Files and Directories

- **index.qmd**: The homepage of the project website.
- **01-introduction.qmd**: Provides an introduction to the study, including background, justification, and model selection.
- **02-data-exploration.qmd**: Contains an initial exploration of the dataset, including summary statistics and visualizations.
- **03-methodology.qmd**: Describes the methodology used, including data cleaning, feature engineering, and model selection.
- **04-results.qmd**: Presents the results of the predictive modeling, including performance metrics and key findings.
- **05-conclusion.qmd**: Concludes the study with a summary of findings and implications for road safety.
- **_quarto.yml**: Configuration file for the Quarto website.

## Dataset

The dataset used in this study contains 25,610 records of traffic accidents in Barranquilla, with the following columns:

- `FECHA_ACCIDENTE`: Date of the accident
- `HORA_ACCIDENTE`: Time of the accident
- `GRAVEDAD_ACCIDENTE`: Severity of the accident
- `CLASE_ACCIDENTE`: Type of accident
- `SITIO_EXACTO_ACCIDENTE`: Exact location of the accident
- `CANT_HERIDOS_EN_SITIO_ACCIDENTE`: Number of injured at the accident site
- `CANT_MUERTOS_EN_SITIO_ACCIDENTE`: Number of fatalities at the accident site
- `CANTIDAD_ACCIDENTES`: Number of accidents
- `AÑO_ACCIDENTE`: Year of the accident
- `MES_ACCIDENTE`: Month of the accident
- `DIA_ACCIDENTE`: Day of the week of the accident

## Model Selection

The primary model used in this study is **Random Forests**, chosen for its balance between predictive accuracy and interpretability. This model is well-suited for handling complex datasets and has been effectively used in similar traffic accident prediction studies.

## How to Build and View the Project

To build and view the Quarto website locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/accident-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd accident-prediction
   ```

3. Install Quarto (if not already installed). Instructions can be found [here](https://quarto.org/docs/get-started/).

4. Preview the website locally:

   ```bash
   quarto preview
   ```

5. The website will be available at `http://localhost:4321`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the contributors of the dataset and the academic community whose research informed this project.
