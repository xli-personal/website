---
title: Home
layout: page
---

<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Lobster&display=swap">

<!-- ![Profile Image]({% if site.external-image %}{{ site.picture }}{% else %}{{ site.url }}/{{ site.picture }}{% endif %}) -->

<p>
Hi! My name is Xiao. I'm a CS PhD student at Princeton University working on computational imaging research. I'm interested in developing novel optical systems by combining hardware design with computation or simulation. Before coming to Princeton, I worked at Magic Leap and contributed to the <a href="https://www.magicleap.com/optics-technology" target="_blank"><u>display optics/waveguide design</u></a> and the <a href="https://developer-docs.magicleap.cloud/docs/guides/features/headpose/" target="_blank"><u>SLAM-based head tracking system</u></a> of AR headsets. I also conducted research in Terahertz photonics at UCLA advised by 
<a href="https://samueli.ucla.edu/people/mona-jarrahi/" target="_blank"><u>Prof. Mona Jarrahi</u></a>.
</p>

<hr class="grey-bar">
<h2 style="margin-top: 30px;">Publications</h2>
<p style="font-family: 'Helvetica', 'Arial', sans-serif; font-size: 14px; line-height: 1.4;margin-top: -10px;">
“*” stands for equal contribution.
</p>

<p style="font-family: 'Helvetica', 'Arial', sans-serif; font-size: 17px; line-height: 1.4;">
  <a href="https://arxiv.org/abs/2308.03407" style="color: #ff6347; text-decoration: underline;">
    Spatially varying nanophotonic neural networks
  </a><br>
<span class="name-list">
  <span class="highlight-name">Kaixuan Wei&nbsp;</span>,
  <span class="highlight-name" style="text-decoration: underline;">Xiao Li&nbsp;</span>,
  <span class="highlight-name">Johannes Froech&nbsp;</span>,
  Praneeth Chakravarthula, 
  James Whitehead, 
  Ethan Tseng, 
  Arka Majumdar, 
  Felix Heide
</span><br>

  <span style="color: #000000; font-size: 14px;">📚 Accepted by Science Advances, Preprint arXiv:2308.03407</span><br>
  <ul style="color: #000000; font-size: 14px; margin-top: -10px; padding-left: 20px;">
    <li><u style="color: blue;">Summary:</u> Demonstrated a metalens array camera that performs large-kernel spatially-varying neural network convolution during the image capture. Combined with a lightweight electronic backend with ~ 2K parameters, this neural network reaches 72.76% blind test classification accuracy on CIFAR-10 dataset and outperforms AlexNet with 57M parameters.</li>
    <li><u style="color: blue;">Contribution:</u> Device design and optimization, optical system setup, dataset collection and calibration</li>
  </ul>
</p>

<p style="font-family: 'Helvetica', 'Arial', sans-serif; font-size: 17px; line-height: 1.4;">
  <a href="https://dl.acm.org/doi/10.1145/3618398" style="color: #ff6347; text-decoration: underline;">
    Thin On-Sensor Nanophotonic Array Cameras
  </a><br>

  <span class="name-list">
  Praneeth Chakravarthula, 
  Jipeng Sun, 
  <span style="text-decoration: underline;">Xiao Li&nbsp;</span>,
  Chenyang Lei, Gene Chou, Mario Bijelic, Johannes Froesch, Arka Majumdar, Felix Heide
  </span><br>

  <span style="color: #000000; font-size: 14px;">📚 SIGGRAPH ASIA 2023</span><br>
  <ul style="color: #000000; font-size: 14px; margin-top: -10px; padding-left: 20px;">
    <li><u style="color: blue;">Summary:</u> Demonstrated a wide FoV broadband flat camera that combines a metalens array design with probabilistic deconvolution implemented using a conditional diffusion model to improve the image quality.</li>
    <li><u style="color: blue;">Contribution:</u> Design and setup of the hardware prototype, dataset collection and alignment. </li>
  </ul>
</p>

<p style="font-family: 'Helvetica', 'Arial', sans-serif; font-size: 17px; line-height: 1.4;">
  <a href="https://light.princeton.edu/publication/seeing-through-obstructions/" style="color: #ff6347; text-decoration: underline;">
    Seeing Through Obstructions with Diffractive Cloaking
  </a><br>

  <span class="name-list">
  Zheng Shi, Yuval Bahat, Seung-Hwan Baek, Qiang Fu, Hadi Amata,
  <span style="text-decoration: underline;">Xiao Li&nbsp;</span>,
  Praneeth Chakravarthula, Wolfgang Heidrich, Felix Heide
  </span><br>

  <span style="color: #000000; font-size: 14px;">📚 SIGGRAPH 2022</span><br>
  <ul style="color: #000000; font-size: 14px; margin-top: -10px; padding-left: 20px;">
    <li><u style="color: blue;">Summary:</u> Proposed a computational monocular camera that optically cloaks unwanted obstructions by jointly designing a diffractive optical element at the aperture plane and a feature-based deep learning reconstruction network to recover the unobstructed image.</li>
    <li><u style="color: blue;">Contribution:</u> Participated in discussions and assisted the experiments.</li>
  </ul>
</p>

<p style="font-family: 'Helvetica', 'Arial', sans-serif; font-size: 17px; line-height: 1.4;">
  <a href="https://opg.optica.org/oe/fulltext.cfm?uri=oe-23-24-31206&id=332775" style="color: #ff6347; text-decoration: underline;">
    Tunable terahertz wave generation through a bimodal laser diode and plasmonic photomixer
  </a><br>
  <span class="name-list">
  S.-H. Yang, R. Watts,
  <span style="text-decoration: underline;">X. Li&nbsp;</span>,
  N. Wang, V. Cojocaru, J. O’Gorman, L. P. Barry, and M. Jarrahi
  </span><br>

  <span style="color: #000000; font-size: 14px">📚 Optics Express </span><br>
  <ul style="color: #000000; font-size: 14px; margin-top: -10px; padding-left: 20px;">
    <li><u style="color: blue;">Summary:</u> Demonstrated a compact broadband terahertz source based on difference frequency generation by pumping a plasmonic photomixer with the dual frequencies from a two-section digital distributed feedback laser diode. </li>
    <li><u style="color: blue;">Contribution:</u> Device simulation and characterization</li>
  </ul>
</p>

<h2>Patents</h2>
<ul class="Patents">
	<li>Eyeball Camera for Display System Calibration, US 2021/0014477, WO/2021/011420, CN114128256, EP3997867</li>
	<li>Waveguides with High Index Materials and Methods of Fabrication thereof, US 2022/0128817, WO/2020/185954 </li>
	<li>Systems and Methods for External Light Management, WO2020/023266, US 2021/0231951, CN113811803, EP3938824</li>
</ul>

<h2>Non-work stuff</h2>
<ul class="Patents">
	<li>When I'm not playing with cameras and pixels in the lab, I like taking photos, with street photography being my favorite. Here's selected <a href="https://www.instagram.com/xli_photography/" target="_blank">photos</a> that I took with an iPhone.</li>
</ul>

    
