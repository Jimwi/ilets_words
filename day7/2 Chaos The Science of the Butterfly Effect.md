https://www.youtube.com/watch?v=fDek6cYijxI&ab_channel=Veritasium 

```  
hallmark     n. 特点；品质证明
prominent    adj. 重要的，著名的；显眼的，突出的；突起的，高耸的
diverge      vi. 分歧；偏离；分叉；离题
fascinate    v. 深深吸引，迷住；深深吸引，迷住；<旧>（尤指蛇）以眼神震慑（人，动物），使无法动弹        
repel        v. 击退，驱逐；抵御，驱除；使厌恶，使反感；抵制，不愿接受；排斥，相斥
manifest     v. 显示，表明；（鬼魂或神灵）显灵，出现；（病症）显现；把……列入货单
convection   n. [流][气象] 对流；传送
utter        adj. 完全的，彻底的
blow  
decipher     v. 破译，译解；辨认，解释，理解
indecipherable  adj. 无法解释的；破译不出的；难辨认的
authentic    adj. 真正的，真实的；可信的  
coincide     vi. 一致，符合；同时发生  
consequent   adj. 随之发生的，由此引起的；（河流，山谷）顺向的    
```

Chaos: The Science of the Butterfly Effect 

WEBVTT Kind: captions Language: en 

Part of this video is sponsored by LastPass. More about last pass at the end of the show. 

