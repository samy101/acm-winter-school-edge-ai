---
title: 'Home'
date: 2025-11-10 # Current date
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # === 1. HERO BLOCK: School Name, Dates, Host (CLEANED) ===
  - block: hero
    id: top
    content:
      title: ACM India Winter School on Edge AI
      text: |
        **28 DECEMBER 2025 to 4 JANUARY 2026**

        **Host:** Indian Institute of Science, Bengaluru
        
        **Venue:** RBCCPS, Indian Institute of Science
        
        **Coordinators:** Pandarasamy Arjunan & Yogesh Simmhan
        
      primary_action:
        text: View Topics
        url: '#topics'
        icon: list-bullet
      secondary_action:
        text: Full Program Details
        url: 'URL_FOR_PROGRAM_DETAILS'
        icon: calendar
    design:
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
        The **ACM India Winter School on Edge AI** will provide an in-depth overview of software platforms, hardware systems, and AI models and algorithms for efficient deployment on accelerated and classic edge devices. The program will cover topics such as edge computing architectures and accelerators, co-optimization techniques of edge systems and ML models for performance, power and accuracy, federated learning frameworks, and the deployment of AI, generative AI/LLM models and AI agents at the edge for practical and IoT applications such as smart mobility and smart agriculture. Through lectures, hands-on sessions, and expert talks, participants will gain practical skills to design, implement, and optimize intelligent edge systems for diverse real-world applications.

    design:
      columns: 1 # FIX: Forces content to use the full width
      spacing:
        padding: ["3rem", 0, "3rem", 0]
        
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

  # === 4. SPEAKERS BLOCK (Enhanced with Photos and URLs) ===
  - block: markdown
    id: speakers
    content:
      title: 🎤 Invited Speakers
      text: |
        <div style="display: flex; flex-wrap: wrap; justify-content: center; text-align: center; max-width: 1000px; margin: 0 auto;">

        <div style="width: 200px; margin: 20px;">
          <a href="URL_TO_PROFILE_1">![Photo of Gayathri Ananthanarayanan](/media/speaker_gayathri.jpg)</a>
          <p><strong>Gayathri Ananthanarayanan</strong><br/>IIT Dharwad</p>
        </div>

        <div style="width: 200px; margin: 20px;">
          <a href="URL_TO_PROFILE_2">![Photo of Manik Gupta](/media/speaker_manik.jpg)</a>
          <p><strong>Manik Gupta</strong><br/>BITS Pilani</p>
        </div>
        
        <div style="width: 200px; margin: 20px;">
          <a href="URL_TO_PROFILE_3">![Photo of Ajay Pratap](/media/speaker_ajay.jpg)</a>
          <p><strong>Ajay Pratap</strong><br/>IIT Bhuvaneswar</p>
        </div>

        <div style="width: 200px; margin: 20px;">
          <a href="URL_TO_PROFILE_4">![Photo of Pandarasamy Arjunan](/media/speaker_pandarasamy.jpg)</a>
          <p><strong>Pandarasamy Arjunan</strong><br/>IISc</p>
        </div>

        <div style="width: 200px; margin: 20px;">
          <a href="URL_TO_PROFILE_5">![Photo of Yogesh Simmhan](/media/speaker_yogesh.jpg)</a>
          <p><strong>Yogesh Simmhan</strong><br/>IISc</p>
        </div>

        <div style="width: 200px; margin: 20px;">
          <a href="URL_TO_PROFILE_6">![Photo of Sumit Mandal](/media/speaker_sumit.jpg)</a>
          <p><strong>Sumit Mandal</strong><br/>IISc</p>
        </div>

        <div style="width: 200px; margin: 20px;">
          <a href="URL_TO_PROFILE_7">![Photo of Punit Rathore](/media/speaker_punit.jpg)</a>
          <p><strong>Punit Rathore</strong><br/>IISc</p>
        </div>
        
        <div style="width: 200px; margin: 20px;">
          <a href="URL_TO_PROFILE_8">![Photo of Prasant Misra](/media/speaker_prasant.jpg)</a>
          <p><strong>Prasant Misra</strong><br/>TCS Research (Tutorial)</p>
        </div>

        <div style="width: 200px; margin: 20px;">
          <a href="URL_TO_PROFILE_9">![Photo of Varun Ojha](/media/speaker_varun.jpg)</a>
          <p><strong>Varun Ojha</strong><br/>New Castle University, UK</p>
        </div>

        <div style="width: 200px; margin: 20px;">
          <a href="URL_TO_PROFILE_10">![Photo of Sajal Das](/media/speaker_sajal.jpg)</a>
          <p><strong>Sajal Das</strong><br/>Missouri Univ. of Sci. & Tech, USA</p>
        </div>
        
        </div>
        
        ---
        
        *Additional speakers being invited from Industries.*
        
    design:
      view: compact
      columns: 1 # Center the container

  # === 5. AGENDA ===
---
