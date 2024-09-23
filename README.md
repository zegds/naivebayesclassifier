# Naive Bayes Classifier
A simple loan approval classification model that uses historical data to predict new cases.

<b>Goal:</b> To predict whether someone will be approved for a loan based on characteristics like ```age```, ```income```, ```student status```, and ```credit rating```. It uses historical data to calculate the probabilities of loan approval or rejection for each characteristic.
<br><br>
<b>Input:</b> The code takes three things:
* A dataset containing information about people's characteristics and whether they were approved for a loan.
* A list of the characteristics (attributes) to analyze.
* A dictionary that lists the possible values for each characteristic (e.g., age can be "<=30", "31-40", ">40").

<b>Output:</b> The code returns a set of probabilities showing the likelihood of ```loan approval ("yes")``` or ```rejection ("no")``` for each attribute. For example, it can tell us how likely someone is to get approved for a loan based on their age or income.

<b>Algorithm:</b>
1. <b>Read the dataset:</b> It reads a file containing the data.
2. <b>Count the loan approvals:</b> It checks how many people were approved ("yes") and how many were rejected ("no").
3. <b>Calculate probabilities:</b> For each characteristic (e.g., age or income), it calculates the probability of getting a loan or not, depending on the characteristic’s value. For example, it might find that people under 30 have a higher chance of being rejected.

<b>Probabilities:</b> The results are stored in a dictionary where the probabilities are calculated for each characteristic based on past loan decisions.
