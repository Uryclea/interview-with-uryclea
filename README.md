# interview-with-uryclea
Thanks for your interest in Uryclea! We're excited to get to know more about you. This repo contains enough detail about our interview process to give you a great shot at landing a job here. While we know that our process isn't perfect, it is designed to get to a point where everyone on the team has high conviction in hiring you.

## The Interview Process
We have an extremely rigorous interview process, but we're very transparent about it along the way, and want to give you the opportunity to decide at any point if Uryclea is the right choice for you. That said, we also try to make the process fun (or at least what we all consider fun!), and edifying. And you can always give us feedback if that wasn't the case.

The interview process is going to look roughly like the following:

An introductory call with a founding team member (this is usually an outbound call, given that we are much more likely to find you than the reverse, but there are exceptions to this!)

If we are all very high conviction in your capabilities after, what we will do is pay you to fly out to meet us, and work with us for a day. You have agency in this—in terms of when you can come and how long you can stay. Essentially, we'll have you go through a technical interview (most of you will come here because of that). You'll have essentially a day to work on this with us throughout a day. *We will donate the amount equaling the pay rate for this day of work to your favorite open-source project.*

Finally, we'll make you an offer and/or discuss logistics. In most cases, we'll have already discusses some of the specifics already, so this won't be full of bad surprises.
And that's "it"! You can obviously bow out at any time, and we will try to not waste your time if things aren't looking like a strong fit.

## Preparation

### Specific Practice Activities
The best practice you can do is to actually just take a few hours to build a tool, package, module, or repo from scratch. For python programmers, an easy thing to work on would be a CLI tool built in a tool such as Typer. You should try and create a CLI tool that does something like, e.g. print out a fractal in ASCII. Something complicated enough to be challenging but satisfying. Make sure you get practice with stuff like classes, list/dict comprehension, and syntax stuff like loops. That way, when you do your interview, you can focus on the problem and not the syntax.

If you are doing more ML work, you should have a strong working knowledge of Pytorch and/or Numpy. You should be able to do things like finding the argmax of a tensor along some dimension, etc. Really just standard stuff that implies that you can work "natively" in pytorch. You should also have a precise understanding of how backprop works in code as well as in theory (but we won't make you write out equations, we promise!).

If you are a front-end person, I would get a test project set up in NextJS, which is the frontend framework we use. Though you will not be required to know Next as a condition for being hired, the more you know the better your chances. Note that we aren't dogmatic about frameworks -- you will have more than enough leeway to convince us out of Next if you so choose. We're excited when people argue with us about technical decisions (seriously!) because it implies passion.

## Evaluation
- Be yourself, and don't feel expected to have to know everything. The interview is as much about reacting as it is to knowing. We judge this part through a PRD process at the very beginning and you can call it `ideation` or `system_design`.
- Our primary goal is to give you the opportunity to show off your skills. If you are good at something, e.g. a particular library, threading, async, numpy jujitsu, etc. you have the opportunity to show it off in the context of your day. 
- Did you understand the "hard part" of the problem and craft a succinct solution? We want to know if you have the ability to find clever and functional solutions to hard problems. We are not interested in whether your code is optimized beyond broad O(n) considerations. So optimizing for number of lines of code, etc. is not meaningful to us. You can always add comments to help explain what optimizations you left out for time's sake. However, understanding `trade-offs` is.
- Does your code exhibit high quality and logical structure? Did you adhere to abstractions? Do your classes make logical sense? Did you use good programming patterns?
- Can you show us how to verify your solution? Does the code run, or compile? Instructions do not need to be extreme, just some way to wrap our heads around what you've done.
- If you have any clarifying questions about your interview prompt or the interview process, please put this on private Slack channel. We do consider this as a part of evaluation and label it as `assumption_verification`.

### Stuff that doesn't matter
- Writing unit tests
- Fully-type hinted code
- Complete analysis, charts, ablations, etc.
