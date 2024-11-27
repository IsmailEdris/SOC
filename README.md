# SOC Analyst Home Lab Project
Becoming a skilled SOC analyst requires more than just theoretical knowledge; hands-on experience is crucial. In this blog, I will take you through the process of setting up my SOC home lab. I used tools like LimaCharlie and YARA rules to detect and respond to malicious activities, such as Sliver C2 payloads, while refining Detection and Response (D&R) rules to minimize false positives. This process closely mirrors the workflows employed in real-world SOC operations. This project was inspired by Eric Capuano's [So you want to be an SOC Analyst?](https://blog.ecapuano.com/p/so-you-want-to-be-a-soc-analyst-part)

## Table of Contents
1. [Setting up the Lab Environment](https://github.com/IsmailEdris/SOC/blob/c9c513ed0dc587d6dd0c16cab2e1712fd457d2ea/1.%20Setting%20up%20the%20Lab%20Environment.md)
2. [Generating C2 Payload](https://github.com/IsmailEdris/SOC/blob/0cdf421db401a737822c762f47fa88432a198217/2.%20Generating%20C2%20Payload.md)
3. [Observing the EDR Telmetry](https://github.com/IsmailEdris/SOC/blob/ce42260c39ba7769cc4fc09f36c7259263769e35/3.%20Observing%20the%20EDR%20Telmetry.md)
4. [Building and Testing D&R Rules for lsass.exe](https://github.com/IsmailEdris/SOC/blob/c9c513ed0dc587d6dd0c16cab2e1712fd457d2ea/4.%20Building%20and%20Testing%20D%26R%20Rules%20for%20lsass.exe.md)
5. [Building and Testing D&R RUles for Volume Shadow Copies](https://github.com/IsmailEdris/SOC/blob/c9c513ed0dc587d6dd0c16cab2e1712fd457d2ea/5.%20Building%20and%20Testing%20D%26R%20Rules%20for%20Volume%20Shadow%20Copies.md)
6. [Tuning False Positives](https://github.com/IsmailEdris/SOC/blob/c9c513ed0dc587d6dd0c16cab2e1712fd457d2ea/6.%20Tuning%20False%20Positives.md)
7. [Creating YARA Rules to Detect Sliver Payloads](https://github.com/IsmailEdris/SOC/blob/c9c513ed0dc587d6dd0c16cab2e1712fd457d2ea/7.%20Creating%20YARA%20Rules%20to%20Detect%20Sliver%20Payloads.md)


