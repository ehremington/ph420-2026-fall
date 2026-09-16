# Fall 2026 - Thermal Physics - Daily Log



## Notes:

[Chapter 1](<https://github.com/ehremington/ph420-2026-fall/raw/main/chapter1.pdf>)

## Homework: 

[Schroeder chapter 1 to get you started on hw.](<https://samford.instructure.com/courses/59847/files/6557959?wrap=1> "schroeder-chapter1.pdf")

| Homework Due | Assignment | Submission |
| --- | --- | --- |
| 260826 W | \# 1.1, and question from notes | [260826](<https://samford.instructure.com/courses/59847/assignments/691796> "260826") |
| 260828 F | week 1 worksheet | week 1 |
| 260831 M | week 2 worksheet | week 2 |
| 260902 W | week 3 worksheet | week 3 |

## day 10 | 260916 W

We will finish the problem 1.16 that we started last time. There are some important notes from this I want you to have. Separation of Variables is an extremely useful technique for solving many differential equations in physics. 

## day 9 | 260914 M

We will begin today going through in class some above average questions from chapter 1, which do not belong within the broader text, but which are still important, either because they are using some element of reasoning that we will use again, or they have some math technique in them that is good to see. 


## day 8 | 260911 F

We will talk through the last few bits of intoductory thermo, by discussing the isothermal process along with the adiabatic process. I want to leave some notes here as a summary of our discussion today on these processes.

An *isothermal process* is one where the temperature is constant. This amounts in most situations to no change in internal energy, so we can summarize it like this

\\[\Delta U = 0 = Q + W\\]
\\[Q=-W\\]

Now this is fine to say, but it leaves a question about how to we find the work? The pressure changes as the volume changes, so this means that there is an integral to do. The answer is that 

\\[W = -N k_B T \ln\frac{V_2}{V_1}\\]

and since in the heat is the opposite of work in this case:

\\[Q = N k_B T \ln\frac{V_2}{V_1}\\]

Just be careful about some books absorbing that negative sign in the work formula and inverting the Volume ratio without telling you.

An *adiabatic process* is one in which no heat is added or removed during the change in volume. There are two ways of looking at this:

1. According to the first law in the way that we have used it

\\[\Delta U = \cancelto{0}{Q} + W\\]

The consequence of this is that 

\\[\Delta U = \frac{f}{2}N k_B T = W \\]


2. Also according to the first law, but in a smaller sense we have

\\[dU = \bar{d}W\\]

From this expression, we can derive the following formula:

\\[\left(\frac{T_2}{T_1}\right)^{f/2} = \frac{V_1}{V_2}\\]

And combined with the ideal gas law, we can work through many different situations.



## day 7 | 260909 W

We will continue to work on the week 3 worksheet and finish up thermodynamic cycles by talking through

## 260907 M - Labor Day



## day 6 | 260904 F

We begin right in the middle of a problem, but there are some important things within this problem that I did not want to rush through. Some of these things we will see and offer proofs of throughout this semester. One of the most important of these is the equipartition theorem, which is jumping a head slightly, but I'll go ahead and introduce it now and we will cover it again soon. The equipartition theorem says that for each degree of freedom (that is each way or direction that a particle can have energy) each add \\(1/2 kT\\). This means that for N particles within a substance the total energy of that substance can be found with:

\\[U\_{int} = N f \frac{1}{2} k_B T\\]

Thus for an ideal, monatomic gas, which can only move in three dimensions and can not spin in a way that we can measure would have \\(f=3\\). For a diatomic gas, which can move in three dimension and can spin in a couple of ways that are distinquishable, then in that case \\(f = 5\\). 

This is something that we will use repeatedly with the first law of Thermo, so it will be very useful to see it in action here. 

With this in place, we continue to go through the worksheets, keeping in mind what our questions are and the things that we need to revisit. As far as our content goes, these worksheets have served as a quick introduction, and a fast paced sweep through sections 1-6 of chapter 1. But we need to make sure that we are covering things carefully as we begin, so next week we will go through some extra pieces in chapter 1 and hopefully clean up some misunderstandings that we have so far.

## day 5 | 260902 W

Today we will begin to add *work* in with the heat as the two ways to change the internal energy of a gas. We talked through the usefulness of a PV diagram to keep track of how the state of a gas changes over some type of transformation. There are infinitely many transformations, but we will stick with a few that help us categorize and learn more about all of these quantities. In particular, we ended talking about the isobaric transformation and we will pick up next time talking through how heat is given off or absorbed during an isobaric transformation.

## day 4 | 260831 M

We continued through week 2 worksheet. Week 2 is focussed on heat and how heat can be applied to both a solid, liquid and gas. We typically treat solids and liquids together with the *specific heat* equation, and treat gases separately with the heat capacity at constant volume or pressure. This shows that there is a little bit more going on with gases and this is something that we are going to cover much more of in the future. 

## day 3 | 260828 F

We kept going through the worksheets and worked through more of the week 1 worksheet. This worksheet focusses on the ideal gas law and the parameters that we think of when we are talking about a gas. These *state variable* work together through a *state equation*. One kind of state equation is the ideal gas law, but there are others as well that we will encounter soon. 

## day 2 | 260826 W

We are going to review some basics from Thermodynamics and add to them as we go through the next several classes. For today, we will review through "week 1" of PHYS102 by doing a worksheet from that class as a way to get started in this. Over the next few days we will do "week 2" and "week 3", and then we will begin to add some things onto this basic understanding. The following sets of notes from my 102 class will help you as you go through these worksheets.

* week 1 notes
* week 2 notes
* week 3 notes

## day 1 | 260824 M

[Link to our book](https://physics.weber.edu/thermal/default.html)

## day 0

We will meet in room 011 of Propst Hall. Sorry about the confusion of this. 

Check out the syllabus!

Check out this website: https://manytinythings.github.io/

![thermotweet.jpg](README_files/30c15490-55c1-49ff-83a7-4f020a526fce.jpg)


    [NbConvertApp] Converting notebook README.ipynb to markdown
    [NbConvertApp] Support files will be in README_files/
    [NbConvertApp] Writing 4706 bytes to README.md

