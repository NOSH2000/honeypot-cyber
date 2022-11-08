# Honeypot Assignment

**Time spent:** **25** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** How did you deploy it? Did you use GCP, AWS, Azure, Vagrant, VirtualBox, etc.?

I used google cloud platform (gcp) to deploy MHN-Admin (Modern Honey Network). I created a gcp account and installed gcp sdk on my local machine. After the gcp setup, I created the MHN Admin VM and setup firewall rules.

<img src="mhn.gif">

### Dionaea Honeypot Deployment (Required)

**Summary:** Briefly in your own words, what does dionaea do?

Dionaea is a honeypot used to capture malware samples. It gathers information on malware used to exploit the system and reports them to external analysis service providers.

<img src="honeypot.gif">
<img src="dionaea.gif">

### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?

Ubuntu is the RDBMS that MHN-Admin uses. The exported JSON file record contains specific data on the nature of the attacks and where they came from such as the IP address, session ID, and such.

## Notes

Resource: https://hackmd.io/@nkogkneeto/H1YKtqk9r
