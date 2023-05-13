# Everything-LLMs-And-Robotics
The world's largest GitHub Repository for the intersection of LLMs (multimodal variants included!) + Robotics 

Why I made this: An Explanation (blue link here) (This explanation also includes why I'm not filing it under an "awesome" category, because I wanted to do a fundamental restructuring of this topic and I think I can do better than what currently exists).

Heavily Inspired by [Awesome-LLM-Robotics](https://github.com/GT-RIPL/Awesome-LLM-Robotics)

# Logistics 
If you want to make a change this repository [click here](PR-Guide.md)

If you want to learn why we do the things that we do (and how you can incorporate them in your own work) [click here](https://jrin771.github.io)

# What Does This Repository Have? 

- [Research: Reasoning](#research-reasoning)
- [Research: Planning](#research-planning)
- [Research: Manipulation](#research-manipulation)
- [Research: Instructions and Navigation](#research-instructions-and-navigation)
- [Research: Simulation Frameworks](#research-simulation-frameworks)
- [Project Demos](#project-demos) 
- [Educational Materials](#educational-materials) 
- [Thoughtful Twitter Threads](#thoughtful-twitter-threads)
- [Citation](#citation)


Things to add: 

Alan's paper 

Condename Burnham - Amazon GPT robot 

Tidybot - LLM powered robot 

This paper: https://arxiv.org/abs/2302.12915  

1 additional new category to add based off of the prior repository  
See if there's anything else course-wise I can add espeically lecture slides/talks/etc. 
4 Full categories to add in proper documentation 

After all of that is done I'm going to go through and see if I can add at a minimum 5 papers to each of these categories if not more.
Make sure links, spacing, typos, overall message is good, then draft a tweet thread and have this thing blow up. 

## Reasoning <a name="research-reasoning"></a> 

* **RT-1**: "RT-1: Robotics Transformer for Real-World Control at Scale", arXiv, Dec 2022. [[Paper](https://arxiv.org/abs/2212.06817)] [[Code](https://github.com/google-research/robotics_transformer)] [[Website](https://robotics-transformer.github.io)]

* **ProgPrompt**: "Generating Situated Robot Task Plans using Large Language Models", arXiv, Sept 2022.  [[Paper](https://arxiv.org/abs/2209.11302)] [[Code Doesn't Really Exist here](https://github.com/progprompt/progprompt)] [[Website](https://progprompt.github.io)]

* **Code-As-Policies**: "Code as Policies: Language Model Programs for Embodied Control", arXiv, Sept 2022.  [[Paper](https://arxiv.org/abs/2209.07753)] [[Code](https://github.com/google-research/google-research/tree/master/code_as_policies)] [[Website](https://code-as-policies.github.io)]

* **Say-Can**: "Do As I Can, Not As I Say: Grounding Language in Robotic Affordances", arXiv, Apr 2021. [[Paper](https://arxiv.org/abs/2204.01691)] [[Code](https://say-can.github.io/#open-source)] [[Website](https://say-can.github.io)]

* **Socratic**: "Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language", arXiv, Apr 2021. [[Paper](https://arxiv.org/abs/2204.00598)] [[Code](https://socraticmodels.github.io/#code)] [[Website](https://socraticmodels.github.io)]

* **PIGLeT**: "PIGLeT: Language Grounding Through Neuro-Symbolic Interaction in a 3D World", ACL, Jun 2021. [[Paper](https://arxiv.org/abs/2201.07207)] [[Code](https://github.com/rowanz/piglet)] [[Website](https://rowanzellers.com/piglet/)]

## Planning <a name="research-planning"></a>

* **LM-Nav**: "Robotic Navigation with Large Pre-Trained Models of Language, Vision, and Action", arXiv, July 2022. [Paper] [Pytorch Code] [Website]

* **InnerMonlogue**: "Inner Monologue: Embodied Reasoning through Planning with Language Models", arXiv, July 2022. [Paper] [Website]

* **Housekeep**: "Housekeep: Tidying Virtual Households using Commonsense Reasoning", arXiv, May 2022. [Paper] [Pytorch Code] [Website]

* **LID**: "Pre-Trained Language Models for Interactive Decision-Making", arXiv, Feb 2022. [Paper] [Pytorch Code] [Website]

* **ZSP**: "Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents", ICML, Jan 2022. [Paper] [Pytorch Code] [Website]

## Manipulation <a name="research-manipulation"></a>

* **DIAL**:"Robotic Skill Acquistion via Instruction Augmentation with Vision-Language Models", "arXiv, Nov 2022", [Paper] [Website]

* **CLIP-Fields**:"CLIP-Fields: Weakly Supervised Semantic Fields for Robotic Memory", "arXiv, Oct 2022", [Paper] [PyTorch Code] [Website]

* **VIMA**:"VIMA: General Robot Manipulation with Multimodal Prompts", "arXiv, Oct 2022", [Paper] [Pytorch Code] [Website]

* **Perceiver-Actor**:"A Multi-Task Transformer for Robotic Manipulation", CoRL, Sep 2022. [Paper] [Pytorch Code] [Website]

* **LaTTe**: "LaTTe: Language Trajectory TransformEr", arXiv, Aug 2022. [Paper] [TensorFlow Code] [Website]

* **Robots Enact Malignant Stereotypes**: "Robots Enact Malignant Stereotypes", FAccT, Jun 2022. [Paper] [Pytorch Code] [Website] [Washington Post] [Wired] (code access on request)

* **ATLA**: "Leveraging Language for Accelerated Learning of Tool Manipulation", CoRL, Jun 2022. [Paper]

* **ZeST**: "Can Foundation Models Perform Zero-Shot Task Specification For Robot Manipulation?", L4DC, Apr 2022. [Paper]

* **LSE-NGU**: "Semantic Exploration from Language Abstractions and Pretrained Representations", arXiv, Apr 2022. [Paper]

* **Embodied-CLIP**: "Simple but Effective: CLIP Embeddings for Embodied AI ", CVPR, Nov 2021. [Paper] [Pytorch Code]

* **CLIPort**: "CLIPort: What and Where Pathways for Robotic Manipulation", CoRL, Sept 2021. [Paper] [Pytorch Code] [Website]

## Instructions and Navigation <a name="research-instructions-and-navigation"></a>

* **ADAPT**: "ADAPT: Vision-Language Navigation with Modality-Aligned Action Prompts", CVPR, May 2022. [Paper]

* **Pre-Trained Vision Models for Control**: "The Unsurprising Effectiveness of Pre-Trained Vision Models for Control", ICML, Mar 2022. [Paper] [Pytorch Code] [Website]

* **CoW**: "CLIP on Wheels: Zero-Shot Object Navigation as Object Localization and Exploration", arXiv, Mar 2022. [Paper]

* **Recurrent VLN-BERT**: "A Recurrent Vision-and-Language BERT for Navigation", CVPR, Jun 2021 [Paper] [Pytorch Code]

* **VLN-BERT**: "Improving Vision-and-Language Navigation with Image-Text Pairs from the Web", ECCV, Apr 2020 [Paper] [Pytorch Code]

* **Interactive Language**: "Interactive Language: Talking to Robots in Real Time", arXiv, Oct 2022 [Paper] [Website]

## Simulation Frameworks <a name="research-simulation-frameworks"></a>

* **MineDojo**: "MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge", arXiv, Jun 2022. [Paper] [Code] [Website] [Open Database]

* **Habitat 2.0**: "Habitat 2.0: Training Home Assistants to Rearrange their Habitat", NeurIPS, Dec 2021. [Paper] [Code] [Website]

* **BEHAVIOR**: "BEHAVIOR: Benchmark for Everyday Household Activities in Virtual, Interactive, and Ecological Environments", CoRL, Nov 2021. [Paper] [Code] [Website]

* **iGibson 1.0**: "iGibson 1.0: a Simulation Environment for Interactive Tasks in Large Realistic Scenes", IROS, Sep 2021. [Paper] [Code] [Website]

* **ALFRED**: "ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks", CVPR, Jun 2020. [Paper] [Code] [Website]

* **BabyAI**: "BabyAI: A Platform to Study the Sample Efficiency of Grounded Language Learning", ICLR, May 2019. [Paper] [Code]

## Project Demos <a name="project-demos"></a> 

* **SPOT GPT**: "Boston Dynamics Integration of ChatGPT into SPOT Robot", Boston Dynamics, 2023, [[Video](https://www.youtube.com/watch?v=XyCKe3rrYik)] 

* **RobotGPT**: "Orangewood Labs RoboGPT Demo", Orangewood Labs, 2023, [[Video](https://www.youtube.com/watch?v=56Ip4CBfX-E)]

* **Mona**: "Vitruvian Works Robot Demonstration", Vitruvian Works, 2023, [[Video](https://www.youtube.com/watch?v=xZ7ROSxcako)]

* **Ameca**: "Ameca Expressions with GPT-3 / 4", Engineered Arts, 2023, [[Video](https://www.youtube.com/watch?v=yUszJyS3d7A)]

* **Sarcastic Robot**: "Sarcastic Robot powered by GPT-4", Gabrael Levine (Hackathon Project), 2023, [[Video](https://www.youtube.com/watch?v=PgT8tPChbqc)] 


## Educational Materials <a name="educational-materials"></a> 

* **Controlling Robots Via Large Language Models**: "Controlling Robots Via Large Language Models", *Sanjiban Choudhury, CS 4756/5756, Cornell, 2023* [[Slides](https://www.cs.cornell.edu/courses/cs4756/2023sp/assets/slides_notes/lec26_slides.pdf)]

## Thoughtful Twitter Threads <a name="thoughtful-twitter-threads"></a>
* **Bitter Lesson 2.0**: *@hausman_k, 2023* [[Thread](https://twitter.com/hausman_k/status/1612509549889744899 
)] 


Content
## Citation <a name="citation"></a>

If you find this repository useful, please consider citing this list:

```
@misc{rintamaki2023everythingllmsandroboticsrepo,
    title={Everything-LLMs-And-Robotics},
    author={Jacob Rintamaki},
    journal={GitHub repository},
    url={https://github.com/jrin771/Everything-LLMs-And-Robotics},
    year={2023},
}
```
