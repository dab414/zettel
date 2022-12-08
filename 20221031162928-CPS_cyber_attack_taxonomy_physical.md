# 20221031162928-CPS_cyber_attack_taxonomy_physical
#hcps #cyber-security

Cyber threats come in many forms across many systems, with a multitude of motivations and incentives for hackers to target a particular person or persons. These attacks come in the form of physical harm to the user(s) of a cyber-physical system. Below are a number of examples across the domains of smart cars, healthcare/medical, and energy.

## Physical/Personal:
- Smart cars:
	- Hacking a vehicle's on-board diagnostics port, which is typically used by mechanics to read maintenance issues, allows direct access to a vehicle's computer without any security measures. This may allow hackers to manipulate different car systems. Such attacks may have consequences for both the car and the user [1]
	- Pedestrian warning systems in teslas emit sound when driving under a certain speed to alert pedestrians who may not hear the car otherwise. This could cause an issue if the alarm were to be turned off and people crossing a street aren't aware of a passing car [14]
	- A car's controller area network (CAN) (which "lacks encryption, authethication, and access control" [16]) allows communication between the various systems present in a car, such as airbags, brakes, power windows, and windshield wipers. Cyber threats known as replay attacks allow hackers who have access to a vehicle's CAN system to repeat commands that were done in the vehicle previously, such as re-engaging window or brake systems, with varying consequences
	- Systems connected to the CAN network (i.e., Adaptive Cruise Control (ACC), Lane Keep Assist, and Collision Prevention) are vulnerable and may be disrupted (through noise or spoofing). For example, hackers could "reduce or increase speed unexpectedly, or even cause collisions" by manipulating ACC. [18]
	- Potential accidents from other "smart" vehicles such as "aircraft, ships, trains" [12]
- Healthcare/medical:
	- Pacemakers may be hacked to rapidly deplete the device's battery or change its rate, both attacks having potentially fatal consequences. Thankfully, these devices are quite secure in that such attacks may only happen exactly when data is being transmitted to the user's doctor and the hacker would need to be in close proximity to the user. Data transmission typically takes between 3 and 12 minutes [2], [3]
	- Insulin pumps communicate data similarly to pacemakers, wirelessly. A hacker with access to one may be able to change the rate at which insulin is delivered, or stop delivery altogether. Pumps often only communicate with paired devices, so this is one of the most sensitive points where a hacker may gain access to one. [4]
	- Some CPS sensors can identify when individuals fall in their homes, or if their physical condition degenerates over time. These sensors may be able to converge information taken from cameras and algorithms. If compromised, the consequences could be substaintial for people who are already in bad physical/mental shape. For example, they might not receive treatment in a timely manner if a sensors monitoring capability is shut off, leading to potentially fatal issues [13]
	- If a medical device's owner is absent, an attacker could install malware on it or modify its setup so the device delivers incorrect treatment.
	- Replay attacks can be done on medical devices by retransmitting legitimate commands (e.g. inject the wrong amount of insulin by delivering the right amount twice)
	- A hacker might jam an insulin pump so it cannot perform its function
- Energy/Infrastructure:
	- Smart meters can be hacked and their parameters changed to lead to house fires/explosions which may be fatal for the building's resident(s) [8]
	- Industrial plants (e.g., petro-chemical refinement plants, electric power stations, and manufacturing plants) may be targeted which could lead to asset damage, environmental damage, and importantly here: physical harm to nearby people/workers. [9]
		- "**Explosions, fires, floods, etc. resulting from failures of power plants, refineries, faulty computer controls, batteries**" [12]
		- Chemical spills
- Military:
	- Military weapon systems may be hacked into with varying levels of consequences depending on the system [9]. For example, UAVs in the military could have autonomous targeting and attacking capabilities (in the future, there is great debate about the safety of this idea). [10]
	- Other weapon system malfunctions such as "artillery, missles, drones, UAVs" [12]
- Robotics
	- Robots may work in health-care, professional, public, and private settings. A few examples include "industrial robots, warehouse robots, feeding robots, exoskeletons, assistants, socially interactive robots, robotic wheelchairs, or robotic surgeons.
		- These CPSs are highly complex, and if their security is compromised the consequences may be great.
		- Robotic surgeons in healthcare settings are particularly dangerous, as they may directly harm patients on the operating table. "Hackers could remotely access, control, and issue commands" to such robots

References:
1. **https://www.webroot.com/blog/2019/09/17/keeping-your-vehicle-secure-against-smart-car-hacks/**
2. **https://manuals.medtronic.com/content/dam/emanuals/crdm/M981757A001A_view.pdf**
3. **[https://www.upi.com/Top_News/US/2017/08/31/FDA-alerts-public-to-recall-of-pacemakers-vulnerable-to-cyberattack/4861504223465/](https://www.upi.com/Top_News/US/2017/08/31/FDA-alerts-public-to-recall-of-pacemakers-vulnerable-to-cyberattack/4861504223465/)**
4. **[https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed_770G_System_User_Guide.pdf](https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed_770G_System_User_Guide.pdf)**
5. **[https://www.tandemdiabetes.com/docs/default-source/product-documents/tslim-insulin-pump/tslim-user-guide-(4-3-2).pdf?sfvrsn=da6e39d7_10](https://www.tandemdiabetes.com/docs/default-source/product-documents/tslim-insulin-pump/tslim-user-guide-(4-3-2).pdf?sfvrsn=da6e39d7_10)**
6. **[https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed-Mobile-App-User-Guide.pdf](https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/MiniMed-Mobile-App-User-Guide.pdf)**
7. **[https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/CareLink-Connect-App-User-Guide.pdf](https://www.medtronicdiabetes.com/sites/default/files/library/download-library/user-guides/CareLink-Connect-App-User-Guide.pdf)**
8. https://texasenergyreport.com/news/2021/06/25/hacking-into-your-smart-meter-theres-a-lot-you-may-not-know/
9. Guzman, N. H. C., Kozine, I., & Lundteigen, M. A. (2021). An integrated safety and security analysis for cyber-physical harm scenarios. _Safety science_, _144_, 105458.
10. Protti, M., & Barzan, R. (2007). _UAV Autonomy-Which level is desirable?-which level is acceptable? Alenia Aeronautica Viewpoint_. ALENIA AERONAUTICA SPA TORINO (ITALY).
11. Fosch-Villaronga, E., & Mahler, T. (2021). Cybersecurity, safety and robots: Strengthening the link between cybersecurity and safety in the context of care robots. _Computer Law & Security Review_, _41_, 105528.
12. Axelrod, C. W. (2013, May). Managing the risks of cyber-physical systems. In _2013 IEEE Long Island Systems, Applications and Technology Conference (LISAT)_ (pp. 1-6). IEEE.