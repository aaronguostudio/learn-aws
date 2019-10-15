# Exam 2

## Question 10

- Question
  - One of your EC2 instances is reporting an unhealthy system status check. The operations team is looking for an easier way to monitor and repair these instances instead of fixing them manually. How will you automate the monitoring and repair of the system status check failure in an AWS environment?
- Explaination
  - Using Amazon CloudWatch alarm actions, you can create alarms that automatically stop, terminate, reboot, or recover your EC2 instances. You can use the stop or terminate actions to help you save money when you no longer need an instance to be running. You can use the reboot and recover actions to automatically reboot those instances or recover them onto new hardware if a system impairment occurs.
  - When creating an alarm, there is a section of taking the action for recover/stop/terminate/reboot the instance
