# Some Effects of Dataset Bias in AI Systems

*(These lecture materials were created in part by Paolo Pedercini)*

---

Joy Buolamwini, ["The Coded Gaze: Bias in Artificial Intelligence"](https://www.youtube.com/watch?v=eRUEVYndh9c) (0-5:00")

[![buolamwini.jpg](img/buolamwini.jpg)](https://www.youtube.com/watch?v=eRUEVYndh9c)


---

In their essay and exhibition [Excavating AI](https://excavating.ai/), artists Kate Crawford and Trevor Paglen show how the datasets used to train machine-learning image recognition systems are not neutral technical artifacts but socially and politically constructed objects. They argue that the selection, sourcing, taxonomies, and labeling of images (especially of people) embed cultural prejudices and power dynamics, shaping how AI systems interpret and classify the world in ways that can reproduce or amplify social biases.

![imagenet.jpg](img/imagenet.jpg)


---

[*Deep Hysteria* by artist, Amy Alexander](https://amy-alexander.com/projects/deep-hysteria/)

Amy Alexander created an AI system that generates synthetic "twins", who differ only in gender presentation. She also created a second AI system, trained on human perceptions, which attempts to identify the emotion on the twins' faces. The female-presenting faces are often categorized as "upset", "confused", etc. 

![alexander_amy](img/alexander_amy.jpg)

---

Various types of racial and gender bias have been affecting AI systems since their inception. For example, in [AI-generated barbies](https://www.youtube.com/watch?v=L2sQRrf1Cd8&t=105s) (1:45"–2:22")

[![barbie](img/barbie.jpg)](https://www.youtube.com/watch?v=L2sQRrf1Cd8&t=105s)

---


Also see the [Stable Diffusion Bias Explorer](https://huggingface.co/spaces/society-ethics/DiffusionBiasExplorer) (Working as of 1/21/26)

[![stable-explorer](img/stable-explorer.jpg)](https://huggingface.co/spaces/society-ethics/DiffusionBiasExplorer)

---

DALL-E3 attempts to combat the racial bias in its training data by occasionally randomly inserting race words that aren’t white into a prompt. These can bubble up accidentally: 

> Prompt: *Guy with swords pointed at me meme except they are Homer Simpson.*

![homer-simpson-ai](img/homer-simpson-ai.jpg)

---

Object recognition can be affected by skin color.

![googlevision](img/googlevision.png)

---

Biases can bubble up in everyday software applications.

Here is the LinkedIn profile of journalist, Melissa Heikkilä, who writes about AI for the Financial Times and MIT Review:

![melissa_heikkila](img/melissa_heikkila.jpg)

In her article, ["The viral AI avatar app Lensa undressed me—without my consent"](https://www.technologyreview.com/2022/12/12/1064751/the-viral-ai-avatar-app-lensa-undressed-me-without-my-consent/), she writes: 

> *My avatars were cartoonishly pornified, while my male colleagues got to be astronauts, explorers, and inventors*.<br />
> *When I tried the new viral AI avatar app Lensa, I was hoping to get results similar to some of my colleagues at MIT Technology Review. The digital retouching app was first launched in 2018 but has recently become wildly popular thanks to the addition of Magic Avatars, an AI-powered feature which generates digital portraits of people based on their selfies. But while Lensa generated realistic yet flattering avatars for them—think astronauts, fierce warriors, and cool cover photos for electronic music albums— I got tons of nudes. Out of 100 avatars I generated, 16 were topless, and in another 14 it had put me in extremely skimpy clothes and overtly sexualized poses.*

![heikkila](img/heikkila.png)

---

### Additional References: 

*Beyond media representation, why does bias in AI matter?*

* [Flawed facial recognition system sent a man to jail](https://www.wired.com/story/flawed-facial-recognition-system-sent-man-jail/?ref=dl-staging-website.ghost.io)
* [Predictive policing](https://www.technologyreview.com/2021/02/05/1017560/predictive-policing-racist-algorithmic-bias-data-crime-predpol/)
* [AI used to deny health insurance](https://www.cbsnews.com/news/unitedhealth-lawsuit-ai-deny-claims-medicare-advantage-health-insurance-denials/) and to [appeal such denials](https://qz.com/fight-health-insurance-denials-appeals-ai-1851733712)
* [AI tool used to predict the need of extra medical care is biased against Black patients](https://www.technologyreview.com/2019/10/25/132184/a-biased-medical-algorithm-favored-white-people-for-healthcare-programs/)
* [AI-powered recruiting tool is biased against women](https://www.reuters.com/article/us-amazon-com-jobs-automation-insight-idUSKCN1MK08G/) (luckily scrapped by Amazon)
* [AI tools are used to grade student essays](https://www.vice.com/en/article/flawed-algorithms-are-grading-millions-of-students-essays/)
* [AI tools are used to review college admissions](https://www.thenation.com/article/society/artificial-intelligence-chatgpt-college-applications/)
