# LearnMarlowe
first crack at simple contract in marlowe

Hypothetical contract:
two parties agree that a 3rd party 'judge' is to choose who gets the sum of their deposited funds, after a certain amount of time the debt of this judgement is paid back

1. parties (PK=person1,person2) deposit equal value of funds to intermediary (account:intermediate) 
2. intermediary (role:judge) decides who is deserving of all funds
3. all funds in account:intermediate are paid out to chosen party
4. after slot 60, funds are returned from 'chosen' party to 'not chosen' party and contract is closed.

known issues:
1. if 'chosen' party has spent all funds in account at slot 60, no funds are available to be paid back
