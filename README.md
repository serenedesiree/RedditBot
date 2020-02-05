# RedditBot
A Reddit Bot that connects to IBM's Watson!

This bot is built to run on AWS, so it has a few idosyncracies. First of all, AWS needs everything to run in one file,
so instead of spreading out my code, I'm leaving it in the main folder. 

It also uses a handler, which allows Amazon to start the code when it's triggered. 

I uploaded this code to AWS using Lambda, EC2, RDS and Cloudwatch logs as the trigger. 
