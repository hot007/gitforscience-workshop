# git for science

A workshop about how to use git for managing science tasks. Or 'how to spend less time hunting for the last working version; and keep track of collaborative works'

nb EGU timeslots are 1.5 hours but we can ask for as long as we need. How long should this course be? 3.5 hours?

### workshop overview and goals [10min]

What is revision control? Why should we use it as scientists?

Learning expectations:
1. Have an understanding about how version control can help you
2. Create a repository
2. Push and pull content to the repository
4. Pull a specific version of content
5. A short practice at community collaboration

### git overview [15 mins]

- what is revision control?
- What is git?
- installing git (make this a prerequisite? - no, demo it here, install during the workshop when people can see the value if they're not already users)
- ways to use git
    - command line (this workshop)
    - GUI (provide links), e.g. gitk, SourceTree (bitbucket), GitKraken, Git Cola. Also see [this list](https://www.cloudways.com/blog/best-git-gui-clients/) (considers OS).
    - familiarity with browser interface
    
### case 1: your awesome science function [30 mins]

- working with code:
   - create a repo
   - push code
   - make local changes
   - commit revisions
   - tag working versions
   
### case 2: your Nature Geoscience paper [30 mins]
   
- construct a paper in a revision friendly way (need help here: I can see how LaTeX would work here.. or markdown.. anything else?)
- push your changes
- work with a collaborative team
- **Hint**: use [Git Large File Storage](https://git-lfs.github.com/) for binary files (PDF, images, ...).
- **Hint**: use [draw.io](https://www.draw.io/) to generated diagrams stored on GitHub. 
- **Note**: private repos on GitHub are [free for academic research](https://help.github.com/articles/applying-for-an-academic-research-discount/). 

### discussion [20 mins]

For example, 'I like git but github's corporate policy is awful.. how can I do revision control?' (eg gitlab instance, uni-hosted repos etc). In my day to day life I use locally hosted git instances, and you'd probably want to do that for your Nature Geoscience paper too...

### ideas
- use this repo to work on examples
- existing materials - happy to use them if you're happy to share them!
- When to use a branch
    - avoiding conflicts from multiple developers
    - Trying out ideas without touching master
    - what to do when you can't commit your change (e.g. use of stash)
    - remember to pull master before you do anything there
    - branch merging
    - what to do when you get into git chaos
    - help from git ninjas appreciated - especially in branch merging (something we could demonstrate here... but that may be too much)

### format?
- short course (2 hrs I think?) or splinter session



