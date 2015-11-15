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








