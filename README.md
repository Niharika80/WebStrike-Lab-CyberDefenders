# WebStrike-Lab-CyberDefenders
### Scenario
A suspicious file was identified on a company web server, raising alarms within the intranet. The Development team flagged the anomaly, suspecting potential malicious activity. To address the issue, the network team captured critical network traffic and prepared a PCAP file for review.
Your task is to analyze the provided PCAP file to uncover how the file appeared and determine the extent of any unauthorized activity.

---

## Questions:

Q1 : From which city did the attack originate?  
Answer : `Tianjin`  

![Q1](https://github.com/Niharika80/WebStrike-Lab-CyberDefenders/blob/bc37ffa446d5dae9a5e07d243b61ad724b2f3991/images/1.jpg)
___

Q2 : What's the attacker's Full User-Agent?  
Answer : `Mozilla/5.0 (X11; Linux x86_64; rv:109.0) Gecko/20100101 Firefox/115.0`  

![Q2](https://github.com/Niharika80/WebStrike-Lab-CyberDefenders/blob/ff4842bd8605cda9ad199caa5b4e6d5683f75781/images/2.jpg)
___

Q3 : What is the name of the malicious web shell that was successfully uploaded?  
Answer : `image.jpg.php`  

![Q3](https://github.com/Niharika80/WebStrike-Lab-CyberDefenders/blob/ff4842bd8605cda9ad199caa5b4e6d5683f75781/images/3.jpg)
___

Q4 : Which directory is used by the website to store the uploaded files?  
Answer : `/reviews/uploads/`  

![Q4](https://github.com/Niharika80/WebStrike-Lab-CyberDefenders/blob/b04d595aec384b531d0df896005ffb6859e5962f/images/4.jpg)
___

Q5 : Which port, opened on the attacker's machine, was targeted by the malicious web shell for establishing unauthorized outbound communication?  
Answer : `8080`  

![Q5](https://github.com/Niharika80/WebStrike-Lab-CyberDefenders/blob/ff4842bd8605cda9ad199caa5b4e6d5683f75781/images/5.jpg)
___

Q6 : Which file was the attacker attempting to exfiltrate?  
Answer : `passwd`  

![Q6](https://github.com/Niharika80/WebStrike-Lab-CyberDefenders/blob/ff4842bd8605cda9ad199caa5b4e6d5683f75781/images/6.jpg)
___

---

## What I Learned:

- Strengthened my **Wireshark** and **PCAP analysis** skills to investigate web-based intrusions.  
- Learned how to trace **web shell uploads**, identify **exfiltration attempts**, and recognize **attacker behavior** through network patterns.  
- Understood the importance of **directory enumeration** and **filtering HTTP traffic** for incident response.  
- Improved my capability to analyze **HTTP methods, ports, and outbound connections** used in attacks.  

This lab deepened my understanding of **real-world web exploitation and network forensic investigation** — essential for any **SOC or Blue Team analyst**.

---

### 🔗 References
- [CyberDefenders – WebStrike Challenge](https://cyberdefenders.org/blueteam-ctf-challenges/challenge/webstrike/)
