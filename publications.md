---
layout: default
title: Publications
permalink: /publications/
---

> (*: equal contribution)

## Conference Paper

<ol class="pub-list">
  <li>
    <div class="pub-title">MULTI3IR: A Benchmark for Multi-perspective Multi-domain Multi-modal Information Retrieval</div>
    <div class="pub-author"><b>Seokwon Song</b>, <a href="https://ohmyksh.github.io/" target="_blank">Sohyeon Kim</a>, <a href="https://vision.snu.ac.kr/gunhee" target="_blank">Gunhee Kim</a></div>
    <div class="pub-venue"><em>In EMNLP</em>, 2026</div>
    <div class="pub-tldr">Can retrievers <b>search</b> for evidence that covers the many perspectives an open-ended question admits? We build a 105K-query multi-domain, multi-modal benchmark and find that existing multimodal retrievers show single-perspective bias. SPIN, a lightweight steering method, substantially improves perspective coverage and transfers to unseen open-ended IR benchmarks.</div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2608.30949" class="pub-btn">PDF</a>
      <a href="https://github.com/seokwon99/Multi3IR" class="pub-btn">Code</a>
      <a href="https://huggingface.co/datasets/seokwon99/Multi3IR" class="pub-btn">Dataset</a>
      <a href="https://seokwon99.github.io/Multi3IR/" class="pub-btn">Project Page</a>
    </div>
  </li>
  <li>
    <div class="pub-title">MAVIS: A Benchmark for Multimodal Source Attribution in Long-form Visual Question Answering</div>
    <div class="pub-author"><b>Seokwon Song</b>, <a href="https://0601p.github.io/" target="_blank">Minsu Park</a>, <a href="https://vision.snu.ac.kr/gunhee" target="_blank">Gunhee Kim</a></div>
    <div class="pub-venue"><em>In AAAI</em>, 2026</div>
    <div class="pub-tldr">Once multimodal evidence is retrieved, can an MLLM <b>read</b> it and write a long-form answer where every fact is cited? We introduce 157K visual QA instances with fact-level citations to multimodal documents and metrics for informativeness, groundedness, and fluency. Multimodal RAG yields more informative answers, but models ground image documents far less reliably than text.</div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2511.12142" class="pub-btn">PDF</a>
      <a href="https://github.com/seokwon99/MAVIS" class="pub-btn">Code</a>
      <a href="https://huggingface.co/datasets/seokwon99/MAVIS" class="pub-btn">Dataset</a>
    </div>
  </li>
  <li>
    <div class="pub-title">Is a Peeled Apple Still Red? Evaluating LLMs' Ability for Conceptual Combination with Property Type</div>
    <div class="pub-author"><b>Seokwon Song*</b>, <a href="https://taehyunlee.net/" target="_blank">Taehyun Lee*</a>, <a href="https://ahnjaewoo.github.io/" target="_blank">Jaewoo Ahn</a>, <a href="https://okaybody10.github.io/" target="_blank">Jae Hyuk Sung</a>, <a href="https://vision.snu.ac.kr/gunhee" target="_blank">Gunhee Kim</a></div>
    <div class="pub-venue"><em>In NAACL</em>, 2025 <span class="pub-badge">Oral</span></div>
    <div class="pub-tldr">When concepts are combined, do LLMs <b>reason</b> about which properties emerge, carry over, or get canceled? CCPT provides 12.3K annotated triplets and three tasks. Even o1 struggles to generate phrases with target emergent properties, and a method inspired by cognitive models of concept combination improves all generative tasks.</div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2502.06086" class="pub-btn">PDF</a>
      <a href="https://github.com/seokwon99/CCPT" class="pub-btn">Code</a>
      <a href="https://huggingface.co/datasets/seokwon99/CCPT_12.3K" class="pub-btn">Dataset</a>
    </div>
  </li>
  <li>
    <div class="pub-title">Read-only Prompt Optimization for Vision-Language Few-shot Learning</div>
    <div class="pub-author"><a href="https://dgjun32.github.io/" target="_blank">Dongjun Lee*</a>, <b>Seokwon Song*</b>, Jehee Suh, Junmyeong Choi, <a href="https://www.sanghyeoklee.com/" target="_blank">Sanghyeok Lee</a>, <a href="https://www.hyunwoojkim.com/" target="_blank">Hyunwoo J. Kim</a></div>
    <div class="pub-venue"><em>In ICCV</em>, 2023</div>
    <div class="pub-tldr">How can a frozen vision-language model adapt to unseen tasks and domains from few examples without disturbing its internal representations? Read-only prompts with masked attention prevent representation shift and improve base-to-new and domain generalization over CLIP and CoCoOp, especially in data-scarce settings.</div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2308.14960" class="pub-btn">PDF</a>
      <a href="https://github.com/mlvlab/RPO" class="pub-btn">Code</a>
    </div>
  </li>
</ol>
