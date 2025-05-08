# Programming-Project

About:
    The Dataset shows 25 metrics on cybersecurity attacks. These metrics show information such as, when the attack happened, the type of attack, the action that was taken in response to the attack, etc. The jupyter notebook analyzes the data using different commands, and uses these commands to answer the questions below. 

Question 1: What Protocol was the most common?
            The analysis revealed that the most common protocol was ICMP with a value count of 13429. We were able to conclude this by using teh command 'df['Protocol'].value_counts()', which identifies and counts the occurences of each unique value within the specified column, in this case, 'Protocol'. To enhance this finding, we imported maplotlib to generate a visual representation that would provide a clean and concise depiction of the data distribution. 

Question 2: What was the highest anomaly score?

Question 3: Where most attacks Blocked, Logged, or Ignored?

Question 4: What Attack was the most common?
            The analysis revealed that Distributed Denial of Service (DDoS) attacks were the most prevalent type of attack within the dataset. This conclusion was derived using the command `df['Attack Type'].value_counts()`, which identifies and counts the occurrences of each unique value within the specified column, in this case, `'Attack Type'`. The results indicated that DDoS attacks had the highest frequency. To enhance the interpretability of this finding, the `matplotlib` library was utilized to generate a visual representation, providing a clear and concise depiction of the data distribution for the audience.