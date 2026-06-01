## \#💻 Ransomware:

###### &#x20;It is a type of malicious software that encrypts or locks access to files, systems, or devices until a ransom is paid, usually in cryptocurrency. It has evolved into one of the most dangerous cyber threats globally, targeting individuals, businesses, and even governments. Paying the ransom is strongly discouraged, as it does not guarantee recovery and fuels further attacks.



###📖 History \& Evolution:

##### &#x20;> 1989:

###### &#x20;     First known ransomware, the AIDS Trojan (PC Cyborg), spread via floppy disks.



##### &#x20;> 2006–2013:

###### &#x20;           More advanced variants like Gpcode and CryptoLocker introduced strong encryption, making

###### &#x20;           recovery without keys nearly impossible.



##### &#x20;> 2015–Present:

###### &#x20;              Ransomware-as-a-Service (RaaS) emerged, allowing even non-technical criminals to launch

###### &#x20;              attacks. Modern strains often combine encryption with data theft (double extortion),

###### &#x20;              threatening to leak sensitive information if ransom isn’t paid.

##### 

####🧩 Types of ransomware:

###### &#x20;1.Encrypting (Crypto-ransomware): Encrypts files and demands payment for decryption. Ex-CryptoLocker.

###### &#x20;2.Screen Lockers: Locks the device with a full-screen ransom message. Ex-Fake “government” warnings.

###### &#x20;3.MBR Ransomware: Alters the Master Boot Record, preventing system boot. Ex-Petya.

###### &#x20;4.Mobile Ransomware: Infects smartphones via malicious apps or drive-by downloads. Ex-Android ransomware.

###### &#x20;5.Scareware: Fake alerts claiming infection, demanding payment. Ex-Rogue antivirus pop-ups.



####⚙️ How Attacks Work:

##### > Delivery Methods:

###### &#x20;                   Malicious email attachments (executables, archives, images).

###### &#x20;                   Compromised websites (drive-by downloads).

###### &#x20;                   Exploiting vulnerabilities in software or servers.



##### > Execution:

###### &#x20;         Once opened, ransomware encrypts files or locks systems.



##### > Demand:

###### &#x20;      Victims see instructions for payment, often with threats of permanent data loss or public leaks.



####🛡️ Prevention \& Protection:

##### > Backups:

###### &#x20;         Maintain offline/cloud backups of critical data.

##### 

##### > Security Software:

###### &#x20;                 Use updated antivirus and endpoint protection.

##### 

##### > Patch Systems:

###### &#x20;              Regularly update operating systems and applications.

##### 

##### > Email Hygiene:

###### &#x20;              Avoid suspicious attachments and links.

##### 

##### > Awareness:

###### &#x20;          Train employees to recognize phishing attempts.





### \#📊 CVSS(Common Vulnerability Scoring System):

#### &#x20;Formula:

###### &#x20;          The CVSS score is built in three layers: Base, Temporal, Environmental.

##### &#x20;1. Base Score

###### &#x20;Impact Subscore (ISC):

###### &#x20;        ISC=1-(1-C)\*(1-I)\*(1-A)

###### &#x20;where:

###### 𝐶= Confidentiality impact

###### I = Integrity impact

###### 𝐴= Availability impact

###### 

###### Impact Calculation:

###### 

###### > If Scope = Unchanged:

###### &#x20;       impact=6.42\*ISC

###### 

###### > If Scope = Changed:

###### &#x20;     impact=7.52\*(ISC-0.0290)-3.25\*(ISC-0.02)^15

###### 

###### > Exploitability Subscore:

###### &#x20;        exploitability =8.22\*AV\*AC\*PR\*UI

###### where:

###### 𝐴𝑉= Attack Vector

###### 𝐴𝐶 = Attack Complexity

###### 𝑃𝑅 = Privileges Required

###### 𝑈𝐼 = User Interaction

###### 

###### \*Base Score Final:

###### 

###### If Scope = Unchanged:

###### &#x20;  Basescore = roundup(min(impact+exploitability,10)

###### 

###### If Scope = Changed:

###### &#x20;     Basescore = roundup(min(1.80 \*(impact+ exploitability),10))



##### 2\. Temporal Score

###### Adjusts the Base Score based on exploit maturity, remediation availability, and report confidence:

###### 

###### &#x20; Temporalscore= roundup (Basescore \*E\*RL\*RC)

###### 

###### where:

###### E= Exploit Code Maturity

###### 𝑅𝐿= Remediation Level

###### 𝑅𝐶 = Report Confidence



##### 3\. Environmental Score

###### Customizes the score for a specific organization’s environment:

###### &#x20;      Environmentalscore= roundup(ModifiedBasescore \* E\*RL\*RC)

