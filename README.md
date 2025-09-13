Screenshot 2025-09-13 123554.png
🧠 Models Used

Logistic Regression (from scikit-learn)

Simple and effective model for binary classification.

Used here to predict eligibility based on categorical and numerical inputs.

The model was trained and saved as model.pkl for deployment.
📥 Input Features

The model takes the following inputs from the user via the Streamlit UI:

Feature	Description	Type	Values
CLMSEX	Gender	Categorical	Male = 1, Female = 0
CLMINSUR	Insurance Detail	Categorical	Yes = 1, No = 0
SEATBELT	Seatbelt Usage	Categorical	Yes = 1, No = 0
CLMAGE	Age	Numerical (Slider)	0 – 100
LOSS	Loss Amount	Numerical	Any float value
📤 Model Outputs

Predicted Class:

Eligible

Not Eligible

Prediction Probabilities:

Probability of class 0

Probability of class 1

Input Summary Table: Shows the exact inputs entered by the user.
🔧 Tech Stack

Python

Streamlit (for deployment UI)

scikit-learn (Logistic Regression model)

pandas & numpy (data handling)
