# 20221016122319-potential_smart_car_cyber-security_measures

#hcps #smart-cars #cyber-security 

While the smart cars of today are lacking solid security standards, there is no shortage of ideas on how to ameliorate the issue in the future.

For example:
- Smart cars rely on a single network in a given city that shares data among other connected vehicles in that network [1]. Thus, if one vehicle is targeted by a hacker, all other vehicles that share the same network will likewise be at risk. If cities were to create multiple, smaller networks for vehicles to interface with, the spread of risk could be minimized.
- Manufacturers and others involved in the availability and installation of smart-car specific applications should priotize the secrutiy of the application before putting it on the market.
- A particularly unique example of how to ensure user security when using smart cars comes from the creators of a decentralized application based on BlockChain: CreditCoin [2].
	- This application allows for users to send anonymous announcements (e.g., traffic information) with usernames. Additionally, "no two messages can be linked to the same source" and the rate of data transmission is faster than typical VANET (vehicular ad hoc network) systems, according to a number of computer simulations.
	- Typical VANETs send similar messages anonymously because sensitive information could be linked to these messages (e.g., customer identities or vehicle number). Anonymity in this case damages the potential reliability of a message.
		- With CreditCoin, usernames ensure reliability. And privacy is ensured with components like Trace Manager, which can literally trace a malevolent users' identity. Also unlike typical VANET systems, CreditCoin is more tamper resistant, preventing hackers from modifying announcements without authorization.
	- Typical VANET users have no real motivation to send anonymous messages not only because of aforementioned privacy risks, but also due to a lack of incentive.
		- CreditCoin solves the issue of incentive by gamifying the transmission of useful vehicle data. Users of CreditCoin are able to earn "coins"  by participating in in-app requests to annouce traffic conditions or by sending traffic information to specific users requesting the information.
		- Accuring "coins" increases a users' reputation score, which ensures the reliability of their announcements and protects against the transmission of data by hackers/bots with low or no reputation scores.

References:
1. **[https://innovationatwork.ieee.org/six-ways-to-protect-against-autonomous-vehicle-cyber-attacks/](https://innovationatwork.ieee.org/six-ways-to-protect-against-autonomous-vehicle-cyber-attacks/)**
2. Li, L., Liu, J., Cheng, L., Qiu, S., Wang, W., Zhang, X., & Zhang, Z. (2018). Creditcoin: A privacy-preserving blockchain-based incentive announcement network for communications of smart vehicles. _IEEE Transactions on Intelligent Transportation Systems_, _19_(7), 2204-2220.