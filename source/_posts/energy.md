---
title: Fundamentals of Energy and Power
date: 2021-06-13 15:06:42
tags:
---

In order to keep up with my blog post more frequently, I think I need to start with the fundamentals. I always feel that there are tons of resources out there that can teach electronics better than I can but at the end of the day, I have to interpret it for myself and maybe someone else interprets information the way I do. So I will attempt to explain the fundamentals of electrical engineering starting with power electronics and why it was interesting to me later in my college years.

As I've stated, I always wanted to feel that I'm contributing to something better for the world. I felt the way I could accomplish this goal is to apply my engineering skills to the real world. Moving our technology to a more sustainable and renewable world is what has always sparked my interest mainly because the effects of this has been hypothesized to change the way we live to a dystopian future if we don't do anything about it. 

As most people know, gas powered vehicles are one of the largest forms of CO2 that are emitted into  the atmosphere. I don't know all the details about the grid where electric vehicles energy source comes from so I want to solely focus on the technology behind making an electric vehicle function. Eventually, I want to be able to explain why electric vehicles weren't made before the 2000s but I think maybe for now I want to focus on the field of power electronics and power conversion because I think it has a lot to do with getting to this point.

What is Energy?
Before we breakdown the word power, it is important to first define the concept of energy because power is derived from energy over a time interval. Energy can be explained in a very broad context but one's that quickly come to mind is food giving us energy or cars getting energy from a gallon of gasoline etc. One of the most important concepts in physics that most people  probably have heard before is that energy cannot be created or destroyed. There is a fixed number of energy in the universe thus it can never disappear or be created out of thin air thus it must be transferred from one system to the next. 
We can quickly see this concept in everyday life. In order for an apple tree to grow, it must receive a combination of energy from the sun, water, and some form of air like CO2. We humans and other mammals then help the tree reproduce by picking the fruit and planting the seeds in another biodiverse area of the land. The fruit gives us energy to do the daily activities of our lives. After thousands of years, humans have been able to design cars to help us transport around the world on daily basis where the cars now receive energy from dead plants (oil). Where does that CO2 go? Into the atmosphere since the energy cannot be created nor destroyed but just transferred in a different way. 

Fundamentally, everything what's interesting of what was described is that every form of energy in some form is derived from the sun. That is our main source of life. What has happened now is that we've unbalanced the natural system that has been around for millennium on our Earth since every living embodiment transfers energy between one form to the next. This is a very conceptual way of thinking of energy but hopefully it better forms an idea of what's happening overall. 

Force 
Lead up to examples of gravity 
Picture a bowling ball sitting  in the middle of a court. What's preventing the ball from falling down into the floor? Or perhaps a better analogy is why should you avoid walking on a frozen lake? What allows us to ask these questions already implies something fundamental. The answer someone would usually say your weight itself is what's preventing you from falling into the lake. But weight itself isn't just some number on the scale. On Earth, we define this as a measurement of the force of gravity on an object. This might get a bit confusing because as a society, we usually define weight in kilograms and pounds. But scientifically, weight is measured in Newtons or the force of gravity on an object. That objects mass is what's measured in kilograms and pounds. 

So there's a few things here I want to help summarize and hopefully help breakdown.
There's the mass of the ball and one more thing I haven't mentioned is the acceleration due to gravity. On the planet Earth, if you were to fall off of cliff with no air resistance this acceleration is constant at 9.18 m/s2. This assumes we live in a vacuum or something that has no air resistance. So this is the rate of which you would accelerate towards the Earth and this is a constant due to the size of our planet. If we were on the moon for example this rate would be a lot smaller so we fall towards the moon at a slower rate since the gravitational pull is smaller. 

So we have the Force of gravity on a Ball = (mass of the ball)*(acceleration). The Force of gravity on a ball is measured in Newtons. What makes this situation unique is that the force is coming from the Earth itself but it's a fundamental concept that is always taught in mechanics because this force always has to be accounted for in many applications.

Conservation of Energy by Applying Work
Now that we understand that there's always a force being applied on every object, we can start introducing the concept of work. How does work relate to energy? Work is the transfer of energy by a force acting on an object as it is being displaced.
To give an idea of where we're going with this, work is measured in Joules and the amount of time it takes to do that work is measured in Power which is measured in Joules/sec. From there we can go into Power. 

Work itself is measured  to be Force x distance. We can use the force of gravity again as we've used before times the distance it takes to lift a ball off from the ground. Say we have two different balls: a volleyball and a bowling ball. A volleyball's mass is about 260 grams or 0.26 kg where a bowling ball can be somewhere around 5kg. The force of gravity on each ball would be the 9.81 m/s2 constant introduced earlier multiplied by the mass
Force of gravity on bowling ball = 5kg x 9.81 m/s2 = 49.05 Newtons.
Force of gravity on volleyball = 0.26kg x 9.81 m/s2 = 2.5506 Newtons.

