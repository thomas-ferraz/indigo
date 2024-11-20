---
title: About
layout: page
---
![Profile Image]({% if site.external-image %}{{ site.picture }}{% else %}{{ site.url }}/{{ site.picture }}{% endif %})

<section id="about-me">
    <h2>👨🏻‍💻 About Me</h2>
    <p>
        Hi, I'm <strong>Thomas Ferraz</strong>, a PhD Track Student at École Polytechnique / Télécom Paris (Institut Polytechnique de Paris), specializing
        in <strong>Natural Language Processing (NLP)</strong> with a focus on <strong>large language models</strong>,
        <strong>multilingual NLP</strong>, and <strong>low-resource languages</strong>. I hold a Master’s degree in Applied Math & AI (Master MVA)
        from <strong>ENS Paris-Saclay</strong> and an engineering degree from the <strong>Universidade de São Paulo</strong>, where I graduated
        top of my class. My research aims to advance methods for building robust, efficient, and inclusive NLP systems, particularly for
        underrepresented languages. I have gained valuable industry experience through research internships at <strong>Meta</strong>,
        <strong>Amazon</strong>, <strong>Apple</strong>, and <strong>NAVER Labs</strong>, where I contributed to projects on
        <strong>Efficient ML</strong>, <strong>multilingual NLP</strong>, <strong>Multilingual ASR</strong>, and <strong>LLMs Instruction-following</strong>.
    </p>
</section>

<section id="research-interests">
    <h2>🔬 Research Interests</h2>
    <ul>
        <li><strong>Low-resource NLP:</strong> Developing techniques to enhance language models for less-represented languages.</li>
        <li><strong>Adversarial Robustness:</strong> Creating methods to make NLP systems more resilient against adversarial inputs.</li>
        <li><strong>Efficient Models:</strong> Optimizing model architectures for better performance with fewer resources.</li>
        <li><strong>Speech Recognition and Translation:</strong> Improving multilingual speech models for robust and accurate transcription and translation, particularly in low-resource language settings.</li>
    </ul>
</section>

<section id="selected-papers">
	<h2>📝 Selected Publications</h2>
    <p>A selection of papers that reflect my main research focus and contributions.</p>

