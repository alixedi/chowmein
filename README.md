# Chow

Slack bot that pairs random people for lunch.


## The problem

I noticed at Duedil that a lot of people preferred having lunch with their team. This is understandable as people want to stay in their comfort zone but it is also a lost opportunity for Duedil on at least 3 counts:

1) Lunch is a great for communication across teams and cross pollination of ideas.

2) Lunch is awesome for ensuring that people who are shy, socially awkward, from half way across the planet or a combination thereof are not left isolated.

3) Lunch is an excuse to make new friends. More happiness. Less turnover.


## The solution

* Many ways to do this. I wrote a slack bot. His name is Chow. Chow responds to 2 commands: People who want to participate should type "In". People who want to bail out can type "Out". If you type anything else, Chow returns tour status - whether you are in or out and some more interesting facts.

* An hour before lunchtime, a reminder is sent to #general about Chow and how to participate.

* 15 minutes to lunch, Chow grab all the participants and pairs them randomly. He drops messages to people to let them know about their pairings. If the participants are odd numbered, Chow throws in a spare. Generally the HR guy is expected to fill this role.

* An hour after lunch, Chow sends a message to all participants asking them "How was your lunch with X today?". Their response is logged.