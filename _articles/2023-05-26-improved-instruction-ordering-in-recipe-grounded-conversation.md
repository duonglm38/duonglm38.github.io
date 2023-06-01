---
title: "Improved Instruction Ordering in Recipe-Grounded Conversation"
category: articles
permalink: "/articles/2023-05-26-improved-instruction-ordering-in-recipe-grounded-conversation"
venue: "Annual Meeting of the Association for Computational Linguistics (ACL) 2023"
date: 2023-05-26
link: https://arxiv.org/abs/2305.17280
---

[comment]: <> (<a href="https://arxiv.org/abs/2305.17280">Download PDF here</a>.)
<b>Duong Minh Le</b>, Ruohao Guo, Wei Xu, Alan Ritter

Abstract: In this paper, we study the task of instructional dialogue and focus on the cooking domain. Analyzing the generated output of the GPT-J model, we reveal that the primary challenge for a recipe-grounded dialog system is how to provide the instructions in the correct order. We hypothesize that this is due to the model's lack of understanding of user intent and inability to track the instruction state (i.e., which step was last instructed). Therefore, we propose to explore two auxiliary subtasks, namely User Intent Detection and Instruction State Tracking, to support Response Generation with improved instruction grounding. Experimenting with our newly collected dataset, ChattyChef, shows that incorporating user intent and instruction state information helps the response generation model mitigate the incorrect order issue. Furthermore, to investigate whether ChatGPT has completely solved this task, we analyze its outputs and find that it also makes mistakes (10.7% of the responses), about half of which are out-of-order instructions. We will release ChattyChef to facilitate further research in this area at: <a href="https://github.com/octaviaguo/ChattyChef">link</a>
