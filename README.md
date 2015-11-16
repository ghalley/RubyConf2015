# RubyConf 2015

rubyconf.org/parties
http://www.mikeperham.com/events/

## Keynote #1
Carina Zona

Algorithms have consequences on people

Mar IO

Target:
> If we wanted to figure out if someone was pregnant, even it they didn't want us to know, could you do that?

> As long as we don't spook her it works

Shutterfly thinks you had a baby.

Inadvertent Algorithmic cruelty
> Works most of the time, but not all the time

### Be humble
> We cannot intuit inner state, emotions, private subjectivity

Accidental algo run-ins
- Out of the user's control

Tools used to make film, the science of it, are not racially neutral
- optimized for white skin with Shirley cards

>If a machine is expected to be infallible, it cannot alsoe be intelligent - Alan Turing

Using a black box for decisions is regressive, to fairness.

### Flipping the paradigm

#### Consider Decisions' potential impacts
- Project the likelihood
- minimize negative consequences
- Not unlike the hippocratic oath

#### Be honest and trustworthy
- Build in recourse for a wrong conclusion
- disclosure of limitations

#### Be visionary about countering bias

#### Anticipate diverse ways to screw up

#### Cultivate informed consent

#### Audit outcomes constantly
- track bias in your own black box

#### Commit to data trasnperency and algo transparency

>Do not build without understanding consequences to others

## How to stop hating your tests
@searls

- Tests make big objects harder to manage

### Rule of Product
- test combo of all params

Test can do 3 things:
- sets up (Given)
- invokes (When)
- verifies (Then)

rspec-given

Sandi Metz's Squint test

#### Test Isolation
- Unfocused tests
- Too realistic tests
    + slower
    + take time to write/change
    + so many moving parts
- Redundant code coverage
- Careless mocking
    + Treats symptoms of test pain, not cause
- Application Frameworks
    + encourage only integration tests

#### Test Feedback
- Useless messages
    + Bad messages provide wasted time
    + judge message quality of tools
- Slow loops
    + limits the tasks you can do in a day
- Painful Data
- Test Durations
- False negatives
    + Unfinished tests
    + erode confidence in tests
    + redundent coverage, slow tests cause false negatives

TL;DR Fewer integration tests

@testdouble


## Seven Rightous Fights

### 1. Localization
- Don't hard code labels
- Support extra types of characters

### 2. Security
- Not cheap/easy, but beats the alternative
- Authentication is not Authorization is not security
- Leave room for encryption
- Be able to delete users
    + Delete data after 7 years or so

### 3. Extensibility

### 4. Documentation
- needs to be more useful than stack overflow
- They are not state secrets, they are subtle self promotion
- Good for dev on-boarding
- GOod for build procedures

### 5. Affordance
- what your software is trying to get people to do
- Software that creates good behavior w/ minimal user effort
- You're never going to fix it later

### 6. Acceptance
- Find actual users
- Don't tell them how to do it, see how they understand it themselves
- if you can't hire an expert, become a student

### 7. Accessibility
- Not everyone uses the retina screens we do
- We're only temporarily able-bodied, so do it for yourself

### Now What?
- Style guides
- brown bag lunches
- pair programming best practices
- add tests for accessibility and usability
- cultivate diversity and representation on your teams
- ask questions

Section 508: no money if not ADA compliant

Advice for winning: make it about money

## Soft Typing
Mostly live coding an interpreter to understand types, which is here:

github.com/jcinnamond/trump

## I estimate this talk will take 20 mins, give or take 10 mins
www.noelrappin.com

Bad estimates are not unique to software

##### What if we just did stuff and got paid?
- Customers reasonably expect estimates

### Estimates are communication
- Communicates the investment
- Communicates progress
- Communicates scope
- Bad estimates communicate bad things
    + unrealistic expectations
    + way too much
    + allows for micromanaging

### Estimates at the beginning is the WORST
- Like guessing time to the airport if you don't know where it is or if you even need to fly

### Kind-of Estimate Theory

#### Estimating Projects vs. Estimating Features
- Nobody cares about feature estimates
    + Only useful in aggregate
- Only care about when users can use stuff
- Estimates are probabalistic

#### What makes estimates go wrong?
- Bad assumptions
- scope creep
- Unknown complexity
- Rework
- sometimes there's pressure

Developers are optimists

A lower estimate doesn't make it less complex

### How to do better
Don't chase false precision

What goes into estimate:
- Complexity of the task
    + We're bad at estimating time on a task
- Skill of dev
    + De-moralizing if personal
    + Consistent
- time on task
    + Devs are pretty good at estimating this

