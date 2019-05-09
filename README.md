# Conditional-Probability-python
here we using Probability with Condition
in the csv file we see two columns :test_result,has_cancer
and we make our Probability dependent on theese columns
if we want the patient has the test are (positive) and doesnt has cancer (false)
we doing that like this code:
(1 - df.query('test_result == "Positive"')['has_cancer'].mean())
