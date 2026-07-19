---
title: "Event 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

{{% notice warning %}}
⚠️ **Note:** The information below is for reference purposes only. Please **do not copy it verbatim** into your report, including this warning.
{{% /notice %}}

# Summary Report: “FCAJ Community Day”

### Event Objectives

- Explore practical applications of AI in software development and enterprise systems
- Learn how context improves AI performance and user experience
- Introduce modern AWS AI services and cloud technologies
- Share real-world experiences in building AI-powered products and systems

### Speakers

- **Bảo Huỳnh** – Docker - A containerization technology
- **Lê Hoàng Gia Đại** – Combining AWS WAF with Machine Learning for Cyber Attack Detection on AWS
- **Nguyễn Quốc Bảo** – Topic: Multiplayer in the Cloud: Connecting Godot Clients with AWS WebSockets
- **Trương Huy Phước** – Topic: Cách làm việc nhóm hiệu quả
- **Việt Phát** – Topic: AWS Neptune for Building a Graph Knowledge Base for GraphRAG
- **Vinh Trần** – Topic: Từ IT Helpdesk lên Senior Sysadmin: Hành trình tự học và Lộ trình dịch chuyển sang Cloud/DevOps

### Key Highlights

#### Docker - A containerization technology
- Emphasized Docker's core value: packaging applications with all their dependencies to ensure they run identically across multiple environments ("build once, run anywhere").
- Highlighted the key differences between Virtual Machines (heavyweight, slow boot, full OS) and Containers (lightweight, fast boot, shared host OS).
- Outlined the significant benefits of containerization, including high portability, operational consistency, resource efficiency, and lower infrastructure costs.

#### Combining AWS WAF with Machine Learning for Cyber Attack Detection on AWS
- Addressed the limitations of traditional rule-based WAFs in detecting novel/zero-day attacks and anomalous behaviors.
- Proposed a Machine Learning-based Network Intrusion Detection System (NIDS) as a proactive defense layer working alongside AWS WAF.
- Detailed the process of building an ML model using the CSE-CIC-IDS2018 dataset, including data cleaning, class balancing, and evaluating models like LightGBM and XGBoost.
- Showcased a system architecture deploying NIDS on AWS, integrated with a real-time dashboard for attack visualization and IP blocking.

#### Topic: Multiplayer in the Cloud: Connecting Godot Clients with AWS WebSockets
- Compared multiplayer networking architectures (UDP, HTTP Polling) and highlighted AWS WebSockets as the optimal choice for real-time, full-duplex communication.
- Demonstrated a scalable AWS architecture utilizing API Gateway for WebSocket connections, Lambda for game logic, and DynamoDB for storing connection states.
- Explained the integration process within the Godot game engine, showcasing how to handle connections, poll packets, and synchronize game states between players in real-time.

#### Topic: Cách làm việc nhóm hiệu quả
- Outlined the "4 Golden Rules" for team success: Clear & Shared Goals, Right Person - Right Place, Open Communication & Active Listening, and Personal Accountability.
- Emphasized the transition from individual "Work Efficiency" to collective "TeamWork Efficiency" to achieve larger project goals.
- Introduced practical digital tools crucial for modern collaboration, including Trello and ClickUp for task tracking, and Slack, Discord, and Google Workspace for seamless communication.

#### Topic: AWS Neptune for Building a Graph Knowledge Base for GraphRAG
- Explained how Retrieval-Augmented Generation (RAG) grounds LLMs with external knowledge, and introduced GraphRAG to overcome limitations in multi-hop reasoning.
- Demonstrated two implementation approaches: a fully managed route using Amazon Bedrock Knowledge Bases and Neptune Analytics, and a custom route using LlamaIndex.
- Highlighted the advantages of using graph databases (Neptune) to explicitly store and traverse complex entity relationships, vastly improving contextual AI responses.

#### Topic: Từ IT Helpdesk lên Senior Sysadmin: Hành trình tự học và Lộ trình dịch chuyển sang Cloud/DevOps
- Shared a practical career progression from IT Helpdesk (troubleshooting, communication) to System Administration (Linux, Networking, Infrastructure).
- Emphasized the "Operations Mindset": automating repetitive tasks, documenting configurations, and the golden rule of "never testing in production."
- Outlined a modern DevOps roadmap, highlighting the crucial shift from on-premise manual configurations to Cloud computing, Infrastructure as Code (Terraform), and CI/CD pipelines.

### Key Takeaways

- **Containerization is the standard:** Docker's lightweight and portable nature makes it essential for modern software deployment, far outpacing traditional virtual machines in efficiency.
- **AI-Enhanced Security is mandatory:** Traditional WAF rules must be supplemented with Machine Learning (NIDS) to proactively detect and mitigate unpredictable cyber threats.
- **Serverless scales gaming:** Combining AWS API Gateway WebSockets with Lambda and DynamoDB provides a robust, scalable backend for real-time multiplayer games without managing dedicated servers.
- **GraphRAG provides deep context:** Using Amazon Neptune to map entity relationships enables LLMs to perform complex, multi-hop reasoning that standard vector-based RAG cannot achieve.
- **Teamwork relies on clarity and tools:** Effective collaboration requires strict adherence to shared goals and personal accountability, supported by agile project management tools like ClickUp and Discord.
- **Continuous learning defines career growth:** Transitioning from Helpdesk to Cloud/DevOps requires hands-on projects, a deep focus on core technologies (Linux, Networking), and a relentless operational mindset.

#### Some event photos
*Add your event photos here*  

> Overall, the "FCAJ Community Day" was an outstanding event that provided deep technical insights across various domains of cloud computing and software development. From the foundational shift toward Docker containerization and modern DevOps practices, to advanced applications of Machine Learning in AWS WAF and GraphRAG architectures, the sessions were highly practical. Learning how to scale real-time game backends with WebSockets and hearing inspiring career progression stories reinforced the idea that success in the IT industry requires a blend of continuous self-learning, effective teamwork, and the adoption of cutting-edge cloud technologies.