---
title: 'Home'
date: 2025-11-10 # Current date
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # === 1. HERO BLOCK: Title, Dates, Host ===
  - block: hero
    content:
      title: '<span class="gradient-animate">ACM India Winter School on Edge AI</span>'
      text: |
        <br>
        **28 December 2025 to 4 January 2026**<br><br>
        **Venue:** CDS building, Indian Institute of Science (IISc), Bengaluru<br><br>
        <div style="margin-top: 10px; text-align: center;">
          <img src="iisc-logo-black.png"
               alt="IISc Logo"
               style="max-height: 250px; max-width: 120%; display: inline-block;">
        </div>
        <br>   
    design:
      min_height: "100vh"   # 90% of screen height (increase if needed)    
      spacing:
        padding: ["0", "0", "40px", "60px"]
        margin: ["0", "0", "0", "0"]      
      css_class: "hero-block light"
      background:
        color: "white"
        image:
          filename: bg-iisc4-min.png
          filters:
            brightness: 0.2
          size: cover
          position: top
          parallax: true

    
  # === 2. ABOUT BLOCK: Description, Background, Software (WIDER & JUSTIFIED VIA CUSTOM CSS) ===
  - block: markdown
    id: about
    content:
      title: About the School
      text: |
        <p style="text-align: justify;">
        
        The **<a href="https://india.acm.org/education/acm-india-winter-schools-2025/">ACM India Winter School on Edge AI</a>** will provide an in-depth overview of software platforms, hardware systems, and AI models and algorithms for efficient deployment on accelerated and classic edge devices. The program will cover topics suchs as edge computing architectures and accelerators, co-optimization techniques of edge systems and ML models for performance, power and accuracy, federated learning frameworks, and the deployment of AI, generative AI/LLM models and AI agents at the edge for practical and IoT applications suchs as smart mobility and smart agriculture. Through lectures, hands-on sessions, and expert talks, participants will gain practical skills to design, implement, and optimize intelligent edge systems for diverse real-world applications.
        </p>
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      columns: 1
      spacing:
        padding: ["6rem","0","6rem","0"]

# === 3. TOPICS BLOCK (FINAL FIX: Emojis Embedded in Name Field) ===
  - block: features
    id: topics
    content:
      title: Key Topics
      text: |
        The winter school covers foundational and advanced aspects of Edge AI.
      items:
        - name: "<span style=\"font-size: 2.5rem;\">🛜</span> <br><br>Foundations of IoT, Accelerated Edge Computing and Edge AI"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🔲</span><br><br>Tiny and Embedded Machine Learning"
          icon: ""    
        - name: "<span style=\"font-size: 2.5rem;\">🚀</span> <br><br>Model Optimization and Acceleration for Edge AI"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">⚙️</span> <br><br>Edge AI Platforms, Frameworks, and Deployment Pipelines"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🌐</span> <br><br>Federated Learning and Distributed Training for Edge Devices"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🧠</span> <br><br>Neuromorphic Computing and Brain-Inspired Architectures"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">✨</span> <br><br>Generative AI and LLM at the Edge"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🤖</span> <br><br>Agentic AI on the Edge"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🛡️</span> <br><br>Security, Privacy, and Responsible AI in Edge Systems"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">📊</span> <br><br>Benchmarking, Profiling, and Performance Evaluation of Edge AI Systems"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🚁</span> <br><br>Edge AI for Drones/UAVs, IoT, Smart Cities, and Industrial Applications"
          icon: ""
    design:
      css_class: ""
      columns: 3


