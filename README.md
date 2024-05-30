# LeetCodeOnlineVoting

# Initialization (TopVotedCandidate Constructor):

We initialize the times and leaders lists.
We use a dictionary voteCount to keep track of the number of votes for each candidate.
We iterate over the persons array, update the vote counts, determine the current leader, and store the leader in the leaders list after each vote.

# Query Method (q):

We use a binary search to find the largest index in times where the time is less than or equal to t. This allows us to quickly determine the leader at any given time.
The binary search helps in efficiently finding the correct leader without having to iterate over the entire times array for each query.