<table style="width: 100%; table-layout: fixed;">

  <tr>
    <td style="padding:10px; width: 25%;">
      <a href="https://arxiv.org/pdf/2410.06458"><img src="{{ site.url }}/assets/images/selected_publications/DeCRIM.png"></a>
    </td>
    <td style="padding:10px; width: 75%;">
      <a class="paper" href="https://arxiv.org/pdf/2410.06458" style="font-size: 20px; text-decoration: none; color: #007acc;">
        LLM Self-Correction with DeCRIM: Decompose, Critique, and Refine for Enhanced Following of Instructions with Multiple Constraints
      </a><br>
      <span style="font-style: italic; color: #555;">Thomas Palmeira Ferraz, Kartik Mehta, Yu-Hsiang Lin, Haw-Shiuan Chang, Shereen Oraby, Sijia Liu, Vivek Subramanian, Tagyoung Chung, Mohit Bansal, Nanyun Peng</span><br>
      <span style="color: #333;">EMNLP, 2024 & Sys2Reasoning @ NeurIPS, 2024</span><br>
      <p style="margin-top: 5px; font-size: 0.95em; color: #333;"><strong>TL;DR:</strong> Introducing RealInstruct to evaluate LLMs on real multi-constrained instructions, and DeCRIM self-correction that improves instruction following decomposing requests and refining responses, enabling open LLMs to outperform GPT-4 with strong feedback.</p>
    </td>
  </tr>

  <tr>
    <td style="padding:10px; width: 25%;">
      <a href="https://arxiv.org/pdf/2311.01070"><img width="200px" style="min-width:100px; object-fit: cover;" src="{{ site.url }}/assets/images/selected_publications/DistilWhisper.png"></a>
    </td>
    <td style="padding:10px; width: 75%;">
      <a class="paper" href="https://arxiv.org/pdf/2311.01070" style="font-size: 20px; text-decoration: none; color: #007acc;">
        Multilingual DistilWhisper: Efficient Distillation of Multi-task Speech Models via Language-Specific Experts
      </a><br>
      <span style="font-style: italic; color: #555;">Thomas Palmeira Ferraz, Marcely Zanon Boito, Caroline Brun, Vassilina Nikoulina</span><br>
      <span style="color: #333;">ICASSP, 2024</span><br>
      <p style="margin-top: 5px; font-size: 0.95em; color: #333;"><strong>TL;DR:</strong> Propose a lightweight adaptation method to bridge the gap between small and large models on under-represented languages. It leverages language-specific experts and knowledge distillation from the larger model, outperforming fine-tuning and LoRA while adding minimal overhead.</p>
    </td>
  </tr>
  <tr>
    <td style="padding:10px; width: 25%;">
      <a href="https://arxiv.org/pdf/2201.01337"><img width="200px" style="min-width:100px; object-fit: cover;" src="{{ site.url }}/assets/images/selected_publications/ZeroBERTo.png"></a>
    </td>
    <td style="padding:10px; width: 75%;">
      <a class="paper" href="https://arxiv.org/pdf/2201.01337" style="font-size: 20px; text-decoration: none; color: #007acc;">
        ZeroBERTo: Leveraging Zero-Shot Text Classification by Topic Modeling
      </a><br>
      <span style="font-style: italic; color: #555;">Alexandre Alcoforado, Thomas Palmeira Ferraz, Rodrigo Gerber, Enzo Bustos, André Seidel Oliveira, Bruno Miguel Veloso, Fabio Levy Siqueira, Anna Helena Reali Costa</span><br>
      <span style="color: #333;">PROPOR, 2022</span><br>
      <p style="margin-top: 5px; font-size: 0.95em; color: #333;"><strong>TL;DR:</strong> ZeroBERTo, a hybrid model for zero-shot text classification combining topic modeling with language models, overcoming input size limitations and reducing runtime, achieving 12% better F1 score and 13x faster inference compared to XLM-R on Portuguese benchmark.</p>
    </td>
  </tr>
<!-- 
  <tr>
    <td style="padding:10px">
      <a href="https://link-to-paper3.com"><img height="75px" style="min-width:100px; object-fit: cover; border-radius: 8px;" src="path/to/image3.jpg"></a>
    </td>
    <td style="padding:10px">
      <a class="paper" href="https://link-to-paper3.com" style="font-size: 20px; text-decoration: none; color: #007acc;">
        Yet Another Paper Title
      </a><br>
      <span style="font-style: italic; color: #555;">Thomas Ferraz, Author F, Author G</span><br>
      <span style="color: #333;">Conference Name, Year</span><br>
      <p style="margin-top: 5px; font-size: 0.95em; color: #333;"><strong>TL;DR:</strong> A concise explanation of the research contributions.</p>
    </td>
  </tr>
-->
</table>


<!-- 
<h2>Skills</h2>

<ul class="skill-list">
	<li>HTML - Jade - Haml - Erb</li>
	<li>Responsive (Mobile First)</li>
	<li>CSS (Stylus, Sass, Less)</li>
	<li>Css Frameworks (Bootstrap, Foundation)</li>
	<li>Javascript (Design Patterns, Tests)</li>
	<li>AngularJS - ReactJS</li>
	<li>Grunt - Gulp - Yeoman</li>
	<li>Git</li>
	<li>PHP</li>
	<li>Python</li>
	<li>MySQL - MongoDB</li>
	<li>Scrum and Kanban</li>
	<li>TDD e Continuous Integration</li>
</ul>

<h2>Projects</h2>

<ul>
	<li><a href="https://github.com/">Lorem Lorem</a></li>
	<li><a href="https://github.com/">Ipsum Dolor</a></li>
	<li><a href="https://github.com/">Dolor Lorem</a></li>
</ul>
-->
