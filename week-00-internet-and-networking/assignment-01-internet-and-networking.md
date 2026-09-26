# Week 00 - Internet and Networking

Part of the DevOps Micro Internship (DMI) with Agentic AI

---

# 🧑‍💻 Task 1: Using ChatGPT as Your Learning Assistant

## Scenario

You're new to DevOps and will frequently encounter technical questions. ChatGPT can be your learning companion.

## Your Task

Write a clear ChatGPT prompt to help you understand:

> "What is a protocol in networking? Explain with a simple real-life example."

Take a screenshot of your interaction showing:

* Your detailed prompt (with clear expectations)
* ChatGPT's simplified response with an example

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.

![Task 1 Screenshot](screenshots_task_1_chatgpt.png, screenshots_task_1b_chatgpt.png, screenshots_task_1c_chatgpt.png)


Replace `task-1-chatgpt.png` with your actual screenshot file name.

---

## What I Learned (2–3 lines)

I learned that protocols are like traffic rules: they make communication organized and predictable instead of chaotic.E.G HTTP/HTTPS, TCP, SSH.
---

# 🌐 Task 2: Internet and Networking

## Scenario

Your friend is launching an online bookstore named **EpicReads**.

He asked you to explain how users globally can access his website hosted in Finland.

## Your Task

Write a short explanation (**100–150 words**) that includes:

* Packet Switching
* IP Address
* TCP/IP
* HTTP/HTTPS

💡 **Tip:** You may use ChatGPT (as demonstrated in Task 1) to refine your explanation.

## Answer

Imagine I am in Nigeria and want to access my online bookstore, **EpicReads**, which is hosted on a server in Finland. When I enter the website address in my browser, my request is broken into small units of data called **packets**. This process is called **packet switching**, and the packets can travel through different networks and routes to reach the server.

The EpicReads server has an **IP address**, which works like its digital address and helps the network locate it. **TCP/IP** provides the rules for moving the data across the Internet. TCP helps ensure the packets are delivered correctly, while IP handles addressing and routing.

Finally, **HTTP/HTTPS** allows my browser and the EpicReads server to communicate. HTTPS also encrypts the connection, helping protect my information while I browse and make purchases.

---

# 🏗️ Task 3: Application Architecture & Stack

## Scenario

EpicReads bookstore has two application versions:

### Two-Tier Application

* Frontend
* Database

### Three-Tier Application

* Frontend
* Backend
* Database

## Your Task

* Draw simple diagrams (hand-drawn or tool-based such as draw.io)
* Label each layer clearly
* List at least two common technologies or tools used for each layer
* Submit a screenshot or photo clearly showing your own drawing

## Diagram Screenshot / Photo

Save your diagram image in the `screenshots` folder and update the file name below.

![Application Architecture Diagram](screenshots/task-3-diagram.png)


Replace `task-3-diagram.png` with your actual diagram file name.

---

## Technologies Used

### Frontend

* HTML
* CSS

### Backend

* PYTHON
* DJANGO

### Database

* SQLite
* MySQL

---

# 🌍 Task 4: Domain Name & DNS (Basic Concepts)

## Scenario

Your friend's bookstore **EpicReads** is currently accessible through:

```text
52.172.142.222:3000
```

He purchased the domain:

```text
epicreads.com
```

## Your Task

In **50–100 words**, explain in your own words:

1. What is DNS (Domain Name System)?
2. Which DNS record type should be used to connect the domain to the given IP, and why?

## Answer

1. DNS (Domain Name System) is like the internet’s phonebook. It translates human-readable domain names, such as **epicreads.com**, into IP addresses that computers use to locate servers. 

2. To connect **epicreads.com** to **52.172.142.222**, an **A (Address) record** should be used because A records map a domain name to an IPv4 address. This allows users to type **epicreads.com** instead of remembering the server’s numerical IP address.

DNS points to the IP, while the `:3000` port is handled separately by the application/server.

---

# 💻 Task 5: Visual Studio Code Setup (Hands-on)

## Your Task

Install Visual Studio Code (if not already installed).

Take a screenshot of your VS Code environment showing:

* Terminal open inside VS Code
* Running a basic command:

### Windows

```powershell
dir
```

### Linux / macOS

```bash
pwd
ls
```

* Your selected VS Code theme clearly visible

⚠️ **Important:** The screenshot must show your username or another identifiable detail to confirm it is your environment.

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.

![VS Code Setup Screenshot](screenshots/task-5-vscode.png)


Replace `task-5-vscode.png` with your actual screenshot file name.

---

# 🔗 Task 6: Publish Your Assignment as a LinkedIn Post

## Objective

Publishing on LinkedIn helps you:

* Build your professional online presence
* Reinforce your learning
* Document your DevOps journey publicly

