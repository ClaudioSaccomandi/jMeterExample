# jMeterExample

The example application it's a service that can query for users. Not a real app, but a similar situation I had to dealt with.

In this example the test will do the following actions:

1) getting a jwt token
2) requesting the landing page
3) requesting a specific user

I've added comments on each step on what they do

The load profile is 100 virtual users ramping up during 5 minutes and running the transactions at constant load for 60 minutes


This test might not open in Jmeter unless the jmeter plugin manager is installed.
