# Game Name

## Elevator Pitch

*A one sentence pitch for your game. Pretend that your were pitching your game to a executive going to the elevator. You have less than 60 Seconds. Check [this resource](http://www.gameacademy.com/perfecting-indie-games-elevator-pitch/) for more information.*

## Influences (Brief)

- *3Blue1Brown*:
  - Medium: Video
  - Explanation: Emphisis on storytelling, and how mathmatical formalisms fall out of wants and needs, not definitions.
  - https://www.youtube.com/watch?v=OkmNXy7er84
- https://explorabl.es/:
  - Medium: *Games*
  - Explanation: I like the way many of these "explorable explinations" are formatted. The way I see it, it's moreso like a texbook chapter but with friendlier prose and lots of interactive examples in the place of where figures would be.
- These French Quantum Physics Videos:
  - Medium: *Video*
  - Explanation: I really dig the minimalist graphical aesthetics and sound design in these videos for some reason. I think it'll fit the theme of the game well.
  - https://www.youtube.com/watch?v=DC0U5viudt0

## Core Gameplay Mechanics (Brief)

Gameplay is a strong word, its more-so having a bunch of sliders and knobs you can twiddle and tweak to see how these various components interact.


- *Gameplay Mechanic #1*
- *Gameplay Mechanic #2*
- *Gameplay Mechanic #3*
- *Gameplay Mechanic #4*

# Learning Aspects

## Learning Domains

- Asymptotic Analysis/Big O Notation
  - In the context of algorithms

## Target Audiences

While I am making this specifically for CISC320, I hope that it is also useful for curious individuals interested in the mathmatical formalism behind algorithm analysis.

## Target Contexts

This is designed to be a public website that can be accessed whenever. It can be used as a supplement for an algorithms course, but can also be consumed standalone.

It's format suits itself to be played individually and in one sitting.

## Learning Objectives
- Explain why Algorithms are best *generally* described using limiting behavior rather than other metrics
- Describe when asymptonic analysis is *not* useful 
- Formally define Big O, Omega, and Theta 
- Given polynomial/exponential functions f(x) and g(x), Formally prove that function f(x) is:
  - O(g(x))
  - Ω(g(x))
  - Θ(g(x))
  - All by finding the appropriate constants and values of N

## Prerequisite Knowledge

- Basic familiarity with high school algebra

## Assessment Measures
As we discussed, it's probably going to be a canvas quiz of some sorts. The original Big O quiz can serve as our pre-test.

Some example questions (not final)

**Prove Big O Relations**

Pretty much identical to what you gave on the quiz.

**Select all that apply type question**

f(x) = n^3-10n

  - O(2^n)
  - O(n^3)
  - Ω(n)
  - Ω(n^3)
  - Θ(n^3)

**When not to use Big O**

Give some general reasons why an algorithm in a "slower" complexity class might be better to use in practice than one in a "faster" complexity class.


# What sets this project apart?

- I have yet to see a nice interactive that deals with Big O notation. A lot of the online resources I see are static websites or videos
- As shown, we have a learning need for proving Big O notation.
- Computer Scientists are scared of math, and this experience will hopefully ease this transition


# Player Interaction Patterns and Modes

## Player Interaction Pattern

This is a single player game that will orginize itself into sections containing prose and interactive objects. In order to go on to the next section, the learner will have to complete a given interactions (Think minigames).

1. Introduction
    - The Big Question: How do we compare algorithms?
2. Just Time It!
    - The first assumption would be to time how long an algorithm runs for a single output.
    - **Problem:** Different computers run at different speeds. So there really isn't any sort of frame of reference.
3. Counting Steps
    - So instead of using the actual time, we can instead count how many operations the algorithm does.
4. Why We Can't Use Straight Functions
    - **Problem**: The functions used to describe algorithms get complex quickly, or sometimes cannot even be defined well.
    - There's an intution here that higher order functions grow faster than lower order ones; but how do we formalize that?
5. Asymptotic Analysis
   - The key, you could multiply 
6. Why Big O Sucks
7. **Bonus**: Sandbox Mode


*Sidenote: If I was teaching Big O my own way, I would instead teach it in almost reverse of what the formalism states. f(x) is O(g(x)) iff for any constant multiple c\*f(x) <= g(x) for n > n_0. I feel like this formulation encapsulates the entire concept of "no matter how much you scale f(x), it will always be eclipsed by a g(x) with no constants.*

*Or, maybe we can frame it as with x and x^2, no matter how hard you scale down x^2, at some point, **at some point it will go higher than x**.*

*However, I'm afraid of confusing students with this rouge way of teaching it.*

## Player Modes


*Your game has one or more player modes. Describe each discrete mode, considering things like menus too. Generally describe the transitions between modes too.*

- *Player mode #1*: *Description*
- *Player mode #2*: *Description*
- *etc.*

# Gameplay Objectives

- *Primary Objective #1*:
    - Description: *Description*
    - Alignment: *Describe how this aligns with one or more learning objectives*
- *Primary Objective #2*:
    - Description: *Description*
    - Alignment: *Describe how this aligns with one or more learning objectives*
- *etc.*

# Procedures/Actions

*Describe the control scheme and what actions a user can take in the game.*

# Rules

*What resources are available to the player that they make use of?  How does this affect gameplay? How are these resources finite?*

# Objects/Entities

*What other things are in the world that you need to design? These may or may not directly translate to actual objects and classes.*

## Core Gameplay Mechanics (Detailed)



- *Core Gameplay Mechanic #1*: *Describe in 2 paragraphs or less, along with how it generally works*
- *Core Gameplay Mechanic #2*: *Describe in 2 paragraphs or less, along with how it generally works*
- *Core Gameplay Mechanic #3*: *Describe in 2 paragraphs or less, along with how it generally works*

    
## Feedback

*Explicitly describe what visual/audio/animation indicators there are that give players feedback on their progress towards their gameplay objectives (and ideally the learning objectives).*

*Describe what longer-term feedback you detect and give that guides the player in their learning and lets them know how they are doing in regards to the learning objectives.*

# Story and Gameplay

## Presentation of Rules

*Briefly describe how the player will learn the gameplay mechanics. Avoid using walls of text, since people will not read them. Think instead of natural ways of teaching mechanics iteratively and slowly.*

## Presentation of Content

*Briefly describe how the player will be taught the core material they are meant to learn. Avoid using walls of text, since people will not read them. Think instead of natural ways of teaching material iteratively and slowly.*

## Story (Brief)

*The Summary or TL;DR version of below*

## Storyboarding

*Go into as much detail as needs be to visually convey the Dynamics of your game. Be detailed. Create storyboards and freeze frame images that concisely capture important key elements of your game. You are strongly recommended to sketch pictures on paper and embed them here. Be sure make it clear how previously-described mechanics come through in the dynamics.*

# Assets Needed

## Aethestics

*Give a sense of the aesthetics of your game, the spirit and atmosphere. Use descriptive, evocative words that can help the reader understand the emotional response of your game.*

## Graphical

There's not going to be too much in the way of graphics. A lot of the material will be presented though prose and dynamic graph plotting. Maybe I'll include some self-drawn cartoonish images relating to the subject to break up the prose if it becomes too dense?

## Audio
- Music List
  - Since this is more of a focused dive into a topic and not a game, the music will most likely be some light, synthy ambient music that's not too busy.
  
- Sound List (SFX)
  - *UI Sounds*: Various types of unintrusive clicks or blips when interacting with UI objects


# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3
