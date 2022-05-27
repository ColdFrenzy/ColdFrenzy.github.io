---
layout: page
title: Adaptive Playing & Opponent Modeling in Competitive Games
description: 
img: assets/img/Adaptive_Playing_and_Opponent_Modeling/board_configuration.png
importance: 1
category: work
---
<a href="https://github.com/ColdFrenzy/Adaptive_Learning">Link to the code</a>
<h2 align="center"> Abstract </h2>

>Despite the success of Artificial Intelligence systems such as Deep Blue, AlphaGo and OpenAI five, most modern commercial videogames still rely on the use of scripts. This is mainly because developers are concerned about the unpredictable behavior of AI.
>
>The ability to create a balanced matching between the user's skills and the level of difficulty of the game can greatly improve the user's gaming experience.
>
>Previous attempts at achieving this goal have required a large amount of data from human matches or specific knowledge related to the game.
>
>In our work, we have proposed a new method that allows us to eliminate the demand for data from games between human players and to decrease the amount of specific knowledge related to the game needed.


<div class="row align-items-center">
    <div class= "col-sm mt-2 mt-md-0" align="center">
        <div class="col align-self-center">
            <h3> Train and Store </h3>
            In this section we train an <br>
            agent through <br>
            reinforcement learning and <br>
            self-play tecniques.  <br>
            During this phase we <br>
            evaluate the agent and <br>
            store some of its best <br>
            policies for the next step.  <br>
        </div>
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/img/Adaptive_Playing_and_Opponent_Modeling/Algorithm1_v2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row align-items-center">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/img/Adaptive_Playing_and_Opponent_Modeling/Learning_Behaviour.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class= "col-sm mt-2 mt-md-0" align="center" vertical-align="middle">
         <div class="col align-self-center">
            <h3> Adaptive Playing </h3>
            We use the previously stored <br>
            policies to create a dataset <br>
            of matches between agents <br> 
            using these policies. <br>
            We train a model to recognize <br>
            the level of the agents by <br>
            looking at their sequence of moves. <br>
        </div>
    </div>

</div>


 <div class="row">
    <div class="mx-auto">
    <!-- <div class="col-sm mt-3 mt-md-1"> -->
        <div class="col align-self-center">
            <h3> Adaptive Playing </h3>
            We use the previously stored <br>
            policies to create a dataset <br>
            of matches between agents <br> 
            using these policies. <br>
            We train a model to recognize <br>
            the level of the agents by <br>
            looking at their sequence of moves. <br>
        </div>
    </div>
</div>

