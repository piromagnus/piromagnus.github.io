---
layout: default # This assumes your theme or _layouts/ folder has a 'default.html'
title: Home
---

<div style="display: flex; align-items: flex-start;">
  <div style="flex: 3; padding-right: 20px;">
    <h1>Pierre Marrec</h1>
    <p>PhD Student in Computer Vision</p>
    <p>INRIA & Université Grenoble Alpes | Grenoble, France</p>
    <p>
      <a href="mailto:{{ site.email }}">[Email]</a> | 
      <a href="https://github.com/{{ site.github_username }}" target="_blank">[GitHub]</a> | 
      <a href="https://www.linkedin.com/in/{{ site.linkedin_profile }}" target="_blank">[LinkedIn]</a> |
      <!-- <a href="https://scholar.google.com/citations?user={{ site.google_scholar_id }}" target="_blank">[Google Scholar]</a> | -->
      <a href="{{ site.header_pages | where: 'name', 'Pierre_Marrec_CV_Placeholder.pdf' | first.path | default: 'assets/pdf/Pierre_Marrec_CV_Placeholder.pdf' }}" target="_blank">[CV]</a>
    </p>
  </div>
  <div style="flex: 1;">
    <img src="assets/img/placeholder_profile.png" alt="Pierre Marrec" style="width: 180px; border-radius: 10%; margin-top: 10px;"/>
    <!-- 
      To add your image:
      1. Create 'assets/img/' folders in your repository.
      2. Put your image (e.g., 'pierre_marrec_photo.jpg') in 'assets/img/'.
      3. Change 'placeholder_profile.png' to 'your_image_filename.jpg'.
    -->
  </div>
</div>

## About Me (Draft)

Welcome! I am a PhD student at INRIA Grenoble, affiliated with the Laboratoire Jean Kuntzmann (LJK) at the Université Grenoble Alpes. My doctoral research, beginning October 2024, delves into the fascinating intersection of **Computer Vision and high-level sports analysis**. I am driven by the challenge of enabling machines to perceive and understand complex human motion from diverse sensory inputs. My core interest lies in developing robust 3D human pose estimation and motion analysis techniques, particularly leveraging multi-view camera systems and multimodal data fusion. I aim to contribute to tools that can offer profound insights into athletic performance, injury prevention, and training optimization.

Before embarking on my PhD, I gained valuable research experience through internships at institutions like INSEP (Paris), the National Institute of Informatics (Tokyo), and PERFANALYTICS (Grenoble). These experiences solidified my passion for applying cutting-edge deep learning models, including large vision models and neural rendering techniques, to real-world challenges in human-centric AI.

## Research Interests (Draft Statement)

My primary research interest is **3D Computer Vision for Human Understanding**, with a strong emphasis on:
*   **Robust 3D Human Pose and Shape Estimation:** From multi-view videos and other sensor modalities.
*   **Multimodal Data Fusion:** Integrating visual information with data from sources like IMUs for comprehensive motion capture.
*   **Dynamic Scene Understanding:** Including tracking, action recognition, and forecasting in complex human-centric scenarios like sports.
*   **Large Vision Models & Generative AI:** Exploring their application to synthesize, analyze, and predict human motion and appearance.
*   **Applications in Sports Science:** Developing tools for performance analysis, biomechanical studies, and tactical insights.

I am excited by the potential of these technologies to revolutionize how we analyze and interact with human movement.

## News
*   **Jan 2025 - Apr 2025:** Teaching Assistant at Université Grenoble Alpes (Systems & Networks, Computer Architecture).
*   **Oct 2024:** Starting PhD in Computer Vision at INRIA / LJK, Grenoble.
*   **Apr 2024 - July 2024:** Research Internship at INSEP, Paris (Deep Learning for athlete training analysis).
*   **2023-2024:** Research Internship at National Institute of Informatics, Tokyo (Animatable Neural Human Bodies).
*   **May 2023:** Presented work at the 18th International Symposium on Computer Methods in Biomechanics and Biomedical Engineering (CMBBE), Paris.
* 

<!--
 *   *To add more news: copy the format above and list chronologically.*
  To update your CV link:
  1. Create 'assets/pdf/' folders.
  2. Place your CV (e.g., 'Pierre_Marrec_CV_2025.pdf') in 'assets/pdf/'.
  3. Update the link in _config.yml and any direct links like the one in the contact info above.
-->