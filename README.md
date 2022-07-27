# Programming networks of organized crime
### Individual Project by Enno Kuyt             
### Supervisor: Frederike Oetker 
### Examiner: Rick Quax
### Date: 14/10/2021
### UvA ID: 11869399

# Readme
This Github page holds all relevant information regarding my individual project. In this Readme, one can read a short summary of the project. More importantly, on the page, one can find the related code files. Most files are small snippets of the main file, _Model_COMPLETE.ipynb_, that have been individually created before integration. The main file exists of some helper functions... 


## Introduction:
For the past two months, I have been assisting Frederike with the creation of a criminal network model. I had received some topic-related papers which I read beforehand to be fully prepared. These papers gave insight into the basics of a criminal network[1], related issues to keep in mind[2], and how criminal networks form and evolve over time[3][4]. I already had solid knowledge on network theory, so these papers were mostly useful in understanding how to apply this in relation to criminal activities. From the papers it became clear that network models are well-suited to analyze organized crime. Not so coincidentally, that was exactly Frederike’s goal. More specifically, the goal was to simulate the removal (e.g. the death of) and replacement of the leader (kingpin) in a criminal network model, and the behavior of the other criminals (agents) in the network. 

## My task:
My main task for this project was to tutor Frederik through the process of creating the network model. The end result should be a fully functional criminal network model. Fully functional in this case means that it should be able to correctly simulate different scenarios as per Frederikes definition. Usually, during meetings and through Slack, Frederike and I would discuss the best way to model some aspect of the system based on her vision concerning that specific subject. Then, I would implement it and explain the exact workings to her, and show how she could extend the functionality to better suit the model requirements. An advantage of this was that it gave me a lot of freedom to design the model to my own preferences and insights. However, a disadvantage of this approach was that I was lacking in tutoring it properly. Luckily, Frederike picked up most things rapidly, which made this issue negligible.

Important to note here is that my task was not to make my own analyses, but to create a framework that would allow Frederike to make analyses. So it was especially important that the model was robust, user-friendly and scalable, so that Frederike would easily be able to extend the model on her own. Also, the functions should have comments about their functionalities such that for Frederike it is clear what the function does, how it does that, and how Frederike can alter it to her preference. Finally, the model should have clear output and data storage so that Frederike can easily track back actions and ultimately, make analyses.    

## What did I learn:
Creating the model further improved my programming skills in Python, especially with the _networkx_ and _mesa_ frameworks. However, as the project progressed, I got more and more involved in the decision-making process of Frederike as well. I noticed that, through creating the code for the model, I also got a better understanding of the reasoning behind the model. This enabled me to assist Frederike not only with the coding, but also to act as a sparring partner when discussing the design of functionalities and scenarios. As my understanding of the matter steadily increased, my input became more and more valuable. Also, I noticed that my increased knowledge of the underlying mechanics made it easier to design robust functionalities. As in, that they would remain relevant and usable, even after big design changes to the model. I believe I can take all these learnt lessons with me to new projects.

## The result:
In my opinion, we have a very nice end result in the form of a fully functional criminal network model. The model does precisely what it should for now, but there are many opportunities to extend upon its functionality. When designing the functions, I already focused on the future, making sure they would still run effortlessly under straightforward full-model adaptations. Moreover, a lot of functions are made in such a way that Frederike should easily be able to extend it. The data collector is set-up and any model data that needs to be stored can be added rather simple, making it possible for Frederike to do analyses. I hope this model will prove to be a base for much research that Frederike is planning to do in the future, and that I tutored her enough so that she can create her own extensions without further help!

[1]: Diviák, T. (2020). Criminal networks: actors, mechanisms, and structures.'\n'
[2]: Campana, P. (2016). Explaining criminal networks: Strategies and potential pitfalls. Methodological Innovations, 9, 2059799115622748.
[3]: Martinez-Vaquero, L. A., Dolci, V., & Trianni, V. (2019). Evolutionary dynamics of organised crime and terrorist networks. Scientific reports, 9(1), 1-10.
[4]: Bright, D., Koskinen, J., & Malm, A. (2019). Illicit network dynamics: The formation and evolution of a drug trafficking network. Journal of Quantitative Criminology, 35(2), 237-258.


