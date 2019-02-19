<!-- .slide: data-background="images/network-background.jpg" class="background" -->

<h2>The Institute for Ethical AI & ML</h2>
<h4>Insights, risks and impact of AI & ML in industry</h4>
<p>
  <br />
  <br />
    Alejandro Saucedo <br/><br/>
    <a href="http://twitter.com/AxSaucedo">@AxSaucedo</a><br/>
    <a href="http://linkedin.com/in/AxSaucedo">in/axsaucedo</a><br/>
  <br />
</p>
<p>

[NEXT]
<!-- .slide: data-background="images/network-background.jpg" class="background" -->


<h2>The Institute for Ethical AI & ML</h2>
<h4>Insights, risks and impact of AI & ML in industry</h4>

<table class="bio-table">
  <tr>
    <td style="float: left">
        <br>
        ![portrait](images/alejandro.jpg)
        <br>
        <font style="font-weight: bold; color: white">Alejandro Saucedo</font>
        <br>
        <br>
    </td>
    <td style="float: left; color: white; font-size: 0.7em;">

        <br>
        Chief Scientist
        <br>
        <a style="color: cyan" href="http://e-x.io">The Institute for Ethical AI & ML</a
        <br>
        <br>
        <br>
        <hr>
        <br>
        Head of Solutions Eng. & Sci.
        <br>
        <a style="color: cyan" href="http://eigentech.com">Eigen Technologies</a>
        <br>
        <br>
        Chief Technology Officer
        <br>
        <a style="color: cyan" href="#">Hack Partners</a>
        <br>
        <br>
        Software Engineer
        <br>
        <a style="color: cyan" href="#">Bloomberg LP.</a>

    </td>
  </tr>
  <tr>
  </tr>
</table>

[NEXT]
<!-- .slide: data-background="images/network-background.jpg" class="background smallquote" -->

## Today

> The Institute & the Ethical AI & ML
> <br>
> <br>
> Intuition on AI & ML
>
> AI-enabled Cyber
> 
> Mitigations

#### Followed by a deep dive discussion

[NEXT]
<!-- .slide: data-background="images/particles.gif" class="background smallquote" -->

# #LetsDoThis

[NEXT SECTION]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

# 1. Intuition on AI, Machine Learning

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## What you've heard:

* AI is going to take your job
* It's going to create a new job for you
* AI is outsmarting all humans
* Machine learning, deep learning...
* It's going to kill us all

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## Let's go beyond the hype

The general label for a field of study, specifically
the study of whatever might answer the question of 
"What is required for a machine to exhibit intelligence"


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## There 2 main approaches to AI

