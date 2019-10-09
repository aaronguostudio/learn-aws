# Quizs

- Your company likes the idea of storing files on AWS. However, low-latency service of the majority of files is important to customer service. Which Storage Gateway configuration would you use to achieve both of these ends? (Choose 2)
  - Gateway-Stored
  - File Gateways
    - Gateway-Stored volumes store your primary data locally, while asynchronously backing up that data to AWS. Depending on the Cache allocated you can achieve the same with File Gateway
- You work for a toy company that has a busy online store. As you are approaching Christmas, you find that your store is getting more and more traffic. You ensure that the web tier of your store is behind an Auto Scaling group. However, you notice that the web tier is frequently scaling, sometimes multiple times in an hour, only to scale back after peak usage. You need to keep Auto Scaling from scaling up and down so rapidly. Which of the following options would help you to achieve this?
  - Modify the Auto Scaling group cool-down timers & modify the Amazon CloudWatch alarm period that triggers your Auto Scaling scale down policy.
