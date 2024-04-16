README
================
Chelsea Linares
2024-04-16

## Introduction

My project is meant to predict whether someone will be approved for a
credit card or not. To do this, I will use multiple classification
machine learning models and compare results to determine the most
accurate. My data comes from kaggle, where it states the original data
was obtained from a UCI confidential source. We don’t know much about
the original source just that its license under Creative Commons
Attribution 4.0 International and that it has been cited in several
different papers. I have provided a link down below from where I found
it on kaggle.

Link:
<https://www.kaggle.com/datasets/samuelcortinhas/credit-card-approval-clean-data?resource=download>

### Inspiration and Motive

Financial literacy and financial freedom have always been a big interest
of mine especially since it’s something most Americans lack. The
consumerism mindset keeps us in the loop of constant need for the latest
gadgets and devices. This is incredibly harmful towards establishing
stable finances, and when credit cards come into play, it can either
improve your life or completely sink it. It all depends on your basic
principles.

Credit cards are a controversial subject, as many who hold them aren’t
good at managing them and thus, will believe they only lead to debt.
This idea is far from the truth as they can acquire cash back on
purchases, if used correctly. Plus, they can provide a good credit
score, which can open many doors such as purchasing a home and obtaining
lower APRs.

At first, opening a credit card or at least attempting to open one will
bring your credit score down. Since banks need a formal credit report,
that automatically lowers it. This explains the necessity of researching
the credit card and feeling confident about being approved. That made me
realize that even though banks do not disclose the effect each variable
has into their decision, we can determine that data ourselves, and
ultimately create a good learning machine that can highly predict
whether someone will be approved or not.

### Project Outline

To build our classification binary model, we will first clean our data
by removing any variables with large amounts of missing data. With our
remaining variables, we will visualize the parts of our data that we
find interesting. This will give us a better understanding of how the
predictors work and how they affect the outcome. Later, we will split
our data into a training and testing set, create a recipe, and fold our
training set to a 10-fold cross validation. These will then be used for
our 6 models: Logistic Regression, Linear Discriminant, KNN, Decision
Tree, Gradient-Boosted Tree, and Random Forest. The models have been
fitted against our cross validation, and the top 2 best performing will
be fitted against our training data and then tested against our testing
set. The best performing after our testing will be declared the winner!
