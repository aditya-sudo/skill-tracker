# **Interactive Skill Navigator & Preparation Tracker**

This repository contains the source code for a two-part web application designed to help recent Computer Science graduates strategically prepare for technical job roles. The application provides tools to both explore required skills and track learning progress.

The live application can be accessed here: \[Link to your Vercel deployment\]

## **Features**

This project consists of two main pages:

### **1\. Interactive Skill Navigator (index.html)**

This is the main landing page of the application. It allows users to:

* **Select Target Roles:** Choose from a list of modern tech roles (e.g., Software Engineer, AI Engineer, LLM Developer).  
* **Visualize Skill Priorities:** Dynamically generates a Polar Area chart that provides a high-level visual summary of the most critical skill domains for the selected roles.  
* **Explore Curated Skills:** Presents a detailed, prioritized list of essential skills, tools, and concepts based on the user's selection.

### **2\. Job Skill Preparation Tracker (tracker.html)**

This page is a personal dashboard for tracking learning progress. It features:

* **Detailed Skill Checklists:** A comprehensive, categorized list of all the skills mentioned in the navigator.  
* **Progress Tracking:** Users can mark each skill as "Not Started," "In Progress," or "Completed."  
* **Automated Progress Bars:** Visual bars show completion percentage for each category and for overall progress.  
* **Analytics Timeline:** A line graph visualizes the number of skills completed over time, helping users see their learning momentum.  
* **Local Storage:** All progress data is saved automatically in the user's browser via localStorage.

## **Tech Stack**

This is a lightweight, front-end-only project built with standard web technologies. No backend or build process is required.

* **HTML5**  
* **Tailwind CSS:** For all styling and layout.  
* **Vanilla JavaScript (ES6+):** For all interactivity, state management, and DOM manipulation.  
* **Chart.js:** For creating the dynamic and responsive charts (Polar Area and Line Chart).  
* **date-fns (via chartjs-adapter):** For handling the time scale on the progress timeline graph.

## **File Structure**

The repository has a simple and flat structure:

/  
├── index.html      \# The main landing page (Interactive Skill Navigator)  
├── tracker.html    \# The progress tracking dashboard page  
└── README.md       \# This file

## **How to Deploy**

This project is optimized for easy deployment on static hosting platforms like Vercel, Netlify, or GitHub Pages.

1. Fork this repository or create your own and upload the files.  
2. Connect your GitHub repository to a Vercel project.  
3. Vercel will automatically detect the static files and deploy them. No special build configuration is needed.
