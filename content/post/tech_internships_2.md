---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Getting a SWE Internship, Part 2"
subtitle: ""
summary: "Preparing for and nailing the interview"
authors: []
tags: [Tech Recruiting]
categories: []
date: 2020-09-05T13:00:25-05:00
lastmod: 2020-09-05T13:00:25-05:00
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

As I said in [part 1](({{< ref "/post/rec_letters.md" >}})) of this post, I started the fall of my junior year having never had an internship in the tech industry, and ended it with software engineering internship offers at Facebook, Palantir, and Microsoft, among other companies. My first post covered having a strong resume/job application, and this one will cover nailing the actual interview.

Before I dive into it, I want to link to a few helpful resources that I'll refer to throughout this post:

- [Cracking the Coding Interview](http://www.crackingthecodinginterview.com/)
- [LeetCode](https://leetcode.com/)
- [Hackerrank](https://www.hackerrank.com/)

There are a few different components to the tech internship interview process and types of interviews:

- Coding challenges: Sometimes, a recruiter will send you a link to a "coding challenge". This will often be on a platform similar to Leetcode or Hackerrank, and is a prerequisite to getting an interview. Be careful when you click on it, because this will normally start a timer. Read the instructions very carefully, since often your code will have to perform in a specific way to pass the challenge.  The best way to prepare for these challenges are to do a lot of questions on such a platform. It's also useful to ask your recruiter if the coding challenge is going to be graded by an automated process or by a human - if by a human, be sure to comment your code so that even if something is off they know your thought process
- Phone screen: Often, before getting to the interviews, you will have a phone screen. The phone screen can be one of many things - it can just be a chance for you to ask the recruiter questions, it can be a behavioral interview, it can contain a brain teaser, or it can have a full 45-minute coding question. Be sure to understand which kind of interview it will be well before the call
- Coding question interview: This is an interview where you are given 1-3 questions that you have to talk through and then write code for. This can be in-person, with coding on a whiteboard, or over the phone, with coding on a Google doc or similar platform. When applying to internships, I had 2-5 of these interviews, depending on the company. The next section will focus on preparation for this type of interview
- Team matching interview: Google has these interviews after you pass the coding interviews (I made it to this stage but dropped out after one interview because I didn't like the team and had offer deadlines with other companies), in order to make sure there's a good fit between you and the team. Some other companies also have similar interviews. Definitely take these seriously, because they can determine whether or not a team is willing to have you join them, which translates into you getting the internship or not
- Other interviews: I don't know that much about other types of interviews such as design or PM (product management), but Cracking the Coding Interview has an amazing breakdown of other types of interviews, and the author has written a separate book on applying to PM jobs

Here's how I prepared for the coding question interviews (the bulk of the interview process):

- First, I decided on the topics I needed to master and reviewed the basics of those topics by implementing data structures/algorithms from scratch. These topics included (but are not limited to - it's been a while) the following:
    - Data structures - arrays, strings, linked lists, trees, DAG, graphs
    - Algorithms - sorting, binary search, tree traversal, BFS/DFS, Dijkstra's, minimum spanning tree algorithms
    - Some bit manipulation and other topics I didn't know well, so I wouldn't be caught completely off guard if asked a question, but I didn't go too in depth on learning things I didn't really know
- Then, I nailed down a solid approach to solving an interview question that I could practice with and hone. The interview is as much testing your coding abilities as your critical thinking and communication skills, so based on knowing that, this was my approach:
    1. Carefully read/process the question, create a small example if it's not provided to help you conceptualize what you're being asked to do 
    2. Ask clarifying questions! Think of different cases you have to consider (for example duplicates, negative numbers), and ask if there are any conditions on the input you are given or the output you have to produce. Oftentimes, part of the challenge is being given a vague question and then having to nail down exactly what you are being asked
    3. Once you have a good idea of what you're supposed to be solving, come up with the first solution you can think of, even if it would be really slow or not provide a completely correct output. Describe your solution and acknowledge these limitations. Your interviewer might ask you to code it up at this point.
    4. Then, work on optimizing your solution. If the small example you created was lacking, come up with a better example to work with. Your interviewer might give you hints and that's completely okay! They want to see how you respond to their suggestions. Cracking the Coding Interview has some good strategies on how to optimize your solution using this approach
- I tried to solve many of the questions in CTCI using this approach . I went slowly, really thought things through, and read hints as needed to get a minimal working solution that I would then code up. After, I would always carefully read the solution no matter how far I got and really understand where I went wrong.
- I also solved some questions in leetcode for more practice - leetcode has a lot of good, hard questions
- I did a mix of paper coding (to emulate a whiteboard) and coding on computer in a basic text editor or Google docs - I think practicing both was very important for me since typing and writing interact with my thought process in different ways, especially when I'm also talking out loud as I code

I would also highly encourage you to practice whiteboard coding with friends! There are so many tech jobs out there and recruiters really want to see all qualified candidates succeed, so there's absolutely no reason to be competitive with your peers and not help each other. Get hints from them when you struggle and talk as you code to emulate a real interview. 
