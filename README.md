# DES INV 202 Journal
Welcome to my new GitHub repository! 

# Outline
[week 2](README.md#week-2-Trying-Rhino-and-grasshopper)

[week 1](README.md#week-1-Intro-to-TDF)

---
# Week 2: Trying Rhino and grasshopper #
## Week of 09/03/2024

### What I've done

This week, we started investigation of our first project -- computational design. I tried more functions in Rhino and started to explore grasshopper. To gain a better understanding of these 2 tools, I completed the following:
* watch linkedin tutorials on navigating Rhino 2D sketches and 3D modeling
* watch linkedin tutorials on getting to know grasshopper UI and basic parametric designs
* follow along a youtube video about creating a box with grasshopper
* play with the phone stand file shared during class, change parameters
* create my own 3d model in grasshopper to familiarize myself with some commonly used components
* make a diagram of how grasshopper works

I want to document the process of me learning and trying out these 2 tools: 


**1. Changing the parameters for the phone case** 

The first thing that I have done was to explore the example files of the phone case given during class. Adjusting the paramters allowed me to see how grasshopper connects to rhino, and how to make small changes to an existing design.

<img width="400" alt="step 1" src="assets/change1.png"> 1
>I toggled the boolean operators and enabled components that I think are necessary for modifying the parameters of the model.

<img width="400" alt="step 2" src="assets/change2.png"> 2
> I changed the parameters of the phone first to make it have the same specs as my current phone. I also changed the orientation of the model to make it be able to film tiktok videos.

<img width="400" alt="step 3" src="assets/change3.png">  <img width="400" alt="step 4" src="assets/change4.png"> 3
> I played around the paramters of the phone stand and see how the shape changes.

<img width="400" alt="step 5" src="assets/change5.png"> <img width="400" alt="step 6" src="assets/change6.png"> 4
> It seems like the current design cannot be modified too much to hold an upright phone, but I baked it anyway to see how it looks.

**2. Replacing the nested spheres** 

Then, I tried to replace the nested sphere structure in the given file to see how I could make some more changes to the design and create something on my own. 

<img width="400" alt="step 1" src="assets/replace1.png"> 1
> I made a box & cylinder in another grasshopper file. I followed the steps during Monday's TDF class to make sure the design is good for replacing the original structure. I copied and pasted it to the phone case file.

<img width="400" alt="step 2" src="assets/replace2.png"> 2
> I used the nested box to replace the original structure. It seems like the design is just too small

<img width="400" alt="step 3" src="assets/replace3.png"> 3
> I changed the parameters of the box based on the size of the phone and the design constraints. The assembly looked good after the modifications.

<img width="400" alt="step 4" src="assets/replace4.png"> 4
> I baked the design, and it looked great.

**3. Creating my own grasshopper design**

Another thing that I have done was to create a design from scratch in grasshopper and experiment with different components. I followed a youtube tutorial for creating parametric objects.

**4. Creating diagrams to understand grasshopper**

I created 2 diagrams about rhino&grasshopper after I've experimented with them. These diagrams helped me think more deeply about the mechanism of these softwares and helped me further understand the modeling process.

<img width="1000" alt="diagram 1" src="assets/diagram1.png"> *diagram v1*
> For this first version, I briefly went through creating the phone stand design again in my head and wrote down bullet points. Based on the bullet points, I thought about the processes and broke it up into these steps.

<img width="500" alt="diagram 2" src="assets/diagram2.jpg"> 

*diagram v2*

> For this second version, I sketched a diagram on paper to go through the steps that I could think of when I used grasshopper and rhino.

### Reflections

In the process of learning Rhino and Grasshopper, I’ve engaged in several hands-on activities that deepened my understanding of how these tools interact and function together. One of my key learning moments was making diagrams of the example files. This exercise helped me visualize how the components in Grasshopper interact with Rhino’s modeling environment and reinforced the parametric logic that drives Grasshopper’s functionality. By breaking down each step in the example files, I gained clarity on how parameters are manipulated to affect the resulting geometry.

Another important part of my learning was experimenting with the shared files and manipulating the parameters. By adjusting various sliders and inputs in Grasshopper, I was able to see how changing values could result in different design outcomes. ‘Baking’ these forms into Rhino allowed me to see rendered results and continue refining the physical model. This hands-on experimentation gave me a good understanding of the design process for modeling and provided practical insight into the parametric workflow.

After experimented with modifying the provided file set by replacing the nested spheres with different geometries, I thought critically about how different shapes interact with one another in this design and further solidified my ability to work independently in Grasshopper. I was able to create simple designs with grasshopper and be proud of the baked formes.

At this stage, I feel confident in my ability to manipulate existing files, understand how parameters drive design changes, and create very basic models using Grasshopper. My documentations provided a helpful record of my learning process. Moving forward, I aim to experiment with more complex parametric models and integrate additional Grasshopper functions into my designs (hopefully).

### Speculations

As I grow more comfortable with Rhino and Grasshopper, I plan to explore more complex, dynamic systems. I am also willing to explore interdisciplinary design challenges. The next step could involve learning about more advanced techniques and try to use them in various kinds of projects. 

I’m also excited for fabrication, as I speculate that my future work will involve experimenting with Rhino and Grasshopper for 3D printing. By combining these parametric designs with fabrication, I can develop workflows that go beyond virtual models into physical prototyping, exploring the boundaries between design, engineering, and production. 

* Some insights: Since I am taking my elective in immersive computing, I anticipate that real-time rendering and VR/AR integration will become more streamlined within Rhino. This can enable designers to experience their creations in immersive environments. This shift would provide deeper spatial understanding of designs before they are physically produced, improving both the efficiency and creativity of the design process.

* Industry insights: [Autodesk unveils Research Project Bernini for generative AI 3D shape creation](https://adsknews.autodesk.com/en/news/research-project-bernini/)
Since 3D modeling softwares, like rhino, could be hard to learn for novices, such AI products will definitely help people create assets that they want very quickly. I wonder if there will be some AI that could generate grasshopper diagrams in the future...


---
# Week 1: Intro to TDF #
## Week of 08/27/2024

**What I've done** 

This week is the first week of school. I took my first TDF class in the MDes program and was introduced to many new tools and new concepts. I learned about：
* the skills required for this class
* the projects we are going to work on (including the levels of expectation)
* the tools that we will learn (Rhino, Grasshopper, Particle IDE, etc)

I explored each tool for a bit after I got home to get a basic sense of what these are like. For now, I am both excited and concerned about moving forward with new tools to learn. I am looking forward to trying out new things and expand my skill set. I also really want to see my creations come into life. I am a bit concerned about how steep the learning curve is going to get for these platforms, especially for Rhino. Given that I have 0 experience in this area, I might need to really spend much time on becoming familiar with such softwares. 

Apart from that, I opened up my github account and completed some trainings for using the equioments at Jacobs. Still trying to familiarize myself with the new environment and new workflow at Berkeley. Here are some images of things I've done: 

<img width="500" alt="Deadpool meme" src="assets/ghub.png"> <img width="200" alt="Studio space" src="assets/studio.jpg">

**Speculations** 

My speculation for the coming weeks is pretty optimistic. For the tools being used in the TDF class, I expect them to be accessible and easier to use as I engage with them over time. I don't really expect tools to evolve or we change tools over this semester, but I am willing to learn about what tools can help with the product design/software learning process. There wasn't any work done this week. I expect to try out the machines in the studio more often, and expect to create products of high quality. For projects that I am not familiar with, I expect to make something that reflects my maximum effort.

<img width="500" alt="Deadpool meme" src="assets/deadpool.gif">

**Goals** 

My goals for this quarter:
* Learn about more diverse skills, such as modeling
* Master digital product design through practice
* Explore the areas of my career interest
* Build up my portfolio, gain professional advice
* Join more projects and activities to meet more people and learn from skilled peers
* Leverage my expertise in quant + qual research and try to contribute to this commuity

**P.S.** I found an article about digital ecosystem and I feel like it ties to our second project. Creating open platforms for sharing and collaboration is definitely a future trend and therefore I think our 2nd project will equip me sufficient skills to get ready for the future. So this project is so far the one that excites me the most!

[Link to article](https://www.reuters.com/technology/google-meta-qualcomm-team-up-push-open-digital-ecosystems-2023-12-13/)

---
# Github Background Information & Context
If you’re new to GitHub, you can think of this as a shared file space (like a Google Drive folder, or a like a USB drive that’s hosted online.) 

This is your space to store project files, videos, PDFs, notes, images, etc., and (hopefully, neatly) organize so it's easy for viewers (and you!) to navigate. That said, it’s super easy for you to share any file or folder with us (your TDF instructional team) - just send us the link!  As a start, feel free to simply add images to the `/assets` folder, which is located [here](/assets). 

The specific file that I’m typing into right now is the **README.md** for this repo. 
##### (💡 TIP: The .md indicates that we’re using [Markdown formatting.](https://www.markdownguide.org/cheat-sheet/)) #####
<h6> (💡 TIP 2: GitHub Markdown supports <a href="https://gist.github.com/seanh/13a93686bf4c2cb16e658b3cf96807f2"> <em>HTML formatting</em> too, including emojis 😄</a>, in case that helps!) </h6>

### :star: Whatever you write in your **README.md** will show up on the “front page” of your GitHub repo. This is where we’ll be looking for your [weekly progress reports](https://github.com/Berkeley-MDes/24f-desinv-202/wiki/3.0-Weekly-Submissions#weekly-progress-report). They might look something like this: ###

# Week 1: Example Report 1 #
## Week of 09/05/2024

This week, I designed a cool phone stand made of rocks. Check out all my cool sketches and progress photos from this week below, etc., etc....

<img width="200" alt="Cool Phone Stand made of rocks" src="assets/exampleimg.png">

---

It's time to start making this space your own! If you want to save these instructions, make a copy.  Also, feel empowered to delete everything in this README.md and start documenting! 

Excited to work with you,
your TDF teaching team

PS: let us know if you have any questions!!

PPS: 

## Quick Links, compiled here for your convenience: ##

- [TDF Wiki](https://github.com/Berkeley-MDes/24f-desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/u/0/folders/1DJ1b6sSDwHXX6NRcQYt10ivyQSgU0ND6) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1537533) - where the grading happens
