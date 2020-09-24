# Cash-Flow-Minimization
The idea is to use Greedy algorithm where at every step, settle all amounts of one person and recur for remaining n-1 persons.
To pick the first person, calculate the net amount for every person where net amount is obtained by subtracting all debts (amounts to pay) from all credits (amounts to be paid).
Once net amount for every person is evaluated, find two persons with maximum and minimum net amounts. These two persons are the most creditors and debtors.
The person with minimum of two is our first person to be settled and removed from list.
