---
layout: post
title: Developed Medical Language Model (MedLMs)
date: 2024-11-29 16:11:00-0400
inline: false
related_posts: false
---

Finetuned multiple LLMs for Medical answering system and achieved remarkable performance.

---

The integration of AI in healthcare is revolutionizing how we approach Medical Question Answering (MedQA) systems, providing clinicians, patients, and researchers with quick and reliable responses. In this project, we explore the fine-tuning of several pre-trained large language models and adapting them to the medical domain through efficient methods like LoRA. The final models were deployed using LangChain and Netlify for better infernece speed.

By experimenting with datasets like WikiDoc and MedQuad, we uncover valuable insights into how these models perform in terms of speed, scalability, and task-specific accuracy. Comparing the models reveals key trade-offs. Larger models like Llama 3 excel at handling complex medical queries, while smaller models such as DistilGPT2 prioritize speed and efficiency for simpler tasks. Our findings emphasize how fine-tuning and careful model selection can create precise, scalable solutions tailored to the unique challenges of healthcare applications.

<!-- Jean shorts raw denim Vice normcore, art party High Life PBR skateboard stumptown vinyl kitsch. Four loko meh 8-bit, tousled banh mi tilde forage Schlitz dreamcatcher twee 3 wolf moon. Chambray asymmetrical paleo salvia, sartorial umami four loko master cleanse drinking vinegar brunch. <a href="https://www.pinterest.com">Pinterest</a> DIY authentic Schlitz, hoodie Intelligentsia butcher trust fund brunch shabby chic Kickstarter forage flexitarian. Direct trade <a href="https://en.wikipedia.org/wiki/Cold-pressed_juice">cold-pressed</a> meggings stumptown plaid, pop-up taxidermy. Hoodie XOXO fingerstache scenester Echo Park. Plaid ugh Wes Anderson, freegan pug selvage fanny pack leggings pickled food truck DIY irony Banksy. -->

#### Models:

<ul>
    <li>Llama 3</li>
    <li>DistilGPT2</li>
    <li>Gemma 1.1</li>
    <li>Mistral 7B</li>
    <li>Llama 2</li>
</ul>

> All the models fine-tuned in our project can be found at <a href="https://huggingface.co/Apurva3509">Apurva's Hugging Face</a> and <a href="https://huggingface.co/abhilash2599">here</a>. Please feel free to use them and test it.

---

Usage and feedback:

Please try our model(s) and give feedback so we can improve and tune our parameters and possibly adapt to different scenarios.

You can make a pull request in this repo: <a href="https://github.com/Apurva3509/MedLMs/pulls">Repository</a>

Thanks !!
