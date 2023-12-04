# Digital Forensics 

## Dealing with digitla forensics recovery:
1. First step is to isolate the target in a timely mannor so that people can't change files on the system:
   - Could be removing people from accessing it
   - Or removing it from the network without powering it down
2. Document the scene of the machine and make sure you have approval for what you're doing from legal!
   - What connections it has
   - What you're doing to it
   - What OS, software, and hardware the machine has 
3. Implement a write blocker on the machine
4. Hash the files to get a hash value
5. Take the temp files and anything that will be deleted when the system is powered down
6. Take the rest of the needed files
7. hash all the files gotten and compare to the hash value taken before
   - If the same carry on
   - If different the files have been tampered with 
8. Securely store the files gotten in a secure location and mark down the following
  - Chain of Custody of the device
  - How it's being stored
  - Who has access to it
9. Go through the files securely as needed and make sure to keep an updated leger of what you're doing
9. Acquire any other evidence thats needed  
