# SOC Analyst Home Lab Project
Becoming a skilled SOC analyst requires more than just theoretical knowledge; hands-on experience is crucial. In this blog, I will take you through the process of setting up my SOC home lab. I used tools like LimaCharlie and YARA rules to detect and respond to malicious activities, such as Sliver C2 payloads, while refining Detection and Response (D&R) rules to minimize false positives. This process closely mirrors the workflows employed in real-world SOC operations. This project was inspired by Eric Capuano's [So you want to be an SOC Analyst?](https://blog.ecapuano.com/p/so-you-want-to-be-a-soc-analyst-part)

## Table of Contents
1. [Setting up the Lab Environment](https://github.com/IsmailEdris/SOC/blob/0c5de3f1f3e4e742eda64a8d4442f5c48c2bbc04/Setting%20up%20the%20Lab%20Environment)
2. [Generating C2 Payload](https://github.com/IsmailEdris/SOC/blob/2eaadc85862cd47112561bb157857b8de3bf5cbd/Generating%20C2%20Payload)
3. [Observing the EDR Telmetry](https://github.com/IsmailEdris/SOC/blob/2eaadc85862cd47112561bb157857b8de3bf5cbd/Observing%20the%20EDR%20Telmetry)
4. [Building and Testing D&R Rules for lsass.exe](https://github.com/IsmailEdris/SOC/blob/2eaadc85862cd47112561bb157857b8de3bf5cbd/Building%20and%20Testing%20D%26R%20Rules%20for%20lsass.exe)
5. [Building and Testing D&R RUles for Volume Shadow Copies](https://github.com/IsmailEdris/SOC/blob/2eaadc85862cd47112561bb157857b8de3bf5cbd/Building%20and%20Testing%20D%26R%20Rules%20for%20Volume%20Shadow%20Copies)
6. [Tuning False Positives](https://github.com/IsmailEdris/SOC/blob/2eaadc85862cd47112561bb157857b8de3bf5cbd/Tuning%20False%20Positives)
7. [Creating YARA Rules to Detect Sliver Payloads](https://github.com/IsmailEdris/SOC/blob/2eaadc85862cd47112561bb157857b8de3bf5cbd/Creating%20YARA%20Rules%20to%20Detect%20Sliver%20Payloads)


