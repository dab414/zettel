# 20221020134323-CPS_cyber_attack_taxonomy
#hcps #cyber-security

Cyber threats come in many forms across many systems, with a multitude of motivations and incentives for hackers to target a particular person or persons. In an effort to construct common themes around these attacks, we can abstract their consequences into the categories of physical, financial, data, and property harm. Below are examples of specific system attacks categorized by their ultimate consequence on the target(s).

## Physical/Personal:
- Smart cars:
	- Hacking a vehicle's on-board diagnostics port, which is typically used by mechanics to read maintenance issues, allows direct access to a vehicle's computer without any security measures. This may allow hackers to manipulate different car systems. Such attacks may have consequences for both the car and the user [1]
	- Pedestrian warning systems in teslas emit sound when driving under a certain speed to alert pedestrians who may not hear the car otherwise. This could cause an issue if the alarm were to be turned off and people crossing a street aren't aware of a passing car [14]
	- A car's controller area network (CAN) (which "lacks encryption, authethication, and access control" [16]) allows communication between the various systems present in a car, such as airbags, brakes, power windows, and windshield wipers. Cyber threats known as replay attacks allow hackers who have access to a vehicle's CAN system to repeat commands that were done in the vehicle previously, such as re-engaging window or brake systems, with varying consequences
- Medical:
	- Pacemakers may be hacked to rapidly deplete the device's battery or change its rate, both attacks having potentially fatal consequences. Thankfully, these devices are quite secure in that such attacks may only happen exactly when data is being transmitted to the user's doctor and the hacker would need to be in close proximity to the user. Data transmission typically takes between 3 and 12 minutes [2], [3]
	- Insulin pumps communicate data similarly to pacemakers, wirelessly. A hacker with access to one may be able to change the rate at which insulin is delivered, or stop delivery altogether. Pumps often only communicate with paired devices, so this is one of the most sensitive points where a hacker may gain access to one. [4]
	- Some CPS sensors can identify when individuals fall in their homes, or if their physical condition degenerates over time. These sensors may be able to converge information taken from cameras and algorithms. If compromised, the consequences could be substaintial for people who are already in bad physical/mental shape. For example, they might not receive treatment in a timely manner if a sensors monitoring capability is shut off, leading to potentially fatal issues [13]
- Energy:
	- Smart meters can be hacked and their parameters changed to lead to house fires/explosions which may be fatal for the building's resident(s) [8]

## Financial:
- Computers/smart phones:
	- Phishing emails with malware or dangerous links attached
		- One common type of malware is ransomware, which may prevent a user's access to their computer until they give the hacker money
	- Near-field communication (NFC) sensors (which are often used to pay for items by placing a phone next to a reader, with a detectable range of about 4 inches) may be misused by nearby hackers who use it to steal financial and other information
		- NFC can be disabled when not in use
- Planes:
	- Hackers gaining access to plane systems that communicate wirelessly to reduce flight delays/idle emissions. This can cost time, money, and give away sensitive information to unauhtorized parties [11]
- Energy:
	- Smart meters can be hacked and their parameters changed to lead to house fires/explosions. Additionally, since they link to the larger energy grid, a blackout can be caused and lead to downstream property damage and financial consequences as energy is not supplied to necessary facilities [8]
		- Hackers may also use this access to change how much a homeowner is paying for energy or siphon energy [9], [10]
- Bionic Limbs:
	- Some bionic limbs have smart capabilities, like displays, near-field communication ability, activity tracking, and bluetooth connectivity. This may allow hackers to steal personal information from the devices [12]

## Data/Privacy:
- Computer/smart-phone based attacks [15]
	- Phishing emails with malware or dangerous links attached
		- One common type of malware is ransomware, which may prevent a user's access to their computer until they give the hacker money
	- Malicious pop-ups that may ask for user feedback on a website, or have dangerous executibles attached to them
	- Web cam/microphone attacks that may give a hacker information about a user's identity, private information, and/or living situation. User's can look out for web cam attacks by noticing if their cam's LED light is on, and can prevent such attacks simply by covering up the cam when it is not being used.
	- Mouse attack that takes control of a user's computer to access potentially confidential information
	- Near-field communication (NFC) sensors (which are often used to pay for items by placing a phone next to a reader, with a detectable range of about 4 inches) may be misused by nearby hackers who use it to steal financial and other information
		- NFC can be disabled when not in use
	- Motion/movement sensor data may be accessed to determine a user's PIN by noting the movement of their fingers on the screen
- Smart cars:
	- GPS spoofing: accessing a vehicle's GPS and tricking the system's ability to ascertain correct location/direction sensor information
		- Smart GPS contains even more information and may provide real-time vehicle status updates about maintenance needs, info on fuel consumption, vehicle speed, etc. Needless to say, information that might be desirable by malicious parties
		- Accessing a tire pressure monitoring system (TPMS) communication log to identify a vehicle's ID. [16]
- VANETs (fits under all categories to some extent)
	- Many types of VANET-specific attacks exist, this is not an exhaustic list:
		- Replay attacks
		- Message tampering to change/alter messages transmitted among vehicles
		- Social attack  to steal information from users by sending immoral/spam messages
		- Masquerading attack to falsely pose as another entity
		- Denial of service attack to prevent communication between vehicles
		- Jamming attack to disturb communication
		- Spamming and removing data
		- Illusion attack to create false happenings in the road around a given vehicle
		- In general, VANET attacks are done to "reduce the performance of VANET, steal information to follow a genuine user, divert a VANET user from his path to get traffic less path, and/or intentionally cause car accident by providing wrong information." [17]
