# Recommender System Using Alternating Least Squares

This repository contains the code and documentation for a collaborative filtering recommender system developed as part of my Master's project in Machine Learning and Artificial Intelligence at Stellenbosch University. The project leverages the Alternating Least Squares (ALS) algorithm to enhance recommendation accuracy by integrating user and item biases with latent factor modeling.

## Project Highlights

- **Algorithm:** Alternating Least Squares (ALS) for collaborative filtering.
- **Datasets:** Evaluated on MovieLens 100K and 25M datasets.
- **Models:** 
  - **Baseline Model:** Captures general user and item tendencies via biases.
  - **Enhanced Model:** Incorporates latent factors for deeper insights into user-item interactions.
- **Evaluation:** Performance measured using Root Mean Square Error (RMSE) and visualized through 2D embeddings.
- **Case Study:** Practical demonstration with a dummy user and an analysis of polarizing movies.
- **Future Enhancements:** Discussion on algorithmic improvements validated through a mock A/B test.

## Repository Structure

maverick250/

├── README.md  
├── Applied_ML_at_Scale_Recommender_System_Technical_Report.pdf  
├── code/  
│   ├── biases_only_model_training.ipynb  
│   ├── full_als_model_training.ipynb  
│   ├── enhanced_practical_3.ipynb  
│   ├── practical_1.ipynb  
│   └── practical_2.ipynb  
└── checkpoints_2D_full_als_model-<timestamp>.zip

*Note: All code has been moved to the `code` folder for better organization, while the technical report remains at the root for easy access.*

## Getting Started

1. **Clone the repository:**
   git clone https://github.com/maverick250/Applied-Machine-Learning-at-Scale-Recommendation-System.git
   cd maverick250

### Navigate to the code directory:
  cd code

### Run the notebooks:

Launch **Jupyter Notebook** or **JupyterLab** and open any of the provided `.ipynb` files to explore or execute the code.

## Documentation and Report

For a comprehensive understanding of the project, please refer to the technical report that details the methodology, experiments, evaluation metrics, and visualizations.

👉 [View Technical Report (PDF)](https://[your-link-to-report.com/your-report.pdf](https://github.com/maverick250/Applied-Machine-Learning-at-Scale-Recommendation-System/blob/main/Applied_ML_at_Scale_Recommender_System_Technical_Report.pdf))

---

## Project Abstract and Introduction

### Abstract:
This report details the development of a collaborative filtering recommender system utilizing the Alternating Least Squares (ALS) algorithm. Tested on the MovieLens 100K and 25M datasets, the system integrates user and item biases with latent factor modeling to enhance recommendation accuracy. Performance was assessed using Root Mean Square Error (RMSE) and visualized through 2D embeddings of latent factors. A case study with a dummy user and an analysis of polarizing movies demonstrated the system’s practical applications. The report concludes with a mock A/B test validating algorithmic improvements and discusses future enhancements for real-world deployment.

### Introduction:
Recommender systems are integral to many online platforms, providing personalized content delivery by analyzing user preferences and behaviors. This project focuses on developing a collaborative filtering recommender system using the MovieLens dataset—a benchmark in the field—to evaluate the effectiveness of the ALS algorithm. The project is structured around two models: a baseline model capturing general user and item tendencies, and an enhanced model that incorporates latent factor vectors to uncover deeper user-item interactions. The work explores the dataset comprehensively, implements both models, and evaluates their performance using RMSE as a key metric, complemented by detailed visualizations and practical demonstrations.

---

## Contributing

Contributions, suggestions, or improvements are welcome. Feel free to open an issue or submit a pull request.

---

## License

[Insert License Information Here]

---

## Acknowledgements

Special thanks to the instructors, collaborators, and international experts, including Max Welling, who have provided valuable guidance throughout this project.


