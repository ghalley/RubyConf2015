# RubyConf 2015

rubyconf.org/parites
mikeperham.com/events

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



