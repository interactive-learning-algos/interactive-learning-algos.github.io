---
layout: home
title: Home
permalink: /:path/
seo:
  type: Course
  name: Algorithmic Foundations of Interactive Learning
---

# Algorithmic Foundations of Interactive Learning
Spring 2025. 17-740. Tuesday / Thursday 11:00-12:20.

## Announcements 📣
{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## Course Overview 📝
Interactive learning is a dynamic approach to machine learning where systems learn and adapt through continuous interaction with their environment or users, receiving feedback and adjusting their behavior in response. These techniques are currently experiencing a resurgence across various domains of artificial intelligence and machine learning, from robotics to language modeling. In this advanced theory course, students will explore interactive learning from its foundational principles to recent applications, including fine-tuning Large Language Models (LLMs) and robot learning from demonstration. 

Key topics include:
1. **Online Learning:** Learning under distribution shift.
2. **Game Solving:** Using no-regret algorithms to compute equilibria.
3. **Reinforcement Learning:** Sequential decision making. Model-free, model-based, and hybrid RL.
4. **Imitation Learning & Applications to Robotics:** Learning from demonstrations. Behavioral cloning, DAgger, and inverse RL.
5. **RL from Human Feedback & Applications to Language Modeling:** Learning from preferences. PPO, DPO, SPO.


## Schedule (Tentative) 📅

{% for module in site.modules %}
{{ module }}
{% endfor %}


## Instructors 👨‍🏫

<figure style="display: inline-flex;">

<figure>
<img src="/assets/images/zsw.jpg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="http://www.zstevenwu.com"><button type="button" name="button" class="btn">Steven Wu</button>
</a></figcaption>
</figure>

<figure>
<img src="/assets/images/jab.jpg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://robotwhisperer.org/"><button type="button" name="button" class="btn">Drew Bagnell</button></a></figcaption>
</figure>

<figure>
<img src="/assets/images/gks.png" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="http://www.gokul.dev"><button type="button" name="button" class="btn">Gokul Swamy</button></a></figcaption>
</figure>

</figure>

