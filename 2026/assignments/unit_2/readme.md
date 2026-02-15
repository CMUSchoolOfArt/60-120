# Unit 2: Creative Coding

Foundations of Electronic Media • 60-120 • Spring 2026

*Creative coding treats programming as a material rather than a utility: a way to think, sketch, and compose through rules, parameters, and systems. In this unit, we will use code to generate form, variation, and time-based behavior, working incrementally from simple visual constraints to systems that produce many outcomes. Our emphasis is not technical mastery, but learning how structured processes, repetition, and controlled variation can become expressive artistic strategies.*


---

## Schedule of Deliverables

Due Monday **2/9** (for Section A) or Tuesday **2/10** (for Section B): 

* [2.1. Orientation](#21-orientation) *(15m)*
* [2.2. Looking Outwards: Generative Art](#22-looking-outwards-generative-art) *(30m)*
* [2.3. Reading-Response: Artist Narratives](#23-reading-response-artist-narratives) *(30m)*
* [2.4. Reading-Response: Effective Complexity and The Oatmeal Problem](#24-reading-response-effective-complexity-and-the-oatmeal-problem) *(45m)*
* [2.5. Warmup Exercise: Ten Shapes, One Rule](#25-warmup-exercise-ten-shapes-one-rule) *(45m)*

Due Wednesday **2/11** (for Section A) or Thursday **2/12** (for Section B): 

* [2.6. Face Generator](#26-face-generator) *(2.5h)*

Due Monday **2/16** (for Section A) or Tuesday **2/17** (for Section B): 

* [2.7. Pattern Generator](#27-pattern-generator) *(4h)*

Due Monday **2/23** (for Section A) or Tuesday **2/24** (for Section B): 

* [2.8. Clocks](#28-clocks) *(5h)*


---

## 2.1. Orientation

Before the end of class on February 4th/5th, please make sure to have done the following:

* If you don't already have one, **create** an account at OpenProcessing.org.
* In your laptop’s web browser, **bookmark** [our OpenProcessing classroom](https://openprocessing.org/class/104705#/), whose URL is [https://openprocessing.org/class/104705#/](https://openprocessing.org/class/104705#/).
* **Join** our OpenProcessing classroom. To do this, **login** to your OpenProcessing account. Then **locate** and **use** the provided private “**OpenProcessing Invite Link**” to join our OpenProcessing classroom, which you can find [here](https://discord.com/channels/1459919117493473312/1459919118860943524/1459952218739314688) in the `#key-information` channel in our Discord.

*Now: (15 minutes; Due Monday 2/9 or Tuesday 2/10)*

**Spend 15 minutes familiarizing yourself** with the following online resources. The goal here is simply to make sure you are *aware* of these media, that you have seen them with your *eyes*, that you know *where* to find them, and that you know *how* they can help you. *There is no deliverable for this exercise.*

* Here's a [p5.js **Cheat Sheet**](https://bmoren.github.io/p5js-cheat-sheet/)
* This is the official [p5.js **Reference**](https://p5js.org/reference/)) and the [older version](https://archive.p5js.org/reference/) that you might like better.
* Here are the [p5.js **Examples**](https://archive.p5js.org/examples/). I recommend you browse at least five of them.
* Here are some extremely helpful and important **YouTube tutorial channels**: 
  * The legendary [**Coding Train**](https://www.youtube.com/@TheCodingTrain/videos) by Dan Shiffman — featuring 1200+ videos, ranging from [this great p5.js introduction](https://www.youtube.com/watch?v=HerCR8bw_GE&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA) to very advanced tutorials
  * [PattVira](https://www.youtube.com/@pattvira) – excellent tutorials (by a CMU alum!), including this great [introductory playlist](https://www.youtube.com/playlist?list=PL0beHPVMklwgMz4Z-mNp4_udo9mjBk7pn)
  * [Xin Xin](https://www.youtube.com/@xinxin1011) — some more excellent introductory videos
* Of possible interest:
  * [p5.j​​s 中文教程](https://www.youtube.com/watch?v=uEffNzLcn60&list=PLznBLb1-pQM_piONXfwND-0h3h493vO1k) by [QianQian Ye](https://qianqian-ye.com/)
  * [한국어로 된 p5.js 튜토리얼](https://www.youtube.com/watch?v=j2fbcQqzJzE&list=PLgAffhOqz2QE0o6TeDW345rcA_YBCDqnt)

<!-- * ["Getting Started with p5.js"](https://openlab.citytech.cuny.edu/mtec1101-hd88-sp2022/files/2019/03/Make_Getting-Started-with-p5dotjs.pdf) **book** by Lauren Lee McCarthy: [PDF](https://openlab.citytech.cuny.edu/mtec1101-hd88-sp2022/files/2019/03/Make_Getting-Started-with-p5dotjs.pdf), [PDF](https://intronewmedia150.wordpress.com/wp-content/uploads/2019/08/gettingstartedp5.pdf). -->

---

## 2.2. Looking Outwards: Generative Art

![William Mapan (detail)](img/mapan.jpg)

*(30 minutes; Due Monday 2/9 or Tuesday 2/10)*

> *“Generative art refers to any art practice where the artist uses a system, such as a set of natural language rules, a computer program, a machine, or other procedural invention, which is set into motion with some degree of autonomy contributing to or resulting in a completed work of art.”* — Philip Galanter

In this exercise, you'll look at some artworks, and make a brief post about one that caught your eye. *So:* 

* [**Here is a list**](some_generative_artworks.md) of about 50 generative artworks. **Browse** these pages, and **select** a project you like (or which appeals to you more than the others). 
* **Create** a post in the Discord channel `#2-2-looking-outwards`. In your post,
* **state** the project's title and artist;
* **provide** a link to the project's URL;
* **write** a sentence or two about what you found interesting about it; and
* **include** an image or screenshot of the artwork.

---

## 2.3. Reading-Response: Artist Narratives

![Vera Molnar's 'Letters from My Mother'](img/molnar_letters.jpg)

*(30 minutes; Due Monday 2/9 or Tuesday 2/10)*

* Briefly **skim** the five short artist narratives below, and **choose** *one* artist's article to focus on. (Each is approximately a 10-15 minute read. You only have to read one article.)
* **Create** a post in the Discord channel `#2-3-narratives`. 
* In your post, **write** 100–150 words responding to the questions below. **Answer** all parts concisely and concretely, please.
	1. *(Process insight)* **Describe** one specific aspect of the artist’s process that stood out to you. For example, this might include how they: begin a project, iterate over time, use constraints, decide when something is “working”, or balance control and surprise.
	2. *(Decision-making)* **Identify** one decision the artist made (conceptual, aesthetic, or technical) that seems especially important to the final work. Why did this decision matter?
	3. *(Personal connection)* Briefly **describe** one way this artist’s process either: *resonates* with how you like to work, or *conflicts* with how you usually approach making things.

**Artist narratives:**

* Robert Hodgin, *Meander* (2020): [**Web**](https://roberthodgin.com/project/meander) / [PDF](pdf/hodgin_meander.pdf)
* Casey Reas, *Phototaxis* (2001-2021): [**Web**](https://medium.com/@REAS/notes-on-phototaxis-db7aa7641ad8) / [PDF](pdf/reas_phototaxis.pdf)
* Vera Molnár, *My Mother’s Letters* (1988-1995): [**PDF**](pdf/molnar-mothers-letters.pdf)
* Zach Lieberman, *Daily Sketches in 2025* (2025) [**Web**](https://zachlieberman.medium.com/daily-sketching-in-2025-60189ffd6b60) / [PDF](pdf/lieberman_2025.pdf)
* Aleksandra Jovanic, *Chromatlas* (2022): [**Web**](http://aleksandrajovanic.com/chromatlas/) / [PDF](pdf/jovanic_chromatlas.pdf)

<!-- * Tyler Hobbs, *Fidenza* (2021): [**Web**](https://www.tylerxhobbs.com/words/fidenza) / [PDF](pdf/hobbs_fidenza.pdf) -->

---


## 2.4. Reading-Response: Effective Complexity and The Oatmeal Problem

![Kate Compton](img/compton.png)

*(45 minutes; Due Monday 2/9 or Tuesday 2/10)*

* **Read** [this one-page excerpt from an article](pdf/kate-compton-oatmeal.pdf) from an article by Kate Compton, “So you want to build a generator...” (2016), in which she discusses the challenge of aesthetics in generative art, and introduces what she calls the "10,000 bowls of oatmeal problem". 
* **Read** [this one-page excerpt from an article](pdf/galanter_effective_complexity.pdf) by Philip Galanter, "Generative Art Theory" (2003), in which he discusses the concept of "effective complexity".
* **Create** a post in the Discord channel `#2-4-oatmeal`, and **respond** to both questions below (in about 150 words total): 
  1. *(Critical synthesis)* In your own words, **explain** why a generator that produces endless novelty can still feel boring. Use Compton’s "10,000 Bowls of Oatmeal" problem and/or Galanter’s concept of effective complexity to support your explanation.
  2. *(Constructive reflection)* **Describe** something you personally find endlessly fascinating despite (or because of) small variations. This could be a natural phenomenon, a specific cultural expression, something visual, sonic, etc. Explain what kinds of variation matter and why they remain perceptually meaningful rather than collapsing into "oatmeal."

---

## 2.5. Warmup Exercise: Ten Shapes, One Rule

*Due: Monday 2/9 (for Section A) or Tuesday 2/10 (for Section B). ~45 minutes.*

* **Create** a new sketch at OpenProcessing, with a canvas no larger than 600×600px. 
* **Write** p5.js code to create a single static composition using only the 2D primitive shapes (`ellipse`, `rect`, `line`, `triangle`, `quad`, etc) described [here](https://p5js.org/reference/#Shape). You may use any of these shapes you wish. 
* **Use** exactly 10 shapes total.
* **Choose** one self-imposed rule and follow it strictly. **Select** *one* of the following rules (or devise your own, if you wish):
	* All shapes must share one edge or touch at one point.
	* All shapes are variations of a single proportion.
	* All shapes align to an invisible grid.
	* Only three colors total.
	* Every shape must overlap at least one other.
	* Shapes get progressively larger or smaller.
	* Horizontal symmetry only, no vertical symmetry.
* **Heed** these additional constraints: 
	* Static results *only*. All your code should be in `setup()`, not `draw()`.
	* No image files, no text, no interaction, no randomness.
* In OpenProcessing, **edit** the information about your project (click ⓘ and EDIT). **Add** a title, **capture** a thumbnail screenshot, and **describe** your rule in the description field. 
* Add your project to the [correct OpenProcessing collection](https://openprocessing.org/class/104705/#/c/105114).
* **Create** a post in the Discord channel, `#2-5-ten-shapes`, to document your work,
* In your Discord post, **upload** a screenshot of your exercise. 
* In your Discord post, **Write** 2–3 sentences describing the rule you chose, and something that surprised you about the process of developing your project.

---

## 2.6. Face Generator

*Due: Wednesday 2/11 (for Section A) or Thursday 2/12 (for Section B). ~2.5 hours.*

**Study** these whimsical hand-drawn faces by Bruno Munari (from *Design as Art,* 1969). His drawings are highly economical constructions: a few specific marks stand in for eyes, nose, and mouth, yet they cohere immediately as faces through [gestalt perception](https://en.wikipedia.org/wiki/Gestalt_psychology) rather than realistic rendering. Their humor comes from a tension between abstraction and specificity: each face is unmistakably "someone", even though almost nothing conventionally descriptive is actually drawn.

![faces by Bruno Munari](img/munari.png)

We now begin an exercise in *procedural character design*. Consider the following examples of *computationally generated faces:* 

![dorfelt_moka_faces.jpg](img/dorfelt_moka_faces.jpg)<br />Matthias Dörfelt’s [*Weird Faces*](https://www.mokafolio.de/works/Weird-Faces) (2012) — The artist’s attempt to recreate his doodling drawing style in code.

![chernoff.png](img/chernoff.png)<br />Herman Chernoff’s [multivariate face visualizations](https://en.wikipedia.org/wiki/Chernoff_face) (1973) — displays of multivariate data in the shape of a human face, whose individual parts represent values of the variables by their shape, size, placement and orientation. *(Another example [from Tufte](img/chernoff_tufte.png))*

![hyphen_labs_pills_usjd_666x522.jpg](img/hyphen_labs_pills_usjd_666x522.jpg)<br/>[Hyphen Labs](https://hyphen-labs.com/who-is-hyphen-labs) (Ece Tankal and Carmen Aguilar y Wedge), [*Everyday Painkillers*](https://hyphen-labs.com/Everyday-Painkillers) (2016): An installation in which, every 24 minutes (the frequency of U.S. opioid deaths), a script directs an onsite CNC machine to carve a novel face into an additional pill. *([Video from Eyeo 2018](https://vimeo.com/287093806#t=24m40s), jump to 24:40)*

![cryptopunks.png](img/cryptopunks.png)<br />Larva Labs, *Cryptopunks* (2018): 10,000 unique, computationally generated faces; some of the first and most successful NFTs.

*And,*

* Mark Wilson, [Meta-Face](http://mgwilson.com/Drawing%20with%20Computers.pdf) (1985): One of the earliest face generators I could find, pictured below.
* Jean-Paul Delahaye, [face generator from *Nouveaux dessins géométriques et artistiques*](img/delahaye_faces_1985.jpg) (1985).
* Shunsuke Takawo, [Face Generator](https://openprocessing.org/sketch/1207768), 2021 (p5.js), and [another](https://openprocessing.org/sketch/2333020)
* Aditya Jain, [Face Generator](img/aditya_jain_face_generator.gif), 2023 *([original](https://x.com/adityajainart/status/1675563610490413056))*
* Kate Compton, [Face Generator](img/compton_kate_onethird.png)
* And [this nice project](https://openprocessing.org/sketch/1361275) (2025)

![mark_wilson_metaface_dwg_w_comp_p18.png](img/mark_wilson_metaface_dwg_w_comp_p18.png)

[![openprocessing_sketch_1361275.png](img/openprocessing_sketch_1361275.png)](https://openprocessing.org/sketch/1361275)

#### Requirements

* In [OpenProcessing](https://openprocessing.org/class/104705/#/c/105113), **create** a p5.js sketch whose canvas is no larger than 600x600 pixels.
* **Write** code to generate an image of a face or character. Using the recommended code structure below, your sketch should generate a new character whenever the user clicks the mouse button.
  * Your project should be parameterized by **at least three variables**, but preferably more (aim for 5–10). Include at least one *discrete* parameter (such as a variable that controls the number of eyeballs, or the presence or absence of a hat), and one *continuous* parameter (such as a variable that controls the size, position, and/or color of features).
  * Your project should include at least one **grounding cue**, such as a background shape or color, neck/shoulders, or a simple prop. Keep it minimal.
* **Upload** your project to the correct [OpenProcessing collection](https://openprocessing.org/class/104705/#/c/105113).
* **Create** a post in the Discord channel, `#2-6-face-generator`.
* In your post, **upload** a couple of screenshots, showing your generator's variety.
* **Write** a sentence to direct our attention. What are you proudest of? 
* **Write** a sentence listing a few of your face's most important variables (e.g. "nose size; number of pimples", etc.)

<details><summary><strong>Helpful Tutorials</strong></summary>
Feeling uncertain? These tutorials may be helpful. 

**Golan's Tutorials at OpenProcessing**

* [**Tutorial on variables**](https://openprocessing.org/sketch/2531328#page-1) (variables, for-loop, if-statement, scoping)
* [**Tutorial on random compositions**](https://openprocessing.org/sketch/2540323)

**Variables**

* [Variable - Creative Coding with p5.js](https://www.youtube.com/watch?v=xhdIJo8lxWA&list=PL0beHPVMklwgMz4Z-mNp4_udo9mjBk7pn&index=5) (Patt Vira)
* [2.1: Variables in p5.js (mouseX, mouseY)](https://www.youtube.com/watch?v=RnS0YNuLfQQ&list=PLglp04UYZK_PrN6xWo_nJ-8kzyXDyFUwi) (Coding Train)
* [2.2: Variables in p5.js (Make your own)](https://www.youtube.com/watch?v=Bn_B3T_Vbxs&list=PLglp04UYZK_PrN6xWo_nJ-8kzyXDyFUwi) (Coding Train)

**Conditional Testing**

* [Conditionals (Boolean Expression)](https://www.youtube.com/watch?v=V8aJnrXlGhY&list=PL0beHPVMklwgMz4Z-mNp4_udo9mjBk7pn&index=6) (Patt Vira)
* [Conditionals (If, Else If, Else)](https://www.youtube.com/watch?v=btVdEgjooGE&list=PL0beHPVMklwgMz4Z-mNp4_udo9mjBk7pn&index=7) (Patt Vira)

**Iteration**

* [For and While Loops](https://www.youtube.com/watch?v=cnRD9o6odjk&t=1s) (Coding Train)
* [For Loop - Creative Coding with p5.js](https://www.youtube.com/watch?v=SFAQ9cn5ImE&list=PL0beHPVMklwgMz4Z-mNp4_udo9mjBk7pn&index=9) (Patt Vira)
* [For Loop - p5.js Tutorial](https://www.youtube.com/watch?v=QdGeb0H5idM&list=PLT233rQkMw761t_nQ_6GkejNT1g3Ew4PU&index=12) (Xin Xin)
</details>

#### Development Notes

In your project, you might have variables that specify the size, position, color, or other visual characteristics of the eyes, nose, and mouth. By randomizing these values, you could vary properties like: the face’s expression (happy, sad, angry); the face’s identity (Chris, Pat, Alex, Sam); or the face’s species (cat, monkey, zombie, alien). (These are just examples.) Give special consideration to controlling the precise shape of face parts, such as the curves of the nose, chin, ears, and jowls, and/or characteristics such as skin color, stubble, hairstyle, blemishes, inter-pupillary distance, facial asymmetry, cephalic index, and prognathism.

**Place your character.** A face floating in an empty void feels unfinished because it omits context that helps viewers interpret scale, orientation, mood, and identity. Even minimal surroundings provide visual grounding: a neck and shoulders establish anatomy and posture; a background color or simple shape sets contrast and emotional tone; a hint of environment can imply lighting and narrative. A little context can help you make a much more compelling character system, and it does so with very little extra code.

We recommend you **begin** with the code template provided below. The particular structure of this code will allow your sketch to generate a new face whenever the user clicks the mouse button.


```
function setup() {
  createCanvas(600, 600);
}

function draw() {
  background('white'); 
  // generate a face HERE...
  noLoop();
}

function mousePressed(){
  loop();
}
```

If you're curious, [**here are a few face generators**](student_face_generators.md) made by previous students from this course. We will evaluate your generator based on considerations including its:

* *Range*: produces meaningfully different faces across clicks (it's not oatmeal).
* *Authorship*: style choices are intentional and specific (only *you* could have made this).

*Please do not use an LLM to write this code for you. LLMs will make generic faces; we are interested in eliciting your own creative work, no matter how basic your skills are. If you do use an LLM for code, you must disclose it in your post.*

---

## 2.7. Pattern Generator

*Five Parts. Due Monday 2/16 (for Section A) or Tuesday 2/17 (for Section B). ~4 hours.*

![freeke.png](img/freeke.png)


Pattern is a way of organizing repetition and variation. Across textiles, architecture, ornament, and computation, patterns emerge from rules that are applied repeatedly. In this project, you will write code that generates an **infinitely extendable pattern**—like wallpaper, fabric, or tile—using iteration, structure, and controlled variation. Your pattern should feel **designed**, not merely repeated.


### What you are making

Create a full-screen p5.js sketch that:

* Defines one or more small visual motifs
* Repeats them using nested iteration (using a grid structure or other rhythmic pattern)
* Creates variation across the pattern using controlled randomness
* Could plausibly be tiled or extended forever without a visible “edge”

Design something you could imagine living with: on a wall, a floor, or a garment.

### Required steps

* **Complete** warm-up exercises 2.7.A–2.7.D before starting the main project: 
	1. [2.7.A. Exercise: Lines to the Cursor](https://openprocessing.org/class/104705/#/c/105301) (10 minutes)
	2. [2.7.B. Exercise: Transitioning Rectangles](https://openprocessing.org/class/104705/#/c/105299) (20 minutes)
	3. [2.7.C. Exercise: Iteration & Positioning](https://openprocessing.org/class/104705/#/c/105302) (15 minutes)
	4. [2.7.D. Exercise: Nested Iteration & Randomness](https://openprocessing.org/class/104705/#/c/105300) (20 minutes)
* **Create** a new OpenProcessing sketch using `createCanvas(windowWidth, windowHeight)`
* **Write** code that:
	* Draws your motif(s)
	* Repeats them using nested loops, with occasional variation
	* Varies at least three meaningful parameters (not just position jitter)
* Upload your sketch to the correct OpenProcessing collection, [**2.7.E. Pattern Generator**](https://openprocessing.org/class/104705/#/c/105115)
* **Post** a screenshot in the Discord channel `#2-7-pattern`
* In your post, **write** one sentence describing your goals or approach.

### Design expectations (read carefully)

Your pattern should demonstrate **intentional structure**. Give consideration to:

* **Repetition vs. variation** — What stays consistent across the pattern? What changes? Why?
* **Rhythm and spacing** — Regular, irregular, alternating, clustered
* **Figure and ground** — How shapes relate to empty space
* **Scale** — Variation at more than one level of detail (overall layout vs. local detail)
* **The potential for surprise** through the placement of infrequent features in the pattern
* **Attention to color**. Feel free to use a palette creator, a palette extraction tool, etc.
* **Constrained Randomness**. Give consideration to the depth of variation in your pattern, and how randomness shapes the design. After how many viewings does your pattern become predictable? How might you forestall this as long as possible?

**Avoid** patterns that are merely:

* Uniform grids of identical shapes
* Random noise without structure


---

## 2.8. Clocks

*Due Monday 2/23 (for Section A) or Tuesday 2/24 (for Section B). ~5 hours.*

![banded_clock.gif](img/banded_clock.gif)

The dynamic control of visual media over time is a core concern in new media arts. In this project, you are asked to create visualizations that display novel or unconventional representations of the time. This work is due at the beginning of class on 2/23 or 2/24.

This project has **4 main components**: 

* **2.8.A.** *(15 minutes; 5%)* **[Looking Outwards](#2-8-a-looking-outwards)**
* **2.8.B.** *(60 minutes; 10%)* **[Readings and Viewings](#42-readings-and-viewings)**
* **2.8.C.** *(9 hours; 80%)* **[Make A Conventional Clock](#43-make-three-clocks)**
4. *(15 minutes, 5%)* **[Document Your Work](#document-your-work)**

The learning objectives of this project are:

* To devise technologies and graphic concepts for representing time that go beyond conventional methods of visualization and mediation.
* To refine your craft skills in the use of code to govern a spatiotemporal design, by effectively and expressively controlling shape, color, form, and motion.
* To become acquainted with the history of systems and devices for timekeeping.

---

### 2.8.A. Looking Outwards

*(15 minutes; 5%)* **Browse** the timepieces listed in this [**Lecture on Clocks**](https://github.com/golanlevin/lectures/tree/master/lecture_clock) directory. Now, in the `#2-8-looking-outwards` Discord channel, **write** a couple of sentences about a clock that you find particularly memorable. Why does it stick with you?

---

### 2.8.B. Readings and Viewings

*(60 minutes; 10%)* You are asked to enrich your understanding of clocks and timekeeping by **reviewing** the following resources. These readings and viewings should take less an hour.

![history-of-calendar.jpg](../../2024/assignments/images/history-of-calendar.jpg)

<!--
Attempts to mark time stretch back many thousands of years, with some of the earliest timekeeping technologies being gnomons, sundials, water clocks, and lunar calendars. Even today’s standard representation of time, with hours and minutes divided into 60 parts, is a legacy inherited from the ancient Sumerians, who used a sexagesimal counting system.

The history of timekeeping is a history driven by economic and militaristic desires for greater precision, accuracy, and synchronization. Every increase in our ability to precisely measure time has had a profound impact on science, agriculture, navigation, communications, and, as always, warcraft.

Despite the widespread adoption of technological standards, there are many other ways to understand time. *Psychological* time contracts and expands with attention; *biological* cycles affect our moods and behavior; *ecological* time is observed in species and resource dynamics; *geological* and *astronomical* rhythms can span millennia. In the twentieth century, Einstein’s theory of relativity further upended our understanding of time, showing that it does not flow in a constant way, but rather in relation to the position from which it is measured—a possibly surprising return to the significance of the observer.

-->

Please **review** the following **5** resources:

* Please **read** this this [**5-page PDF about timekeeping**](../../../readings/drucker_timekeeping.pdf) by design theorist Johanna Drucker, from her book *Graphesis: Visual Forms of Knowledge Production* (Harvard Press, 2014).
* **Browse** or **skim** the [**Wikipedia History of Timekeeping Devices**](https://en.wikipedia.org/wiki/History_of_timekeeping_devices).
* **Review** the information at [**https://yourcalendricalfallacyis.com/**](https://yourcalendricalfallacyis.com/). (It’s awesome!)
* In case you missed it in class, please **watch** this excellent 6-minute YouTube video on the [**History of Timekeeping Devices**](https://www.youtube.com/watch?v=SsULOvIWSUo).
* In case you missed it in class, please **watch** the first 13 minutes of [**A Brief History of the Calendar and Timekeeping**](https://www.youtube.com/watch?v=OaYMK2n9Aow&t=4s), a YouTube lecture by [Dr. Donna Carroll](https://www.maastrichtuniversity.nl/dl-carroll), Lecturer of Physics, Maastricht University.

*Now:* In a Discord post in the `#2-8-b-time-readings` channel, please **write** two sentences about something that stuck with you from any of these readings or viewings. What did you see, read or learn that was interesting? Why was it interesting to you?

---

## 43. Make Three Clocks

![proposals-for-clocks_horvitz.jpg](../../2024/assignments/images/proposals-for-clocks_horvitz.jpg)<br />*“Proposals for Clocks” by David Horvitz*

*(9 hours; 80%)* In OpenProcessing, make three different clocks: 

* **A**. *(20%)* One clock which is "digital", and presents the current time in an appealing way using *numbers* — for example: Arabic, Roman, or Chinese numerals. (This can be an opportunity to experiment with self-made type design or dynamic typography.)
* **B**. *(20%)* One clock which is "analog", and presents the current time in an appealing way using the changing positions of (for example) rotating indicators.
* **C**. *(40%)* One clock which is entirely of your own design, which makes the time legible in a new way (through means other than numbers or a traditional clock face). For example, you might visualize numeric bit patterns, or use iteration to present countable graphic elements.

Each timepiece should appear different at all times of the day, and should (probably) repeat its appearance every 24 hours (or other relevant cycle, if desired). You will probably want to use the *[hour()](https://archive.p5js.org/reference/#/p5/hour), [minute()](https://archive.p5js.org/reference/#/p5/minute), [second()](https://archive.p5js.org/reference/#/p5/second)*, and *[millis()](https://archive.p5js.org/reference/#/p5/millis)* functions, but you’re also welcome to use *[day()](https://archive.p5js.org/reference/#/p5/day), [month()](https://archive.p5js.org/reference/#/p5/month)*, and *[year()](https://archive.p5js.org/reference/#/p5/year)* functions in order to build a clock that evolves over longer timescales. If your timepiece measures other phenomena, that’s fine too. You may choose the dimensions and aspect ratio of each clock as necessary, including fullscreen clocks. If your laptop screen does not inspire you, feel free to design a prototype clock display intended for a different display, such as a smart-watch or a public outdoor LED screen.

You are encouraged to **question** basic assumptions about which kind of time is represented, and how. **Consider** things like biological time ([chronobiology](https://en.wikipedia.org/wiki/Chronobiology)), [ultradian rhythms](https://en.wikipedia.org/wiki/Ultradian_rhythm) and [infradian rhythms](https://en.wikipedia.org/wiki/Infradian_rhythm), solar and lunar cycles, celestial time, geological time, decimal time, historical time, [psychological time](http://cpl.revues.org/4998), and subjective time. (This list is not exclusive or exhaustive.) Remember to **sketch** first in your paper sketchbook. At the top of your code for each timepiece, **add a comment** which explains that project. For example, you might explain what your timepiece displays, or how to read it, or how it works.

[This sketch](https://openprocessing.org/sketch/2018166) demonstrates how to use the p5.js basic time functions:<br />[![clock demo](../../2024/assignments/images/clock-demo.gif)](https://openprocessing.org/sketch/2018166)

Here are some potentially helpful clock tutorials on YouTube: 

* Coding Train's [clock tutorial](https://www.youtube.com/watch?v=E4RyStef-gY)
* Patt Vira's [clock tutorial](https://www.youtube.com/watch?v=3Aa8CzklS6c)
* Xin Xin's [clock tutorial](https://www.youtube.com/watch?v=JgLlQPF22Gw)

### Document Your Work

*(15 minutes, 5%)* In one or more Discord posts in the channel `#43-clocks`, concisely describe your three clocks.

**Embed** one or more images of each clock. Show what it looks like or how it behaves at different times of day. If a clock involves animation in a special way, embed an animated GIF.

**Write** a couple sentences that describes each clock (what is the concept, how is it made, how is a person meant to experience it). **Write** another few sentences reflecting on your experience making this work (what was successful, what was a struggle, what did you learn).

