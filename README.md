# Social Media and Mental Health - Machine Learning Project

## Overview
This project uses machine learning to predict mental health status among students based on their social media usage patterns. The project analyzes various features including daily usage hours, social comparison behavior, sleep disruption, and academic performance to classify mental health into three categories: Poor, Fair, and Good.

## Dataset
The project includes a synthetic dataset (`social_media_mental_health.csv`) with 500 student records containing:
- **Demographics**: Age, Gender
- **Social Media Usage**: Daily usage hours, number of platforms, posting frequency, scrolling frequency
- **Social Behavior**: Online friends, average likes per post, social comparison, validation seeking, FOMO score
- **Health Indicators**: Sleep disruption, GPA
- **Target Variable**: Mental health score and category (Poor/Fair/Good)

## Features
- Comprehensive data exploration and visualization
- Multiple machine learning models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - Support Vector Machine
- Model performance comparison
- Feature importance analysis
- Detailed insights and recommendations

## Requirements
```
numpy
pandas
scikit-learn
matplotlib
seaborn
jupyter
```

## Installation
1. Clone the repository:
```bash
git clone https://github.com/aryah-rao/social-media-and-mental-health-ml.git
cd social-media-and-mental-health-ml
```

2. Install required packages:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

## Usage
1. Open the Jupyter notebook:
```bash
jupyter notebook mental_health_prediction.ipynb
```

2. Run all cells in the notebook to:
   - Load and explore the dataset
   - Visualize relationships between features
   - Train and evaluate multiple ML models
   - Analyze results and insights

## Project Structure
```
├── README.md
├── social_media_mental_health.csv    # Dataset
└── mental_health_prediction.ipynb    # Main analysis notebook
```

## Key Findings
- Social comparison behavior and FOMO scores are strongly associated with mental health outcomes
- Higher social media usage correlates with increased mental health challenges
- Academic performance (GPA) shows positive correlation with mental health
- Sleep disruption due to social media negatively impacts mental health

## Models Performance
The project trains and compares multiple machine learning models, with ensemble methods (Random Forest, Gradient Boosting) typically achieving the highest accuracy.

## Recommendations
### For Students:
- Monitor and limit daily social media usage
- Be mindful of social comparison behavior
- Prioritize sleep over late-night social media use
- Balance online and offline activities

### For Educational Institutions:
- Implement awareness programs about healthy social media usage
- Provide mental health support services
- Encourage digital wellness practices

## Future Improvements
- Collect longitudinal data to track changes over time
- Include more diverse features (specific platforms, content types)
- Develop intervention strategies based on model predictions
- Validate findings with clinical mental health assessments

## License
This project is available for educational purposes.

## Author
Aryah Rao