- Planes:
	- Hackers gaining access to plane systems that communicate wirelessly to reduce flight delays/idle emissions. This can cost time, money, and give away sensitive information to unauhtorized parties [11]
- Medical: 
	- Insulin pumps and Pacemakers may interface with a mobile app where confidential information may be compromised (e.g. Medtronic devices and MiniMed mobile app/CareLink) [4], [5], [6], [7]
- Energy:
	- Smart meters can be hacked and data/history of energy use information can be acquired [8]. Additionally, phishing email notifications may be sent  through some smart meter displays [9], [10]

## Property:
- Computer/smart-phone based attacks:
	- Certain malicious files may be downloaded on a user's computer if they click on the wrong website or are targeted, and may completely remove a computer's function by corrupting or deleting key files
- Smart cars:
	- Key fob relay attacks may allow hackers to gain access to a user's vehicle. This attack is accomplished by planting a transponder and a RFID received to copy a key fob's signal which interacts with the door lock. This copied signal can allow the hacker access to the vehicle. [1]
		- Users can protect against this with a shield pouch or a sterring wheel lock
	- Hacking a vehicle's on-board diagnostics port, which is typically used by mechanics to read maintenance issues, allows direct access to a vehicle's computer without any security measures. This may allow hackers to manipulate different car systems or perform replay attacks that retransmit a previously intitiated command (e.g. engaging the windshield wipers or brake systems). Such attacks may have consequences for both the car and the user. Similar access can be granted by targeting a vehicle's USB ports, media player, Bluetooth, or cellphone connectivity [1]
	- Smart alarms in vehicles are often insecure, and hackers can exploit insecure direct object reference (IDORS) issues with an alarm's software to track GPS, disable alarms, unlock doors, and in a particularly distressing case, turn off an engine while a car is in motion [1]
	* Accessing a car's Bluetooth system may allow for the injection of malware into other components of the car, such as the engine control unit (ECU). [16]
	* Thermometers in vehicles could be tampered with if temperature sensors would subjected to extreme cold or heat. [16]
- Energy:
	- Smart meters can be hacked and their parameters changed to lead to house fires/explosions. Additionally, since they link to the larger energy grid, a blackout can be caused and lead to downstream property damage and financial consequences as energy is not supplied to necessary facilities [8]

References:
1. **https://www.webroot.com/blog/2019/09/17/keeping-your-vehicle-secure-against-smart-car-hacks/**
2. **https://manuals.medtronic.com/content/dam/emanuals/crdm/M981757A001A_view.pdf**
3. **[https://www.upi.com/Top_News/US/2017/08/31/FDA-alerts-public-to-recall-of-pacemakers-vulnerable-to-cyberattack/4861504223465/](https://www.upi.com/Top_News/US/2017/08/31/FDA-alerts-public-to-recall-of-pacemakers-vulnerable-to-cyberattack/4861504223465/)**
4. **[https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed_770G_System_User_Guide.pdf](https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed_770G_System_User_Guide.pdf)**
5. **[https://www.tandemdiabetes.com/docs/default-source/product-documents/tslim-insulin-pump/tslim-user-guide-(4-3-2).pdf?sfvrsn=da6e39d7_10](https://www.tandemdiabetes.com/docs/default-source/product-documents/tslim-insulin-pump/tslim-user-guide-(4-3-2).pdf?sfvrsn=da6e39d7_10)**
6. **[https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed-Mobile-App-User-Guide.pdf](https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed-Mobile-App-User-Guide.pdf)**
7. **[https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/CareLink-Connect-App-User-Guide.pdf](https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/CareLink-Connect-App-User-Guide.pdf)**
8. https://texasenergyreport.com/news/2021/06/25/hacking-into-your-smart-meter-theres-a-lot-you-may-not-know/
9. **[https://www.smartme.co.uk/documents/RAM-Smart-Meter-User-Guide-web.pdf](https://www.smartme.co.uk/documents/RAM-Smart-Meter-User-Guide-web.pdf)**
10. **[https://assets.ctfassets.net/620j9bwnh4b6/76Bee9EXDCcEDOzoOwt2n4/7377cca4379fca36ed422d6116fd9b82/SMETS2_meter_guide.pdf](https://assets.ctfassets.net/620j9bwnh4b6/76Bee9EXDCcEDOzoOwt2n4/7377cca4379fca36ed422d6116fd9b82/SMETS2_meter_guide.pdf)**
11. **[https://www.nsf.gov/news/special_reports/cyber-physical/](https://www.nsf.gov/news/special_reports/cyber-physical/)**
12. https://www.zdnet.com/article/your-bionic-hand-is-now-at-risk-from-hackers/
13. **[https://beta.nsf.gov/news/health-care-follows-you-home-hospital-and-back](https://beta.nsf.gov/news/health-care-follows-you-home-hospital-and-back)**
14. **[https://www.tesla.com/ownersmanual/model3/en_us/GUID-518C51C1-E9AC-4A68-AE12-07F4FF8C881E.html](https://www.tesla.com/ownersmanual/model3/en_us/GUID-518C51C1-E9AC-4A68-AE12-07F4FF8C881E.html)**
15. Hewlett, E. M. (2020). _Human detection of attacks against cyber-physical systems_ (Doctoral dissertation, University of Bristol).
16. Humayed, A., & Luo, B. (2015, April). Cyber-physical security for smart cars: taxonomy of vulnerabilities, threats, and attacks. In _Proceedings of the ACM/IEEE Sixth International Conference on Cyber-Physical Systems_ (pp. 252-253).
17. **http://www.jcreview.com/admin/Uploads/Files/61c07bf6658ea1.10579682.pdf**