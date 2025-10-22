[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/oqKLEXJJ)
# 🎓 Ethical Admissions Algorithm Simulation

This repository is a classroom exercise exploring **ethics and fairness in algorithmic decision-making** — specifically in college admissions.

You’ll implement and reflect on how feature selection and weighting can impact fairness, transparency, and equity in automated systems.

---

## 🧩 Overview

You are part of the admissions committee for **Anonymous University**, located near Anonymous City.  
Due to a large number of applications, the committee decides to use an algorithm to help **rank and shortlist applicants**.

Your task:
- Decide which factors to include (GPA, test scores, extracurriculars, essays, recommendation letters, legacy status, income, etc.)
- Assign weights to each factor.
- Compare outcomes under two models:
  - **Blind model**: Ignores sensitive factors.
  - **Aware model**: Includes them intentionally to promote fairness (e.g., extra weight for first-gen or low-income applicants).

---

## ⚙️ How to Run

You can run the code on any online Java compiler (e.g. [Replit](https://replit.com/~) or [Programiz Java Compiler](https://www.programiz.com/java-programming/online-compiler))  
or locally via terminal:

```bash

    For the blind model, I removed extracuricular and put all weight lost from it into test scores. There are simply too many 
factors that could keep students from participating in a number of extracuricular (generally speaking like scheduling)
that I feel it shouldn't be so highly weighted or even waited at all when it comes to applications. And putting it into test
scores seems like the logical place to be weighted more.

    For the aware model, I not only decided to remove locality as proximity to college shouldn't give you an inherent advantage 
for admission, but I also gave legacy a negative weight of (-0.02). This is to prevent the possibility of nepotism allowing
student to easily get into college simply due to familial connection and promote exploration of other college choices. I
also gave income and disability more weight, considering the difficulties that come from these factors. 

..........................................................

    The results of the algorithmn are admitedly not very interesting. The person who benefited the most from the blind vs 
aware model was Fatima Al-Sayed and Jasmine Okafor. I assume its a result of giving more weight to being lower income. I
think giving lower income makes it fairer in regards to easier oppurtunities people with better financial security have with
doing better in school. And by punishing nepotism and encouraging those at an disadvantage, I find the Aware model
more fairer than the blind one.

..........................................................

    It was fairly obvious why the models functioned the way they did compared to the original, although it gave disadvantaged
people more of oppurtunities, it still clearly prioritized those with fairly good academic standing, with the ones rejected
suffering due to low GPAs and test scores. This is very easy and blatant for the applicant to understand, over factors like
nepotism or extracuricular. If this was for my application I would have a pretty solid chance of being admitted due to my good
GPA and my family income status at the time of my senior year.

..........................................................

    For any possible risk factor for such an algorithmn, extracuricular for clubs and sports will fall completely on the wayside. 
It's also possible that more lower income people getting admitted leads to more people graduating with less possibility of
paying off their student debt. These possibilities will still have to be considered even if the model is fair. Fair models 
don't necessarily mean reliable or helpful, especially if it doesn't consider how it affects the way schools structure programs
based on how it helps those "min-max" the system. Also, I think it's also important to remember, that it is only fair so as far as
I understand it to be, but no matter how objective I try to be my own bias will seep into the program no matter what, which keeps it
from ever being truly fair. So maybe fairness and accountability can be extrapolated from the opinions of a large set of diverse groups
on how the model should be designed.