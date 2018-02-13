
## As participants arrive...

Participants have been asked to install or update R and RStudio prior to the workshop,
as well as install the following packages:

- `knitr`
- `rmarkdown`
- `ggplot2`
- `dplyr`

It is possible that some of them did not yet do that. If people show up early remind
them to complete installation, and re-point them to the instructions in the
pre-workshop email and/or the workshop website. Note that they will not need these tools until after the coffee break.


## Intro (15 min)

## Welcome + overview

- Welcome the participants and briefly go over the schedule for the 2-day workshop.
    - Schedule is purposefully not included on the slides since each workshop might
    follow a slightly different schedule.
- Remind them the mission statement and the tagline:
    - Mission statement: To Train researchers in the best practices and approaches of reproducible research and accelerate scientific progress
    - Tagline: Accelerating scientific progress through reproducible science.
- Getting to know you exercise and group discussion:
   - 6 months from now can you or someone else go back to your project and understand what was going on? What types of methods do you use to document a project?
   - Take notes on the board as to tools people use.
- Review a few case studies:
    - Some are already discussed in `intro-01-slides`
    - If you prefer to discuss others, see some examples at https://github.com/Reproducible-Science-Curriculum/Reproducible-Science-Hackathon-Dec-08-2014/wiki/Irreproducible-Examples

## Exercise: Motivating reproducibility (40 mins)

### Part 1: Analyze + document (20 minutes)

#### From the slides:

<div class="boxed">
Complete the following tasks and **write instructions /
documentation** for your collaborator to reproduce your work starting with the
original dataset (`data/gapminder-5060.csv`).

1. Visualize life expectancy over time for Canada in the 1950s and 1960s using
a line plot.
2. Something is clearly wrong with this plot! Turns out there's a data error
in the data file: life expectancy for Canada in the year 1967 is coded
as `999999`, it should actually be `69.96`. Make this correction.
3. Visualize life expectancy over time for Canada again, with the corrected
data.<br>
*Stretch goal:* Add lines for Mexico and US.
</div>

#### Tips for instructors:

- Some people will assume they have to do this in R, even if they're not an R user,
remind them that the whole point of the exercise is that they do this in an
environment they use / are comfortable with. (Assure them that we'll get to R
later...)
- Remind them that they need to document -- in past workshops most people got hung
up on doing, then documenting, and then the second part of the exercises didn't
have as much of a punch. More important that they document what they do (even if
not all tasks) than that they finish.

### Part 1: Swap + discuss (15 minutes)

#### From the slides:

<div class="boxed">
Introduce yourself to your collaborator and tell them why you're here.

1. Swap instructions / documentation with your collaborator, and try to reproduce
their work, first **without talking to each oher**.
If your collaborator does not have the software they need to reproduce your work, we
encourage you to either help them install it or walk them through it on your computer
in a way that would emulate the experience. (Remember, this could be part of the
irreproducibility problem!)
2. Then, talk to each other about challenges you faced (or didn't face) or why
you were or weren't able to reproduce their work.
</div>

#### Tips for instructors:

- People not having the software their partner used is likely to be the biggest issue
in this exercise. There isn't really enough time to install sofware, or software might
be proprietary. In these cases ask people to keep it to a discussion.
- Encourage people to read code, even if they don't know the language. If well
documented/commented, one might still be able to follow the code even if they couldn't
write it themselves from scratch.

### Reflection - group discussion: (5 mins)

#### From the slides:

<div class="boxed">
- What tools did you use (Excel / R / Python / Word / plain text etc.)?
- Were you successful in reproducing each others' work?

<br>

- What would happen if your collaborator is no longer available to walk you through
their analysis?
- What made it easy / hard for reproducing your partners' work?
- What would have to happen if
    - you had to swap out the dataset or extend the analysis further?
    - you caught further data errors and had to re-create the analysis
    with corrections?
    - you had to revert back to the original dataset?
</div>

#### Tips for instructors:

- Collect data from the students on their tool choice and success. Tallying these
on the board creates a nice visual.
    - If you know that the session will have a large number of participants preparing a
    Google Form might be useful.
- Keep the discussion on the second set of questions to an informal discussion, and
feel free to keep it short if exercise took longer than intended.
