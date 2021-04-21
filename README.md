# CSLR_with_RL

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The aim of Continuous Sign Language Recognition (CSLR) is to **translate videos of signlanguage into  text sentences**. CSLR  is  a  fairly  challenging  task,  and  is  currently an actively growing  field. Any  CSLR  model must capture all the fine details in hand movements and accurately translate them into coherent sentences without semantic gaps. This task of automatic translation is pertinent in today’s world, considering the communication challenges that exist between hearing-impaired individuals and those with hearing abilities. Hence, the use of machines for this task can be particularly beneficial. </p>

  <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The paper we implemented was ”Continuous Sign Language Recognition Via ReinforcementLearning”. It proposes a novel approach to the task of Sign Language Recognition whichapplies Reinforcement Learning. The CSLR model proposed in this paper consists firstly of a 3D ResNet (a type of 3D Convolutional Neural Network) to extract the visual features from the videos. Convolutional Neural Networks are the industry standard for video recognition tasks.The second portion of the model is a Transformer for the purpose of sign language recognition. The Transformer is a state of the art model that helps translate the sign videos into text sentences.   Transformers have shown  tremendous capabilities  in  machine  translation tasks, which are very similar to the CSLR task that we sought to implement. The Transformer was trained using the **self-critic REINFORCE algorithm**. Using RL for training addresses most drawbacks that were observed while using traditional SupervisedLearning techniques. This RL based optimization strategy is hypothesized to lead to major improvements in results.</p>