# === 4. SPEAKERS BLOCK (4-COLUMN GRID FIX) ===
  - block: features
    id: speakers
    content:
      title: 🎤 Speakers
      text: |
        <br><br>
        ### **Keynote & Invited Speakers**
        
        <div style="display: flex; flex-wrap: wrap; justify-content: center; text-align: center; max-width: 1200px; margin: 0 auto;">
        
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;"> 
          <a href="https://edge.seas.harvard.edu/people/vijay-janapa-reddi">
            <img src="speaker_vijay.jpg" alt="Photo of Vijay Janappa Reddi" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://edge.seas.harvard.edu/people/vijay-janapa-reddi"><strong>Vijay Janappa Reddi</strong></a><br/>Harvard University, USA</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://isc.mst.edu/people/ri/sdas/">
            <img src="speaker_sajal.jpg" alt="Photo of Sajal Das" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://isc.mst.edu/people/ri/sdas/"><strong>Sajal Das</strong></a><br/>Missouri University of Science and Technology, USA</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://ojhavk.github.io/">
            <img src="speaker_varun.jpg" alt="Photo of Varun Ojha" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://ojhavk.github.io/"><strong>Varun Ojha</strong></a><br/>Newcastle University, UK</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://sites.google.com/view/archan-misra">
            <img 
              src="speaker_archan.jpg" 
              alt="Photo of Archan Misra" 
              style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; object-position: top; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://sites.google.com/view/archan-misra"><strong>Archan Misra</strong></a><br/>Singapore Management University</p>
        </div>
        
        </div>

        <br><br>
        ### **Technical Session Speakers**
        
        <div style="display: flex; flex-wrap: wrap; justify-content: center; text-align: center; max-width: 1200px; margin: 0 auto;">
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://iitbhu.ac.in/dept/cse/people/ajaycse">
            <img src="speaker_ajay.jpg" alt="Photo of Ajay Pratap" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; object-position: top; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://iitbhu.ac.in/dept/cse/people/ajaycse"><strong>Ajay Pratap</strong></a><br/>IIT (BHU), Varanasi</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;"> 
          <a href="https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan">
            <img src="speaker_gayathri.jpg" alt="Photo of Gayathri Ananthanarayanan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan"><strong>Gayathri Ananthanarayanan</strong></a><br/>IIT Dharwad</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://www.bits-pilani.ac.in/hyderabad/manik-gupta">
            <img src="speaker_manik.jpg" alt="Photo of Manik Gupta" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://www.bits-pilani.ac.in/hyderabad/manik-gupta"><strong>Manik Gupta</strong></a><br/>BITS Pilani</p>
        </div>
        
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://www.samy101.com/">
            <img 
              src="speaker_pandarasamy.jpg" 
              alt="Photo of Pandarasamy Arjunan" 
              style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; object-position: 50% 30%; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://www.samy101.com/"><strong>Pandarasamy Arjunan</strong></a><br/>IISc</p>
        </div>
        
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://cds.iisc.ac.in/faculty/simmhan/">
            <img src="speaker_yogesh.jpg" alt="Photo of Yogesh Simmhan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://cds.iisc.ac.in/faculty/simmhan/"><strong>Yogesh Simmhan</strong></a><br/>IISc</p>
        </div>

        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://labs.dese.iisc.ac.in/zenlab/people/tv-prabhakar/">
            <img src="Speaker_Prabhakar.png" alt="Photo of Prabhakar" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; object-position: top; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://labs.dese.iisc.ac.in/zenlab/people/tv-prabhakar/"><strong>Dr. TV Prabhakar</strong></a><br/>IISc</p>
        </div>

        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://www.punitrathore.com/home">
            <img src="speaker_punit.jpg" alt="Photo of Punit Rathore" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://www.punitrathore.com/home"><strong>Punit Rathore</strong></a><br/>IISc</p>
        </div> 
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://eecs.iisc.ac.in/people/chetan-singh-thakur/">
            <img src="speaker_chetan.jpg" alt="Photo of Chetan Singh Takur" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://eecs.iisc.ac.in/people/chetan-singh-thakur/"><strong>Chetan Singh Takur</strong></a><br/>IISc</p>
        </div>
        
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://www.csa.iisc.ac.in/~skmandal">
            <img src="speaker_sumit.jpg" alt="Photo of Sumit Kumar Mandal" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; object-position: top; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://www.csa.iisc.ac.in/~skmandal"><strong>Sumit Kumar Mandal</strong></a><br/>IISc</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;"> 
          <a href="https://prakadambi.github.io/">
            <img src="speaker_prashanti.jpeg" alt="Photo of Prashanti" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://prakadambi.github.io/"><strong>Prashanti</strong></a><br/>AMD</p>
        </div>
        
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://sites.google.com/site/prasantmisra/">
            <img src="speaker_prasant.jpg" alt="Photo of Prasant Misra" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; object-position: top; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://sites.google.com/site/prasantmisra/"><strong>Prasant Misra</strong></a><br/>TCS Research</p>
        </div>
  
        </div>
        
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      view: compact
      columns: 1 # Set to 1 because the columns are defined by inline HTML width

