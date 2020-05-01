---
layout: page
authors: ["Serah Rono"]
teaser: "Here's a summary of three themed discussions on teaching git and GitHub from December 2019"
title: "Carpentries Conversations: The Carpentries Teaching of Git and GitHub"
date: 2020-05-04
time: "09:00:00"
tags: ["Community", "Carpentries Lessons"]
---
Prompted by [various](https://twitter.com/nicholdav/status/1199699061856751617?s=20) [tweets](https://twitter.com/maddicowen/status/1195161753081929729?s=20) by our community members, and related community deliberations in The Carpentries' Slack and TopicBox in December 2020, The Carpentries Core Team saw an opportunity for broader community discussions around instructors' interest or comfort in teaching git and GitHub as outlined in our lesson programs.

 We conferred with The Carpentries' [Curriculum Advisory Group](https://software-carpentry.org/curriculum-advisors/) who agreed to facilitate [a series of Themed community discussions around The Carpentries Teaching of GitHub](https://carpentries.topicbox.com/groups/discuss/T0d0e93b3a52c01f4-M9cfd4a52ae450ae6265fdf0a/community-discussion-on-the-carpentries-teaching-of-github). This blog post summarises community input from three separate discussions in December 2019, and outlines a way forward for continued deliberations.

### Community Suggestions

The summaries in this section are the collective input of 35 + community members that joined in the December 2019 discussions. Your input is highly appreciated. 

More extensive notes from the three sessions are available in this Etherpad: <https://pad.carpentries.org/git-discussion>. A big thank you to Tracy Teal and David Yakobovitch for leading this set of Themed Discussions.

Overall, there was consensus that git addresses an urgent need for many learners, and the way the lessons introduce it provides sufficient motivation to get started. It is important to continue introducing learners to git, be it through GitHub as the lessons currently do, or via other platforms as appropriate.

These are some challenges with teaching git and GitHub that came up in the discussions, and some suggested approaches to help alleviate them:

- Lack of opportunity for learners to practice in a controlled environment makes adoption of git by new users after workshops more challenging. Suggested changes:
  - the value of repeated practice cannot be overstated, and is an important part of using git. Where possible,
    - introducing project-based assignments post-workshop i.e. let's build a website together for learners to work on after a workshop might help them understand git better, and see opportunities for application in their everyday workflows. 
    - Alternatively, providing pre-workshop resources / exercises on git might provide learners with guided time to interact with the resource before git sessions. This would allow for more in-depth discussion of challenges and opportunities for using git in the workshop.

- Git, GitHub, UI - these three entities can be confusing for new learners and are often conflated. Suggested change:
  - separate content in the git lessons into philosophy and background sections, for example, to help create a distinction early on in the lessons and paint a clearer picture

- Lack of clarity over what adoption would look like for learners in different domains sometimes delays or hinders continued use of git after workshops. Suggested changes:
  - The Carpentries should lead an exercise to collate information about the different approaches people take on in learning, and using git in their contexts
  - create a central resource containing the community-contributed use cases for git in different workflows and domains. This would 
    - give instructors a go-to set of examples to point learners to, and 
    - provide learners with references to guide them in using git to achieve different things as part of their day-to-day work after a workshop. This is especially useful where learners are not able to participate in a git-specific post-workshop project or pre-workshop exercise.
  - Set up a buddy system in The Carpentries to pair learners with others in The Carpentries community post-workshop who can help them navigate various challenges in working with git. It can be difficult for learners to know where to go to get help, so a dedicated community of git helpers could be really valuable.

- Git complexity makes it challenging for instructors to settle on an effective approach for teaching it comprehensively in workshops. Suggested changes:
  - have a more elaborate module in instructor training specifically to equip instructors with approaches for teaching git in workshops.
  - create a standalone checklist on preparing to teach git. 
  - share information from workshop feedback highlighting elements of the git lessons that people struggle with so instructors can prepare more extensively.  
  - consider adding the option for instructors to introduce git through GitHub's web interface or [GitHub Desktop](https://desktop.github.com) where GitHub is the platform of choice.

- Getting buy-in from supervisors to adopt git can be challenging, particularly where other tools are already in use for version control, etc. Suggested changes:
  - create a 'reasons to use git in your workflow' section in the git lesson or other accessible location for instructors and learners to reference.
    - For example, one common argument against using git has been that the Track Changes function in Microsoft Word and Google Docs covers ~98% of git's version control appeal. A good counterpoint to help get buy-in for adopting git might be: git allows you to keep track of changes in all files in a project centrally, rather than track changes in each file separately. Additionally, git allows you to see historical changes after you hit accept / incorporate them in a document, while with the Track Changes function, you cannot see history of changes after hitting 'accept'. 
  - Consider adding code examples to the git lessons in addition to the text examples already provided This will go a long way in showing use cases that collaborative document platforms do not cater to.For existing text examples,to make it more relevant to everyone, consider using examples like shopping lists, etc.

- Policy and Ethics. GitHub is blocked in countries that are sanctioned by the US, which means our lessons on working with git on GitHub are not equitably accessible around the world. Here are some ways to approach policy and ethical issues as they arise:
  - Actively work with The Carpentries community to determine how global technology politics and policy changes should impact The Carpentries' use of different platforms. Developing a broad rubric for how to approach these kinds of decisions will help make recalibrating fast and painless where need be.
  - Introduce a stand-alone module in the lessons on the broader topic of privacy and ethics, and best practices around these, for people looking to adopt git for use in different workflows.
  - Under The Carpentries Incubator program, invite community members to draft new lessons for working with git on platforms other than GitHub. This would afford instructors and learners the opportunity to choose which platforms to work with as they introduce git to learners. Short-term, alternative platforms for working with git can be listed prominently in the lessons.
  - In addition to other platforms available for working with git, it is important to create awareness about git-based, self-hosting options available, listing examples and a guide to self-hosting git-based platforms. For example, Toby Hodges from EMBL has had great experience with a free and self-hosted instance of GitLab, community edition, Claudia has had extensive experience  running a self-hosted and "bare" git server without a web interface at their institute and Code Refinery in the Nordics is using a self-hosted GitLab instance that is available at [source.coderefinery.org](https://source.coderefinery.org/). Tapping into these community experiences and sharing them centrally would be very beneficial for other community members.

- Some anecdotes in the lesson are difficult to understand, especially for people who first encounter these characters in the lesson- case in point, mentions of Wolfman and Dracula at the beginning of the lessons. Suggested change:
  - either, offer several anecdotes, rather than one to cater to more contexts. This can be an opportunity for community members to contribute useful anecdotes, or
  - change the existing unrelatable example to a more general one.


### Next Steps

Here is the TL;DR version on community suggestions from this set of Themed Discussions:
- Curriculum needs to be simplified and made more relevant/motivating for first time coders
- Order of Lessons (Instructors Pre-scoping)
- Update business use cases (Code vs. text)
- Interface of Git Delivery (Bash Shell, Web Interface, Software)
- Platform delivery (i.e., Github vs. Gitlab vs. Bitbucket)
- Consider: Alternative Lesson Plan with Gitlab
- Consider: New Module on Data Ethics/Privacy
- Always start with open source - git first, then platform next


From this post, The Carpentries Core Team will dissect the suggestions made, open issues for content improvements that can be made to the git lessons, and scope the rest of the suggestions to slate them for future work by the Core Team.

In the meantime, community members are encouraged to open issues in the git lessons, or use the New Ideas section of [the git-discussion Etherpad](https://pad.carpentries.org/git-discussion) to share bigger suggestions on the way forward. We will continue to share updates on decisions and progress made as a result of these suggestions periodically on The Carpentries blog. 