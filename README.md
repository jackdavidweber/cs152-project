# BioSnake

![Retro Snake](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRNEnvrWhM_FinzK4yn6n4ROQPM4zX4s8UoAMQYFhLKMRWj2RI3Hd6X3pjMb2OjuKBitN4&usqp=CAU)

## Project Description
For my project, I will use the game of snake in order to better understand reinforcement learning, genetic algorithms, and collaboration.

## Project Goals
Given the team aspect of the project, I designed my goals to make parallelization of work as easy as possible. Once the MVP is completed, we can break our team up into smaller parts so that everyone can explore what they are most interested in while also getting exposure to what others on the team are working on. Thus, the extensions described below should change based on what group members are most interested in investigating!

### MVP: Learn to Play Snake
For the MVP of this project, I'd like to have a working program that can simulate millions of snake games. These simulations can be used by the Reinforcement Learning algorithm to improve the player's strategy. We should observe that with more training, the player's strategy improves. 

There are plenty of resources that we can use to complete this stage of the project. We could build the game from scratch or simply import an already [functioning version of the game](https://github.com/codebasics/python_projects/tree/main/1_snake_game). There even exist [step-by-step tutorials](https://towardsdatascience.com/how-to-teach-an-ai-to-play-games-deep-reinforcement-learning-28f9b920440a) for training NN's to play snake. Given these resources, my hope is to spend relatively little time on our MVP so that we can move onto the more exciting extensions of the project

### Extension 1: Genetic Algorithms
Despite being a computer science major, I find the idea of evolution to be really quite interesting. That's why I was really excited to find out that there exist algorithms that use can evolve to improve over time. These Genetic Algorithms can work instead of or in conjunction with Reinforcement Learning Algorithms. 

For this extension of the project, I'd like to learn more about both types of algorithms and see if we can *"evolve"* the MVP's *"brain"* to play snake better.

### Extension 2: Collaboration
In games like Chess and Go, we've trained computers to beat human players by playing against each other millions of times. But what happens if we try to teach the NN's to collaborate?

For this extension, I'd like to first modify the snake game to enable multiple snakes to play at once. Once the NNs master multi-player snake (maybe play against a human opponent), we could further modify the game to force collaboration. Here are some ideas for multi-player snake modifications that would force collaboration:
* Snake individual scores are combined
* Snakes need to arrive at the fruit at the same time
* One snake eats vegetables and the other snake eats fruit. Both the vegetable and the fruit need to be eaten before more food spawns.

Each modification represents a change in incentives that encourage the snakes to work together rather than compete. It would be interesting to see how quickly the snakes are able to learn to develop these collaborative behaviors. This is especially interesting when considering the contexts of evolution and brain development!

### Extension 3: Game Modifications
Since the MVP shouldn't take too long, there's a  lot of opportunity to see how the NN learns when we modify the game. Maybe somebody on the team is interested in creating different room shapes. Maybe somebody wants to add power-ups and bombs. Maybe we want to experiment with a time limit. The simplicity of snake leaves lots of room for exploration!

## Pitch
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ9AoPJ3yd4zr8dhaaOJ5BvF5DRpechDAWD1zUxUHqZuIJYGLDaUXhlSh2EsOAlx-d-VMdHmprry_5o/embed?start=false&loop=false&delayms=60000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


[Feedback / Interest Form](https://forms.gle/misQDvc8qELpxUdZ7)