# === 5. PROGRAMS (NEW SECTION) ===
  - block: features
    id: program
    content:
      title: 📅 Program
      text: |
        <br><br>
        <h3><strong>⏰ School Timing</strong></h3>
        <p style="text-align: left; font-size: 1.1em; line-height: 1.6;">
          The usual school timing is <strong>8:00 AM to 8:00 PM</strong> on all days.
          Breakfast (8:00–9:00 AM), tea/coffee/snacks (morning and evening),
          lunch (12:45–2:00 PM), and dinner (7:00–8:00 PM) will be provided daily
          to all attendees.
          <em>Participants are expected to arrive at the venue on time each morning.</em>
        </p>
        <br>
        <h3><strong>📚 Session Legend</strong></h3>
        <div style="max-width: 650px; margin: 0 auto; padding: 15px 0;">
        <ul style="list-style-type: none; padding-left: 0; text-align: left;">          
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#CCF4B1; padding:4px 10px; border-radius:4px; margin-right:4px;">🎉 Opening/Closing</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#F7E8FF; padding:4px 10px; border-radius:4px; margin-right:4px;">🎤 Keynote / Invited Talk</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#E8F1FF; padding:4px 10px; border-radius:4px; margin-right:4px;">👨‍🏫 Lecture / Technical Talk</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#FFF3E8; padding:4px 10px; border-radius:4px; margin-right:4px;">🧪 Lab / Tutorial</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#F7EFA4; padding:4px 10px; border-radius:4px; margin-right:4px;">🏢 Industry</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#C8ECEC; padding:4px 10px; border-radius:4px; margin-right:4px;">🗺️ Tour</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#E6F5E6; padding:4px 10px; border-radius:4px; margin-right:4px;">💻 Hackathon</span></li>          
          <li style="display: inline-block; margin: 5px 8px;"><span style="padding:4px 10px;">† Online Talk</span></li>
        </ul>
        </div>
  
        ---    
        
        <br><br>      
        <h3><strong>Day 1 – Sunday, 28th Dec 2025 - Hardware Systems</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#CCF4B1;"><td style="padding:8px;">8:45 – 9:00 AM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc) and Yogesh Simmhan (IISc) </td><td style="padding:8px;">Welcome Address</td></tr>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Vijay Janappa Reddi (Harvard University)<sup>†</sup></td><td style="padding:8px;">Edge AI: Opportunities and Challenges</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Dr. TV Prabhakar (IISc)</td><td style="padding:8px;">In-Network Edge Intelligence for Tactile CPS</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Dr. TV Prabhakar (IISc)</td><td style="padding:8px;">In-Network Edge Intelligence for Tactile CPS</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Tiny ML</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Tiny ML</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Tiny ML</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 2 – Monday, 29th Dec 2025 - Hardware Systems</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <!-- tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Sumit Kumar Mandal (IISc)</td><td style="padding:8px;">Technical Session</td></tr -->
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Gayathri Ananthanarayanan (IIT Dharwad)</td><td style="padding:8px;">Hardware Systems</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Gayathri Ananthanarayanan (IIT Dharwad)</td><td style="padding:8px;">Hardware Systems</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Embedded Computer Vision</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Embedded Computer Vision</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Embedded Computer Vision</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 3 – Tuesday, 30th Dec 2025 - Edge AI Platforms</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">ML Software Platforms</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">ML Software Platforms</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Prashanti (AMD)</td><td style="padding:8px;">ML Software Platforms</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">ML on Edge Accelerators</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">ML on Edge Accelerators</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">ML on Edge Accelerators</td></tr>
        </tbody></table>
        <br><br>   
        <h3><strong>Day 4 – Wednesday, 31st Dec 2025 - Federated Learning</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">Federated Learning</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">Federated Learning</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">FL on Edge</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch</td></tr>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Varun Ojha (Newcastle University)<sup>†</sup></td><td style="padding:8px;">Federated learning</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Varun Ojha (Newcastle University)<sup>†</sup></td><td style="padding:8px;">Federated learning</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">FL on Edge</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 5 – Thursday, 1st Jan 2026 - Gen AI and Edge AI for mobility</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Sumit Kumar Mandal (IISc)</td><td style="padding:8px;">LLM Algorithms</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Sumit Kumar Mandal (IISc)</td><td style="padding:8px;">LLMs at Edge</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Prasant Misra (IISc & TCS)</td><td style="padding:8px;">Edge AI in Mobility</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Punit Rathore (IISc)</td><td style="padding:8px;">Edge AI in Mobility</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Gen AI at Edge</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Gen AI at Edge</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 6 – Friday, 2nd Jan 2026 - Edge Analytics</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>        
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Manik Gupta (BITS, Pilani)</td><td style="padding:8px;">IoT Analytics</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Manik Gupta (BITS, Pilani)</td><td style="padding:8px;">IoT Analytics</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Manik Gupta (BITS, Pilani)</td><td style="padding:8px;">IoT Analytics</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#F7EFA4;"><td style="padding:8px;">4:00 – 5:30 PM</td><td colspan="2" style="padding:8px; text-align:center;">MATLAB for Edge AI</td></tr>
        <tr style="background-color:#C8ECEC;"><td style="padding:8px;">5:30 – 6:30 PM</td><td colspan="2" style="padding:8px; text-align:center;">RBCCPS Tour</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 7 – Saturday, 3rd Jan 2026 - Edge AI in agriculture</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Archan Misra (SMU)</td><td style="padding:8px;">Edge AI for Urban Systems</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Ajay Pratap (IIT (BHU), Varanasi)</td><td style="padding:8px;">UAV and Edge AI in Agriculture</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Ajay Pratap (IIT (BHU), Varanasi)</td><td style="padding:8px;">UAV and Edge AI in Agriculture</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch</td></tr>
        <tr style="background-color:#F7EFA4;"><td style="padding:8px;">2:00 – 3:30 PM</td><td colspan="2" style="padding:8px; text-align:center;">Arm for Edge AI</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">4:00 – 5:30 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon</td></tr>
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">5:30 – 7:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon</td></tr>
        </tbody></table>
        <br><br>      
        <h3><strong>Day 8 – Sunday, 4th Jan 2026 - Hackathon</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Sajal Das (Missouri University of Science and Technology, USA)</td><td style="padding:8px;">Edge AI in Agriculture</td></tr>
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">10:00 – 12:45 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon</td></tr>      
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch</td></tr>      
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">2:00 – 3:30 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon Demo/Presentation</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee/Snacks</td></tr>
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">4:00 – 5:30 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon Demo/Presentation</td></tr>
        <tr style="background-color:#CCF4B1;"><td style="padding:8px;">5:30 – 6:30 PM</td><td colspan="2" style="padding:8px; text-align:center;">Certificate Distribution and Closing Ceremony</td></tr>
        </tbody></table>
        <br><br>      

    design:
      columns: 1
      css_class: ""
      background:
        color: white
      spacing:
        padding: ["6rem","0","6rem","0"]

