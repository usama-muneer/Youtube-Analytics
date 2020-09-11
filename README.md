# Youtube-Analytics

Introduction:
YouTube has been collecting data on their video streaming and the activities of user. They have recently shown their
interest in the proper analysis of this data.
They don’t have an easy way to perform the analysis. They have a set of CSV files that reside in a directory that is given to
you.
What we want from you is following.
 Design an Apache Cassandra Keyspace for YouTube analytics team.
 They have a list of questions that they are interested in. My task is to take necessary steps in form of
(creating tables) that can provide fast results. 
 I have to write an ETL pipeline that will import data from all of the CSV files that contain data about events.
# Dataset:
The dataset for this task lie in the youtube_event_data directory in form of CSV files.
# Questions that I have to answer.
1- Give me the youtuber, video title and video's length in the YouTube app history that was watched during
sessionId = 338, and itemInSession = 4
<br />
2- Give me only the following: name of youtuber, video (sorted by itemInSession) and user (first and last name) for
userid = 10, sessionid = 182
<br />
3- Give me every user name (first and last) in my YouTube app history who watched the video 'All Hands Against
His Own'
