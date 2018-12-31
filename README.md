# AI-Reinforcement-Learning-05-Markov-Decision-Processes
Lecture 2: Markov Decision Processes by David Silver

- A Markov Process (or Markov Chain) is a tuple <S,P>
  - S: a (finite) set of states
  - P: State transition probability 
    - Pss0 = P [St+1 = s0 | St = s]
    - State transition matrix: defines transition probabilities from all states s to all successor states s'
    
- A Markov Reward Process is a tuple <S, P, R, γi>
  - + R is a reward function, Rs = E [Rt+1 | St = s]
  - + γ is a discount factor, γ ∈ [0, 1]
  - The return Gt is the total discounted reward from time-step t.

- A Markov Decision Process is a tuple <S, A, P, R, γi>
  - + A is a finite set of actions
  - A policy π is a distribution over actions given states
    - π(a|s) = P [At = a | St = s]
    
  
