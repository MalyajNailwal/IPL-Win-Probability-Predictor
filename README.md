# IPL Win Probability Predictor

This project predicts the win probability of IPL teams during matches based on live inputs and historical data. The model uses machine learning techniques and IPL datasets to deliver real-time predictions with **89%+ accuracy in seconds**. It is designed to make an impact by providing quick, reliable insights, and it is fully mobile-friendly for on-the-go usage.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Details](#model-details)
- [Contributing](#contributing)
- [License](#license)

## Overview
The IPL Win Probability Predictor analyzes live match data and predicts the probability of each team's victory. It is designed for cricket enthusiasts, analysts, and developers to gain insights and enhance the viewing experience.

### Check it out here: [IPL Win Probability Predictor](https://ipl-win-probability-predictor-bfko.onrender.com)

## Features
- Real-time win probability prediction during IPL matches.
- Visualization of key match statistics.
- Interactive interface for inputting match data.
- Insights based on historical IPL match records.
- **Mobile-friendly design** for accessibility anywhere.

## Setup and Installation
### Prerequisites
- Python 3.8+
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Flask (or Streamlit for a GUI version)

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/MalyajNailwal/IPL-Win-Probability-Predictor.git
   cd IPL-Win-Probability-Predictor
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```

## Usage
1. Start the application by running the `app.py` script.
2. Input the live match data, including team names, score, overs, and wickets.
3. View the predicted win probabilities for both teams.
4. (Optional) Customize the model parameters for better accuracy.

## Dataset
The project uses historical IPL data to train the machine learning model. Ensure you have the IPL dataset in the correct format (CSV/JSON) placed in the `data/` directory. If unavailable, you can download IPL data from platforms like Kaggle.

## Model Details
The model is built using the following techniques:
- **Feature Engineering**: Extracts crucial match details such as run rate, wickets in hand, and match context.
- **Machine Learning Algorithm**: Utilizes a Random Forest Classifier for predictions, trained on historical IPL match data.
- **Evaluation Metrics**: Accuracy, Precision, Recall, and F1-Score.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
Feel free to report any issues or suggest enhancements in the [Issues](https://github.com/MalyajNailwal/IPL-Win-Probability-Predictor/issues) section. Enjoy predicting IPL match outcomes!