Estimate complexity and let time sort itself out == point
- Everything else being consistent, the number of points per iteration becomes the most useful

Key point: decompose problem into smaller stories

The above doesn't help a one-off estimates

### The worst way to estimate
Fake your velocity in the beginning.

Don't chase precision here.

What you'll get is a range

Round point estimates upwards

Clearly describe the limits to your estimate

## Keynote: Stupid Ideas for Many Computers
Worst Ideas Evar -- Aaron Patterson

http://github.com/thagomizer/stupidideas
thagomizer.com

## Keynote: Leagues of Sea and Sky

>Augmented reality!!!

### Sea
Lunar distance used to calc longitutude was not simple way back when

Keeping track of the point of sunset was ok, if you could keep time in different places.
- John Harrsion built a sea clock and asked to has it tested, tests it on fleet to Lisbon
- Builds a second sea clock, then 17 years building a 3rd
    + Figures out how to bring it down to the size of a pocketwatch
    + SMASHING success on trans-atlantic voyage
- Design was stolen by new Royal Astronomer
- King George forces them to pay the prize for longitude
    + they pay most of the prize money, but dissolve the prize entirely
- John Harrison worked as a recluse
    + could've worked together for better results
    + both these methods now guide spacecraft

### Aviation

Most people only saw early flight in stunt shows, which doesn't convince them to try it in any way.

Charles Lindbergh one of the earliest Air Mail pilots

No one tried in first 5 years of prize for NYC - Paris

No one sold Lindbergh a plane, so he has an inexperienced engineer (Donald Paul) to build one: The Spirit of St. Louis.

Lindbergh super famous when he comes home.
- Donald Paul is not, is left out of celebrations
- Talks only about the plane, gives no realy credit to the engineers who built it.

### Sky(ish)
>Put a robot on Mars!!

We explore by physical presence, which is hard to do for the planets.
- Exploring planets through screens is hard, and leads to erroneous models of those planets
- Video games can be useful tools, they're designed to make us feel like we're elsewhere

Virtual Reality can be really, really effective.

Focus on the people you're encountering, and how you might work with new people.

@drjeffnorris


## The Not So Rational Programmer

### Our brain is a legacy system
- Powerful
- bad documentation
- no error handling
- no access to source code

Cognitive bias: heuristics the brain uses to make very quick decisions, especially in a pinch.

You'll recognize a person and their emotional state far faster/easier than you'd solve 17 x 24

Uses cognitive bias to approximate results that are ok most of the time

You can't turn it off, and you can't always know when it's happening

### Personal Decision Making

#### Confirmation Bias
search for/interpret info in a way the confirms preconceptions

- might get angry if preconception is challenged

##### Practice challenging your own opinion
- use devil's advocate if needed

#### Mere Exposure Effect
- Undue liking for things merely because we're familiar with them
- Cognitive Ease
- Cognitive Strain
    + something we find that we're not familiar with
    + seen as a potential threat up front, requires more effort
        * fewer errors, much slower
- Objective Criteria can be helpful for evaluation
- Personal Impression, only as support
- Seperate evaluation/execution

### Team Decision Making

#### False Consensus Effect
Overestimating the degree to which people think like or agree with me.
- We project our own assumptions on other people
    + Stronger when we're a part of the same group
- Be explicity to mitigate the effect
- Encourage questions
- Collect opinions first

#### Groupthink
members try to minimize conflict to reach consensus w/o evaluation, to preserve harmony
- Changing or discarding own opinions to fit this
    + limits critical and independant thinking
- Evolutionarily developed

##### Factors to groupthink
- highly cohesive
- structural faults
    + isolated
    + homogenous members
- situational context
    + perceived threats
    + recent failures

- Have diverse teams in demographics and viewpoints
- Encourage critical evaluation
- Don't prime a discussion by stating your own opinions
- Get outside opinions
- appoint a devil's advocate

>When we all think alike, then no one is thinking - Walter Lippman

### It's ok to change your opinion based on new or updated info

>Our comforting conviction that the world makes sense rests on a secure foundation: our almost unlimited ability to ignore our ignorance. -Daniel Kahneman

@laura_nobilis

## Hacking Spacetime for a successful career
@tehviking

Achievement is a system of control
- It's somebody else's rules

### Technician Track
likes tools and techniques
asks how
focuses on tactics

### Manager
fascination with people
asks who what where when

### Entrepreneur
likes gaps in the world
asks why
focus on vision and invention

What word do you do when you're stressed?

Invest in yourself and others

1. You can opt of the the cycle
2. Your preferences are your friends
3. Build the platform you want to live with










