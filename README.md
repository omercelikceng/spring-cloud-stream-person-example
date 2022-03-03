
Please start the cloud-stream-person-producer application first. 

Then start the cloud-stream-person-consumer and do not close the producer. 

Because I always want to have enough data in the topic.

# Occuring Situation : 
Data came to streamlistener 20 times in 1 second.
I set Concurrency to 3. There was no change in the situation.
I want to receive data periodically. In my case data is constantly flowing. 
And there is always a lot of data on the topic. 
But I don't have enough resources. 
I want to pull data in bulk every 5 seconds. 
However, I could never do that. 
As long as there is data in the topic, it is constantly coming to the streamlistener.


Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:50 EET 2022

# ------------------------------------------

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022

Count : 1000 Date : Thu Mar 03 12:21:51 EET 2022
