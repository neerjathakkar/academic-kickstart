---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Neerja en España #4: My Research Grant"
subtitle: ""
summary: "The research part of my research grant: Life in my lab and the research I'm working on"
authors: []
tags: [Fulbright, 2019, Research]
places: [Spain, Zaragoza]

categories: 
date: 2020-05-24T11:07:00-05:00
lastmod: 2020-05-24T11:07:00-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
*Originally written October 2019*

I can't believe that I've been in Spain for over a month. It's flown by, and strangely feels like this is my life now, and I'm loving it! There's a lot of exciting non-work related stuff happening, but I'll save that for the next update - I want to take this one to explain what I'm doing here work-wise.

I'm working in the [Graphics and Imaging lab](https://graphics.unizar.es/) at University of Zaragoza. There are 3 or 4 professors in the lab, a handful of postdocs, and a decent amount of PhD students, making for a total of about 20 people, which is pretty large. The lab is full of incredibly smart, impressive people. *(In addition to being smart, they're also very nice and fun - I ended up having some fun adventures with my lab mates and am still close to many of them).* They publish at amazing conferences, collaborate with places such as MIT and Stanford (and Dartmouth), and the students intern at top graphics places in industry such as Adobe Research and Disney. I'm really honored to get to be working with people that know so much, and I've already learned a ton. They also seem to be very well-funded, and have encouraged me to attend a conference (there's a few in France/Switzerland in the next few months), which is awesome and such a cool opportunity!

I'm getting started on a really interesting project here: combining deep learning and compressed sensing, and important technique in signal processing. Here's the basic idea of compressed sensing: Normally when we acquire a signal (I'll use the example of taking a picture), we get way more data than we can actually transport, so we immediately compress it. So an image is always immediately reduced to a JPEG or another form, by finding all of the unimportant information and getting rid of it. With compressed sensing, we only acquire a small fraction of the information (so for a 100x100 pixel image, instead of getting values for all 10,000 pixels, we might just get values for 1,000 of them) through a measurement mask, and then we can reconstruct the original image. There's a lot of fascinating math that shows that we can with very high probability reconstruct the image if certain conditions hold, and we can perform these computations in a reasonable amount of time.

 {{< figure library="true" src="CS_overview.png" title="left: the measurement mask used to capture an image of a scene; middle: the captured image, with missing information; right: the reconstructed image" lightbox="true" width="500">}}


There have been some very cool results with this. One of my favorite is a paper where researchers took a single image, that to the naked eye just looks like a normal, slightly blurry photo, but were actually able to get pixels at slightly different times and then from that single photo reconstruct 30 frames for a resulting 1 second video! More recently, with the rise of machine learning, people are combining the mathematical basis of compressed sensing with neural networks to get amazing results in a lot of applications. So my research is generally within this area! I've only had one meeting for my project so far, but it went well, and I like the people I'm working with. *(It's fun remembering the beginnings of my project, now seeing what it has evolved into.)*

In terms of my daily/weekly schedule, it's pretty much what I want. We have a weekly lab meeting, and I have regular meetings for my deep compressed sensing project. Aside from those meetings, there isn't any time I am required to be in the lab, but I've found a regular schedule to be helpful. I also have a lot of flexibility to work remotely and take vacation when I want to, as long as it's not in excess, which is really nice. My daily routine is typically something like this:

- ~8:15 wake up, get ready
- 9:00 head to take the tram to work
- 9:30 get to work, say hi to everyone, and start working. This involves a mixture of reading papers, coding, data analysis, and writing, depending on what I have to do for the day.
- 1:30 break for lunch. We all go eat together and take a full hour for lunch or sometimes more. This is an early lunch by Spanish standards, but the cafeteria fills up at 2 so we try to get there before that
- 2:30 hit the coffee machine after lunch. There's a vending machine that will make you any sort of coffee/hot chocolate beverage you want (very common in Europe, we need these in America), but I prefer these machines - 40 cents for some of the best coffee! My lab mates think it's unremarkable and that the bad coffee in America has ruined my standards

 {{< figure library="true" src="coffee_machine.jpg" title="" lightbox="true" width="400">}}

- ~2:45/3, depending on how long a coffee break we take: back to work! Often around now I'll start getting distracted because all my friends/family in the US will wake up and start sending me messages :)
- 5:30 head out, though sometimes I stay longer if I have more to do
- 6:00 go to gym or go for a run!
- 7:30 make dinner, I've been trying to eat at 8:30/9 but often am hungry much earlier
- 9:00 until bedtime: sometimes more work if I have to, oftentimes reading/watching Spanish TV/talking to friends in America. Sometimes I'll go out for dinner or grab a drink with friends, which will always be at 9 pm or later

I'm loving this lifestyle. I might try to join a club or take formal Spanish lessons soon, but for now it's nice to just focus on work and then on enjoying life. I adore doing research full time. It's nice to not have to put time into classes and to be able to make doing research/learning what I need to learn for research my top priority. I love spending my days making progress on my projects and learning a TON and having freedom in what to work on. I'm learning a lot about my research style and strengths/weaknesses, which I think will be super helpful when I pursue my PhD back in America. There are definitely stressful points, when code doesn't work or something doesn't make sense, or the fact that in research you're literally trying to stretch the boundaries of knowledge which means a lot of times ideas won't pan out. *(I ended up feeling these points a lot, but nontheless really enjoyed what I did).* I'm also working on 2 projects right now, since I'm continuing a project I started at Dartmouth last year, but the intensity of Dartmouth prepared me well, and it's so nice to focus on doing fewer things but doing them well. I also really like the lab environment - I'm so happy that I ended up here!