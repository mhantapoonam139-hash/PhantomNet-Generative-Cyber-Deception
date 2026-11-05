👻 PhantomNet – Generative Cyber-Deception

An AI-powered cybersecurity deception system using locally hosted Large Language Models (LLMs) to generate realistic fictional corporate environments and intelligent honeypots.

 🚀 Project Overview
Traditional cybersecurity honeypots use static fake files, directories, and databases. Experienced attackers can easily identify them because their contents are repetitive and unrealistic.

PhantomNet aims to solve this problem using Generative AI. It dynamically creates a fictional corporate environment containing realistic files, employee records, database responses, and corporate information.

When suspicious activity enters the isolated honeypot environment, the system generates context-aware fictional information while security teams monitor and analyze the activity.

✨ Key Features

- 🧠 **Generative AI Integration – Uses locally hosted LLMs through Ollama.
- 📁 **Generative Filesystem– Dynamically generates fictional corporate files and directories.
- 🗄️ **Dynamic SQL Engine – Simulates realistic corporate database responses.
- 🔄 **Context Retention – Maintains consistency using ChromaDB.
- 🌐 **Network Interception – Monitors and routes selected test traffic.
- 📊 **Security Dashboard – Displays suspicious activities and AI responses.
- 🔍 **Behavioral Analysis – Analyzes commands and suspicious activity.
- 🔐 **Sandbox Security – Isolates the honeypot from the real host environment.

🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend development |
| Linux / Ubuntu | Development environment |
| FUSE | Virtual filesystem |
| Ollama | Local AI model |
| Llama 3.2 | Example LLM |
| ChromaDB | Context retention |
| PostgreSQL | Mock database |
| eBPF | Network monitoring |
| React.js | Security dashboard |
| Tailwind CSS | Frontend styling |
| Git & GitHub | Version control |

 🏗️ Project Modules

1. Generative Filesystem
Develop a Python-based virtual filesystem using FUSE to generate realistic fictional corporate directories and filenames.

2. Lore Engineering
Create a fictional company identity, including company details, executives, departments, and corporate terminology.

3. Dynamic SQL Engine
Develop a simulated database engine that generates realistic fictional database records based on SQL queries.

4. Context Engine
Integrate Ollama and ChromaDB to maintain consistent generated files, employee information, and database responses.

5. Network Interceptor
Use Python and eBPF-based monitoring to observe selected network activities and route authorized test traffic into the isolated honeypot.

6. Security Analyst Dashboard
Develop a React-based dashboard to display commands, database queries, generated responses, and security events.

7. Behavioral Analysis
Analyze suspicious activities and classify observed behavior for security monitoring.


📅 Week-wise Development Roadmap

 🟢 Week 1 – Generative Filesystem & Lore Engineering

Objective:** Build the basic virtual filesystem and establish fictional corporate identity.

Development Tasks:**
- Set up Python and Linux development environment.
- Install and configure FUSE.
- Create the Python virtual filesystem.
- Integrate Ollama with Python.
- Generate realistic fictional filenames.
- Create fictional company details and executives.
- Maintain consistent corporate terminology.

Expected Output:** A basic working virtual filesystem with AI-generated fictional corporate filenames.

🟡 Week 2 – Dynamic SQL Engine & Context Retention

Objective:** Develop simulated corporate database responses and AI memory.

Development Tasks:
- Set up a mock PostgreSQL database.
- Develop SQL query processing.
- Generate fictional employee and payroll records.
- Integrate Ollama with the database engine.
- Install and configure ChromaDB.
- Implement context retention.
- Test consistency of generated information.

Expected Output: A simulated SQL engine with realistic fictional records and context-aware AI responses.

🟠 Mid-Project Review

Review Activities:
- Demonstrate the virtual filesystem.
- Show AI-generated fictional filenames.
- Demonstrate SQL query processing.
- Show context retention.
- Present implementation screenshots and GitHub progress.

🔵 Week 3 – Network Routing & Telemetry Dashboard

Objective:Implement controlled network monitoring and a live security dashboard.

