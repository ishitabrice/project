This repository provides an overview and implementation of key economic competition models, specifically Cournot Competition and Bertrand Competition. It also includes accompanying Python and C code for simulating these models.
Overview

Cournot Competition
Description: Firms compete by deciding quantities of production. Market price is determined by the total quantity produced.
Key Elements:
Market price: 
p(q)=a−q
Where 
𝑞=𝑞1+𝑞2
Profit for each firm: 
Profit=p(q)⋅qi−ci⋅qi
​Derivation of best responses for firms to determine equilibrium.

Bertrand Competition
Description: Firms compete by setting prices for a homogeneous good, aiming to attract consumers based on lower prices.
Key Elements:
Equilibrium price equals marginal cost: 𝑝1=𝑝2=𝑐 

Profits depend on price differences and demand distribution.

Games
Task Titans (Cournot-based game):

Players complete tasks, earning points but losing health points per task.
Rules and formulas determine best responses and mutual equilibrium strategies.
Property Rush (Bertrand-based game):

Players set prices for selling flats, competing for customers.
Players aim to undercut competitors while maintaining profitability.
Features
Code Implementations:

Cournot Game: Python script calculates individual and mutual best responses, and visualizes equilibrium points.
Bertrand Game: C program models price competition scenarios.
Sample Data: Example datasets provided to test and understand the models.

Prerequisites
Python 3.x for Cournot Game
C compiler for Bertrand Game
Spreadsheet software to explore sample data