# === 6. LOGISTICS AND MAPS (NEW SECTION) ===
  - block: markdown
    id: venue
    content:
      title: 📍 Venue & Logistics
      text: |
        This program is hosted at the **CDS building, Indian Institute of Science (IISc), Bengaluru**.
        
        ---
        
        ### 🧭 Location and Access (IISc Campus)
        
        The IISc campus is easily accessible from all parts of Bengaluru. The nearest metro station is **Yeshwanthpur**.
        
        * **Getting to IISc:** <a href="https://iisc.ac.in/about/general-information/how-to-reach-iisc/"> Click here for detailed travel information.</a>
        
        #### CDS Building Venue Map
        
        <div style="width: 100%; height: 400px; margin-top: 20px; margin-bottom: 20px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
          <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3887.3023152873743!2d77.56789517592448!3d13.016410313892576!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bae1786c19d1f6d%3A0xba84d2e59b2425a2!2sComputational%20and%20Data%20Science%20Department%20(CDS)!5e0!3m2!1sen!2sin!4v1765886420757!5m2!1sen!2sin" 
            width="100%" 
            height="100%" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy" 
            referrerpolicy="no-referrer-when-downgrade">
          </iframe>
        </div>
        
        ---
        
        ### 🏨 Accommodation Details
        
        Accommodation has been arranged for participants at the following locations.
        
        #### Girls' Accommodation: Hoysala Guest House (IISc)
        
        <div style="width: 100%; height: 400px; margin-top: 20px; margin-bottom: 20px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
          <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3887.133303205331!2d77.56789017592463!3d13.027182013655528!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bae17db9ce985b9%3A0xc21a2bb90740ff4d!2sCentenary%20Visitors%20House%20IISc!5e0!3m2!1sen!2sin!4v1765886124154!5m2!1sen!2sin" 
            width="100%" 
            height="100%" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy" 
            referrerpolicy="no-referrer-when-downgrade">
          </iframe>
        </div>
        
        #### Boys' Accommodation: Sri Durga Hotel
  
        * **Address:** 35/1, Gayathri Temple Rd, Dr.Ambedkar Nagar, Yeshawanthapura, Bengaluru, Karnataka 560022.
        * **Phone Number:** 09019158456
        
        <div style="width: 100%; height: 400px; margin-top: 20px; margin-bottom: 20px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
          <iframe 
            src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d485.90791870600185!2d77.5566539!3d13.0188945!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bae3ddd540daad7%3A0x184f0f4c5916e6a8!2sSri%20Durga%20International!5e0!3m2!1sen!2sin!4v1765886292885!5m2!1sen!2sin" 
            width="100%" 
            height="100%" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy" 
            referrerpolicy="no-referrer-when-downgrade">
          </iframe>
        </div>
            
    design:
      columns: 1
      css_class: "bg-gray-100 dark:bg-gray-900"
      background:
        color: white
      spacing:
        padding: ["6rem","0","6rem","0"]

