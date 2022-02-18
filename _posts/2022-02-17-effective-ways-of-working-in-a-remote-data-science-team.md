---
layout: post
title: Effective Ways of Working in a Remote Data Science Team
---

The last two years have seen a lot of us work from home, and a lot of us look like we will continue to do so. Working effectively has been something that we have all had issues, whether this be through not having the right equipment, various distractions around the house or not having the right processes in place in your team. Concerning this last point, tech teams have probably dealt best with this better than most. Of course, that is no surprise - people in tech are obviously better with tech than the average person, and it is also an industry that had seen remote working a common place before the pandemic. Nonetheless, this has mostly been amongst software developers, and less so amongst data scientists. A lot of this has been down to not having the correct processes, workflows and communication tools in place. In this article, I will share my thoughts on how a data science team can work remotely effectively. A lot of these tips can in fact be used for a lot of other remote roles too, both technical and non-technical.

I will split this post into four main sections: communication (how to use various communication tools to maximise productivity), workflow (how individuals carry out their work when working on projects with others), team processes (things that happen repeatedly to ensure the smooth running of the team) and review processes (deciding whether a task is complete).

## Communication

I will talk about three really useful tools but all that have slightly different roles, which a lot of people don't see. These tools are email, Slack and Zoom. Slack can be replaced by any other instant messaging tool that has both individual and group message capabilities and Zoom can be replaced by any other video calling service, although as you'll see if you read on I don't think they should be the same service.

I think it is best to think about these tools if you were physically in the office. If you would be in a meeting, then you should obviously be using Zoom. However, if you were to just go up to someone and ask them a question, then Zoom should also be used in my opinion. This is because you can get an instant response, like if you were tapping them on the shoulder in the office. If the response can wait for a couple of hours, then that is where you use Slack to avoid distraction.

What about the differences between email and Slack. In my opinion, the golden question to ask yourself is: do you want there to be an audit trail? If the answer is yes, then you should use email. Email is for messages that are to the point without discussion that can be found again easily. Slack is for quick questions/brief discussions about a project, company announcements or just keeping morale up - all things that don't need to be retrieved in the future. A piece of advice that I would add is that email and Slack messages shouldn't expect an instant reply - they can be very distracting and cause you to lose flow, and so I recommend instead just checking them periodically.

Finally, I would like to add some tips about using Slack in particular. Keep the number of channels minimal. People can easily end up creating too many channels and it can be difficult to keep track of the announcements in the channels that actually matter. Therefore delete channels once they become no longer irrelevant, for example a channel for a certain project that is finished. Another handy trick to find channels is to use prefixes - such as "team-" for specific teams, "project-" for projects and "social-" for various water cooler topics.

## Workflow

I am a big advocate of working in an agile way, and whilst a lot of this is usually focussed on processes (which I will describe below), I think it is a great tool when applied to workflow as well. My biggest piece of advice is to work on one thing at a time, and there are many tools that can help with this. Using cards on a kanban board is something that I cannot stress highly enough. This is very prominent in software development, however I think other roles can use this effectively as well. The primary critical response in using this is that it is a lot more difficult to plan the direction of the work compared to software development. Whilst this is true, planning is still vital and you should consider what direction the project could go and use kanban boards accordingly. On a card you should clearly describe why you are doing this, what you are doing and when you know that it is finished.

I'm sure most people do work on one task at a time, but I've seen plenty of people who don't, and if you are logically minded then I don't understand why not: you have a clear goal in your head of what you are trying to achieve for this task, it allows you to communicate clearly with others what you are working on, and I've found that I am a lot less likely to procrastinate when I know precisely what I am doing.

Another great thing about working in this manner is time tracking. If you are working on one thing, then you can clearly see how long you have spent working on different tasks. This is really useful information, because you can then estimate how long future tasks will take based upon how long similar tasks took before, which is one of the most difficult things when it comes to planning.


## Team Processes

A few recommendations.
* Stand Ups
* Planning/Retrospectives, admit to not being an expert on the best way of working with this.

## Review Processes

There are loads of tools that explain what a good review process looks like. The trouble I have is that there are so many, often with so many points that the review process takes longer than the actual work itself! Also, a lot of these focus on the code itself, which is of course important but I will just leave that as one main point really under "coding standards", which is up to the team to define.

The easiest way to do a review is to through a checklist and ensure that the following has been done:
* The work does what the ticket says
* Coding standards are followed
* The code is tested (where required)
* Documentation has been updated

Documentation is one of the most interesting points, this varies across different organisations, from zero documentation to more documentation that code itself! In my opinion, good documentation is multi layered. The first layer is the readme file in a repository. This should contain information of what the repository does, how to run the code in the depository and how to add new code to the repository. Ensuring that the readme is up to date is one of the most important parts of a pull request. The next layer is some kind of team wiki, such as confluence. Trying to have good team documentation is difficult, because it can become very complex as time progresses. I would suggest trying to look at it from the top down, in terms of thinking about what the team does, and then think how the current piece of work fits in to that, so that the documentation is kept up to date in a logical, tree like manner. Sketching this all out by hand multiple times is something that I have found helps in creating this.

## Knowledge Sharing

This is something that can be neglected when it comes to remote work (along with things like the social aspect of work), and its important that it isn't. You miss out on eavesdropping on background chat from the people that sit near you, which between two data scientists is probably something related to data science, as well as just the general chatter about what people are working on. My advice with this, is similar to when it comes to most things that remote working entails - try and mimic this as closely as possible.

Trying to mimic a spontaneous conversation is obviously a difficult task. And as with all conversations on Zoom, there will be awkwardness at first. But, if you are a podcast listener, then you can see that an online chat doesn't have to be awkward. There are two things that contribute to this in my view: firstly having a topic to talk about, and secondly engaging in these conversations frequently. Frequent demos satisfy this - each person in the team demonstrates something related to their work that could be of interest to the rest of the team. In a team of about six, I would suggest having these occur every two weeks, so each person gets an opportunity to present once a quarter. This can be of a wide variety, from an algorithm that someone wants to talk about, a particular library, or even something such as a new productivity tool that could be useful for the team. The presentation doesn't have to be long at all, but it can then lead to a discussion amongst everyone.

To support this I would suggest using a slack channel where people can share any interesting new concepts that they come across, possible conferences to attend or to simply ask questions and promote discussion.

## Summary

That was quite a long article, but if you've made it this far then congrats and I hope at least some of the sections may provide some use for you and your team.