---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

---
## Probabilistic Multivariate Gaussian Distance for Uncertainty-Aware Learning
<div style="display: flex; align-items: center;">
  <div style="flex: 1; text-align: justify; margin-right: 20px;">
    <p>
      In this work we introduce a custom distance metric for <b>non-parametric supervised learning</b> algorithms when each data sample comes as a collection of pairs of means and standard deviations, rather than a single fixed vector. Unlike traditional metrics such as Euclidean distance, this approach accounts for <b>uncertainty</b> and variability in each feature, making it more robust to fluctuations. By leveraging variance as informative data, the metric can better discriminate between stable and volatile samples, improving on classic algorithms performances in contexts where <b>distributional information matters</b>.
    </p>
    <div style="text-align: center; margin-top: 15px;">
      <img src="/images/custom_knn.png" alt="custom_knn" style="max-width: 80%; display: inline-block;">
    </div>
  </div>
</div>

[[Paper](/files/custom_knn.pdf)]


---
## ARC Challenge
<div style="display: flex; align-items: center;">
  <div style="flex: 1; text-align: justify; margin-right: 20px;">
    <p>The Artificial Reasoning Corpus (ARC) is a dataset designed to evaluate machine reasoning capabilities. The <a href="https://arcprize.org/">ARC Prize 2024</a> is an award for advancements in <b>AI reasoning</b>, recognizing innovative research that pushes the boundaries of machine reasoning performance using the ARC dataset. The limited number of samples per puzzle prevents statistical learning of puzzle peculiarities, calling for <b>neuro-symbolic</b> approaches instead. Current methods heavily rely on human-crafted elementary transformations, which are combined in search of the puzzle's transformation, a process that falls short of the challenge's goals. <!--My approach focuses on <b>inductive biases</b>, aiming to let features <b>emerge</b> from a minimal set of constraints with minimal human intervention. --></p>
  </div>
  <div style="flex: 1;">
    <img src="/images/ARC.png" alt="ARC" style="max-width: 90%;">
  </div>
</div>

---
## Graph Signal Processing
<div style="display: flex; align-items: center;">
  <div style="flex: 1; text-align: justify; margin-right: 20px;">
    <p>Investigation of Graph Signal Processing (GSP) applied to analysing brain fMRI data. In collaboration with <a href="https://fr.linkedin.com/in/ines-vati">Ines Vati</a>, we leveraged GSP along with other <b>time series</b> analysis tools to predict how much subjects liked pictures shown to them during <b>fMRI</b> recordings. For a 3-class classification task, our best approach achieved a 40% accuracy, which is slightly above random chance. This approach involed adapting Dynamic Time Warping metric to a series of features obtained through the <b>graph Fourier transform</b>. This project highlighted the critical need to <b>collaborate with experts</b> to successfully conduct such subtle analysis.</p>
  </div>
  <div style="flex: 1;">
    <img src="/images/MVA_GSP.png" alt="MVA_GSP" style="max-width: 95%;">
  </div>
</div>
[[Paper](/files/MVA_GSP.pdf)] [[GitHub](https://github.com/InesVATI/TimeSeries-GraphSignalProcessing)] [[Data](https://arxiv.org/abs/1809.01281)]

---
## Brain Connectome
<div style="display: flex; align-items: center;">
  <div style="flex: 1; text-align: justify; margin-right: 20px;">
    <p>Study of the limitations of a novel <b>Riemannian method</b> for inferring <b>brain connectomes</b> from Diffusion Weighted Imaging (DWI) data, aiming to enhance method's ability to handle <b>fiber crossings</b> effectively. This framework is intended to improve individual <b>tractography</b> methods but still yield doubtable results due to noise in DTI data, when it comes to build a robust average connectome atlas.</p>
  </div>
  <div style="flex: 1;">
    <img src="/images/MVA_brain_connectome.png" alt="MVA_brain_connectome" style="max-width: 95%;">
  </div>
</div>
[[Paper](/files/MVA_brain_connectome.pdf)] [[GitHub](https://github.com/aarentai/Metric-Cnn-2D-IPMI/tree/main)]

---
## Mathematical Olympiads
<div style="display: flex; align-items: center;">
  <div style="flex: 1; text-align: justify; margin-right: 20px;">
    <p>I spent my free-time during my last 2 years of highscool studying <b>autonomously</b> Olympiad mathematics, on <a href="https://www.mathraining.be">Mathraining</a>. I've took <b>additional courses</b> and attended a summer school to deepen my understanding. In addition, I founded a mathematics club at my high school where I <b>taught Olympiad maths</b> to other students. I’ve also competed in several <b>contests</b>, and I am proud to have been selected by the <a href="https://maths-olympiques.fr/">POFM</a>, the French organization responsible for preparing students for the <a href="https://www.imo-official.org/">International Mathematical Olympiad</a> (IMO)</p>
  </div>
  <div style="flex: 1;">
    <img src="/images/POFM.png" alt="POFM" style="max-width: 95%;">
  </div>
</div>
[[Mathraining Profile](https://www.mathraining.be/users/1547)] [[Results](https://maths-olympiques.fr/wp-content/uploads/2018/10/R%C3%A9sultats_coupe_automne_2018.pdf)]

---