# === 7. Contact Us ===
  - block: markdown
    id: contacts
    content:
      title:
      text: |
        ## <i class="fas fa-envelope"></i> Contact Us
        If you have any **logistical or academic questions** regarding the Winter School, please reach out to the program coordinators below.
  
        1. <a href="https://www.samy101.com/"><strong>Pandarasamy Arjunan (IISc)</strong></a>
            * **Email:** [samy@iisc.ac.in](mailto:samy@iisc.ac.in)
  
        2. <a href="https://cds.iisc.ac.in/faculty/simmhan/"><strong>Yogesh Simmhan (IISc)</strong></a>
            * **Email:** [simmhan@iisc.ac.in](mailto:simmhan@iisc.ac.in)
  
    design:
      columns: 1
      css_class: ""
      background:
        color: white
      spacing:
        padding: ["6rem","0","6rem","0"]
      

  # === 8. SPONSORS / SUPPORTED BY (NEW SECTION WITH LOGOS) ===
  - block: markdown
    id: sponsors
    content:
      title: Sponsored By
      text: |
        <div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 30px; margin-top: 30px;">
        
          <a href="https://india.acm.org/" target="_blank">
            <img src="acm-logo.png" alt="ACM India Council" style="max-height: 100px; width: auto;">
          </a>

          <a href="https://artpark.in/" target="_blank">
            <img src="ARTPARK-logo.png" alt="ARTPARK" style="max-height: 100px; width: auto;">
          </a>

          <a href="https://rbccps.org/" target="_blank">
            <img src="rbccps-logo.png" alt="RBCCPS" style="max-height: 100px; width: auto;">
          </a>
          
          <a href="https://cds.iisc.ac.in/" target="_blank">
            <img src="cds_logo.png" alt="CDS" style="max-height: 100px; width: auto;">
          </a>

        </div>
        
    design:
      columns: 1
      css_class: "bg-gray-100 dark:bg-gray-900"
      background:
        color: white
      spacing:
        padding: ["3rem","0","3rem","0"]
---
