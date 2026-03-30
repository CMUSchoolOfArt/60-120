# Unit 5: Responsive Environment

Foundations of Electronic Media • 60-120

---

### TouchDesigner

*In this unit, we will create a responsive environment using visual programming software called TouchDesigner to interact with real-world inputs. You will build a system to receive live media input, generate and manipulate data streams, and output responsive content.*

This unit extends through Wednesday, April 29 (Sections A & B), and has **six deliverables**:

* `Apr 06/07` - **Due**: [**5.1. Looking Outwards: Responsive Environments**](#51-looking-outwards-responsive-environments) *(~30 minutes)*
* `Apr 08/09` - **Due**: [**5.2. TouchDesigner Tutorials**](#52-touchdesigner-tutorial) *(~2 hours)*
* `Apr 13/14` - **Due**: [**5.3. Generative Patterns: Converting Data Types**](#53-generative-patterns) *(~2 hours)*
* `Apr 15/16` - **Due**: [**5.4. MediaPipe Tutorials**](#54-mediapipe-tutorials) *(~2 hours)*
* `Apr 20/21` - **Due**: [**5.5. Responsive Environment Draft**](#55-draft-of-environment) *(~6 hours)*
* `Apr 28` - **Due**: [**5.6. Responsive Environment**](#56-responsive-environment) *(~10 hours)*
* `Apr 29` - **Showcase**: [**Responsive Environment Presention**](#responsive-environment-presentation)


### Learning Objectives

*TouchDesigner is a powerful visual programming environment. Its capabilities far exceed the scope of this assignment; however, in this unit you will:*

* Learn the fundamental logic of node-based visual programming systems.
* Explore techniques for generating and manipulating data in real-time, using live media inputs and outputs.
* Create responsive media systems that actively engage the body, beyond traditional computer hardware interfaces.
* Expose opportunities and techniques for spatial interaction with computational art systems.
* Learn to effectively document and present interactive systems and computational artworks.

---

#5.1. Looking Outwards: Responsive Environments

*This Looking-Outwards report is due Monday, April 06 (Section A) or Tuesday, April 07 (Section B). Estimated time is ~1.5 hours.*


### What is TouchDesigner?

**TouchDesigner is a node-based visual programming environment created by Derivative for building real-time interactive multimedia content.**

In practical terms, it’s used to design and run things like:

* Interactive installations (museum exhibits, immersive artworks)
* Live visuals for concerts and performances (VJing)
* Projection mapping
* Generative art and data visualizations
* Real-time graphics driven by sensors, audio, video, or other input

Instead of writing traditional code, you connect “operators” (nodes) that process graphics, audio, video, and data streams. 

Key strengths of TouchDesigner include its real-time media affordances—the systems that you design "cook"  (update) continuously, making it ideal for live performances and interactive media environments.

### Due: 04/06 (Section A) & 04/07 (Section B)
* Spend 30 minutes online looking for content made in Touchdesigner that features some interaction that interests you. Search under takgs like #touchdesigner /#doitintops. Recommended sites to do this viewing are Instagram, Twitter, Youtube, and Vimeo. [**The official TouchDesigner showcase on Vimeo**](https://vimeo.com/groups/touchdesigner/) is particularly good.
* Write one sentence about why this form of interaction or visualization interests you.
* Screenshot and submit the link to the piece. In the Discord channel `#5-1-looking-outwards`
* Note: please do not just skim the first page of results!

---

#5.2. TouchDesigner Tutorials

*This is due before class on Wednesday, April 08 (Section A) or Thursday, April 09 (Section B). Estimated time: ~2 hours.* 

### Due: 04/08 (Section A) & 04/09 (Section B)

* Here are the official [**TouchDesigner Documentation and Learning Resources**](https://derivative.ca/learn); **Behold** the fact that this exists.
* Watch the following demo videos on [**The Touchdesigner 101 Course**](https://learn.derivative.ca/courses/100-fundamentals/). **WHILE FOLLOWING ALONG**: hit "Mark Complete" as you watch.
  * [The User Interface](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/user-interface/)
  * [Using the OP Create Dialog](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/using-the-op-create-dialog/)
  * [Reading Network Anatomy](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/reading-network-anatomy/)
  * [Reading Operator Anatomy](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/reading-operator-anatomy/)
  * [Operator Wires, References & Links](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/manipulating-operator-wires/)
  * [Working with TOPs](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/working-with-tops/)
  * [Working with CHOPs](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/working-with-chops/)
  * [Working with DATs](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/working-with-dats/)
  * [Working with SOPs](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/working-with-sops/)
  * [Working with COMPs](https://learn.derivative.ca/courses/100-fundamentals/lessons/101-navigating-the-environment/topic/working-with-comps/)
  * [Intro to POPs](https://www.youtube.com/watch?v=bWfUk6MF8B0)
* **Screenshot and submit** the progress you have made. In the Discord channel `#5-2-tutorials`, include some screenshots of your tutorial work.

---

#5.3. Generative Patterns
### Converting Data Types

*This is due before class on Wednesday, April 13 (Section A) or Thursday, April 14 (Section B). Estimated time: ~2 hours.* 

Review introductory tutorials related to:

* [Shapes & Color]()
* [Basic Compositing]()
* [Mattes & Masks]()
* [Building Patterns]()

Explore these foundational concepts in relation to  [**Instancing**](https://learn.derivative.ca/courses/200-intermediate/lessons/201-converting-data-types-and-instancing/), [**Feedback**](https://learn.derivative.ca/courses/200-intermediate/lessons/202-tops-intermediate/), and [**Signal Manipulation**](https://learn.derivative.ca/courses/200-intermediate/lessons/203-chops-intermediate/) techniques.

### Due: 04/13 (Section A) & 04/14 (Section B)

* **Create a generative pattern** that uses CHOP data to drive the spatial and/or temporal distribution of a TOP, SOP, or POP network.
* **Upload** your network TOX file to the following Google Drive Share.
* **Screenshot and Post** a description of your network in the Discord channel `5-3-generative-pattern`

---

#5.4. MediaPipe Tutorials

*This is due before class on Wednesday, April 15 (Section A) or Thursday, April 16 (Section B). Estimated time: ~2 hours.* 

The MediaPipe tools for TouchDesigner developed by Torin Blankensmith are an open-source plugin that integrates Google MediaPipe directly into TouchDesigner, enabling real-time computer vision inside a node-based workflow.

In short, they provide a plug-and-play bridge between AI vision models and TouchDesigner.

You can download the MediaPipe plugin from our class [**Google Drive Share**](https://drive.google.com/drive/folders/1hR10qvu5fOGpEqOKLbxk8Br_nVLLrLYg?usp=drive_link), or grab the latest version from [**Torin Blankensmith's GitHub**](https://github.com/torinmb/mediapipe-touchdesigner).

### Due: 04/15 (Section A) & 04/16 (Section B)

* **Download and Install the MediaPipe plugin** by copying the MediaPipe TOX files into a project folder and dragging the MediaPipe TOX into a new TouchDesigner project file.

* **Review** the following MediaPipe tutorials related to:

  * [MediaPipe Tracking Capabilities](https://www.youtube.com/watch?v=Cx4Ellaj6kk&list=PLk51J7zejbawIdr9qBY077tzl2f6L8kCo)
  * [MediaPipe Hand Tracking (part 1)](https://www.youtube.com/watch?v=e2FtkufeErY&list=PLgfxkm9xFocaQXGTxu7HlFomE05kPbO8z&index=1&pp=iAQB0gcJCdkKAYcqIYzv)
  * [MediaPipe Hand Tracking (part 2)](https://www.youtube.com/watch?v=XRw1AUa57Zw&list=PLgfxkm9xFocaQXGTxu7HlFomE05kPbO8z&index=2&pp=iAQB)
  * [MediaPipe Object Tracking](https://youtu.be/pwqZk3oTjEQ?si=PV2MjJ20Q-YAuZKb)
* **Test** the various tracking methods one at a time and **Post** screenshots of your **Face**, **Hand**, and **Pose** tracking results in the Discord channel `5-4-mediapipe-tutorials`

---
#5.5. Responsive Environment Draft

*This is due before class on Monday, April 20 (Section A) or Tuesday, April 21 (Section B). Estimated time: ~6 hours.*

Create a responsive environment in TouchDesigner that is driven by real-time data. Convert data from live media streams or use prebuilt MediaPipe components to capture inputs such as hand gestures, facial detection, or body pose, to generate visual content or map visual parameters—such as color, motion, scale, or particle behavior. Establish a clear relationship between human movement and system response, emphasizing experimentation with interactivity, data flow, instancing, and real-time feedback. Demonstrate a working prototype where user presence and motion directly influence the behavior of a dynamic responsive environment.

### Due: 04/20 (Section A) & 04/21 (Section B)

* Name a copy of your TouchDesigner project file as:

  * **Section[A or B]_YourName**

* Upload a working draft of your project file to the following [Google Drive share](https://drive.google.com/drive/folders/1jCkoKSvAAlW1w1VvFdAQysRM_vjyLBh4?usp=sharing).
* **Post** a screenshot and a brief description of your project goals in the Discord channel `5-5-responsive-environment-draft`

---

#5.6. Responsive Environment

*This is due before 12pm (noon) on Tuesday, April 28 (Sections A & B). Estimated time: ~10 hours.*

### Due: 04/28 (Section B)

* Name a copy of your TouchDesigner project file as:

  * **Section[A or B]_YourName**

* Produce a short video that includes documentation of your network, its interaction, and visual output.
* Upload your final project file and video documentation to the following [Google Drive share](https://drive.google.com/drive/folders/1eIfA_mTaiS3fcfFjPeouKiqW4VvaPpwD?usp=sharing).
* **Post** a screenshot and a brief description of your final project results in the Discord channel `5-6-responsive-environment`

---