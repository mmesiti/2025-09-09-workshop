+++
template = "page-with-toc.html"
title = "Questions and notes from workshop day 1"
+++



# Icebreakers
Let's test the notes with some icebreakers! :icecream:

## Where are you connecting from? How is the weather there?

- Helsinki - sunny? 19 degrees? (confirm!) +1 
- Reykjavik - rainy and 8 degrees :) 
- Karlsruhe - rainy (soon to be over) and 17 degrees
- Holar (Island) - cloudy, 10 degrees
- Lyngby (Denmark) - cloudy maybe going sunny, 20 degrees; 10 physical participants + three helpers (more in-coming).
- Prague (Czech) - sunny, 19 degrees
- Belgrade (Serbia) - sunny, 25 deegrees
- Tartu (Estonia) - Sunny!!(surprisingly)
- Freiburg (Germany) - Rainy and grey :( :+1:
- Sydhavnen (Denmark) - 20 degrees and grey
- Bergen, Norway - 14, Rainy, Standard 
- Hämeenlinna, sunny +35 ;)
- Stockholm, Sweden - Sunny 17 degrees :^)
- Manchester, UK - 14oC but sunny
- Lund, Sweden - 20C and sunny
- Chiang Mai, Thailand 33C and cloudy
- San Sebastián (Spain) - 18 C, cloudy
- Tübingen (Germany) - 16 °C, raining
- Eindhoven (Netherlands) - 14C, raining
- Berlin (Germany) - 17C sunny (somewhat rare)
- Stockholm (Sweden), sunny and partly cloudy about 20 degrees :+1: :sun_with_face: 
- Konstanz (Germany) - very cold (16) and cloudy!
- Taofeeq (United Kingdom) - 13 degree celcius and sunny here
- Gliwice (Poland) - sunny after the yesterday's storm
- Uppsala (Sweden) - 20 degrees, quite sunny :) +1
- Göttingen (Germany) - 17 degrees, cloudy :) 
- Göttingen, like the minipig model? :D 
- Mainz (Germany) - very rainy
- Oslo (Norway) - Cloudy and chilly, autumn is here!
- Madrid (Spain) - 20ºC sunny
- Quebec (Canada) - Cold and 5am
- Kiel (Germany) - 38 °C <-- are you sure? I wish -- pls no 
- Joensuu (Finland) - 19ºC degrees
- Copenhagen (Denmark) - 19 degrees Celsius
- Stockholm - 20 degrees
- Lausanne - 18 degrees
- Karlsruhe - 18 degrees, rain, =/
- Oslo (Norway) - Rainy and sad! ;) <-- Don't be sad, drink a hot chocolate! <- right!!!
- Espoo sunny :) H
- Eren (Germany) - rainy unfortunately
- Espoo- 21 degrees sunny!! 
- Lund - warm and lovely today!
- Oslo - cloudy 
- Copenhagen- windy
- Göttingen (Germany) - cloudy 20 degree Celsius 



## Have you ever wished you had a "code" time-machine to travel back in time?
Poll: Add an 'o' to the answer that applies to you

- Yes: oooooooooOOoooooooooooooo
- No: oooooOOO
- Not sure: ooo🤔o
- Yes when changes went wrong: o
- Yes: ooo 
- what if you change something so you'll never get born? 
- For code - no. For life - yes <--😂
- I wish
- Yes

## Test and ask any question you want!
1. Are you excited instructors ;) ?
2. I didnt attend the prepration sessions (installation etc), is it ok? Will I be fine? I am not completely new to the topics but only have a basic familiarity. 
     - You can follow without installing any software. Today you probably don't need to install anything special.
     - But do take a look at the installation instructions when you have time, especially if you are a bit familiar.
       - Great! thanks! 
     - And if you have any problems, just ask here :)
3. I am very exited about the workshop! I am an advanced user already, but I'd love to learn new approaches :D
   - there can be something new also for advanced users (maybe just because the tools we use evolve over time, and new features appear that we are not aware of)
   - Perfect to be a more active contributor ;)
