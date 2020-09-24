# Cash-Flow-Minimization
The idea is to use Greedy algorithm where at every step, settle all amounts of one person and recur for remaining n-1 persons.
To pick the first person, calculate the net amount for every person where net amount is obtained by subtracting all debts (amounts to pay) from all credits (amounts to be paid).
Once net amount for every person is evaluated, find two persons with maximum and minimum net amounts. These two persons are the most creditors and debtors.
The person with minimum of two is our first person to be settled and removed from list.
<img width="948" alt="C1" src="https://user-images.githubusercontent.com/66682829/94113357-64d3ac80-fe64-11ea-9169-52b5d52e26ff.PNG">
<img width="946" alt="C2" src="https://user-images.githubusercontent.com/66682829/94113360-67360680-fe64-11ea-9436-9b5fe39d2be7.PNG">
