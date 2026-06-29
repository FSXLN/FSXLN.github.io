---
title: "Autonomous Imagination: Closed-Loop Decomposition of Visual-to-Textual Conversion in Visual Reasoning for Multimodal Large Language Models"
collection: publications
category: manuscripts
permalink: /publication/autonomous-imagination
excerpt: >-
  Under pure textual modality, Large Language Models (LLMs) have demonstrated
  remarkable success in complex reasoning tasks by decomposing them into simpler
  sub-problems. However, Multimodal Large Language Models (MLLMs) still struggle
  with some seemingly straightforward visual tasks, such as counting and solving
  jigsaw puzzles. We argue that these tasks challenge the ability of
  *visual-to-textual conversion*, where MLLMs convert visual information
  perceived from the input scene, to textual information for further reasoning
  and generating the answer. If the complexity of the visual input is beyond the
  perceptual capability of the MLLMs, without decomposing this conversion
  process, simply scaling inference-time reasoning cannot solve the task because
  it repeatedly encounters the same perceptual bottleneck. We propose an
  approach, *autonomous imagination*, to enable MLLMs to iteratively modify
  visual inputs (e.g. isolating objects, rearranging puzzle pieces) into
  intermediate visual states, decomposing visual-to-textual conversion into
  closed-loop visual modification steps. We show that, without any retraining,
  MLLMs can now solve tasks initially beyond their perceptual capability,
  highlighting that closed-loop visual modification can be an effective way of
  decomposing the visual reasoning task into solvable substeps.
date: 2025-09-21
venue: 'TMLR'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2411.18142'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: 'Jingming Liu, Yumeng Li, <strong>Boyuan Xiao</strong>, Yichang Jian, Ziang Qin, Tianjia Shao, Yao-Xiang Ding, Kun Zhou. &quot;Autonomous Imagination: Closed-Loop Decomposition of Visual-to-Textual Conversion in Visual Reasoning for Multimodal Large Language Models&quot; <i>TMLR</i>.'
---
  Under pure textual modality, Large Language Models (LLMs) have demonstrated
  remarkable success in complex reasoning tasks by decomposing them into simpler
  sub-problems. However, Multimodal Large Language Models (MLLMs) still struggle
  with some seemingly straightforward visual tasks, such as counting and solving
  jigsaw puzzles. We argue that these tasks challenge the ability of
  *visual-to-textual conversion*, where MLLMs convert visual information
  perceived from the input scene, to textual information for further reasoning
  and generating the answer. If the complexity of the visual input is beyond the
  perceptual capability of the MLLMs, without decomposing this conversion
  process, simply scaling inference-time reasoning cannot solve the task because
  it repeatedly encounters the same perceptual bottleneck. We propose an
  approach, *autonomous imagination*, to enable MLLMs to iteratively modify
  visual inputs (e.g. isolating objects, rearranging puzzle pieces) into
  intermediate visual states, decomposing visual-to-textual conversion into
  closed-loop visual modification steps. We show that, without any retraining,
  MLLMs can now solve tasks initially beyond their perceptual capability,
  highlighting that closed-loop visual modification can be an effective way of
  decomposing the visual reasoning task into solvable substeps.
