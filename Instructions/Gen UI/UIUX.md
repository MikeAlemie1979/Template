**UI/UX & Code Design Workflow  
  
General Instruction:  
The design will be in 2 layers. A general layer design and a Specific page or elements within each page design.  
Initially follow the general design, then fall into the specific design. So, each design has 2 styles:**

**1- General style in “\\Sprints\\Website\\<gen-style>.md”  
2- Page style in “\\Sprints\\Pages\\<page>\\<page-style>.md”**

**\* CSS Style Hierarchy:** General Design Style 🡪 Specific Page Design

**Use Designmd.ai or Stitch.withgoogle.com for professional UI designer settings suggestions.  
**

**\* Use subagents to divide the execution tasks.  
**

**Gen Style:**

*   Minimum font size all over everything: 11px.
*   Font Families: Arial, Saira, Michroma, Audiowide, Orbitron, Syncopated.
*   Font Colors: White, Yellow, Light Blue, Green, Red.
*   Default Backgrounds: #000000 , #525252 , #B3BD11, #4B5C04, #0CA9AD, #3014A1 , #581270, #4A0F10, #F7F7F0, #E5DFF7, #F7EAF7.
*   Website Logo: “\\Sprints\\Website\\Logo.png”

**  
Design Collection:  
UI Direction**

Ask if this design is for a desktop web application, mobile application, or both?

\- If a mobile app **and** a desktop web app is needed, then ask if the mobile app should follow all the above instructions or be a lighter version?  
\* should be compatible with any mobile size dynamically.  
\* Use Flutter.

1.  **Design Model:  
    Ask all the below items** in a checkbox for identifying the design style:

*   Editorial
*   brutalist
*   Overlayered
*   Grid-Based
*   Retro-futuristic
*   Luxury
*   Playful Material
*   Parallax Scrolling
*   Cinematic
*   Digital Maximalist
*   Digital Minimalist
*   Static
*   Rhythmic and Motional
*   Advanced 3D
*   Hybrid (combination of two or more styles)

**If** Cinematic Design Style is selected:

* Ask for only 2 high-quality reference images as first and last frames.  
    Use Google Flow or Higssfield AI to generate clip frames to use on the website background.

**2\. Reference Collection**  
Website subject and vibe for design?  
If there is a specific sample design to mimic?  
Any Images, Icons, Charts, KPIs to mimic?  
Navigation bar and design?  
Typography?  
Spacing, padding and borders?  
Colors and Template?  
Motion effects?  
Image/Background appearance (1-Smooth integration / 2-Overlayered / 3-Fade in / 4-Fade Out / 5-Flashes / 6-Scale in-out / 7-Boom and wave / 8-Looped / 9- Random motion / 10- Integrated)?  
If social media links and connections are needed?  
if each user profile selects a customized template?  

/compact  

**3\. Design Generation**  
Ask for design skills to use, like /ui-ux-pro-max.  
Ask for an image and video creator app? Claude Design, Leonardo.AI , Google Flow, Higgsfield AI, Figma, Canva

**4\. Required ChatBot**

Ask if it's needed?  
Chatbot icon image?  
Chatbot location? (Top right or left / Bottom left or right / Floating but defaulted at bottom right.)  
Chatbot name?  
Can Chatbot disappear by X button and reappear with “C”+”B” buttons?

**5\. Interactive Design**

Shall enhance usability, visibility, friendliness plus performance.

/compact  

**To demo the prototype, use: localhost port: 8089.  
If localhost is unavailable, use the static page to load on Google Chrome.**  
Log in:  
Admin Username: Admin / Password: App@dmin0123  
Customer Username: Cust / Password: Cust@mer01

**\* Test and verify each creation before any saving.**

**\* Save or update the last approved progress in: “\\Development\\Implementation\\Roadmap.md” and Claude.md after I enter “Save Point”.**

**\* Save or update each page specific approved design in: “\\Development\\Implementation\\<page>\_design.md” after I enter “Save Page”.**

**\* For any other files use: “\\Development\\Implementation\\”.  
  
Make sure Graphyfi has been installed. Then after each Save Page:  
IF project has just started, then run: “/graphify .” to create graphify-out folder and files in “\\Development\\Implementation\\”.**

**Else run “/graphify ./docs –update” ,or “/graphify update ./src”**