So we can see that gravity is applying a much larger force on the bowling ball mainly due to its mass. 

What happens now if I wanted to lift each ball over my head? This is the scientific definition of work which is the action of force being exerted over a distance. I being the object applied a force equal to the force of the balls over a distance. Lets say this distance is two meters. 
Work done on bowling ball = 49.05 Newtons x 2 meters = 98.1 N*meters or Joules. 
Work done on volleyball = 2.5506 Newtons x 2 meters = 5.1 N*meters or Joules. 

As previously stated, energy can be defined as the ability to do work. When defining power we typically say the amount of energy expended on the system when explaining this concept. 

When we start to get into the analysis of power conversion, it is important to understand that most of the things we do is in reference to energy. Newtons law states for every action, there is an equal and opposite reaction.

Going very high level to climate change, our goal is the same for gas powered vehicles and electric powered vehicles. We are taking a chemical agent in gasoline and creating a combustion to drive us around for our daily lives and the same thing applies for electric vehicles. We are taking our charged up battery and converting it into electrical energy to drive our cars around. Ultimately, both are converted in to mechanical energy. The source of this energy is what we want to change. 

Now we can define power. Power is the amount of work done divided by the time it takes to do that work.
This is defined as:

Power = Work/time = 98.1 Joules / 1 sec = 98.1 Watts for the bowling ball
Power = Work/time = 5.1 Joules / 1 sec = 5.1 Watts for the volleyball

These two balls help us clearly understand that it takes more work to lift the bowling ball up 2 meters in one sec. versus lifting up a volleyball. If I wanted to lift the ball up faster say in 0.5 sec then I would need to apply more work. This whole analogy I'm providing as much work as equal to gravity but yes nothing stops me from doing something faster or applying a higher force. This is seen when I throw a ball up in the air. In those instances, I'm applying a force larger than gravity but not when It's slower.

From here we can move on to our analogy by bringing up a lightbulb rating of 60 Watts. This is the measure of energy a light bulb consumes when in operation. Typically, standard American households measure the energy used in kilowatt-hours.

So an incandescent light bulb would take roughly.

Energy = Power x time = 60 Watts x 1 hr =  0.06 kW*hr
Energy = Power x time = 216,000 Joules consumed per hour

Since we're on topic, note the efficiency provided with an LED lightbulb. Typical LEDs have a rating of about 8.5 Watts.

Energy = Power x time = 8.5 Watts x 1 hr =  0.0085 kW*hr
Energy = Power x time = 30,600 Joules consumed per hour

An LED takes up roughly 85% less energy than an incandescent light bulb. 

Kinetic Energy and the Work-Energy Theorem
I want to lead to electronics but I think it's necessary to at least understand the conservation of energy in a more conceptual way before doing so. Going back to our example of lifting a bowling ball. 

Recall: 
Work done on bowling ball = 49.05 Newtons x 2 meters = 98.1 N*meters or Joules. 
Force of gravity on bowling ball = 5kg x 9.81 m/s2 = 49.05 Newtons.

Now what happens instead once I lift the bowling ball, I place the bowling ball on a platform above my head? I have transferred energy into the bowling ball where now if that bowling ball was to fall off the platform, it can cause a lot of damage to someone or an object. This form of energy is known as potential energy. At a higher platform the bowling ball has a higher potential energy then it did when it was set to the ground. The bowling  ball is stored in a bowling ball-Earth system and can be recovered at any time. The energy it took for me to raise the bowling ball to the platform is now available in a form of potential energy.

As I'm moving the bowling ball, it has a Kinetic energy defined as:
KE = 1/2 * m* v2

Thus, Potential Energy is also now introduced by PE = mass*acceleration(due to gravity)* height.
If the object was to fall back down from the height of the platform, it would be equal to:
KE = -PE.

Recall Work =  F * d where F = m*acceleration. Thus, Work = distance*mass*acceleration
Acceleration can be defined as:

Acceleration = velocity2 - velocity02/2*d

So in total:
Wnet = m* (velocity2 - velocity02/2*d )*d or

W = 1/2 * m* v2 - 1/2 * m* v02

This makes sense because at some point as I'm raising the bowling ball, I have to accelerate it to a velocity other than 0. Thus, our initial velocity is 0 and we know what our work is, we can find the velocity that we're moving the bowling ball at.

The point here is mainly to define the relationship between Work and Energy. The transfer of energy was done from me to the ball as a form of kinetic energy. The net Work on a system changes its kinetic energy. Placing it on top of the platform is the new Potential Energy.

Thus we can summarize this with the following:
KEi + PEi = KEf + PEf

In our example, KEi was our original definition of 98.1 Joules that I'm exerting on the bowling ball where there is no initial Potential Energy defined. The KE final is zero where now final PE is also 98.1 Joules.

Thus KEi = PEf thus conserving the energy in the system. The energy is still there only if was transferred to potential energy
