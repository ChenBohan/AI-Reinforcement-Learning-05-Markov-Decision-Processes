# AI-Reinforcement-Learning-05-Markov-Decision-Processes
Lecture 2: Markov Decision Processes by David Silver

Website: http://www0.cs.ucl.ac.uk/staff/D.Silver/web/Teaching.html

Videos: https://www.bilibili.com/video/av32149008/?p=4

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
    
<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-05-Markov-Decision-Processes/blob/master/readme_img/Bellman%20Equation%20in%20Matrix%20Form.png" width = "70%" height = "70%" div align=center />

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-05-Markov-Decision-Processes/blob/master/readme_img/Solving%20the%20Bellman%20Equation.png" width = "70%" height = "70%" div align=center />

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-05-Markov-Decision-Processes/blob/master/readme_img/Bellman%20Expectation%20Equation%20for%20v%CF%80.png" width = "70%" height = "70%" div align=center />

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-05-Markov-Decision-Processes/blob/master/readme_img/Bellman%20Expectation%20Equation%20for%20Q.png" width = "70%" height = "70%" div align=center />
