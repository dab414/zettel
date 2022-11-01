# 20221031163631-CPS_cyber_attack_taxonomy_data-privacy
#hcps #cyber-security

Cyber threats come in many forms across many systems, with a multitude of motivations and incentives for hackers to target a particular person or persons. Some of these attacks can infringe on the privacy of CPS users and result in attacks that lock people out of important systems, or steal sensitive information from them. Below are a number of examples across the domains of computers/smart-phones, smart cars, VANETs, planes, healthcare/medical, and energy.

## Data/Privacy:
- Computer/smart-phone based attacks [1]
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
		- Accessing a tire pressure monitoring system (TPMS) communication log to identify a vehicle's ID. [2]
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
		- In general, VANET attacks are done to "reduce the performance of VANET, steal information to follow a genuine user, divert a VANET user from his path to get traffic less path, and/or intentionally cause car accident by providing wrong information." [3]
- Planes:
	- Hackers gaining access to plane systems that communicate wirelessly to reduce flight delays/idle emissions. This can cost time, money, and give away sensitive information to unauhtorized parties [4]
- Healthcare/medical: 
	- Insulin pumps and Pacemakers may interface with a mobile app where confidential information may be compromised (e.g. Medtronic devices and MiniMed mobile app/CareLink) [5], [6], [7], [8]
	- Physical access to a device allows an attacker to obtain its serial number
- Energy:
	- Smart meters can be hacked and data/history of energy use information can be acquired [9]. Additionally, phishing email notifications may be sent  through some smart meter displays [10], [11]

References:
1. Hewlett, E. M. (2020). _Human detection of attacks against cyber-physical systems_ (Doctoral dissertation, University of Bristol).
2. Humayed, A., & Luo, B. (2015, April). Cyber-physical security for smart cars: taxonomy of vulnerabilities, threats, and attacks. In _Proceedings of the ACM/IEEE Sixth International Conference on Cyber-Physical Systems_ (pp. 252-253).
3. **http://www.jcreview.com/admin/Uploads/Files/61c07bf6658ea1.10579682.pdf**
4. **[https://www.nsf.gov/news/special_reports/cyber-physical/](https://www.nsf.gov/news/special_reports/cyber-physical/)**
5. **[https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed_770G_System_User_Guide.pdf](https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed_770G_System_User_Guide.pdf)**
6. **[https://www.tandemdiabetes.com/docs/default-source/product-documents/tslim-insulin-pump/tslim-user-guide-(4-3-2).pdf?sfvrsn=da6e39d7_10](https://www.tandemdiabetes.com/docs/default-source/product-documents/tslim-insulin-pump/tslim-user-guide-(4-3-2).pdf?sfvrsn=da6e39d7_10)**
7. **[https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed-Mobile-App-User-Guide.pdf](https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed-Mobile-App-User-Guide.pdf)**
8. **[https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/CareLink-Connect-App-User-Guide.pdf](https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/CareLink-Connect-App-User-Guide.pdf)**
9. https://texasenergyreport.com/news/2021/06/25/hacking-into-your-smart-meter-theres-a-lot-you-may-not-know/
10. **[https://www.smartme.co.uk/documents/RAM-Smart-Meter-User-Guide-web.pdf](https://www.smartme.co.uk/documents/RAM-Smart-Meter-User-Guide-web.pdf)**
11. **[https://assets.ctfassets.net/620j9bwnh4b6/76Bee9EXDCcEDOzoOwt2n4/7377cca4379fca36ed422d6116fd9b82/SMETS2_meter_guide.pdf](https://assets.ctfassets.net/620j9bwnh4b6/76Bee9EXDCcEDOzoOwt2n4/7377cca4379fca36ed422d6116fd9b82/SMETS2_meter_guide.pdf)**