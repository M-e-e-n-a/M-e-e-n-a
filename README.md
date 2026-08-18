# Hey, I'm Meena! 👋

I am a Software Engineer at **JPMorgan Chase** (SEP) and a CS graduate from **MSRIT** (graduated June 2025). 

By day, I write enterprise backend services. By night, I'm diving headfirst into **AI Safety, Mechanistic Interpretability, and Post-Training Dynamics**. I’m actively looking to transition my software engineering background into full-time empirical alignment research.

Email: [smkblr9@gmail.com](mailto:smkblr9@gmail.com) | [Google Scholar](https://scholar.google.com/citations?user=Wi2E1fwAAAAJ) | [LinkedIn](https://linkedin.com/in/meena-kumari-)

---

## 🧠 Why AI Safety, and Why Right Now?

I spent my university years building traditional software and running SFT fine-tuning experiments on models. But the more I watched how modern models behave, the more I realized: **building increasingly massive systems without understanding their internal circuits or how to reliably control them is an engineering crisis.**

I don't want to just build bigger commercial pipelines. I want to help solve the core technical bottlenecks of alignment. I am currently self-studying the **ARENA curriculum**, reading mechanistic interpretability papers, and writing code to white-box probe running models.

---

## 🔬 What I'm Obsessed with & Hacking on Lately

### 1. Loom 🧵 (Causal Activation Steering)
* **What it is**: A tiny, from-scratch PyTorch engine I wrote to understand how **forward hooks** actually work in transformer residual streams [rec2qWv2uQC5ontGH, recS6nNc9hVyyVXBk]. 
* **My "Aha!" Moment**: I tested it on a tiny model (`pythia-14m`). I extracted the brain waves for the word "Yes" and injected them back into the model mid-computation. 
  * I found that if you steer with a high coefficient (`2.5`), you completely break the model's narrow 128-dimensional latent space, causing it to glitch and repeat quotation marks endlessly [recS6nNc9hVyyVXBk, rectBzHvY22Efwfqn]. 
  * But if you nudge it with a tiny coefficient (`0.1`), the model stays perfectly coherent, but its actual downstream completion is causally shifted [recS6nNc9hVyyVXBk]. Seeing this causal shift happen on my local machine was incredibly cool.


---
