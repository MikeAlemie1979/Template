**General Unified Architecture Guidelines  
**

Ask for the Repo path to start.

  
**Section 1:**

SDLC model: Modular Agile Iterative (MAI)  
Development Approach: Modular, Incremental.

**Governance Rules (Highly Important):**

*   **No architectural or UIUX modification without approval.**
*   **Do not invent workflows or new design.**
*   **Prevent architectural, functional, and implementation drift.**

Default Application Layers:  
1- UIUX  
2- Frontend  
3- Security & Compliance  
4- Authentication, if needed.  
5- Ai Orchestration if needed.  
6- Agents , if needed.  
7- Cloud Services, if needed  
8- Third Party tools and API connection, if needed.  
9- DataBase, If needed.  
10- Storage and Warehouse, if needed  

Development Mode:

1) AI Dev Modes:

Ask to choose one of the following:

“Mode 1 — Single AI Development”

Either Claude Code or OpenAI Codex completes the full project independently.

“Mode 2 — Collaborative AI Development”

Claude Code and OpenAI Codex work collabratively and saving their progress log in  
**“\\Development\\Implementation\\Roadmap.md”.**

AI Responsibilities If Mode 2 is Selected:

Claude Code is for

*   Architecture
*   Planning
*   Project management
*   Test & Verification
*   Quality review
*   Integration
*   CI/CD
*   Architecture governance

OpenAI Codex is for

*   Software implementation
*   Code generation
*   UI/UX implementation
*   Asset generation
*   Coding assistance

Ask if the App Layer is approved?  

**Tools collection:**

select from below by showing all in a checkbox:

  
FrontEnd: C#.net / ASP.net / Javascript / HTM / CSS/ Flutter Dart (for mobile).  
Security: DDOS and MMAT guard.  
Authentication: RBAC / EntraID / Active Directory Domain User / Local User / Login Pass / Oath  
AI Platform and Orchestration: OpenAI Codex / Claude Code.  
Database: Ms.SQL Server 2019+/ Azure SQL Server / CosmosDB / Redis / Google Sheet / Ms. Ecxel 2019+.  
Storage: Google Drive / Azure Blob Storage / Local Disk.  
DevOps and CICD: Github / Azure Devops  
Final Environment: Azure Cloud, Internet Web Host Provider, On-Prem Windows.  
Payment Processing: Stripe / Square / Both ready to configure.  
Location and Mapping: TomTom / Google Map.  
Phone, Messaging,Telegram,Whatsapp: Twilio, Plivo.  
Email and Meetings: Ms 365 / Email Service on the Internet host / Google/ Yahoo / Hotmail or combination.  
  
\*Avoide containers and kubernetes initially.  
\*Try to use any needed Skills/MCPs/Plugins/extensions available on the dev application like VS Code.  
\*If On-Prem Windows is selected then an installable setup wizard package “Setup.Exe” is needed. Ask for more details.

**Ask for the tools and layers to come up with the layered architecture:**

1.  Info Collection:  
    What would be the final host?  
    Estimated Transactions Per Minute (TPM)?  
    Estimated concurrent users?  
    Could consider Container and Kubernetes?  
    Whats the DB/s Name?  
    
2.  General App story:

Read on “\\Instructions\\Epic\\AppStory.md” .

**Analyze for architectural blueprint.**

**/optimize the analysis.**  
Generate two mermaid flowchart images and save into “\\Development\\Implementation\\”  
\- Arch App Layers and Tools in SysArch.jpeg .  
\- Activity Diagram image ActivityDG.jpeg .

Save all architectural guidance in Roadmap.md as well and update project Claude.md file as well.

/compact  
/context

**Section 2:**  
UI/UX and Coding Workflow:

Follow the UI/UX/Code design from “\\Instructions\\Gen UI\\UIUX.md”.  
After The UIUX finished completely create the Database DDL code in : \\Development\\Implementation\\<dbname>.sql  
  
Tips:

*   Always consider the Roadmap.md to find which phase is done to pursue the rest.
*   Use \\Compressed\\Implementation as a temp folder or the folder to save the progress.
*   Final deployable code files will be saved in: “\\Compressed\\Codes\\”.