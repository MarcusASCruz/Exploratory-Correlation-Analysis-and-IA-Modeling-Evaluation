Project Title: Dynamic Integration of AI and Temporal Windows for Inflow Forecasting in Sobradinho Reservoir, Brazil

This repository contains the complete code and data for an academic study focused on utilizing machine learning and deep learning models to predict hydrological inflow to Sobradinho reservoir in Sâo Francisco River, Brazil. The project provides a detailed and reproducible workflow, from initial data exploration to the final evaluation of various AI models.

1. Repository Structure

The repository is organized to ensure clarity and easy navigation:

    notebooks/: Contains the Jupyter Notebooks (.ipynb) used for the analysis and modeling.

        GitHub_MaxiCorrLAG.ipynb: Details the initial data exploration, temporal analysis, and correlation studies.

        GitHUB_HydroAI.ipynb: Covers the implementation, training, and evaluation of all machine learning and deep learning models.

    data/: Stores the raw data files necessary for the study.

    requirements.txt: Lists all the required Python libraries and their specific versions to replicate the computational environment.

    .gitignore: Specifies files and directories that should be ignored by Git, ensuring a clean and focused repository.

2. How to Reproduce the Study

To reproduce the full analysis and model results, follow these steps:

    Clone the repository:

    git clone https://github.com/your-username/your-repository-name.git
    cd your-repository-name

    Create a virtual environment and install the necessary libraries:

    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    pip install -r requirements.txt

        Note: This project utilizes NVIDIA L4 GPU acceleration via the RAPIDS libraries (cudf, cuml). For optimal performance, ensure you have a CUDA-enabled GPU and the appropriate NVIDIA drivers installed. The code includes fallbacks to CPU-based libraries where GPU acceleration is unavailable.

    Open the notebooks: Launch Jupyter Lab or open the notebooks directly in Google Colab via the links provided within the repository. Run the cells in sequential order to replicate the full analysis.

3. Citation

If you use this code or data in your own research, please cite the corresponding academic paper and this repository. A dedicated DOI has been issued for this repository to facilitate proper citation.

[Your full academic citation in APA format]

Repository DOI: [Your DOI here]

4. Contact

For any questions or feedback, please open an issue in this repository or contact the lead author at marcus.cruz@embrapa.br
Data/ original data from ana.gov.br