4. By set up of conda environment, do you mean any specific environment that needs to be set up with specific packages maybe or do you just mean downloading conda?
   - https://coderefinery.github.io/installation/conda/, which means:
    1. downloading conda (best done with miniforge)
    2. install the coderefinery conda environment, which contains all the software that is needed to follow in the next days of the workshop.
   - keep in mind though that we will not strictly need the  conda environment today, for today a gitHub account can be enough

5. Is it possible to make the screen bigger? A bit
   - Working on it
6. How the changed are marked? There is some colour code?
   - typically a red background means that the line was removed, a green background means add (possibly cumbersome for colorblind people, unfortunately?) (referring to https://github.com/bast/runtest/commit/ff48b1222315b45f8b0717d7bf51b671bf737bbc)

7. Where is this repo? will we be working with this repo or recipe-book repo?
   - we are talking about an example repository. Later we will be working on an example you can actively follow


## Introduction to version control with git

https://coderefinery.github.io/git-intro/

8. Is there a limit to how much you can store on free GitHub?
   - There are different limits for different things. Typically, for code only, it is *very* difficult to hit a "size" limit (personally, I have never encountered that limit)
   - The recommended repository size is below 1 GB, and keeping a repo under 5 GB is “strongly recommended”; exceeding 5 GB may trigger a review or contact from GitHub support but is not automatically blocked
   - https://docs.github.com/en/repositories/creating-and-managing-repositories/repository-limits
   - https://docs.github.com/en/get-started/learning-about-github/githubs-plans, see GitHub Free for personal accounts
   - https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github, see Repository Size Limits
   - Storing code on GitHub is ok, storing *data* might mean that you hit the limit. There are other services where you can store/archive research data which might be more suitable than github.

9. Are the permalinks a unique concept in github/git?
   - These are a github feature, but also gitLab for example has them (also bitbucket, forgejo/codeberg)... 
   - it is a pretty standard feature that any service that display code on the web needs to have to be useful 
10. Please, do zoom in. It is impossible to read the materials. We have a room with two big screens, but everyone is forced to follow on laptops.
    - we will be more careful, thank you!
12. Can you use Git for version control in excel and word files?
    - while you theoretically could, the tooling associated with git works best with plain text files.  
    - docx and xlsx are compressed file formats (basically a zip of a folder with a few documents inside), so it is impossible to quickly compare two versions without "unpacking" (fun terminal side quest: rename with the terminal a .docx file into a .zip extension, and unzip it)
14. Can you connect easily google g-drive, colab and GIT?
    - google drive is an *alternative* to git, but only as a fileshare, with different focus (e.g., not version control). Colab files can be added to a git repository on GitHub, directly from Colab, once Colab is allowed to access your github account 
    - Short answer: there is currently no direct integration between GitHub and Google drive (or any other cloud drive). But there're always "indirect ways", e.g. https://github.com/orgs/community/discussions/120530
    - Can you rollback previous versions of code from GIT to Collab?
      - I see that one can open a notebook in colab from any GitHub repository it has access to, and on any branch (which could point at past versions - see next lessons about branches). It does not seem you can do exactly what you could do with git from the Colab interface, though - git from the command line, or the github web interface seem to give more possibilities

15. Is the font size large enough? Can you read it?
     - It looks good in my tiny 12" laptop.
     - Remember to set twitch tv video quality to "source" otherwise you will see big pixels

16. How can I configure visual Studio to git(lab) from organization/University ?  
     - When you clone a repository (we will do this later), git will remember where you cloned it from. You probably need to set up SSH keys for the GitLab account (profile picture -> preferences -> SSH Keys). You need to create the SSH key in a terminal (`ssh-keygen`).


:::success
# Break until xx:03
Relax for 10 minutes, after that some exercise!
:::

17. I should not fork the -recorded repo, right?
    - if you collaborate on the `-recorded` repo, glimpses of your activity might be streamed on twitch and recorded - just because that is the repository that we show on stream. If you want to be sure nothing of your activity will be shown on stream/recorded, then you should use the other repository.

18. What the "verified" label mean?
    - close to a commit, it means that GitHub had a way to verify that the author mentioned in a commit was, with reasonable certainty, the person that they claim to be (this is because in principle, you could configure git on your laptop to "impersonate" someone else)
19. When looking at the network graph: Why does the main branch change (from black to purple) with one user’s branch but not another? 
20. Be aware that the "search" might take some time when you forked (indexing takes time for searching?)
21. What is the difference between "changes" question 4 and commits?
    - It is the same.
23. Why do guacamole's "commit history" and "blame" differ regarding orderes? In blame one sees 6 changes in history 5?
    - They show different things. Blame shows last valid version of code, and for each line in it it links the corresponding commit when that line was changed last time.
25. My search for 'salt' results in 'This repository's code is being indexed right now. Try again in a few minutes'. What do I do wrong?
    - Nothing, but seemingly github is internally indexing the repository for faster searches, and this hasn't finished yet. So probably you just have to wait for a bit.
26. After I select some line(s), like when I want to copy link to them, I cannot deselect them. Is there convenient way to select them instead of reloading the page.
    - Where? In this document? 
    - When I open any particular file source. I can select / mark yellow one or more lines, but cannot deselect them
        - I don't think there is a "deselect" unfortunately. Seems like this is something in the github UI. Good observation though. (Exit and enter again, and the selection is gone.)
        - The selected line(s) are reflected in the URL bar of your browser: e.g. the `#L6` in https://github.com/cr-workshop-exercises/recipe-book/blob/main/desserts/pumpkin-pie.md?plain=1#L6. If you delete that from the url and reload, the highlight disappears



:::success
# Exercise until xx:34
https://coderefinery.github.io/git-intro/browsing/

I am:

done: oooooooooooooooooooooooooooooo
not trying: 
had major problems: 
wish for more time: 
:::

27.  could you share the link to the excercise questions again
     - it is on the page linked in the green box above
 
28. i can see 103 forks in description, but if i want to listed - there are only 5. Why?
     - https://github.com/cr-workshop-exercises/recipe-book/forks here you can see, by default, 6. But that is because of the visualization filters (activity, for example)
     - the 2 repository are not identical so what you have in the recorded versin is not we have the fork version, so answers are different
     
30. how your own forked repository and show us the Network graph?
    - thanks - so here we see everybody's branches, i.e. of those who have forked from the original repository, right? 
 
32. Can I get access to recorded sessions of workshop? I will be out of city tomorrow.
    - All streamed content will also be recorded and put on youtube. It will also stay on twitch for 2 weeks.

33. I thought MIT license was the one to use for code, CC is more for other materials (documents, images) [See also](https://opensource.guide/legal/#which-open-source-license-is-appropriate-for-my-project)
    - That is correct. The difference is small, but CC is intended for other materials. 
    - We have a lesson about licenses on Sep 24th (https://coderefinery.github.io/social-coding/)

34. I am not sure that my forked version of the repository has all the history of the original repository, e.g. pull requests...
    - it definitely should have all the commits. The pull requests are specific to a repository, so the pull requests to the original repo will not be visible in your fork. Issues, as well do not transfer when you fork.

35. How to see what change is proposed in the pull request?
    - This will be discussed later in detail this week

36. Now this example with license is for a very text based repository, but how about licenses for software? Creative Commons is not really recommended for code in general..
    - There will be a lesson where licenses will be discussed in detail (social coding and open software, on Sep 24) (https://coderefinery.github.io/social-coding/)

37. How should we add license to our github repo? why? and where should this license come from?
    - Licenses are paramount when you start collaborating with others. Do not write your own license, choose one from existing templates. But it's a complex issue, we will discuss that on Sep 24 (unless someone wants to chime in now).

38. If i delete a branch after i am done with a merge, will the network graph still show the branch that was deleted? 
    - The commit tree will still show the "branches", and the commit where the two "branches" (main and the other) were merged. The branch name might disappear from the network graph, but the commits will still exist

39. Do we need to submit the solutions ? if so how? 
    - Some (all?) universities can give you credit (1 ECTS). See https://coderefinery.github.io/2025-09-09-workshop/certificates/
    - If you are affilliated with a university, most likely you can convert the certificate to credit.

40. If, when you forked the repository, you clicked 'Copy the main branch only' by mistake, how can you change that afterwards?
    - you can still push other branches to your fork

41. In which situations we will create branch vs when the pull request is used?
    - when you cannot create branches on a repository because you were not given the permissions to do so, then you need to create your own fork (where you can do whatever you want) and make a pull request to the original repo
    - if instead you have "write" access to the original repository, meaning that you can create new branches there, you can do so. But very often this is not the case.

43. When we click fork, we basically get to save the "folder" as our  own to be able to do changes in it ? and the branch shows which did changes in the different "files" or created them ? i am not sure i understand the branch 
    - making a fork is basically making a copy of the repository that you own and can do everything you want about. 
    - "branches" are "chains of commits", (which each commit being a set of changes to a set of files), like the branch of a tree. BUT technically in git a *branch* is represented by the last commit on that "branch" (let's say, the "leaf" at the end of the "branch", in our forestry/gardening analogy, which is changing over time as the tree grows - i.e., we add more commits)


:::success
# Break until xx:00
Relax for 60 minutes
:::



## Introduction to version control with Git - Part 2

Continuing from here: https://coderefinery.github.io/git-intro/commits/

49. The demonstration was a little fast, so if we could slowdown the pace a little bit?
    - there will be time now to practice
50. We are having issues with the internet, the live session is not working now (Lyngby, Danmark).
    - The video will be on Twitch for a couple of days and we will upload to Youtube as soon as possible.
    - It is back (Lyngby, Danmark)!
51. How can I rename my branch?
    - you select "view all branches"  in the branch switch, and in the page that comes you can click on "..." at the end of the row of the branch you want to rename, and click on "rename"
    - Done. Thank you😊

:::success
# Exercise Until xx:35

https://coderefinery.github.io/git-intro/commits/

*If you have problems that cannot be solved easily here, please join the help zoom room - the address was communicated via mail*

I am:

- done: oooooooooo0o
- not trying: 
- had major problems: 
- wish for more time: 
:::


52. Does DTU provide 1 ects point as well? 
    - The best is to confirm with your study coordinator / supervisor that the certificate we generate can be registered as 1 ECTS. The certificate explicitly mentions that the work you have done is equivalent to 1 ECTS, and so far we have never had any university to refuse the registration of the credit. If your study coordinator / supervisor has question, please let them be in touch with us at support@coderefinery.org.
    - Yes (most likely). Please reach out to the DTU coordinators.

53. When I go to look at Network for the main branch, I do not see my new branch. Are things the way they should be?
    - It should be visible. Have you checked you are in the right repository? (Your username should be in the url)

54. when i create a new branch it says for example  ""'name of the branch' had recent pushes". so even just creating a branch, as a pushing a commit?
     - The new branch has the same last commit as the original branch. So the "recent push" is the same commit that the main branch has.
      - wow cool!

55. The network graph stays "loading", it hasnt finished after several minutes. Is this normal?
     - Try reloading. It usually doesn't take that long but depends on traffic.
     - have the same issue, guess its because there are so many forks?
     

56. If in the insight-network I see my new branch but also few other new ones, does it mean someone edited the upstream repository instead of their copy?
    - When you created the repository, did you include all branches or just main? 
    All but initially, there was only one branch, now there are a few.
- have the same "issue", never heard of the peoples names as well :D


58. Network is taking forever to load.
    - this is a known problem, sorry.

60. I failed at the new tag excercise :/ What does it mean "for on of the commits"? Is the tag pinned somehow to the commit? How to do it?
    - A tag is basically a name you give to one commit. For example, if you want to call a particular commit in your history "version 1.0", you could do that by adding a tag.

62. Where did Sabry find the must-have content for the new file? Could my file lacking this content mean that I can't see my branch on Network for the repository?
    - I think it came from a section below the exercise in the notes.
    - The content should not affect the branches on the network. But maybe the commit did not happen correctly?
      - check the history of the branch you created to make sure that the commit did happen

62. When trying to make a tag and associate it with a commit, for some reason the newer commits are not available on the list that is provided by GitHub. Is there a fix around it? Do i have to wait for some time before they become available?
    - GitHub is usually quick. Did you reload the page to make sure?
    - i refreshed once or twice. the tag button is also bugged for me now and it will not allow me to create a new tag for some reason... 
    - Is this your repository? Can you check that the URL contains your username? Something like github.com/USERNAME/recipe-book
    - yep i am on the url you just described, go figure...
    - I actually cannot create a tag either right now... Let's see if Sabry can :)
    - okie : ) Well it appears we found a work around : ) Yes i am doing the same steps as the presenter and this method works. the plain tag does not still work though
        - Same here :)

63. Do I need to accept a push request for my branch to be visible? Will that mean I commit? I cannot currently see the new branch I created.
    - You will not need to do anything - yet - with pull requests.
    - Can you see the branch in the list of branches? 
    - No.
    - Then the branch creation was not successful, you might have to do that again?
    - No.
    - No, I can see the branch along side the main branch. I just can't see it in Network. 
    - The network view is notoriously problematic, unfortunately.
    - Try to update the page maybe?

64. How to merge new branch with the main one?
    - good question. We will see this next.


65. can you repeat the step for the compare again please?
    - As written in the solution of the exercise:
      - to compare two branches, go to your repository (e.g. https://github.com/USER/recipe-book) and add `/compare` to the end of the URL
      - https://github.com/USER/recipe-book/compare/branch1..branch2 for arbitrary commits
    - Seen. Thanks

:::success

# Break until xx:11

:::

66. When making two thing separately (e.g. glasses and hat), who is making sure these two do not conflict in the end when moved back to main branch? Is there a way upfront to make sure this doesn't happen?
    - Modifying different files, or different parts of the same file, should not result in a conflict. But the absence of conflicts is not enough to ensure correctness: a merge in a codebase can introduce easily bugs even if there are no conflicts.

67. Why do make a change to a recipe on own fork, and then make a branch and add a new recipe.  Why not just add a recipe to our branch directly?
    - Well, we are practicing making a branch. But the reason for using a branch usually would be so that others can make changes at the same time and we can later merge them. In a more complicated case this would be necessary.

68. When doing Insights and Network; is there a way to filter so I only my own changes?
    - Not exactly filtering, but if you click on a username the view changes by bringing that user on top of the graph https://github.com/cr-workshop-exercises/recipe-book-recorded/network (e.g. click Sabryr)

69. Can we also have a brief introduction to a landing page of our Git account (all those icons, etc.)?
    - Interesting consideration! Thanks for the suggestion.

70. What is the history behind naming "pull request" (why not "merge request" instead because the direction seems make more sense)?
    - the reason why it is named this way is that it does not need to be a proper "merge", in the git sense. It cannot be a "push" because we do not have write access to the remote repository. It must be a request to the owner of the remote repository to pull from our repository. So it's called "pull request".
    - when instead we do have the privileges to write on the remote repository, then we can create a branch there, and then we can as the maintainers to "merge" (they could theoretically do other things to integrate our work). 
    - On GitHub these are called "pull request"s anyway because of the similarity. On GitLab insI tead the "merge request" term is used (at least when working on the same repository)



71. When I try to merge, i got this: ""T IhisHI can't get to merge  branch has ct must be resolved""
     - This means that both branches (your branch and the main branch), have modified the same file. Someone would need to manually decide which changes to keep.
     - Check that the target branch in the pull request is correct. 

73. What happnes when we click close with comment?
    - Closing a pull request means it will not be merged. 

74. What can be a reason to not delete a branch that you have merged with the main branch? 
    - You might want to keep developing on that branch. Not necessarily the best idea: while it is possible to create infinite branches with git, it is best to keep the number of branches to a minimum for clarity. In some situations it is unavoidable to have a number of independent branches in a repository

75. Note: to check ssh is configured correctly, you should use `ssh -T git@github.com`

76. Can you comment on using GitHub desktop vs. command line?
    - command line: more transparent and powerful
    - github interface: less transparent, probably easier to use for the most common use cases


## Feedback

:::info
### News for day 1 / preparation for day 2
- Today, we covered everything in the schedule: the basics of git version control and various aspects of the GitHub user interface.
- **Day 2 moves to your local computer**. If today was too boring or easy for you, don't worry!  Day 2 gets to the way we really work.
- For day 2, If you plan to do the exercises please make sure you have a **working git installation in your computer** (e.g. with VS Code or with the shell terminal, see instructions at https://coderefinery.github.io/installation/).o
    - **GitHub account**
    - VSCode (recommended, if you don't know what to do) OR git from the command line
- If you had/have issues with the installation, **we will provide a 1h support zoom session tomorrow morning 9:00 CEST (Oslo/Rome)**. More info in the email later today. Let us know if this is useful with some emojis :heart_eyes_cat: <3
- Twitch will store this video for 7 days, and hopefully it will be on YouTube by the time that expires.o
- **Day 3 is when we will collaborate together** and we will send you detailed instructions on how to do that via email later today.
:::

Today was (vote for all that apply):
- too fast: 
- too slow: 
- right speed: ooooooooooooooo
- too slow sometimes, too fast other times:ooo0o
- too advanced:
- too basic: oo
- right level: oooooooooooooo
- I will use what I learned today: oooooooooooooooo
- I would recommend today to others: oooooooooooooooo
- I would not recommend today to others: 

One good thing about today:
- Someone accidentally asked to merge their branch with mine, so i think i just made a new friend : ) :heart_eyes_cat: 
- Always new things learnt :heart_eyes_cat: 
- This collaborative document is really sweet! yes!yesss! +2
- the exercises walktroughs are helpful
- I really appreciate the professional stream, and how quickly you fixed all minor issues! Very cool to see. +2
- very interesting! i didn't know any of this stuff before :) - Me neither! +2
- I manage to follow and practice
- Interesting to participate! 

One thing to improve for next time:
- font size is sometimes a bit small, for example the github pages fonts were too small on big screens, but notes and course material were fine.
    - We'll try to raise this directly by voice in the future, so it doesn't go on so long.  Thanks for the feedback.
- Materials used during lecture by teachers looked not clear (i.e. not prepared especially and only for lesson). Everything that is not related to lesson should not be present. It looked like they did some things prior and looked messy. Yeah, that's my feeling. It was good but quite messy.
- There was extra steps compare to the ones in the materials so sometimes it was hard to follow some exercises.
- Try not to hide the URL of the current web page with the presenters camera view

Any other feedback?
- I like the platform you use for presenting :D +3
    - Thanks!  It's been developed over a long time.
- We should have more time to discuess during excerises. Those real talks with lecturers were nice, better than passive listening.
- It's hard to follow the lecture and check the notes, the materials and the practice screen.
    - Yes, it's a lot!  Unfortunately it is.  I'd recommend strategically closing less important stuff depending on how much you are focusing on the main stream.  We have stuff for many different levels, you can adapt to what is right for you, don't worry.
- Answering questions here on the spot was really good.

General questions continued:
- I have VS code - is that okay?
    - Yes, you also need it linked to Github but that should be almost automatic tomorrow.  We should use VSCode for most examples tomorrow.
- Our next session is the day after tommorow, right? I am asking because it is being said tommorow in the session.. 
  - It should be tomorrow (24 hours after today started).
- I am not a university student, therefore I do not need the ECTS. However, may I still ask for a certificate after the course ends? +2 to this!
    - We do not provide certificates for non-university-affiliated individuals because our trainings are in support of academic activities of our partner organisations. We are happy that you find this useful of course, and if you want feedback on your activities we are always happy to provide it. Please get in touch if you want to clarify.
    - Note that certificates are also available for postdocs, professors, IT support at university/research institutions, etc...
- students can get ECTS?
   - https://coderefinery.github.io/2025-09-09-workshop/certificates/


