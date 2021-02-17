# NotWorkingIQN

Functions which have a lot of problems because I changed their logic:

1) run_episode in run_expiriment.py(I changed it there that the two agents will run the episode, and only when the episode is finished the transitions will be added to the replay memory)

2) select_action in rainbow_agent.py

3) the q_argmax tensorflow graph in implicit_quantile_agent.py(I changed it there so it would only consider the possible actions at the state, not ALL the actions).

