# AZURE--TASK-8


### Creating two virtual networks:

1. Log in to your Azure portal.

2. Navigate to create a resource and go to networking, then click virtual network.

3. Enter details for VNet name, Region, and Resource group.

4. Under IP Addresses, you'll find the option to add subnets.

5. Click on add subnet and define Subnet1 with its IP address range.

6. Add subnet2 with a different IP address range.

7. Once you've added both subnets click review+create and then create.
   
###  Creating the availability set:

1. Go to Create a resource and go to compute then click availability Set.

2. Enter the name, region, and resource group.

3. Set the fault domains and update domains according to your redundancy requirements.

4. Click review + create and then click create.

### Launch VMs into the Availability Set and Specific Subnets.

1. Go to create a resource then, compute and then click virtual machine.

2. In the basics tab, specify the resource group, VM name, Region, and Image.

3. For availability options, select availability set and choose the availability Set created in Step 2.

4. In the networking tab, select the VNet created.

5. Choose subnet1 for the first VM.

6. Follow the same steps for the second VM, but in the networking tab, choose Subnet2.

7. Click on review+create for both VMs and then click create.

HENCE DAY - 8 TASK IS FINSHED !!!!....
