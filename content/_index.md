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

# === 4. SPEAKERS BLOCK (Using NATIVE 'people' block for a clean layout) ===
  - block: people
    id: speakers
    content:
      title: 🎤 Invited Speakers
      text: |
        *Additional speakers being invited from Industries.*
      # Ensure speaker images are in `assets/media/` or adjusted path.
      items:
        - name: Gayathri Ananthanarayanan
          role: IIT Dharwad
          url: 'https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan'
          image:
            filename: speaker_gayathri.jpg # Path relative to assets/media/ or the page bundle
            focal_point: Top # Example: try adjusting focal_point if faces are cut
          
        - name: Manik Gupta
          role: BITS Pilani
          url: 'https://www.bits-pilani.ac.in/hyderabad/manik-gupta'
          image:
            filename: speaker_manik.jpg
            focal_point: Top
          
        - name: Ajay Pratap
          role: IIT Bhuvaneswar
          url: 'https://iitbhu.ac.in/dept/cse/people/ajaycse'
          image:
            filename: speaker_ajay.jpg
            focal_point: Top

        - name: Pandarasamy Arjunan
          role: IISc
          url: 'https://www.samy101.com/'
          image:
            filename: speaker_pandarasamy.jpg
            focal_point: Top

        - name: Yogesh Simmhan
          role: IISc
          url: 'https://cds.iisc.ac.in/faculty/simmhan/'
          image:
            filename: speaker_yogesh.jpg
            focal_point: Top

        - name: Sumit Mandal
          role: IISc
          url: 'https://www.csa.iisc.ac.in/~skmandal'
          image:
            filename: speaker_sumit.jpg
            focal_point: Top

        - name: Punit Rathore
          role: IISc
          url: 'https://www.punitrathore.com/home'
          image:
            filename: speaker_punit.jpg
            focal_point: Top
          
        - name: Prasant Misra
          role: TCS Research (Tutorial)
          url: 'https://sites.google.com/site/prasantmisra/'
          image:
            filename: speaker_prasant.jpg
            focal_point: Top

        - name: Varun Ojha
          role: New Castle University, UK
          url: 'https://ojhavk.github.io/'
          image:
            filename: speaker_varun.jpg
            focal_point: Top

        - name: Sajal Das
          role: Missouri Univ. of Sci. & Tech, USA
          url: 'https://isc.mst.edu/people/ri/sdas/'
          image:
            filename: speaker_sajal.jpg
            focal_point: Top
            
    design:
      columns: 3 # Now this will actually work!
      show_role: true
      show_social: false # We don't have social icons yet, so hide them
      css_class: "bg-white dark:bg-dark" # Ensure a white background as in the image

  # === 5. AGENDA (NEW SECTION) ===
  - block: markdown
    id: agenda
    content:
      title: 📅 Agenda
      text: |
        The program will run from **28 DECEMBER 2025 to 4 JANUARY 2026**.

    design:
      columns: 1
      css_class: "bg-gray-100 dark:bg-gray-900"
      background:
          color: white
---
