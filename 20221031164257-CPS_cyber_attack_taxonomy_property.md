# 20221031164257-CPS_cyber_attack_taxonomy_property
#hcps #cyber-security

Cyber threats come in many forms across many systems, with a multitude of motivations and incentives for hackers to target a particular person or persons. Some of these attacks can result in damage or harm to physical property/devices that interface with cyberspace, and adjcaent facilities/systems. Below are a number of examples across the domains of computers/smart-phones, smart cars, and energy.

## Property:
- Computer/smart-phone based attacks:
	- Certain malicious files may be downloaded on a user's computer if they click on the wrong website or are targeted, and may completely remove a computer's function by corrupting or deleting key files
- Smart cars:
	- Key fob relay attacks may allow hackers to gain access to a user's vehicle. This attack is accomplished by planting a transponder and a RFID received to copy a key fob's signal which interacts with the door lock. This copied signal can allow the hacker access to the vehicle. [1]
		- Users can protect against this with a shield pouch or a sterring wheel lock
	- Hacking a vehicle's on-board diagnostics port, which is typically used by mechanics to read maintenance issues, allows direct access to a vehicle's computer without any security measures. This may allow hackers to manipulate different car systems or perform replay attacks that retransmit a previously intitiated command (e.g. engaging the windshield wipers or brake systems). Such attacks may have consequences for both the car and the user. Similar access can be granted by targeting a vehicle's USB ports, media player, Bluetooth, or cellphone connectivity [1]
	- Smart alarms in vehicles are often insecure, and hackers can exploit insecure direct object reference (IDORS) issues with an alarm's software to track GPS, disable alarms, unlock doors, and in a particularly distressing case, turn off an engine while a car is in motion [1]
	* Accessing a car's Bluetooth system may allow for the injection of malware into other components of the car, such as the engine control unit (ECU). [2]
	* Thermometers in vehicles could be tampered with if temperature sensors would subjected to extreme cold or heat. [2]
	* Systems connected to the CAN network (i.e., Adaptive Cruise Control (ACC), Lane Keep Assist, and Collision Prevention) are vulnerable and may be disrupted (through noise or spoofing). For example, hackers could "reduce or increase speed unexpectedly, or even cause collisions" by manipulating ACC. [3]
- Energy:
	- Smart meters can be hacked and their parameters changed to lead to house fires/explosions. Additionally, since they link to the larger energy grid, a blackout can be caused and lead to downstream property damage and financial consequences as energy is not supplied to necessary facilities [4]
	* As an example of what can happen when a power grid is compromised, natural disasters hitting power grids in major cities have caused hundreds of thousands of people to be without power for days [5].

References:
1. **https://www.webroot.com/blog/2019/09/17/keeping-your-vehicle-secure-against-smart-car-hacks/**
2. Humayed, A., & Luo, B. (2015, April). Cyber-physical security for smart cars: taxonomy of vulnerabilities, threats, and attacks. In _Proceedings of the ACM/IEEE Sixth International Conference on Cyber-Physical Systems_ (pp. 252-253).
3. Humayed, A., Lin, J., Li, F., & Luo, B. (2017). Cyber-physical systems security—A survey. _IEEE Internet of Things Journal_, _4_(6), 1802-1831.
4. https://texasenergyreport.com/news/2021/06/25/hacking-into-your-smart-meter-theres-a-lot-you-may-not-know/
5. Humayed, A., Lin, J., Li, F., & Luo, B. (2017). Cyber-physical systems security—A survey. _IEEE Internet of Things Journal_, _4_(6), 1802-1831.