The butter fly effect is the idea that the tiny causes, like a flay of a butter fly's wings in Brazil, can have huge effects, like setting off a tornado in Texas. Now that idea comes straight from the title of a scientific paper published nearly 50 years ago. and perhaps more than any other recent scientific concept, it has captured the public imagination I mean on IMDB there is not one but 61 different movies, TV episodes, and short films with 'butterfly effect' in the title, `not to mention` prominent references in movies like Jurassic Park, or in songs, books, and memes. Oh the memes in pop culture the butterfly effect has come to mean that even tiny, seemingly insignificant choices you make can have huge consequences later on in your life and I think the reason people are so `fascinated` by the butterfly effect is because it gets at a fundamental question Which is, how well can we predict the future? Now the goal of this video is to answer that question by examining the science behind the butterfly effect so if you go back to the late 1600s, after Isaac Newton had come up with his `laws of motion` and universal gravitation, everything seemed predictable. I mean we could explain the motions of all the planets and moons, we could predict eclipses and the appearances of comets with pinpoint accuracy centuries in advance French physicist Pierre-Simon Laplace summed it up in a famous thought experiment: he imagined a super-intelligent being, now called Laplace's demon, that knew everything about the current state of the universe: the positions and momenta of all the particles and how they interact. if this intellect were vast enough to submit the data to analysis, he concluded, then the future, just like the past, would be present before its eyes. This is total determinism: the view that the future is already fixed, We just have to wait for it to manifest itself I think if you've studied a bit of physics, this is the natural viewpoint to come away with I mean sure there's Heisenberg's uncertainty principle from quantum mechanics, but that's on the scale of atoms; Pretty insignificant on the scale of people. `Virtually`, all the problems I studied were ones that could be solved analytically like the motion of planets, or falling objects, or `pendulums` and speaking of pendulums I want to look at a case of a simple pendulum here to introduce an important representation of dynamical systems, which is phase space. so some people may be familiar with position-time or velocity-time graphs but what if we wanted to make a 2d plot that represents every possible state of the pendulum? Every possible thing it could do in one graph. well on the x-axis we can plot the angle of the pendulum, and on the y-axis its velocity. And this is what's called phase space. If the pendulum has friction it will eventually slow down and stop and this is shown in phase space by the inward spiral -- the pendulum swings slower and less far each time and it doesn't really matter what the initial conditions are, we know that the final state will be the pendulum at rest hanging straight down and from the graph it looks like the system is attracted to the origin, that one fixed point so this is called a fixed point attractor now if the pendulum doesn't lose energy, well it swings back and forth the same way each time and in phase space we get a loop the pendulum is going fastest at the bottom but the swing is in opposite directions as it goes back and forth the closed loop tells us the motion is periodic and predictable. anytime you see an image like this in phase space, you know that this system regularly repeats we can swing the pendulum with different `amplitudes`, but the picture in phase space is very similar, just a different sized loop now an important thing to note is that the curves never cross in phase space and that's because each point uniquely identifies the complete state of the system and that state has only one future so once you've defined the initial state, the entire future is determined now the pendulum can be well understood using Newtonian physics, but Newton himself was aware of problems that did not submit to his equations so easily, particularly the three-body problem. so calculating the motion of the Earth around the Sun was simple enough with just those two bodies but add in one more, say the moon, and it became virtually impossible Newton told his friend Haley that the theory of the motions of the moon made his head ache, and kept him awake so often that he would think of it no more the problem, as would become clear to Henri Poincaré two hundred years later, was that there was no simple solution to the three-body problem Poincaré had glimpsed what later became known as chaos. Chaos really came into focus in the 1960s, when meteorologist Ed Lorenz tried to make a basic computer simulation of the Earth's atmosphere he had 12 equations and 12 variables, things like temperature, pressure, humidity and so on and the computer would print out each time step as a row of 12 numbers so you could watch how they evolved over time. now the breakthrough came when Lorenz wanted to redo a run but as a shortcut he entered the numbers from halfway through a previous printout and then he set the computer calculating he went off to get some coffee, and when he came back and saw the results, Lorenz was `stunned`. The new run followed the old one for a short while but then it `diverged` and pretty soon it was describing a totally different state of the atmosphere. I mean totally different weather Lorenz's first thought, of course, was that the computer had broken Maybe a `vacuum` tube had blown. But none had. The real reason for the difference came down to the fact that printer rounded to three decimal places whereas the computer calculated with six So when he entered those initial conditions, the difference of less than one part in a thousand created totally different weather just a short time into the future. now Lorenz tried simplifying his equations and then simplifying them some more, down to just three equations and three variables which represented a toy model of `convection`: essentially a 2d slice of the atmosphere heated at the bottom and cooled at the top but again, he got the same type of behavior: if he changed the numbers just a tiny bit, results diverged dramatically. Lorenz's system displayed what's become known as sensitive dependence on initial conditions, which is `the hallmark of chaos`. Now since Lorenz was working with three variables, we can plot the phase space of his system in three dimensions. We can pick any point as our initial state and watch how it evolves. Does our point move toward a fixed attractor? Or a repeating loop? It doesn't seem to In truth, our system will never revisit the same exact state again. Here I actually started with three closely spaced initial states, and they've been evolving together so far, but now they're starting to diverge From being arbitrarily close together, they end up on totally different `trajectories`. This is sensitive dependence on initial conditions in action. Now I should point out that there is nothing random at all about this system of equations. It's completely deterministic, just like the pendulum so if you could input exactly the same initial conditions you would get exactly the same result the problem is, unlike the pendulum, this system is chaotic so any difference in initial conditions, no matter how tiny, will be `amplified` to a totally different final state It seems like a paradox, but this system is both deterministic and unpredictable because in practice, you could never know the initial conditions with perfect accuracy, and I'm talking infinite decimal places. But the result suggests why even today with huge supercomputers, it's so hard to forecast the weather more than a week in advance. In fact, studies have shown that by the eighth day of a long-range forecast, the prediction is less accurate than if you just took the historical average conditions for that day and knowing about chaos, meteorologists no longer make just a single forecast instead they make `ensemble` forecasts, varying initial conditions and model parameters to create a set of predictions. Now far from being the exception to the rule, chaotic systems have been turning up everywhere. The double pendulum, just two simple pendulums connected together, is chaotic here two double pendulums have been released simultaneously with almost the same initial conditions. but no matter how hard you try, you could never release a double pendulum and make it behave the same way twice. its motion will forever be unpredictable you might think that chaos always requires a lot of energy or irregular motions, but this system of five `fidgets` spinners with `repelling` magnets in each of their arms is chaotic too At first glance the system seems to repeat regularly, but if you watch more closely, you'll notice some strange motions a spinner suddenly flips the other way Even our solar system is not predictable a study simulating our solar system for a hundred million years into the future found its behavior as a whole to be chaotic with a characteristic time of about four million years that means within say 10 or 15 million years, some planets or moons may have `collided` or been `flung` out of the solar system entirely. The very system we think of as the model of order, is unpredictable on even modest timescales So how well can we predict the future? Not very well at all at least when it comes to chaotic systems. The further into the future you try to predict the harder it becomes and past a certain point, predictions are no better than guesses. The same is true when looking into the past of chaotic systems and trying to identify initial causes I think of it kind of like a fog that sets in the further we try to look into the future or into the past Chaos puts fundamental limits on what we can know about the future of systems and what we can say about their past But there is `a silver lining`. Let's look again at the phase space of Lorenz's equations. If we start with a whole bunch of different initial conditions and watch them evolve, initially the motion is messy. But soon all the points have moved towards or onto an object the object, coincidentally, looks a bit like a butterfly. It is the attractor For a large range of initial conditions, the system evolves into a state on this attractor Now remember: all the paths traced out here never cross and they never connect to form a loop, If they did then they would continue on that loop forever and the behavior would be periodic and predictable. So each path here is actually an infinite curve in a finite space. But how is that possible? Fractals. But that's a story for another video this particular attractor is called the Lorenz attractor, Probably the most famous example of a chaotic attractor though many others have been found for other systems of equations now if people have heard anything about the butterfly effect, it's usually about how tiny causes make the future unpredictable but the science behind the butterfly effect also reveals a deep and beautiful structure underlying the dynamics. One that can provide useful insights into the behavior of a system So you can't predict how any individual state will evolve, but you can say how a collection of states evolves and, at least in the case of Lorenz's equations, they take the shape of a butterfly. 

Hey this part of the video is sponsored by LastPass, the password manager with unlimited password storage and free cross-device sync before I used a password manager, I've got to admit, I used the same password for a lot of different accounts and I know that is incredibly dangerous because if even one of those sites got hacked, then all of my important accounts would be exposed. Quite the butterfly effect. LastPass auto generates strong passwords for you so you have a different, `indecipherable` code for each website and let's face it: If there's anything in your life that you want to be chaotic, it is the characters in your passwords the best part is because it autofills user names and passwords on websites or on iOS or Android apps and mobile sites, you never have to remember another password again. Not for the rest of your life and that means no more writing down passwords, no more getting locked out of accounts, no more password resets. You can use your brain for what it's meant to be doing. and if you want extra features like advanced multi-factor `authentication`, you can upgrade to LastPass premium I got to say, it works like magic. so put your passwords on autopilot with LastPass Click the link below to find out more, and thanks to LastPass for sponsoring this part of the video. 