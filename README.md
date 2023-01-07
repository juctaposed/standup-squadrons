<div align="center">

# Standup Squadrons

</div>

The aim of this project is to contribute steps to make daily Standups becoming more self governing by the community and provide additional structure to those who might benefit from it. Particularly, reiterating important technical concepts folks may be seeing on their job hunt, while allowing the means to snowball or build their way up to more abstract concepts, and eventually perhaps provide rolling sprints for those who may be "catching up".

## Structure
Standup is currently blocks of allotted time to prep/assist folks in their hunt, structured into two parts:
>1. Q&A
>
>2. Problem Solving/Coding Challenges


### Q&A / PH
I didn't necessarily see a good way to structure roadmaps for Q&A. It is variable depending on where folks are at in the job process. A general idea is to have either Q&A (30 minutes) or PowerHour (1 hour) every week day allocated to answering questions. This could be done by one host or a panel of folks with industry experience (a weekly panel perhaps?)

### Coding Challenges
For the problem solving/coding challenge portion of standup, there can be a "behind the scenes" roadmap. Since folks aren't as likely to complete the material if a roadmap is laid out in front of them, volunteers could participate to spearhead specific areas of the roadmap

Backbone for roadmap includes Sprints, Recalls, and Hosts
        
        Sprints -> Try to drive home certain concepts in ~2 week (6-10 business days) intervals before moving on to next sprint.

		Recalls -> Review previously learned concepts (3-4 days). This allows for ancillary repetition on concepts after completion of sprints + anki. Provides progression checkpoints, and group learning to combat memory decay

		Hosts -> Folks that would PREP out and emulate how they would communicate through a predetermined coding challenge. Emphasize key talking points for general problems, specific talking points (something like gauss applying here for brownie points), overall successful communication styles.



![sprint-recall](https://i.gyazo.com/fb55c27ad030b0ebc6e1b965c3a184b4.png)
<p align="center">
  <img src="https://i.gyazo.com/f55f9c953cd910f3c6d7e57eb80fd641.png">
</p>

Mapping out the process would look something like this. Obviously the actual topics need to be set by Leon or someone with more technical expertise, but this would provide a consistent path for hitting common technical concepts seen in coding challenges while giving leeway for breaks/other things to be added.


### Spaced Repetition Planning
I don't have the magical skills of Anki - but thanks to attending lovely 100Devs standups I am familiar with utilizing the Fibonacci Sequence. A sequence that looks pretty similar to Anki's spaced repetition model...


> 0,1,1,2,3,5,8,13,21,34,55,89,144,233,377…

![:thinking:](https://images.emojiterra.com/twitter/v14.0/128px/1f914.png)

<p align="center">
Here is an extremely poorly illustrated diagram of fibonacci sprints/recall cycles represented on a calendar:
<br></br>
  <img src="https://i.gyazo.com/4ab223843c2db8955766d027a5ad0fe4.png">
</p>

<span align="center">

>Red underscore: Sprint 1 (Fundamental coverage)
>
>Blue underscore: Sprint 2 (String Method coverage)
>
>Green underscore: Sprint 3 (Array Method coverage)

</span>

Each sprint roughly represents a two week period with tight focused learning on one sprint subject, followed by 2 recalls spaced out approximately 8 and 13 days later. This isn't perfect, but we're plotting on calendars with holidays and observance, so it's not always going to be 100% flawless.

For example, Fundamentals Sprint is depicted as occuring from Jan 3 - Feb 21, consisting of

<span align="center">

>Totals Days: 49
>
>Business Days: 33
>
>Weekend Days: 14
>
>Holidays: 2 (Jan 16/Feb 20)

</span>

The general idea with Fibonacci sprints is heavy learning in the first month, focused recall in the second, and then sprint complete. This specific example increments up to Fib(9), we can branch that out higher if needed but this format provides 3 sprints to wrap up in ~2 months with decent spaces/breaks allowed in the second month. Depending on how many different types of sprints being planned, we could also have rolling sprints: 

<span align="center">

e.g.

>Jan-Feb/Jun-Jul/Nov-Dec => Fundamentals, Strings, & Arrays

</span>

That's of course constrained by number of volunteers & desired pace of concepts.

**Note** - Where would we stand on having standup on days of class (if cohort 3 is incoming)? Would we want coding challenge + q&a + class all in one day? Would it be better to space them out (e.g. Leave coding challenge on Tu/Th) ... is it too much time for folks to dedicate to one block on these days?

### Organization
To keep track of specific sprints and recalls, we can organize each roadmap into "squadrons" to organize where each squad is at on their roadmap, as well as hosts for each squad.

If we were to plan rolling sprints like stated above, We could say the following:

<span align="center">

>
>Jan-Feb => Fundamentals, Strings, Arrays => Squadron 1 - Sprint 1,2,3
>
>Jun-Jul => Fundamentals, Strings, Arrays => Squadron 2 - Sprint 1,2,3
>
>Nov-Dec => Fundamentals, Strings, Arrays => Squadron 3 - Sprint 1,2,3

</span>

This would allow folks from Squad 1 to continue onto more advanced sprints come March/April, and allow newer folks at this time to start codewars to prep for Squad 2, which would then move onto advanced sprints come Aug/Sep.
Ideally it becomes a cycle for folks to have a place to jump in alongside others no matter where they are on their journey.

This could be setup and maintained all on GitHub with their Kanban board, hosts being assigned the desired sprint under any given Squad. 

Here's a quick mock up:
![kanban-squads](https://i.gyazo.com/0a38863c30f5034433bc28017990d40a.png)

### Optimizations
If these sprints/recalls are being PREP'd out fully each time, sessions can take ~30 minutes, perhaps longer.
The opportunity to have multiple hosts could make each session longer. If resources allow, we could have 2 hosts emulating a mock interview system:

> Host 1 introduces a coding challenge that Host 2 must solve, Host 2 emphasizing PREP system and communication. Perhaps a group of hosts to add to simulation of nerves ;)

>>Personally, I found watching Leon PREPing out problems super valuable as a stepping stone to how I should be approaching them. e.g. nailing home how to think about string inputs (what characters? Num/Letters/Specials? Empty inputs?) and things of that nature was a big "ah-ha" moment for me. It might ease some peoples nerves to see how it's done in a "genuine" interview environment, calming one of many anxieties during this process... perhaps a gradual shift into mock interviews toward the end of sprints, or maybe just recalls can be mocks? Would love to hear ideas on this

 There is also the possibility of these being recorded (since this bit is purely educational, separated from Q&A) or can be kept a live experience, up to the hosts/Leons discretion. 

I love the idea of coding challenges being done on twitch. It allows for reviewing (VODs), especially for folks who cant make it live, but at the same time providing folks who can make it live to ask questions. It can also be a good way of building up the hosts' following, especially if they're part of the stream team. Q&A can be moved to Discord after the coding challenge is done - providing a 5+ min break/grace period before answering folks questions about the hunt.

### Conclusion
Hopefully this gives ideas for a system that can be set up to benefit folks on their journey and alleviate the time Leon puts in for daily standups. It can be modified in many ways, including the fib scheduling, sprint/recall/hosts setup, topics covered etc.
