# Using Amazon Personalize to recommend cars

(Amazon Personalizer)[https://aws.amazon.com/personalize/] is a machine learning service that makes it easy for developers to create individualized recommendations for customers using their applications. This set
of notebooks provides developers that are new to Personalize with an end-to-end example for getting
started with the service. This gives an easy to understand and approachable baseline you can use
before bringing the service to your own datasets and recommendation applications.

The example is based on the domain of personalized car searches. A synthetic dataset is provided, and
testing has been done with 750K interactions against a set of 50K users and 30K users. Code is provided
to do the following:

1. Generate the synthetic dataset of users, cars, and interactions (users visiting detail page of a specific vehicle).
2. Create Amazon Personalize schemas and corresponding datasets and import jobs for users, cars, and interactions.
3. Create Personalize solutions, solution versions, and campaigns for HRNN, HRNN-metadata, personalized ranking, SIMS, and popularity count.
4. Exercise each of the campaigns, demonstrating accurate recommendations against these datasets. 
5. Exercise real time event tracking, submitting events after a campaign is already active, and demonstrating that Personalize recommendations leverage those new events.
6. Delete solutions, solution versions, event trackers, and campaigns.

Enjoy, and let me know your feedback.
