# Amazon-Alexa-Reviews


## HOW TO RUN

Step 1: Clone the repository
```
git clone 
```

Step 2: Open the cloned repository and create a conda environment. Activate the new environment
```
conda create -n amazonreview python=3.10
```
```
conda activate amazonreview
```

Step 3: Install the requirements file
```
pip install -r requirements.txt
```

Step 4: Run the app
```
flask --app api.py run
```

Step 5: The app will run on port 5000. 
```
localhost:5000
```

Algorithm

    The application uses the XGBoost algorithm for analyzing reviews. This algorithm is known for its performance and accuracy in classification tasks.

Notes  

     1. The backend of this application is implemented using Flask.
     2. Due to limited data for negative reviews, the model might sometimes give incorrect predictions. 3.3. 3. Future improvements could include gathering more data to enhance the model's accuracy.
     4. Contributing
     5.Contributions are welcome! Please fork the repository and create a pull request with your changes.

Features

    1.Sentiment Analysis: Predicts whether a review is positive or negative.
    2.Review Summarization: Summarizes the content of the reviews.
    3.User Interface: Easy-to-use web interface for submitting reviews and viewing results.


Technologies Used

    1.Python: Core programming language.
    2.Flask: Web framework for the backend.
    3.XGBoost: Machine learning algorithm for review analysis.
    4.Conda: Environment and package management.

Fork the Project

    Create your Feature Branch (git checkout -b feature/AmazingFeature)
    Commit your Changes (git commit -m 'Add some AmazingFeature')
    Push to the Branch (git push origin feature/AmazingFeature)
    Open a Pull Request


License

    Distributed under the MIT License. See LICENSE for more information.
