class: center, middle

# Internet of Robots

## What's beyond IoT and M2M?

---

# Who Am I?

- Aaron Kondziela
- Technologist and Serial Entrepreneur
- Hardware & Software Hacker
- Working on IoT lately

* @aaronkondziela
* aaron@openrobotics.company

???

I'm Aaron Kondziela, technologist and entrepreneur.

I hack hardware and software, and sometimes people.

I've been working on the IoT lately, and I want to share my thoughts with you.

You can find me on the Internet, Google knows where.

---

# What's the Plan, Here?

- Beyond IoT and M2M

- Current state of the arts

- Challenges we face

- How to get to the future

- Robots!

???

Beyond IoT - not even there yet

State of Art - beta, demos

Challenges - scaling, distributed systems, solving real problems

How to get - I have some ideas on how to get there

Robots - You'll see what I mean by robots

---

# What is IoT and M2M

- IoT -> Internet of Things

???

First let's clarify what these mean

Most have heard the term IoT

It's a terrible name

It has a bad reputation

---

Image of "smart fridge" with note on display reading, "why the fuck does my fridge need twittr?"

???

This is what people think of when they hear IoT

---

# What is IoT and M2M

- IoT -> Internet of Things

???

Does it mean anything useful?

Or is it just an industry buzzword?

I take it to mean...

--

- _Small things that were once economically infeasible to connect_

???

We can afford to stick a chip into everything

--

- M2M -> Machine to Machine

???

Also hear this term

Often used in industrial contexts

--

- _Small devices communicate with each other, creating useful behaviour_

???

This is how I interpret it

Different than client-server cloud models

---

# What's the state of IoT?

???

in many ways, it's seen as bad

--

- A bunch of demo-quality "products"

- Solutions looking for problems

- Nebulous value propositions

- "AI" that feels like a parlor trick

???

Demos - solutions that don't work or scale

Solutions - not sure what to do with them, lack of imagination

Nebuluous - Like that refrigerator we just saw, wtf?

AI - Amazon Alexa. Not yet reached artifical general intelligence.

Constitution of the united states - of america

Useful in constrained environments

---

class: center, middle

it has a bad rap because...
# _We're not there yet._

Still a nascent industry

???

Of course it has a bad rap

The promises of IoT have not yet delivered

We need to build it out so that it does, because it can

---

# Getting There

- 21 billion devices by 2020. (Gartner, Nov 2015)

- IPv4 has ~4.2 billion addresses

- Traditional architectures can't handle it

???

LAMP stack not gonna do it

--

- _\#1 issue will be Scaling_

???

Scaling is very hard

We are only just learning how to do it well

We don't have good tools to manage scale yet

The data will be unimaginably big

---

# Really Big Data

- 21bn messages per second

- 0.000006bn msg/sec from Twitter

- - 7 orders of magnitude

- What about images and video?

???

Imagine if these 21bn devices were all sending telemetry

Twitter firehose is irrelevant in comparison

Data can get a lot larger than temperature in your back yard

Imagine when we have video, HD, 4K, 8K streams

There is no way to handle all that with most architectures we have now

---

# Really Big Data

- That much traffic looks like DoS attack

- Systems must be distributed, not central

???

Imagine a pyramid, 21bn on bottom, database on top

Traffic would look like a giant Denial-of-Service

You cannot centralize processing of data from 21 bn devices

...How do we handle it, then?

--

- Processing and storage at the edge

- Intelligent behaviour at the edge

???

Processing and storage to the edge, where it scales linearly

a layer up use hubs or devices to aggregate

Needs intelligent behaviour at the edge M2M

...Trouble is...

--

- _Very few people know how to build systems at this scale_

???

This is not a common skill set outside of a few architects at a few large web companies

---

# Where'd My Device Go?

- You are the product

- You don't own your data

- Your device relies on the cloud

- They can just turn it off

???

In the current state of affiars, we have another problem.

You are the product - value is derived, by someone else, from data you generate

You don't own that data, ofent cannot even access it.

