# OOW-18: Oracle Code ONE Lab session [HOL4973]
Prep repository for OOW-18, Oracle Code ONE Hands-on Lab.

PLEASE NOTE: YOU MUST BRING YOUR OWN LAPTOP (BYOL) TO PARTICIPATE IN THE HANDS-ON LABS.<br>
Get your skills going on decentralized application development before everybody else! This session will jump-start your career in the decentralized field—making you ready for the future and an even more requested resource for companies all over the world. Blockchain is on everybody’s lips, and in this hands-on lab, you will have the opportunity to get your hands dirty developing chaincode directly in the cloud, using a fun and engaging forest-saving use case. Later on your code might be implemented to help save the environment!

# USE CASE - Current Situation: A Hyperledger Fabric Network of 3 Parties:
1. Claudio's Controlling (Founder) - Owners of the Trusted Trees brand - The Trusted Tree branding guarantees the lumber origin as well as the worker terms and it also guarantees that more trees are planted than cut. This brand attracts a lot of investors.
2. Franco's Forestry (Participant) - Plant & grow trees on site in Senegal under Trusted Tree umbrella.
3. Leopold's Lumber (Participant) - Cut trees into lumber under the Trusted Trees brand.

# USE CASE - Whats Going On:
A second tree planting participant, Pape's Plantation, wants to join the network. It is our job to spin up their chaincode and adapt the code to this participant.

# LAB - Suggested Workflow:
- Log in to OABCS using the credentials provided.
- Locate the instance of Pape's Plantation.
- Locate the provided channel between Pape's Plantation and the umbrella organisation for Trusted Trees - Claudio's Controlling.
- Download the chaincode from GitHub in Go. (Or NodeJS - your choice!)
- Upload, install and instantiate the chaincode on your channel.
- Invoke the chaincode using REST (PostMan or cUrl recommended).
- Update the code with a new price per tree for this participant.
- Upgrade the chaincode with the new version.

# Challenge:
- Claudio's controlling could really benefit from a "Query all" function. Please help them out!

# Optional:
- Send a pull request with your new code on GitHub.
