# 🔐 Day 4 — Vishing & Smishing Awareness Simulation

![Kali Linux](https://img.shields.io/badge/Kali_Linux-2026.2-557C94?logo=kalilinux\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.13.12-3776AB?logo=python\&logoColor=white)
![Vishing](https://img.shields.io/badge/Vishing-Awareness_Training-orange)
![Smishing](https://img.shields.io/badge/Smishing-Awareness_Training-red)
![Social Engineering](https://img.shields.io/badge/Social_Engineering-Analysis-purple)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Authorized_Lab-green)
![GitHub](https://img.shields.io/badge/GitHub-Documentation-181717?logo=github\&logoColor=white)

> **SQROCK Cybersecurity Internship — Phase 1 | Day 4**
> **Project:** Vishing & Smishing Simulation Scripts
> **Difficulty:** Beginner
> **Focus:** Social Engineering Awareness & Defensive Analysis

---

## 📌 Project Overview

This project was completed as **Day 4 of the SQROCK Cybersecurity Internship — Phase 1**.

The objective was to develop a **Python-based Social Engineering Awareness Simulator** capable of generating controlled training scenarios representing common **vishing (voice phishing)** and **smishing (SMS phishing)** techniques.

The simulator models how social engineering attacks may use psychological triggers such as:

* Authority
* Urgency
* Fear
* Trust
* Curiosity

Rather than targeting real individuals or organizations, the project uses **simulated scenarios** for cybersecurity education and awareness training.

The generated scenarios cover three common contexts:

1. **IT Support**
2. **Banking**
3. **Government Services**

Each scenario identifies potential social engineering indicators and provides appropriate defensive responses.

---

## 🎯 Objectives

The main objectives of this project were to:

* Understand the fundamentals of **vishing and smishing**.
* Develop a Python-based awareness-training script generator.
* Simulate common social engineering scenarios in a controlled environment.
* Identify psychological techniques used by social engineers.
* Recognize common vishing and smishing red flags.
* Develop appropriate defensive responses.
* Practice Python functions, loops, dictionaries, strings, and formatted output.
* Strengthen cybersecurity documentation and evidence-collection skills.
* Apply ethical and responsible cybersecurity practices.

---

## 🛠️ Tools and Technologies Used

| Tool / Technology       | Purpose                                   |
| ----------------------- | ----------------------------------------- |
| **Kali Linux 2026.2**   | Cybersecurity laboratory environment      |
| **Python 3.13.12**      | Development of the awareness simulator    |
| **Nano**                | Python source-code editing                |
| **Linux Terminal**      | Script execution and testing              |
| **Python `py_compile`** | Syntax validation                         |
| **GitHub**              | Project documentation and version control |
| **Markdown**            | README documentation                      |

### Python Concepts Used

* Functions
* Dictionaries
* Lists
* Loops
* String formatting
* Multiline strings
* Console output
* File output using shell redirection
* Basic input/output automation

---

## 🧠 Skills Demonstrated

This project demonstrates the following cybersecurity and technical skills:

### Cybersecurity Skills

* Social engineering awareness
* Vishing analysis
* Smishing analysis
* Phishing awareness
* Psychological trigger identification
* Security awareness training
* Identification of suspicious communication patterns
* Defensive security analysis

### Technical Skills

* Python scripting
* Automation of repetitive awareness scenarios
* Structured data representation
* Linux command-line operations
* Python syntax validation
* Output generation
* Technical documentation

### Professional Skills

* Security-focused documentation
* Evidence collection
* Ethical cybersecurity practice
* Risk identification
* Defensive thinking
* Clear communication of security risks

---

## 🔬 Methodology

The project followed a structured cybersecurity awareness-training methodology.

### Phase 1 — Environment Preparation

A dedicated project directory was created:

```bash
mkdir -p ~/sqrock-internship/day4-vishing-smishing
cd ~/sqrock-internship/day4-vishing-smishing
```

The Python environment was verified using:

```bash
python3 --version
```

Result:

```text
Python 3.13.12
```
<img width="665" height="250" alt="Project 4 directory created" src="https://github.com/user-attachments/assets/0363fb28-802f-4981-ab54-cc86e0e64f5a" />

---

### Phase 2 — Simulator Development

A Python script named:

```text
se_awareness_generator.py
```
was developed.
<img width="652" height="441" alt="run awareness generator" src="https://github.com/user-attachments/assets/a009015e-db4a-4bab-a041-f62f136fec9a" />
<img width="680" height="48" alt="python awareness generator built" src="https://github.com/user-attachments/assets/656a3871-f61b-41f2-b078-aaeb83ffe974" />


The program contains separate functions for generating:

* Vishing awareness scenarios
* Smishing awareness scenarios

---

### Phase 3 — Scenario Development

Three simulated scenarios were created:

#### 1. IT Support

**Pretext:** Password Reset / Account Security

The scenario demonstrates how attackers may impersonate IT support personnel and create urgency around an account-security issue.

#### 2. Banking

**Pretext:** Suspicious Transaction Alert

The scenario demonstrates how social engineers may exploit financial concerns and fear to encourage immediate action.

#### 3. Government

**Pretext:** Document / Account Verification

The scenario demonstrates how perceived government authority can be used as a psychological trigger.

---

### Phase 4 — Psychological Trigger Analysis

Each scenario identifies common social engineering psychological triggers:

* **Authority** — pretending to represent a trusted organization or role.
* **Urgency** — creating pressure to act immediately.
* **Fear** — suggesting negative consequences if action is not taken.
* **Trust** — attempting to appear legitimate or familiar.
* **Curiosity** — encouraging the recipient to investigate an alleged issue.

---

### Phase 5 — Red-Flag Identification

The simulator identifies warning signs such as:

* Unexpected calls or messages.
* Pressure to act immediately.
* Requests for passwords or authentication codes.
* Suspicious links.
* Requests to bypass normal procedures.
* Unverified caller or sender identity.
* Suspicious spelling or formatting.
* Attempts to obtain sensitive information.

---

### Phase 6 — Defensive Response

The project provides security recommendations including:

1. Do not disclose passwords, PINs, or MFA codes.
2. Do not click suspicious links.
3. Independently verify the communication.
4. Contact the organization through an official channel.
5. Report suspicious activity to the appropriate security team.
6. Avoid bypassing established security procedures.

---

### Phase 7 — Testing and Validation

The simulator was executed using:

```bash
python3 se_awareness_generator.py
```

The output was also saved for documentation:

```bash
python3 se_awareness_generator.py | tee awareness_output.txt
```

Python syntax was validated using:

```bash
python3 -m py_compile se_awareness_generator.py
```

---

## 🧪 Laboratory Environment

The project was conducted inside a controlled cybersecurity learning environment using:

```text
Operating System : Kali Linux 2026.2
Python           : 3.13.12
Environment      : Local Virtual Cybersecurity Lab
Network          : Private/Controlled Lab Environment
Project Location : ~/sqrock-internship/day4-vishing-smishing
```

The project did **not** involve:

* Real phishing campaigns
* Real victims
* Real credentials
* Real banking accounts
* Real government accounts
* Live malicious links
* Unauthorized communication
* Impersonation of real organizations

All scenarios were designed strictly for cybersecurity education and awareness.

---

## ⚙️ Environment Configuration

The project directory was created with:

```bash
mkdir -p ~/sqrock-internship/day4-vishing-smishing
```

The working directory was:

```text
/home/kali/sqrock-internship/day4-vishing-smishing
```

Python was verified:

```bash
python3 --version
```

Output:

```text
Python 3.13.12
```

The project was implemented using Python's standard functionality, so no external Python packages were required.

---

## 📁 Project Structure

```text
day4-vishing-smishing/
│
├── se_awareness_generator.py
│
├── awareness_output.txt
│
├── README.md
│
└── screenshots/
    ├── 01-project-directory.png
    ├── 02-python-script.png
    ├── 03-generator-execution.png
    ├── 04-awareness-output.png
    └── 05-python-validation.png
```

### File Description

| File                        | Description                         |
| --------------------------- | ----------------------------------- |
| `se_awareness_generator.py` | Python awareness-training simulator |
| `awareness_output.txt`      | Generated training scenarios        |
| `README.md`                 | Project documentation               |
| `screenshots/`              | Evidence of project implementation  |

---

## 📊 Generated Scenarios

The simulator successfully generated six awareness-training scenarios:

| Scenario   | Vishing | Smishing |
| ---------- | :-----: | :------: |
| IT Support |    ✅    |     ✅    |
| Banking    |    ✅    |     ✅    |
| Government |    ✅    |     ✅    |

### Vishing

The simulator demonstrates how voice-based social engineering may exploit:

* Authority
* Urgency
* Fear
* Trust

### Smishing

The simulator demonstrates how SMS-based social engineering may exploit:

* Urgency
* Fear
* Authority
* Curiosity

---

## 🎓 Learning Outcomes

After completing this project, I developed a better understanding of:

* The difference between **vishing and smishing**.
* How social engineering manipulates human psychology.
* Common psychological triggers used in social engineering.
* How to recognize suspicious voice and SMS communications.
* Why attackers attempt to create urgency.
* Why passwords and MFA codes must never be disclosed.
* The importance of independently verifying unexpected requests.
* The role of security awareness in reducing human-related security risks.
* Using Python to automate cybersecurity awareness scenarios.
* Documenting cybersecurity projects professionally.

---

## ⚠️ Challenges Faced and How They Were Overcome

### Challenge 1 — Designing realistic but safe scenarios

A major challenge was creating scenarios that demonstrate social engineering techniques without producing material intended for real-world abuse.

**Solution:**
The simulator was designed exclusively for awareness training. It uses simulated roles, generic scenarios, no real organizations, no real credentials, and no live malicious links.

---

### Challenge 2 — Representing multiple social engineering scenarios

Different organizations can be used as social engineering pretexts.

**Solution:**
A structured Python list of dictionaries was used to represent three scenario categories:

```text
IT Support
Banking
Government
```

This allowed the same functions to generate multiple training scenarios.

---

### Challenge 3 — Identifying psychological manipulation

Social engineering is not purely technical; it relies heavily on human psychology.

**Solution:**
Each generated scenario explicitly identifies psychological triggers including authority, urgency, fear, trust, and curiosity.

---

### Challenge 4 — Validating the Python implementation

The simulator needed to execute correctly without syntax errors.

**Solution:**
The script was tested using:

```bash
python3 se_awareness_generator.py
```

and validated using:

```bash
python3 -m py_compile se_awareness_generator.py
```

---

### Challenge 5 — Maintaining ethical boundaries

Vishing and smishing techniques can easily cross from educational simulation into unauthorized activity.

**Solution:**
The project remained strictly within a controlled cybersecurity laboratory and focused on **detection, awareness, and defensive response** rather than real-world targeting.

---

## 🔐 Ethical and Legal Considerations

This project was conducted strictly for **educational cybersecurity awareness and authorized laboratory training**.

No real individuals, companies, financial institutions, government agencies, credentials, telephone numbers, or live phishing infrastructure were targeted.

The project follows the principle:

> **Learn ethically. Test responsibly. Defend effectively.**

Any real-world social engineering testing should only be conducted with explicit authorization, defined scope, and appropriate legal and organizational approval.

---

## 📸 Evidence and Screenshots

Recommended evidence for this project includes:

### 1. Project Directory

```bash
pwd
ls -la
```


### 2. Python Source Code

```bash
nano se_awareness_generator.py
```
<img width="680" height="48" alt="python awareness generator built" src="https://github.com/user-attachments/assets/5b42a4d8-7afe-4e34-a439-26eec0f0d72f" />


### 3. Generator Execution

```bash
python3 se_awareness_generator.py
```

<img width="652" height="441" alt="run awareness generator" src="https://github.com/user-attachments/assets/02e94746-2d76-477d-8bb4-7e99fdc84a5c" />
<img width="680" height="48" alt="python awareness generator built" src="https://github.com/user-attachments/assets/0479edcf-8dcb-4ab4-b7ad-de020bc8c59d" />

### 4. Generated Awareness Output

```bash
cat awareness_output.txt
```

<img width="688" height="482" alt="saved output verified" src="https://github.com/user-attachments/assets/fb1c75a2-0651-410c-aa87-f200b1120816" />

### 5. Python Syntax Validation

```bash
python3 -m py_compile se_awareness_generator.py
echo $?
```

A return value of:

```text
0
```

<img width="681" height="106" alt="echo script" src="https://github.com/user-attachments/assets/027a212b-1905-43ea-9796-a40585ad7a09" />

indicates successful syntax validation.

---

## 🏁 Conclusion

The **Day 4 Vishing & Smishing Awareness Simulation** successfully demonstrated how Python can be used to create controlled cybersecurity awareness scenarios.

The project combined programming with social engineering analysis by modeling common vishing and smishing techniques, identifying psychological triggers, highlighting red flags, and providing appropriate defensive responses.

The exercise strengthened practical skills in **Python scripting, social engineering awareness, defensive cybersecurity, Linux command-line usage, security analysis, and technical documentation**.

Most importantly, the project reinforced the importance of recognizing and resisting manipulation before sensitive information or unauthorized actions are involved.

---

 # 👤 Author
  Atemlefac Nkafu Bechem
  
  Cybersecurity Engineer

LinkedIn: https://www.linkedin.com/in/atemlefac-nkafu-bechem-179987248

# 📌 Project Information
**Program Name:** Cybersecurity internship at SQROCK | **Week:** 01 | **Project 4:** Vishing and smishing simulation scripts | **Repository:** GitHub
