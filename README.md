##In this repository you will going to get the proper configuration for ISCSI Server and iscsi initiator 

Q) What is iscsi server ?
ANS:
 - ISCSI server is responsible to share disk (block device) to the ISCSI clients.
 - ISCSI server from which disk is getting shared is target server. 
 - ISCSI client is called initiator in ISCSI language. 


##Pre-requisities for ISCSI server and client:

 - AWS account is needed.
 - Create 2 ec2-instances in same AZ (availability zone).
 - Follow the same intructions which is given in this document.
 - attach one EBS on your target machine.


#On your 1st instance and give the name of that instance iscsi server (target server)

 - Follow the iscsi-target.txt file and execute the commands which is written in it.

#On your 2nd instance it will be your initiator machine (to use your shared storage) 

 - follow the iscsi-initiator.txt file and execute the commands which is written in it.


##now follow and enjoy the tutorial  
