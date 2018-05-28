# AV-Innoplexus
In this competition a publication firm has presented you with a problem of identifying the articles that another article will cite as a reference.

# Problem Statement
Researchers often build upon the work of other researchers and as a result cite their research articles for inspiration or comparison of work. But for some publication firms, it is a problem when a research article cites irrelevant articles as references.

So, in this competition, a publication firm has presented you with a problem of identifying the articles that another article will cite as a reference.

For a particular article, the client has provided information such as its abstract, author name, title of the article etc. More details on the information can be found below. Also, it is worth noting that, research articles in both train and test are divided on the basis of set. A research article belonging to say set 1 can only cite articles from set 1 and not any other set.

Training data set has 9 sets in total, whereas Test data set has 9 sets. The Test has been further divided into public and private data set each containing 5 and 4 sets respectively.

Note: All sets irrespective of whether in train, public or private are independent of each other and share no article ids(pmid) in common.

# My Solution Approach
Start with document cleaning and pre-processing.
Find the tfidf score of each paper. 
Use cosine similarity to find similar papers within that set. (Constraint as per problem).

# Overall Rank
23