* Hard coding the rules (such as what you'd do in complex excel formulas)

## or

* Building systems that can "learn the rules" by learning from examples


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## The "AI" most people refer to

The main sub-field that currently people refer to when they
talk about AI is the latter - <font style="color: #00ffda !important">**Machine Learning**</font>

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

But machine learning has been there for a long time...

## Then why the hype now?

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## Deep Learning

A branch of Machine Learning that has allowed engineers
and data scientists build systems that learn from data

#### Very <font style="color: #00ffda">very</font> large amounts of data! 



[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## In essence, all Machine Learning is:

If give you examples, would you be able to learn to give the correct answers?

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->
Given some input data, predict the correct output

![shapes](images/shapes.svg)

Let's try to build a system to predict whether a shape is a square or a triangle

## How do we do this?


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->
## First, let's visualise it

* Imagine a 2-d plot
* The x-axis is the area of the input shape
* The y-axis is the perimeter of the input shape

![classification](images/classification-points.png)

[NEXT]
<!-- .slide: data-transition="slide-in fade-out" data-background="images/partistat.png" class="background smallquote" style="color: white" -->
## We want to find a division line

<br>

<div class="left-col">
The line defined by function
<br>
<br>
**$f(x̄) = mx̄ + b$**,  where:
<br>
<br>
**x̄** is input (area & perimeter) </li>
<br>
<br>
**m** and **b** are weights/bias
<br>
</div>

<img width="40%" src="images/classification-line.png">

[NEXT]
<!-- .slide: data-transition="fade-in slide-out" data-background="images/partistat.png" class="background smallquote" style="color: white" -->
## So we can predict new data

<br>

<div class="left-col">
The result **$f(x̄)$** states whether it's a triangle or square
<br>
<br>
(e.g. if it's larger than 0.5 it's triangle otherwise square)
</div>

<img width="40%" src="images/classification-newinput.png">


<br>
<br>

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

So now let's start with a blank brain

[  ]

The machine knows nothing yet...

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->
Now let's take some data examples

![shapes](images/shapes.svg)

And let the machine do the learning



[NEXT]
<!-- .slide: data-transition="slide-in fade-out" data-background="images/partistat.png" class="background smallquote" style="color: white" -->
## The machine does the learning

![classification](images/feature-1.jpg)

We give it two examples (one square, one triangle)

[NEXT]
<!-- .slide: data-transition="fade-in" data-background="images/partistat.png" class="background smallquote" style="color: white" -->
## The machine does the learning

![classification](images/feature-2.jpg)

We give it more examples

[NEXT]
<!-- .slide:data-transition="fade-in slide-out" data-background="images/partistat.png" class="background smallquote" style="color: white" -->
## The machine does the learning

![classification](images/feature-3.jpg)

and more...


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->
## Minimising loss function

We optimise the model by **minimising its loss**.

Keep adjusting the weights...

...until loss is not getting any smaller.

![gradient_descent](images/gradient_descent_cropped.gif)


[NEXT]
<!-- .slide: data-transition="slide-in fade-out" data-background="images/partistat.png" class="background smallquote" style="color: white" -->
## Finding the weights!

<img width="40%" src="images/classification-line.png">

When it finishes, we find optimised weights and biases

i.e. **$f(x̄)$ = triangle  if ($0.3 x̄ + 10$) > 0.5 else square**

[NEXT]
<!-- .slide: data-transition="fade-in slide-out" data-background="images/partistat.png" class="background smallquote" style="color: white" -->
## Now predict new data

![classification_small](images/classification-newinput.png)

We now have a system that "knows" how to differentiate triangles from squares

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->
### But triangles and squares are boring...


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

### What do we do when we have more complex cases?

![classification_small](images/perceptron_learning4.png)

...way more complex!

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

We just need more flexible models...

...and more data...

### Much more data!

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

### Neural networks!

Remember our function `f(x) = mx + b`

<div class="left-col">
![perceptron](images/perceptron.svg)
</div>
<div class="right-col">
![line](images/classification-line.png)
</div>

This is the same function for a neuron (perceptron)

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->
### Instead of just one neuron

![rnn_diagram](images/rnn-perceptron.svg)


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->
### We just have many

![rnn_diagram](images/rnn-feedforward.svg)

This gives the function more flexibility


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->
### With a few layers

![deep_rnn_diagram](images/rnn-feedforwardlayers.svg)

This gives more flexibility for learning

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->
#### But this technology has been out there for decades!

## Why the hype now?

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->
### Deep Networks &mdash; many hidden layers

![deep_rnn_diagram](images/rnn-deepfeedforward.svg)

## Possible due to backprop!



[NEXT]
<!-- .slide: data-transition="slide-in fade-out" data-background="images/partistat.png" class="background smallquote" style="color: white" -->
![classification_small](images/perceptron_learning1.png)

[NEXT]
<!-- .slide: data-transition="fade-in" data-background="images/partistat.png" class="background smallquote" style="color: white" -->
![classification_small](images/perceptron_learning2.png)

[NEXT]
<!-- .slide: data-transition="fade-in" data-background="images/partistat.png" class="background smallquote" style="color: white" -->
![classification_small](images/perceptron_learning3.png)

[NEXT]
<!-- .slide: data-transition="fade-in slide-out" data-background="images/partistat.png" class="background smallquote" style="color: white" -->
![classification_small](images/perceptron_learning4.png)


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->


You are now an expert on Machine Learning!

# Congratulations

#### You can pick up your certificates, valid in:

* Non-technical meetups
* Twitter discussions
* Linkedin Titles


[NEXT SECTION]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

# 4. Challenges in AI


[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

## Synthetic Face Generation
<iframe width="560" height="315" data-src="https://www.youtube.com/embed/AmUC4m6w1wo?rel=0&amp;controls=0&amp;showinfo=0&amp;start=18&amp;autoplay=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

## Synthetic Voice Generation
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" data-src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/318661840&color=%23ff5500&auto_play=true&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>


[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
## Using bots on top of voice
<iframe width="560" height="315" data-src="https://www.youtube.com/embed/bd1mEm2Fy08?rel=0&amp;controls=0&amp;showinfo=0&amp;start=60&amp;autoplay=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
## And there's already a global bot industry
<iframe data-src="https://www.technologyreview.com/s/611123/inside-the-business-model-for-botnets/" style="width: 100%; height: 50vh"></iframe>


[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

## Tricking Machine Learning Classifiers
<iframe width="560" height="315" data-src="https://www.youtube.com/embed/i1sp4X57TL4?rel=0&amp;controls=0&amp;showinfo=0&amp;autoplay=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
# We could say
## AI has a Hallucination problem that’s hard to Fix...


[NEXT]
## It becomes a problem with cars...
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
<iframe width="560" height="315" data-src="https://www.youtube.com/embed/c_5EH3CBtD0?rel=0&amp;controls=1&amp;showinfo=0&amp;start=60&amp;mute=1&amp;autoplay=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


[NEXT]
## Did anyone say robots?
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
<iframe width="560" height="315" data-src="https://www.youtube.com/embed/knoOXBLFQ-s?rel=0&amp;controls=1&amp;showinfo=0&amp;autoplay=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

[NEXT]
## Or maybe drones...
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
<iframe width="560" height="315" data-src="https://www.youtube.com/embed/TlO2gcs1YvM?rel=0&amp;controls=1&amp;showinfo=0&amp;autoplay=1&amp;start=47" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

## How do we defend?
<iframe width="560" height="315" data-src="https://www.youtube.com/embed/HluANRwPyNo?rel=0&amp;controls=0&amp;showinfo=0&amp;start=0&amp;autoplay=1&amp;mute=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### Disclaimer: It's not that exciting

[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

## But Machine Learning will help

[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

## Cyberattacks are in your data

* Application logs
* Server logs
* Network logs
* Login information
* Security footage
* And more...

[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

## It's not easy to find

* There is TONS of data
* A lot of it is not structured
* It's almost impossible for a human
* Real-time alerts are required
* Anomality detection is hard


[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
## But ML allows this
<iframe width="560" height="315" data-src="https://www.youtube.com/embed/b6Hf1O_vpwQ?rel=0&amp;controls=1&amp;showinfo=0&amp;autoplay=1&amp;start=18&amp;mute=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

## Core ML Applications

* Real time optimisation / Predictive analytics
* Strategic optimisation / Forecasting
* Radical personalisation
* Data analysis from (real) big data
* Automation of operational processes
* Anomality detection
* Information retrieval
* Unstructured data processing



[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
## Data is more personalised
<iframe width="560" height="315" data-src="https://www.youtube.com/embed/pon3zOxMH8M?rel=0&amp;controls=1&amp;showinfo=0&amp;autoplay=1&amp;start=18&amp;mute=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## (Company owned by Sergey Brin's wife)
<!-- .element: class="fragment" data-fragment-index="1" -->

[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
## The public (and staff) need to be educated

[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
Would you let staff bring strangers to meetings?

## What about these?



[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
## Researchers are Expensive...
<iframe data-src="https://www.nytimes.com/2018/04/19/technology/artificial-intelligence-salaries-openai.html" style="width: 100%; height: 60vh"></iframe>

[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
## And so are cyber consultants
<iframe data-src="https://securious.co.uk/cybersecurity-experts-charge-10000-a-day-to-protect-uks-top-firms/" style="width: 100%; height: 60vh"></iframe>

[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
## AI & Cyber-intel

## Mostly in the private sector
<br>

Article: 
<a href="https://www.nytimes.com/2018/05/04/technology/facebook-artificial-intelligence-researchers.html">
    Facebook Adds A.I. Labs in Seattle and Pittsburgh, Pressuring Local Universities
</a>

<br>
### This is risky for nation states...

[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

## Regulation and public frameworks
# Are critical


[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

## But still far (e.g. GDPR)
<iframe data-src="https://www.crowdemotion.co.uk/" style="width: 100%; height: 50vh"></iframe>


[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->

“Artificial intelligence is the future, not only for us, but for all of humankind. It comes with colossal opportunities, but also threats that are difficult to predict. Whoever becomes the leader in this sphere will become the ruler of the world.”

## Can you guess who said this?



[NEXT]
<!-- .slide: data-background="images/space.jpg" class="background smallquote" style="color: white" -->
## Let's see how this fits with the industry


[NEXT SECTION]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

# 4. Next session: 
# AI-Cyber impact in industry

[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

# Overview

Analysis of applications, players and impact of AI enabled cybersecurity across sectors


[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->


## Sectors:

| | | | |
| - | - | - | - |
| Automotive | Manufacturing | Consumer | Defense |
| Agriculture | Energy | Healthcare | Pharma | 
| Public | Media | Telecom | Transport |
| Education | Legal | Programming | Construction | 
| Space | Finance | Security | | 
| | | | |


[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->


## Sectors for deep dive:

| | | | |
| - | - | - | - |
| Manufacturing | Defense | Agriculture | Healthcare/Pharma |
| Politics | Transport | Education | Finance | 
| | | | |


[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->


Assessment of impact in sector

* Availability of data
* Ripeness for disruption

[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

### Deep dive discussion
* Select one of the AI applications
* Pick an industry
* Let'As deep dive on economic dangers
* Find out key actions that could be taken



[NEXT SECTION]
<!-- .slide: data-background="images/network-background.jpg" class="background smallest" style="color: white" -->
# 5. Wrapping up

[NEXT]
<!-- .slide: data-background="images/network-background.jpg" class="background smallquote" -->

## Today we covered

> The Institute & the Ethical ML Pledge
> <br>
> <br>
> Intuition on AI & ML
>
> AI-enabled Cyber
> 
> Mitigations

#### Next session: Deep dive

[NEXT]
<!-- .slide: data-background="images/network-background.jpg" class="background" -->
### Code
https://github.com/axsauze/cybersecurity-machine-learning

### Slides
https://axsauze.github.io/cybersecurity-machine-learning


[NEXT]
<!-- .slide: data-background="images/network-background.jpg" class="background" -->

<h2>The Institute for Ethical AI & ML</h2>

<h4>Cybersecurity in an AI enabled world</h4>

<table class="bio-table">
  <tr>
    <td style="float: left">
        ![portrait](images/alejandro.jpg)
        <br>
        <font style="font-weight: bold; color: white">Alejandro Saucedo</font>
        <br>
    </td>
    <td style="float: left; color: white; font-size: 0.7em;">

        <br>
        Head of Deployed Engineering
        <br>
        <a style="color: cyan" href="http://eigentech.com">Eigen Technologies</a>
        <br>
        <br>
        Chairman
        <br>
        <a style="color: cyan" href="http://ethical.institute">The Institute for Ethical AI & ML</a>
        <br>
        <br>
        Fellow (AI, Data & ML)
        <br>
        <a style="color: cyan" href="#">The RSA</a>
        <br>
        <br>
        Advisor
        <br>
        <a style="color: cyan" href="http://teensinai.com">TeensInAI.com initiative</a>
        <br>

    </td>
  </tr>
  <tr>
  </tr>
</table>

[NEXT SECTION]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

# 6. Appendix

[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

# Manufacturing

_note_
* Predict failure and recommend proactive maintenance for equipment
* Optimize complex manufacturing processes in real time
* Predict future demand trends in supply chain
* Identify design problems in pre-production to reduce ramp-up time


[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

# Agriculture 

_note_
* Optimise growth techniques with reinforcement learning

* Optimise pricing in real time based on future market, weather, etc

* Predict yield for farming or production leveraging data

* Predict demand trends for production decisions

* Automate produciton vehicles

Examples:
Observe tech
agrosight



[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

# Healthcare / Pharma
_note_
* Automatic disease detection from sources across the body

* Continuous monitoring of health for personalised prevention

* Triage patient cases during hospital admission using patient data

* Optimise design of clinical trials, including label writing/patient selection

* Reduce experiments (ie animal testing) through big data analysis

* Identify targeted patient sub-groups that are underserved

* Reduce cost and time to market for developing medicine

Examples:
Babylon
Improbable
GKN

[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

# Politics
_note_
* Predict risk of ilicit activity or terrorism using historical crime data and other statistics

* Optimize public policy opinions by taking into account greater set of complex interactions

* Personalise public services to target individual citizens based on multi-modal data

* Optimize procurement strategy to reduce costs for large government agencies (e.g. defense)

* Optimise labor and budget allocation for publicly provided services

* Monitor and automate processes in public prisons to reduce costs

Examples:

Cambridge Analytica
AdBrain
Magic Pony Technology


[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->


# Transport 
_note_
* Optimise pricing and scheduling based on real-time demand updates (e.g. airlines, trucking, etc)

* Predict failure and recommend proactive maintenance for vehicles

* Enable autonomous road/flying vehicles to become commodatised within cities

* Open the possibility for intelligent infrastructure communicating with autonomous vehicles and trains

* Automate operational processes of loading, driving, checking, etc. vehicles

Examples:
Blue Vision Labs
Tesla / Hyperloop
Sky.ai
Five.AI


[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

# Education 
_note_
* Automation of operational tasks for teachers, staff and even parents

* Personalised education methods optimising individual learning preferences 

* Drastically increase the amount of information taught in less time

* Educational material is restructured to optimise for long-term performance

* Tutoring will be replaced with chatbots and intelligent systems

Examples:
TeensInAI Initiative
Linguimi
Coursera


[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

# Defense 
_note_
* Complex systems to enhance and counteract autonomous drones

* Intelligent automated online warfare will increase drastically

* Smart weapons will enable super-human skills in battle-field (auto-aiming, robotic extensions, etc)

* Increase psychological warfare via new communication mediums

* Strategic prediction advice when making decisions

Examples:
Palantir
Darktrace
The Eng Company


[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

# Finance

_note_
* Identify fraudulent activity using customer transactions and other relevant data

* Evaluate customer credit risk using large amounts of data

* Predit more accurate price movements based on greater amount of data

* Automate regulatory exercises by gathering and analysing structure data

Examples:
Monzo
Revolut
Transferwise



[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

## [Demo](http://e-x.io/)

<iframe style="height: 60vh; width: 100%;" data-src="http://e-x.io/">
</iframe>

[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->


A lot of this sounds good, but

#### how's it going to affect the world?

[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

# Implications
* Real time optimisation / Predictive analytics
* Strategic optimisation / Forecasting
* Radical personalisation
* Data analysis from (real) big data
* Automation of operational processes
* Anomality detection
* Information retrieval
* Unstructured data processing


[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->
# Implications
* Automation of processes and people
* New generation cybersecurity (talk 21st)
* New unsuspected national threats 
* Danger of algorithmic bias (beyond human traits)
* Disasters due to lack (and misunderstanding) of regulation
* Dangers of "staying behind" in the AI race
* Increased efficiency, reduction of cost


[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

## Jevons Paradox

<img src="images/train.gif">

_note_
In 1865, William Jevons described:

Machines that were using coal for fuel became more efficient

They needed less coal to complete a given task

Because machines were more cost effective they were before

their use became more widespread and demand rised

despite each machine requiring less coal to operate

the total amount of coal required to power machines is greater and not less

[NEXT]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallquote" style="color: white" -->

### But is this still valid?

Yes, we have seen this with electricity

But also with mobile phones, cars, computers, TVs, etc.
 

## AI Policy around the world