Development Tasks:
- Study Linux networking and eBPF.
- Implement network monitoring.
- Develop controlled traffic routing.
- Create a React dashboard.
- Integrate backend APIs.
- Display suspicious commands and SQL queries.
- Implement live event monitoring.

Expected Output: A network monitoring prototype with a real-time security dashboard.

🔴 Week 4 – Behavioral Analysis & Security

Objective: Analyze suspicious activities, strengthen sandbox security, and integrate all modules.

Development Tasks:
- Implement behavioral analysis.
- Classify suspicious activities.
- Develop risk evaluation.
- Harden sandbox isolation.
- Test filesystem and network restrictions.
- Integrate all project modules.
- Perform end-to-end testing.
- Fix bugs and update documentation.

Expected Output: An integrated PhantomNet cybersecurity deception prototype.



📂 Project Folder Structure


PhantomNet/
│
├── filesystem/
│   ├── virtual_fs.py
│   └── file_generator.py
│
├── ai_engine/
│   ├── ollama_client.py
│   └── prompts.py
│
├── company_lore/
│   ├── company.json
│   ├── executives.json
│   └── departments.json
│
├── database/
│   ├── mock_database.py
│   └── sql_engine.py
│
├── context_engine/
│   ├── memory.py
│   └── context_manager.py
│
├── network/
│   ├── network_monitor.py
│   └── traffic_router.py
│
├── analysis/
│   └── behavior_analyzer.py
│
├── dashboard/
├── tests/
├── screenshots/
├── requirements.txt
├── .gitignore
├── README.md
└── main.py


This is the planned structure. Files will be added as development progresses.



⚙️ Installation & Getting Started

Prerequisites

- Python 3.10 or later
- Ubuntu / Linux
- Git
- FUSE 3
- Ollama
- VS Code

Step 1: Clone the Repository


git clone https://github.com/mhantapoonam139-hash/PhantomNet-Generative-Cyber-Deception.git


Step 2: Open the Project


cd PhantomNet-Generative-Cyber-Deception


Step 3: Create Virtual Environment


python3 -m venv venv
source venv/bin/activate


Step 4: Install Dependencies


pip install -r requirements.txt


Step 5: Install Ollama

Download Ollama:

https://ollama.com/download

Download the example model:


ollama pull llama3.2


Step 6: Start Development

Begin with Week 1 and implement each module according to the development roadmap.

The complete application execution commands will be added after module integration.*

---

🧪 Testing & Validation

- [ ] Virtual filesystem testing.
- [ ] Dynamic filename generation testing.
- [ ] Ollama integration testing.
- [ ] Fictional company consistency testing.
- [ ] SQL engine testing.
- [ ] ChromaDB context retrieval testing.
- [ ] Network monitoring testing.
- [ ] Dashboard integration testing.
- [ ] Behavioral analysis testing.
- [ ] Sandbox isolation testing.

---

👥 Team Collaboration

All team members will collaborate through GitHub.

Development Workflow:

1. Clone the shared repository.
2. Create a separate feature branch.
3. Implement assigned modules.
4. Commit changes regularly.
5. Push changes to GitHub.
6. Create Pull Requests.
7. Review and merge approved changes.

---

🔐 Security Guidelines

- Use an isolated virtual machine or sandbox.
- Use fictional corporate information only.
- Never upload confidential data or API keys.
- Restrict network and filesystem access.
- Perform testing only in authorized environments.
- Keep the host system isolated from honeypot activities.

---

🎯 Expected Final Outcome

PhantomNet aims to demonstrate an intelligent cybersecurity deception environment that dynamically generates fictional corporate information, simulates database interactions, maintains AI context, monitors suspicious activity, and provides security insights through a dashboard.

Project Name:PhantomNet

Project Domain: Cybersecurity & Generative AI

Development Duration: 4 Weeks

Project Status: Under Development

Repository: [PhantomNet – GitHub](https://github.com/mhantapoonam139-hash/PhantomNet-Generative-Cyber-Deception)


Building intelligent deception systems for safer digital environments. 👻*
