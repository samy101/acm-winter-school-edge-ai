---
title: 'Home'
date: 2025-11-10 # Current date
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # === 1. HERO BLOCK: Title, Dates, Host (FIXED TITLE & SPACING) ===
  - block: hero
    id: top
    content:
      title: ACM India Winter School on Edge AI
      text: |
        **28 DECEMBER 2025 to 4 JANUARY 2026**<br><br>

        **Host:** RBCCPS, Indian Institute of Science, Bengaluru<br><br>

        **Venue:** IDR Building, Indian Institute of Science<br><br>

        **Coordinators:** Pandarasamy Arjunan & Yogesh Simmhan
        
      primary_action:
        text: View Topics
        url: '#topics'
        icon: list-bullet
      secondary_action:
        text: Agenda
        url: '#agenda'
        icon: calendar
    design:
      columns: 1
      css_class: "dark"
      background:
        color: "navy"
        image:
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false

# === 2. ABOUT BLOCK: Description, Background, Software (FIXED ALIGNMENT) ===
  - block: markdown
    id: about
    content:
      title: About the School
      text: |
        <div style="text-align: left;">
        The **ACM India Winter School on Edge AI** will provide an in-depth overview of software platforms, hardware systems, and AI models and algorithms for efficient deployment on accelerated and classic edge devices. The program will cover topics suchs as edge computing architectures and accelerators, co-optimization techniques of edge systems and ML models for performance, power and accuracy, federated learning frameworks, and the deployment of AI, generative AI/LLM models and AI agents at the edge for practical and IoT applications such as smart mobility and smart agriculture. Through lectures, hands-on sessions, and expert talks, participants will gain practical skills to design, implement, and optimize intelligent edge systems for diverse real-world applications.
        
        ### Recommended Background / Prior Courses
        * Introductory course on Data science, Machine learning, or AI
        * Basics of Computer Systems
        * Embedded systems and IoT programming
        
        ### Specific Software to be Used
        * **Python 3** (scikit-learn, TensorFlow, Keras, LiteRT, PyTorch Edge, ExecuTorch)
        * **Jetpack SDK**
        * **MicroPython**
        </div>
        
    design:
      columns: 1
      # Aggressive override classes to maximize width and force left alignment
      css_class: "container-fluid text-left mx-auto max-w-full" 
      spacing:
        # Reduced padding slightly since the class will handle the width
        padding: ["3rem", "3rem", "3rem", "3rem"]

  # === 3. TOPICS BLOCK (Visually interactive with icons) ===
  - block: features
    id: topics
    content:
      title: Key Topics
      text: |
        The winter school covers foundational and advanced aspects of Edge AI.
      items:
        - name: Foundations of IoT, Accelerated Edge Computing and Edge AI
          icon: server
        - name: Tiny and Embedded Machine Learning
          icon: computer-desktop
        - name: Model Optimization and Acceleration for Edge AI
          icon: arrow-up-circle
        - name: Edge AI Platforms, Frameworks, and Deployment Pipelines
          icon: code-bracket
        - name: Federated Learning and Distributed Training for Edge Devices
          icon: users
        - name: Neuromorphic Computing and Brain-Inspired Architectures
          icon: cube
        - name: Generative AI and LLM at the Edge
          icon: sparkles
          
        # Note: I removed some items here to prevent line 45 error if it was related to items:
        # Re-adding them now, but keeping the syntax clean

        - name: Agentic AI on the Edge
          icon: cog
        - name: Security, Privacy, and Responsible AI in Edge Systems
          icon: lock-closed
        - name: Benchmarking, Profiling, and Performance Evaluation of Edge AI Systems
          icon: chart-bar
        - name: Edge AI for Drones/UAVs, IoT, Smart Cities, and Industrial Applications
          icon: globe-alt
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      columns: 3

# === 4. SPEAKERS BLOCK (RELIABLE MARKDOWN LIST) ===
  - block: markdown
    id: speakers
    content:
      title: 🎤 Invited Speakers
      text: |
        
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
        
        <div style="width: 48%;">
        
        ### Group 1
        
        **[Gayathri Ananthanarayanan](https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan)** (IIT Dharwad)
        
        ![Photo of Manik Gupta](speaker_manik.jpg)
        **[Manik Gupta](https://www.bits-pilani.ac.in/hyderabad/manik-gupta)** (BITS Pilani)
        
        ![Photo of Ajay Pratap](speaker_ajay.jpg)
        **[Ajay Pratap](https://iitbhu.ac.in/dept/cse/people/ajaycse)** (IIT Bhuvaneswar)
        
        ![Photo of Pandarasamy Arjunan](speaker_pandarasamy.jpg)
        **[Pandarasamy Arjunan](https://www.samy101.com/)** (IISc)
        
        ![Photo of Yogesh Simmhan](speaker_yogesh.jpg)
        **[Yogesh Simmhan](https://cds.iisc.ac.in/faculty/simmhan/)** (IISc)
        
        </div>
        
        <div style="width: 48%;">
        
        ### Group 2
        
        ![Photo of Sumit Mandal](speaker_sumit.jpg)
        **[Sumit Mandal](https://www.csa.iisc.ac.in/~skmandal)** (IISc)
        
        ![Photo of Punit Rathore](speaker_punit.jpg)
        **[Punit Rathore](https://www.punitrathore.com/home)** (IISc)
        
        ![Photo of Prasant Misra](speaker_prasant.jpg)
        **[Prasant Misra](https://sites.google.com/site/prasantmisra/)** (TCS Research - Tutorial)
        
        ![Photo of Varun Ojha](speaker_varun.jpg)
        **[Varun Ojha](https://ojhavk.github.io/)** (New Castle University, UK)
        
        ![Photo of Sajal Das](speaker_sajal.jpg)
        **[Sajal Das](https://isc.mst.edu/people/ri/sdas/)** (Missouri Univ. of Sci. & Tech, USA)
        
        </div>
        
        </div>
        
        ---
        
        *Additional speakers being invited from Industries.*
        
    design:
      columns: 1

  # === 5. AGENDA (NEW SECTION) ===
  - block: markdown
    id: agenda
    content:
      title: 📅 Agenda
      text: |
        The program will run from **28 DECEMBER 2025 to 4 JANUARY 2026**.

        | Date | Time | Topic/Event | Speaker |
        | :--- | :--- | :--- | :--- |
        | Day 1 (Dec 28) | 9:00 - 10:30 | Inauguration & Keynote | Coordinator Team |
        | Day 1 (Dec 28) | 10:45 - 12:30 | Foundations of Edge AI | Speaker 1 |
        | Day 8 (Jan 4) | 14:00 - 16:00 | Hands-on Lab: LLMs on Edge | Team TBD |
        | Day 8 (Jan 4) | 16:00 - 17:00 | Closing Ceremony | Coordinator Team |

        *Note: This is a placeholder agenda. The full detailed agenda will be updated soon.*

    design:
      columns: 1
      css_class: "bg-gray-100 dark:bg-gray-900"
      background:
          color: white
---
