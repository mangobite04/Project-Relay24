# Project-Relay24
# This Project has below requirement:
#         1: Build 3 Ec2 Instances in 3 Avaiability Zone and install Java 8/9 and Maven 
#         2: Code Changes to this app on github commits
#         3: Deploys the code in the 3 availability zones with ASGs
#         4: Make sure Application is running or start
#         5: Add 3 Ec2 Instances to an ELB
#         6: Hit ELB usrl with /hello which shows displays the AZ on which the app is located
#         7: Terminating an instance within the AZ should trigger the creation of another instance in the same AZ, but the availability of the service shouldn’t be interrupted
