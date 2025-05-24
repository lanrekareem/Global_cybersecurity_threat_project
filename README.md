# Global_cybersecurity_threat_project

GLOBAL CYBERSECURITY THREATS 2015 - 2024 OVERVIEW

DATA SOURCE

DATA STRUCTURE

TOOLS

KEY QUESTIONS

DATA CLEANING

DATA ANALYSIS AND INSIGHTS

DATA VISUALIZATION

RECOMMENDATIONS



GLOBAL CYBERSECURITY THREATS 2015 – 2024
The Global Cybersecurity Threats Dataset (2015-2024) provides extensive data on cyberattacks, malware types, targeted industries, and affected countries. It is designed for threat intelligence analysis, cybersecurity trend forecasting, and machine learning model development to enhance global digital security.


DATA SOURCE

The dataset was gotten from Kaggle: www.kaggle.com

DATA STRUCTURE

Column Descriptions

Country: Country where the attack occurred

Year: Year of the incident

Attack Type: Type of cybersecurity threat (e.g., Malware, DDoS)

Targeted Industry: Industry targeted (e.g., Finance, Healthcare)

Financial Impact ($M): Estimated financial loss in millions

Number of Affected users

Attack source: The source of the attack (hacker group, insider)

Security Vulnerability type: The vulnerability type (Unpatched software, weak password)

Defense Mechanism used: The defense type (VPN, Firewall)

Incident Resolution Time (Hours): Time taken to mitigate the attack


TOOLS

•	MICROSOFT POWER BI 

KEY QUESTIONS

1.	What is the financial Impact (loss) caused by the various attack types?

2.	What is the percentage of financial loss incurred by each Attack source?

3.	What is the count of attacks on the various target industry?

4.	What is the estimated financial loss incurred by various countries due to cyber attacks?

5.	What are the trends and patterns in the frequency of cyber attacks over the past decade?

6.	What is the estimated financial loss incurred by various industries due to cyber attacks?

7.	What are the trends and patterns in the financial loss incurred over the last decade as a result of cyber attacks and threats?

8.	What are the types of cybersecurity vulnerabilities and how many users are affected by these vulnerabilities in various industries?

DATA CLEANING

These processes were carried out using power query on Microsoft powerBI

•	No duplicates were found in the dataset

•	The dataset is properly clean



DATA ANALYSIS AND INSIGHTS

This is the step in understanding the characteristics of the dataset

•	Average Resolution time: 36.48hours

•	Attack types: 6

•	Affected Users: 2998k

•	Financial Loss: $151,000,000

•	Defense Mechanism used: 5

•	Security Vulnerability type: 4



FINANCIAL LOSS BY ATTACK TYPE

•	DDOS: $27,631,000

•	Phishing: $26,693,000

•	SQL Injection: $25,157,000

•	Ransomware: $24,479,000

•	Malware: $23,968,000

•	Man-In-The-Middle: $23,551,000

Based on the analysis, DDOS has the highest financial loss with phishing following close, while Man-In-The-Middle has the lowest financial loss

FINANCIAL LOSS BY ATTACK SOURCE

•	Nation state: 26.73%

•	Unknown: 25.62%

•	Insider: 24.21%

•	Hacker group: 23.43%

According to the analysis, The attack source with the highest financial loss percentage is Nation state with 26.73% and Hacker group with the lowest at 23.43% of the financial loss

TARGET INDUSTRY AND ATTACK

•	IT: 478

•	Banking: 445

•	Healthcare: 429

•	Retail: 423

•	Education: 419

•	Government: 403

•	Telecommunication: 403

The industries that suffers the most cyber attacks include IT with 478 attacks, Banking with 445 attacks and Healthcare with 429 attacks, with Government at the bottom of the list with 403 attacks

FINANCIAL LOSS BY C0UNTRY

•	UK: $16,503,000

•	Germany: $15,793,000

•	Brazil: $15,783,000

•	Australia: $15,403,000

•	Japan: $15,197,000

•	France: $14,972,000

•	USA: $14,812,000

•	Russia: $14,735,000

•	India: $14,566,000

•	China: $13,714,000

The countries that incurred the highest financial loss include The United Kingdom with a loss of $ 16,503,000, Germany with a loss of $ 15,793,000, followed closely is Brazil with a loss of $ 15,783,000, while China incurred the lowest loss among the countries with a loss of $ 13,714,000  

CYBER ATTACKS OVER TIME

The number of cyber attacks has fluctuated over the past decade, with notable trends and variations:

•	2015: 277 Attacks

•	2016: 285 Attacks

•	2017: 319 Attacks

•	2018: 310 Attacks

•	2019: 263 Attacks

•	2020: 315 Attacks

•	2021: 299 Attacks

•	2022: 318 Attacks

•	2023: 315 Attacks

•	2024: 299 Attacks


 Initial increase (2015-2017) Cyber attacks rose from 277 in 2015 to a peak of 319 in 2017, then decline and stabilize (2018-2019) attacks decreased to 310 in 2018 and further dropped to 263 in 2019.
Resurgence (2020-2022) in Cyber attacks surged to 315 in 2020, reached 318 in 2022, Recent trends in (2023-2024) attacks remained steady at 315 in 2023 and slightly decreased to 299 in 2024.


