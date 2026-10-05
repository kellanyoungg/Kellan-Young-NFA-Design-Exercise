# Kellan-Young-NFA-Design-Exercise
1. The problems that gave me the most trouble were #7 and #9. This is because the NFAs for these questions could follow multiple paths at the same time. I did not avoid any of the problems because it was too hard, but I chose to do the ones I was most confident in. Additionally, I did use AI to clarify how NFAs work as well as how to understand the state-by-state simulation in JFLAP.
   
2. Problems 7 and 9 surprised me the most during the step-by-step testing. In Problem 7, after reading a 1 from q0, the NFA could be in both q0 and q1. This happened because q0 has a loop on 1 and also has a transition to q1 on 1. After reading the next 0, one path could remain in q0 while another path reached the accepting state q2.
To avoid these mistakes, I will track every possible state after each symbol and test different types of strings. This will help me avoid missing transitions in future projects and exams.

3. This homework assignment was a great way for me to practice and understand how NFAs work and practice creating them.
