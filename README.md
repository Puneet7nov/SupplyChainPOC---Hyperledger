# SupplyChainPOC---Hyperledger
####This is a POC created in Hyperledger Fabric for Supply Chain in Automobile Industry############

In the Supply Chain of Autombile Industry there are following participants:
a) Distributors/Retailers
b) Manufacturing dept.
c) Procurement dept.
d) Finance/Accounts dept.
e) External Vendors
etc

In this POC we want to demonstrate how different entities in the network can share the ledger and how different ascpects of supply chain can be automated using Chaincodes (Smart Contracts).

########## Sprint 1 ##################################
==========================
In the first sprint we target to:

1) Setup docker swarm and run atleast 3 nodes 
2) Define various participants in the supply chain with the 3 nodes representing Finance dept., Procurement dept. and a vendor node.
3) Establish channel between:
  a) Procurement and Vendor
  b) Procurement and Finance depts.
 4) Right Chaincode to trigger action from Finance depts based on input from Procurement dept.
  a) Finance depts dispenses X amount to the vendor once the Procurement dept finalizes and approves the given vendor at an agreed Total cost price of 2X.
  b) Dispense another X amount once Procurement team approves of the delivery with 99% and above Quality Index.
  c) If the quality of deliver is < 99% and > 90% then disburse only 0.5X
  d) If the quality index is < 90% then do not disburse any further amount.
  
===========================