AVERAGE FINANCIAL LOSS BY INDUSTRIES

•	Government: $53,000,000

•	IT: $52,000,000

•	Banking: $51,000,000

•	Telecommunication: $51,000,000

•	Retail: $50,000,000

•	Healthcare: $49,000,000

•	Education: $48,000,000

The financial impact of cyber attacks varies across industries, with some sectors experiencing significantly higher losses like the Government with a loss of $53 million, followed by IT and Banking with a loss of $52 millon and $51 million respectively with Education sector having the least financial loss of $48 million

MOST COMMON ATTACK TYPES

The following data illustrates the frequency of various cyber attack types:

•	DDOS: 531 Attacks

•	Phishing: 529 Attacks

•	SQL Injection: 503 Attacks

•	Ransomware: 493 Attacks

•	Malware: 485 Attacks

•	Man-In-The-Middle: 459 Attacks

This distribution highlights the prominence of DDoS and phishing attacks, followed closely by SQL injection and ransomware threats.

FINANCIAL LOSS OVERTIME

The financial impact of cyber attacks has fluctuated over the years, with notable peaks and troughs:

•	2015: $14,510,000

•	2016: $13,947,000

•	2017: $16,262,000

•	2018: $14,720,000

•	2019: $13,135,000

•	2020: $15,768,000

•	2021: $15,873,000

•	2022: $15,871,000

•	2023: $15,958,000

•	2024: $15,434,000

The Key Trends with Highest loss of $16.26 million (2017) and Lowest loss of $13.14 million (2019) with recent stability in Losses have stabilized around $15-16 million per year (2020-2024)

SECURITY VULNERABILITY TYPE AND AFFECTED USERS

The following security vulnerabilities have affected a significant number of users:

•	Zero day: 785 Affected users

•	Social Engineering: 747 Affected users

•	Unpatched software: 738 Affected users

•	Weak passwords:730 Affected users

This data highlights the importance of addressing these vulnerabilities to prevent cyber attacks and protect user data.

ATTACK TYPES AND DEFENCE MECHANISM USED

DDOS

•	AI Based Detection: 113

•	Antivirus: 103

•	Encryption: 92

•	Firewall: 103

•	VPN: 120

Phishing

•	AI Based Detection: 92

•	Antivirus: 111

•	Encryption: 121

•	Firewall: 93

•	VPN: 112

SQL Injection

•	AI Based Detection: 94

•	Antivirus: 113

•	Encryption: 107

•	Firewall: 86

•	VPN: 103

Ransomware

•	AI Based Detection: 97

•	Antivirus: 103

•	Encryption: 91

•	Firewall: 98

•	VPN: 104

Malware

•	AI Based Detection: 102

•	Antivirus: 111

•	Encryption: 86

•	Firewall: 99

•	VPN: 87

Man in the middle

•	AI Based Detection: 85

•	Antivirus: 87

•	Encryption: 95

•	Firewall: 106

•	VPN: 86

DATA VISUALIZATION

![image alt](https://github.com/lanrekareem/Global_cybersecurity_threat_project/blob/main/Global%20cybersecurity%20threats%20dashboard%201.png?raw=true)

![image alt](https://github.com/lanrekareem/Global_cybersecurity_threat_project/blob/main/Global%20cybersecurity%20threats%20dashboard%202.png?raw=true)



RECOMMENDATIONS

1. Strengthening Defenses

•	Implement robust security measures: Enhance incident-response capabilities, conduct regular vulnerability assessments, and deploy advanced threat detection systems.

•	Develop and update national cybersecurity strategies: Regularly review and refine strategies to stay ahead of evolving threats.

•	Foster international cooperation: Collaborate with other countries to share intelligence, best practices, and coordinate responses to cyber threats.

•	Conduct regular incident response drills and update protocols to reduce resolution time

•	Prioritize security measures in telecommunications and IT sectors

	
2. Protecting Against Specific Threats

•	Social Engineering: Educate users about phishing and other social engineering tactics, and implement measures to prevent email spoofing and phishing attacks.

•	Ransomware: Regularly back up critical data, implement robust access controls, and keep software up-to-date to prevent exploitation of known vulnerabilities.

•	Malware: Use antivirus software, firewalls, and intrusion detection systems to prevent malware infections.

•	Strengthen phishing prevention through employee training

•	Implement specialized defenses against nation-state attacks

•	Enhance insider threat monitoring systems

•	Implement AI-based detection systems, especially for high-risk industries

3. Capacity Building and Awareness

•	Cybersecurity training and awareness: Provide regular training for cybersecurity professionals, youth, and vulnerable groups to strengthen cybersecurity skills.

•	Public awareness campaigns: Conduct cyber awareness initiatives targeting the general population to create a culture of cybersecurity.

•	Capacity development initiatives: Reinforce capacity development initiatives to address the cyber capacity gap, particularly in developing countries.

4. Emerging Threats

•	AI-powered threats: Stay informed about the latest AI-powered threats and develop strategies to counter them.

•	Zero-day exploits: Implement robust vulnerability management processes to quickly respond to zero-day exploits.

•	Cloud intrusions: Secure cloud infrastructure with robust access controls, monitoring, and incident response plans.
