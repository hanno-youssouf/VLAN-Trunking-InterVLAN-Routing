VLAN, Trunking and Inter-VLAN Routing

 About This Project

This is my Cisco Packet Tracer project. I worked on VLANs, trunk links, and routing between VLANs.

I used switches, a router, and a Layer 3 switch to build and test the network.

What I Did

- Created VLAN 10, VLAN 20, and VLAN 30.
- Added switch ports to the correct VLANs.
- Connected two switches using a trunk link.
- Used a router to allow communication between VLANs.
- Used a Layer 3 switch to route traffic between VLANs.
- Tested the network using ping commands.

 VLAN Information

  VLAN   Department   Network             Gateway                |
  10     Admin        192.168.10.0/24     192.168.10.1 
  20     Finance      192.168.20.0/24     192.168.20.1 
  30     IT           192.168.30.0/24     192.168.30.1 

 Labs

 Lab 2: VLAN Segmentation

I created three VLANs and assigned switch ports to each department.

 Lab 3: Trunking Between Switches

I configured a trunk link between S1 and S2 to carry traffic from different VLANs.

Lab 4: Router-on-a-Stick

I configured router subinterfaces to allow communication between VLANs.

 Lab 5: Layer 3 Switch

I configured VLAN interfaces and enabled IP routing on the Layer 3 switch.

 Testing

I used Cisco IOS commands to check my configuration.

I also used ping tests to check communication between VLANs. The tests were successful, with 0% packet loss in the final results.

Screenshots are available in the Verification` folder.

 Files

- VLAN-Trunking-InterVLAN-Routing.pkt— My Packet Tracer project.
- Configurations/— My device configuration files.
- Verification/ — Screenshots of my tests.

Tools Used

- Cisco Packet Tracer
- Cisco IOS commands
   
 What I Learned

I learned how to create VLANs, configure trunk links, and allow communication between different VLANs. I also learned how to test and troubleshoot a network.
