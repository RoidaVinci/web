---
layout: default
title: "Roi Vence Personal Website"
---

<main role="main" class="container-sm" style="max-width: 1080px">
    <div class="row">
        <div class="col">
            <p class="h1 mt-5 page-title">
                <img class="profile-img-small d-md-none" src="{{ '/assets/profile.jpg' | relative_url }}" />
                <span style="clear: right">Long (Tony) Lian</span>
            </p>
            <p class="h4 section-title" style="clear: right">About</p>
            {% capture bio %}{% include bio.md %}{% endcapture %}
            <p>{{ bio | markdownify }}</p>
            <a href="mailto:roi.vence@gmail.com">Email</a> 
            <a href="https://www.linkedin.com/in/roivence">LinkedIn</a> / <a href="https://github.com/RoidaVinci">Github</a>
        </div>
        <div class="col-auto d-none d-md-block">
            <img class="profile-img" src="{{ '/assets/profile.jpg' | relative_url }}" />
        </div>
    </div>
    <div class="row">
        <div class="col">
            <p class="h4 section-title">Side Projects</p>
            <p><a href="https://github.com/TonyLianLong/stable-diffusion-xl-demo">Stable Diffusion XL Demo WebUI</a>: A gradio-based WebUI that allows playing around with <a href="https://arxiv.org/abs/2307.01952">SDXL</a> locally and on Colab for free. <a target="_blank" href="https://colab.research.google.com/github/TonyLianLong/stable-diffusion-xl-demo/blob/main/Stable_Diffusion_XL_Demo.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a></p>
            <p><a href="https://github.com/TonyLianLong/AnimeGAN.js">AnimeGAN.js</a>: An implementation of AnimeGAN, which converts photos to anime style online, with <a href="https://github.com/tensorflow/tfjs">tf.js</a>.</p>
            <p><a href="https://github.com/TonyLianLong/Rainbow">Rainbow</a>: An implementation of Rainbow algorithm with <a href="https://github.com/PaddlePaddle/PARL">PARL</a> reinforcement learning framework.</p>
        </div>
    </div>
</main>

<footer class="footer">
    <div class="container-sm">
        <div class="row">
            <div class="col" style="text-align: center">
                <span class="text-muted">
                    Credits to <a href="https://github.com/TonyLianLong/websitev2"> for a version of the source code for this website. 
                </span>
            </div>
        </div>
    </div>
</footer>
