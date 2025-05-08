# Programming-Project
# Programming-Project
About:
    The Dataset shows 25 metrics on cybersecurity attacks. These metrics show information such as, when the attack happened, the type of attack, the action that was taken in response to the attack, etc. The jupyter notebook analyzes the data using different commands, and uses these commands to answer the questions below. 

Question 1: What Protocol was the most common?

Question 2: What was the highest anomaly score?

Question 3: Where most attacks Blocked, Logged, or Ignored?

Question 4: What Attack was the most common?

            The data showed that 'DDoS' was the most common attack. We used the command df['Attack Type'].value_counts() to answer this question. The ['Attack Type'] allows us to access a specific column in the csv. The value_counts() counts how many times a value shows up. DDoS showed the highest count. 