## Your Task

Summarize your answers from Tasks 1–5 into a LinkedIn post.

Clearly structure your post into the following sections:

* ChatGPT
* Internet & Networking
* App Architecture
* DNS
* VS Code Setup

Use the credit note that matches your track:

Add the following credit note at the end of your post **(If you are DMI Cohort 3 student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) with Agentic AI — Cohort 3 — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=cohort3**

**Tag [Pravin Mishra](https://www.linkedin.com/in/pravin-mishra-aws-trainer/) in your LinkedIn post, then tag Lead Co-Mentor — [Anjana Muthunayake](https://www.linkedin.com/in/anjana-muthunayake/).**

Add the following credit note at the end of your post **(If you are DMI Self-paced track student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) — Self-Paced Engineer Track — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=self-paced**

Add the following credit note at the end of your post **(If you are DMI Campus student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) — Campus — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=campus**

**Tag [Pravin Mishra](https://www.linkedin.com/in/pravin-mishra-aws-trainer/) in your LinkedIn post, then tag Lead Co-Mentor — [Anjana Muthunayake](https://www.linkedin.com/in/anjana-muthunayake/).**

Hashtags:

#DMIByPravinMishra #AgenticAI #DevOps

Replace `YOUR-GITHUB-USERNAME` with your GitHub username — that link is your public DMI progress page (your graded badge page).
---

## LinkedIn Post URL

Paste your LinkedIn post URL here:

```text
https://lnkd.in/p/e96fVzYh
```

---

## LinkedIn Post Backup Copy

Paste the full text of your LinkedIn post here:

Week 00 of my DevOps Micro Internship (DMI) with Agentic AI is complete.

This week was about understanding the foundations behind how applications communicate and how users access them.

🔹 ChatGPT
I explored how to use ChatGPT as a learning assistant by creating detailed prompts that help break technical concepts down into simple, real-world explanations. One concept I explored was networking protocols.

🔹 Internet & Networking
I learned how packet switching, IP addresses, TCP/IP, and HTTP/HTTPS work together when a user accesses a website. For example, when someone in Nigeria accesses a bookstore hosted in Finland, data is broken into packets and routed across networks to reach the destination server.

🔹 App Architecture
I explored the difference between two-tier and three-tier architecture:
* Two-tier: Frontend → Database
* Three-tier: Frontend → Backend → Database
I also looked at technologies such as HTML, CSS, Python, Django, SQLite, and MySQL.

🔹 DNS
I learned that DNS translates human-readable domain names into IP addresses. An A record can map a domain such as epicreads.com to an IPv4 address such as 52.172.142.222.

🔹 VS Code Setup
I set up my VS Code environment, opened the integrated terminal, and practiced basic commands while getting more comfortable working from the command line.

Week 00 reminded me that DevOps isn't just about learning tools. Understanding the fundamentals underneath those tools matters.

One concept at a time. One hands-on task at a time. Building the foundation.

P.S. This post is part of the DevOps Micro Internship (DMI) with Agentic AI — Cohort 4 aspirant — by Pravin Mishra. 

My graded progress is public: https://lnkd.in/eRwGJhfs

Start your DevOps journey: https://lnkd.in/eVAbSjUw
Pravin Mishra
Anjana Muthunayake
#DMIByPravinMishra #AgenticAI #DevOps
---

# Reflection – Week 0

### What did you find easy?

Being truthful and helping others, thanking people for the littlest things.
---

### What was difficult?

Multi-tasking

---

### What will you improve next week?

Time Management and commitment level.

---

## 📌 About DMI & CloudAdvisory

DevOps Micro Internship (DMI) is a project-based DevOps program run by Pravin Mishra (The CloudAdvisory) focused on real-world execution, systems thinking, and career readiness.

It helps learners build strong DevOps foundations with hands-on experience.


## 📌 Resources

- 🌐 **DMI Official Website:** https://dmi.pravinmishra.com?utm_source=github&utm_medium=readme  
- 🎓 **University:** https://university.pravinmishra.com?utm_source=github&utm_medium=readme  
- 💬 **Discord Community:** https://discord.pravinmishra.com?utm_source=github&utm_medium=readme  
- 📝 **Blog:** https://dmi.pravinmishra.com/blog?utm_source=github&utm_medium=readme  
- ▶️ **YouTube Playlist (DMI Cohort 3):** https://www.youtube.com/playlist?list=PLFeSNDtI4Cho  
- 🔗 **Pravin Mishra (LinkedIn):** https://www.linkedin.com/in/pravin-mishra-aws-trainer/  
- 🏢 **CloudAdvisory (LinkedIn):** https://www.linkedin.com/company/thecloudadvisory/

---

*This submission is part of DevOps Micro Internship (DMI) — Agentic AI Track*