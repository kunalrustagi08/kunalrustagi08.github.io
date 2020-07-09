---
title: My first hackathon at HackJaipur
published: true
mathjax: true
---

Hackathons: A place to learn, network, meet brilliant minds, have fun and of course, get freebies :P  
I am writing this blog to describe my experience at a recently conducted remote hackathon at HackJaipur.  

# HackJaipur?? hmm...
HackJaipur is a community-focused virtual Hackathon, designed especially for the needs of the communities, with problem statements centered around the community itself. Whether you are a beginner or an expert, here is the perfect chance to hone and show your skills and witness the competitive yet inclusive developer community around you! 

<img src="/assets/post-2/hackjaipur.jpeg">

# What interested me to take part?
Having never taken part in a hackathon before, I was eager to know how is it conducted and what can be done. Due to the covid-19 pandemic and lockdown in India, I had a good opportunity to take part in this hackathon. My main aim was to build a project centered around python as it is the language that I feel comfortable with.  

# Team building
I didn't know where to begin!! Gladly, the moderators were kind, helpful and guided me on my journey. I posted my skills and my final team stood as follows:

- [Pradeep Pradyumna](https://github.com/pradeepradyumna)
- [Shivam Sherkar](https://github.com/ShivamSherkar23)
- [Harshavardhan Surisetty](https://github.com/harsha-iiiv)

# Themes
There were four themes offered:  
1. Diversity
2. Remotely Working
3. Tech and Health 
4. Creating Awareness

Many ideas from face mask detection to a social distancing application were discussed, but we finally settled with building a Workspace Monitor System.

# Project details
I will just summarize the main features here. The full description for the project can be found at [WorkspaceMonitorSystem](https://github.com/pradeepradyumna/WorkspaceMonitorSystem/blob/master/README.md).  
* We used the code for building an autotimer from this [link](https://github.com/KalleHallden/AutoTimer) as our base. The autotimer tracks the time spent on each application and stores the data in a `JSON` format.  
<img src="/assets/post-2/json_data.png">

* Next, we tried to incorporate a notification system for the application. For instance, many a times we tend to forget the amount of time we spend on Facebook/ Instagram or Youtube. So, it was necessary to add notifications highlighting the amount of time spent. This was achieved by using the `plyer` python package. 

* Finally, we built a dashboard to visualize the logs. For this, firebase integration was necessary to send the data to a server.  
<img src="/assets/post-2/dashboard.png">

# Future additions?
We believe that these features are the most essential to make the system more effective.
* Addition of a total time key in the `JSON` data for each application navigated. This would help us to enhance our notification system by showing the overall time spent and not the current time spent.
* Building a login feature to improve security. Should be accessed by IT personnel and admins only.  

Many features can be added and are found [here](https://github.com/pradeepradyumna/WorkspaceMonitorSystem#future-scope).

# Video tutorial

<div class="embed-container">
<iframe width="500" height="315" src="https://www.youtube.com/embed/TSFS25x0Rfw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

# Things I learned
* It is important to participate in hackathons, even if you are a beginner. I would always shy from participating in such events as I believed that you need to be a super developer. No!! Hackathons are meant to learn new technologies from teammates, other teamsn and experienced mentors.
* The desire to solve real world problems.
* Don't be afraid to reach out to mentors for help.
* Acknowledge your small wins and learn from mistakes.


### In the end, I would just like to say that it was a valuable experience for me, made new peers and learnt a lot. I look forward to participate in many more hackathons :)  
---
P.S: Please let me know if there any typo-errors or you want to provide feedback that would help me to improve my blogs.  
Shoot me a mail [here](mailto:rustagi.kunal@outlook.com?subject=[GitHub%20Page]%20Blog%20on%20HackJaipur). I would really appreciate any positive or negative feedback :D