# Model-based-thinking
We live in a complex world with diverse people, firms, and governments whose behaviors aggregate to produce novel, unexpected phenomena. We see political uprisings, market crashes, and a never ending array of social trends. How do we make sense of it? Models. Evidence shows that people who think with models consistently outperform those who don't. And, moreover people who think with lots of models outperform people who use only one. Why do models make us better thinkers? Models help us to better organize information - to make sense of that fire hose or hairball of data (choose your metaphor) available on the Internet. Models improve our abilities to make accurate forecasts. They help us make better decisions and adopt more effective strategies. They even can improve our ability to design institutions and procedures. This course is offered at: [Model-thinking](https://www.coursera.org/learn/model-thinking)

## 1. Why Model?
- Intelligent Citizens of the World
- Thinking More Clearly
- Using and Understanding Data

[**Netlogo**](https://ccl.northwestern.edu/netlogo/) multi-agent programmable modeling environment.

**Agent based model:** You have a bunch of agents. These can be people, these can be firms, they can be countries, they could be organizations. But they're agents, objects of the model. Now these agents have behaviors. Things that they do, rules they follow. Now in some cases these rules might be optimal rules. They may be optimized. In that case it becomes what we call a game theory model or rational choice model where individuals are doing the optimal thing in the context of the model. In a shoot we study here, they're not going to be optimizing. They're going to following Pretty simple rules. And then the third part of the models, once you've got all these agents following all these rules, that creates something at the macro level. It creates some sort of outcome. And so what we can do is then ask sort of what kind of outcome do we get. 

[**Schelling's Segregation Model**](https://ccl.northwestern.edu/netlogo/models/Segregation): This project models the behavior of two types of agents in a neighborhood. The orange agents and blue agents get along with one another. But each agent wants to make sure that it lives near some of "its own." That is, each orange agent wants to live near at least some orange agents, and each blue agent wants to live near at least some blue agents. The simulation shows how these individual preferences ripple through the neighborhood, leading to large-scale patterns. 

The orange and blue agents are randomly distributed throughout the neighborhood. But many agents are "unhappy" since they don't have enough same-color neighbors. The unhappy agents move to new locations in the vicinity. But in the new locations, they might tip the balance of the local population, prompting other agents to leave. If a few agents move into an area, the local blue agents might leave. But when the blue agents move to a new area, they might prompt orange agents to leave that area.

Over time, the number of unhappy agents decreases. But the neighborhood becomes more segregated, with clusters of orange agents and clusters of blue agents.

*In the case where each agent wants at least 30% same-color neighbors, the agents end up with (on average) 70% same-color neighbors. So relatively small individual preferences can lead to significant overall segregation.*

[Interviews: "The World on a Screen" (March 29, 2002) Jonathan Rauch talks about what the study of artificial societies has to tell us about the real world.](https://www.theatlantic.com/magazine/archive/2002/04/seeing-around-corners/302471/)

It's a threshold based model. Each person has eight neighbors. If 3 of them are same as his (in this case Red) the person doesn't move. But if it goes below that (2/8 or 1/8) then the person moves. The result shows even if people are tolerent (like happy to live with 30 - 40 % same type people) it creates 70-80 % segregation. It conludes to **Micromotives are Not Equal to Macro-behavior**.

[**Measurement of segregation**] = Sum(number of blocks * (number of specific type of people in the block/total number of that specific people in that segment)/2

<img src="https://github.com/sudokhan112/Model-thinking/blob/main/image/img_1.png" width ="300" height="300">

Number of people each block = 10

Total Blue people = 150

Total Yellow People = 90

Green People = 50% mix of Blue and Green

Measurement of segregation = 12*(10/150) + 6*(10/90) + 6*(5/150+5/90) /2 = 72/90 = 80% segregation

*divide by 2 helps to scale it from 0-1*

