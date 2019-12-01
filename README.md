# MHN Honeypot

Overview
![Alt Text](honeypot-overview.gif)

#### Which Honeypot(s) you deployed

1. **Dionaea** a nepenthes successor, embedding python as scripting language, using libemu to detect shellcodes, supporting ipv6 and tls.
2. **Snort:** an intrusion prevention system that can do real-time traffic analysis and packet logging.
3. **Amun:** a python-based low-interaction honeypot, following the concepts of Nepenthes but extending it with more sophisticated emulation and easier maintenance
4. **Conpot:** a honeypot that logs brute force attacks and the attacker's shell interaction.

#### Any issues you encountered

Nothing major to state. Just took some time figuring out how to setup MHN Admin and the honeypots. At some point, I had a hard time getting the honeypots to show up on MHN admin. The instructions on setting up could be a little bit more clear regarding Milestone 4.

#### A summary of the data collected:

**Number of Attacks:** 767,129
**Number of Malware Samples:** 0

**Top 5 Attacker IPS**

1. 105.157.199.157 (72,906 attacks)
2. 82.215.81.86 (72,078 attacks)
3. 120.89.94.246 (71,618 attacks)
4. 60.211.231.86 (71,505 attacks)
5. 2.50.40.205 (69,354 attacks)

**Top 5 Attacked Ports**

1. 1433 (757,535 times)
2. 445 (2,373 times)
3. 80 (2,329 times)
4. 139 (1,397 times)
5. 3389 (1,196 times)

**Top 5 Honey Pots:**

1. dionaea (767,344 attacks)
2. amun (2,314 attacks)
3. conpot (937 attacks)
4. snort (239 attacks)

#### Any unresolved questions reaised by the data collected

### Issues

I am unable to attach the session.json file because the file exceeds more than 200gb and there is an error saying I am unable to attach it to the repository.