Your hardware relies on connectivity and cloud services that can be turned off at any time, when you are no longer perceived as profitable

To derive real value, we need to have this tech tightly wired into our lives. But we can't trust it enough to do that, if it can just go away.

--

- _We need more options_

???

For all this to really work, we need more options

---

# What About The Robots?

???

I said robots. Where are the robots?

You probably think of something like this...

---

Image of Honda's humanoid Asimo robot

???

Or this...

---

Image of humanoid cartoon robot

???

Or maybe even...

---

Image of industrial robot arms on an automotive assembly line

???

industrial robot

---

Image of a Roomba vacuum cleaner made by iRobot

???

Or possibly this. Which is a bit closer to the mark, but still not what I mean.

---

# What About The Robots?

- _Robot_ meaning _Automated System_

- They are already everywhere

- The best ones are invisible

- Parts and economics are falling into place

???

A robot is any automated system with complex behaviour

It's everywhere. You have one in your pocket or bag right now.

You have one in your car

The best ones are invisible, and just work

This is being driven by economies of scale, and really cool hardware coming out of cellphones and consumer electronics.

--

- _We're about to see a major surge_

???

...About to see a surge!

---

Image of a typical smartphone

???

phones are everywhere, of course, and they practically run our lives.

---

Image of a Nest connected thermostat

???

we have connected devices with some built-in smarts, like the Nest

but it could be turned off suddenly!

---

Image of a Pebble smartwatch

???

we have robots strapped to our bodies

and sometimes don't know what to do with them

Remember that failure of imagination I mentioned?

---

# A Hardware Renaissance

- Hackers reborn as makers

- Components are amazing these days

- Ubiquitous connectivity and processing

- Economies of scale

???

Once upon a time, hackers hacked on hardware, but it went out of style in the 2000's

Hardware is hard, and we had a generation that didn't grow up learning it

It's coming back. Components are amazing and powerful. Maker movement is driving interest.

Connectivity and processing is cheap and everywhere

--

- But _hardware is still hard_

???

...but hardware is still HARD

So how do we get more robots? How do we make our lives better with them?

---

# Want More Robots?
### Open Systems Win - Make More!

- Open games (Doom, Quake)

- Open software (GNU Linux)

- Open Hardware (Novena)

???

I say we need more open systems.

Open systems have proven very successful, starting with games that could be modified

Software like linux that could be examined, learned, changed

And now, we are starting to see hardware like the Novena, and other projects

--

- _Empower people to own their data and hardware. Help them tinker and invent._

???

...the point is to empower people to own their data and hardware. Help them tinker and invent.

To do that we need TOOLS

---

# Want More Robots?
### Make Great Tools!

- We build software from sand and pebbles, but we need bricks

- Big software tools could be much better

???

Make great tools!

The way we build software and hardware today is terrible. Sand, when we need bricks. Prefab concrete.

We have big software tools, but they are a mess in many ways.

--

- _Good hardware tools are rare_

...good hardware tools are rare. Almost none. We need to fix that.

How?

---

# Want More Robots?
### Teach People To Make Them!

- Learn and spread good engineering

- Study and teach distributed systems

- Work with the amazing tech we have

???

Learn and spread good engineering principles. fundamentals.

Study distributed sytems. Teach what you learn. Invent new ways to do this stuff.

It's not easy and we need to try many approaches and ideas.

Dive in and work with the tech. Push it.

--

- _Use your imagination to solve problems_

???

Use your imagination. Solve problems.

---

# Why Make Robots?

- Humans make tools. Robots are powerful tools

- Market forces are driving it, good timing

- Opening it up will drive it forward

???

Humans make tools. Robots are powerful tools to make our lives better.

The market is primed and ready, so it's a good time to start working on this stuff.

Making it open, will get more people into it faster. And will create better solutions.

--

- Robots are cool : ) Make more!

???

Plus, robots are cool. So make more!

---

class: center

Image of a robot with questions, drawn by Vintango (a local Buffalo artist)

The End! Questions?

