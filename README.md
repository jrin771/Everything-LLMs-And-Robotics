# Everything-LLMs-And-Robotics
The world's largest GitHub Repository for the intersection of LLMs (multimodal included!) + Robotics 

Heavily Inspired by [Awesome-LLM-Robotics](https://github.com/GT-RIPL/Awesome-LLM-Robotics)

# Logistics 
If you want to make a change this repository [click here](PR-Guide.md)

Why I made this: [Go here.](https://jrin771.github.io/EverythingLLMsAndRobotics.html)

# What Does This Repository Have? 

- [Education: LLMs](#llms) 
- [Education: Robotics](#robotics)
- [Education: LLMs + Robotics](#llms-and-robotics)
- [Research: Reasoning](#research-reasoning)
- [Research: Planning](#research-planning)
- [Research: Manipulation](#research-manipulation)
- [Research: Instructions and Navigation](#research-instructions-and-navigation)
- [Research: Simulation Frameworks](#research-simulation-frameworks)
- [Research: Perception](#research-perception)
- [Project Demos](#project-demos) 
- [Thoughtful Twitter Threads](#thoughtful-twitter-threads)
- [Citation](#citation)

## LLMs Educational Resources <a name="llms"></a>  
* **START HERE**: "Transformers from Scratch", Brandon Rohrer, [[Website](https://e2eml.school/transformers.html)]

* **Stanford Transformers Class**: "CS25: Transformers United", Stanford, 2022, [[Website](https://web.stanford.edu/class/cs25/)]

* **Andrej Karpathy GPT Tutorial**: "Let's build GPT: from scratch, in code, spelled out." Andrej Karpathy, 2023 [[Youtube Video](https://www.youtube.com/watch?v=kCc8FmEb1nY)]

## Robotics Educational Resources <a name="robotics"></a> 
* **AI-Enabled Robotics Class**: "CS199: Stanford Robotics Independent Study", Stanford, 2023, [[Website](https://pupper-independent-study.readthedocs.io/en/latest/index.html)] 

## LLMs + Robotics Educational Resources <a name="llms-and-robotics"></a> 
* **Google's 2022 Research**: "Google Research, 2022 & beyond: Robotics", Google, 2023, [[Website](https://ai.googleblog.com/2023/02/google-research-2022-beyond-robotics.html)]

* **Controlling Robots Via Large Language Models**: "Controlling Robots Via Large Language Models", *Sanjiban Choudhury, CS 4756/5756, Cornell, 2023* [[Slides](https://www.cs.cornell.edu/courses/cs4756/2023sp/assets/slides_notes/lec26_slides.pdf)]

## Reasoning <a name="research-reasoning"></a>  

* **LLM3**: "LLM3: Large Language Model-based Task and Motion Planning with Motion Failure Reasoning.", IROS,  Mar 2024. [[Paper](https://arxiv.org/abs/2403.11552)][[Code](https://github.com/AssassinWS/LLM-TAMP)]

* **AutoTAMP**: "AutoTAMP: Autoregressive Task and Motion Planning with LLMs as Translators and Checkers", arXiv, June 2023. [[Paper](https://arxiv.org/pdf/2306.06531.pdf)]

* **LLM Designs Robots**: "CAN LARGE LANGUAGE MODELS DESIGN A ROBOT?", arXiv, Mar 2023. [[Paper](https://arxiv.org/pdf/2303.15324.pdf)]

* **PaLM-E**: "PaLM-E: An Embodied Multimodal Language Model", arXiV, Mar 2023. [[Paper](https://arxiv.org/abs/2303.03378)] [[Website](https://palm-e.github.io)] [[Demo](https://palm-e.github.io/#demo)]

* **RT-1**: "RT-1: Robotics Transformer for Real-World Control at Scale", arXiv, Dec 2022. [[Paper](https://arxiv.org/abs/2212.06817)] [[Code](https://github.com/google-research/robotics_transformer)] [[Website](https://robotics-transformer.github.io)]

* **ProgPrompt**: "Generating Situated Robot Task Plans using Large Language Models", arXiv, Sept 2022.  [[Paper](https://arxiv.org/abs/2209.11302)] [[Code Doesn't Really Exist here](https://github.com/progprompt/progprompt)] [[Website](https://progprompt.github.io)]

* **Code-As-Policies**: "Code as Policies: Language Model Programs for Embodied Control", arXiv, Sept 2022.  [[Paper](https://arxiv.org/abs/2209.07753)] [[Code](https://github.com/google-research/google-research/tree/master/code_as_policies)] [[Website](https://code-as-policies.github.io)]

* **Say-Can**: "Do As I Can, Not As I Say: Grounding Language in Robotic Affordances", arXiv, Apr 2021. [[Paper](https://arxiv.org/abs/2204.01691)] [[Code](https://say-can.github.io/#open-source)] [[Website](https://say-can.github.io)]

* **Socratic**: "Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language", arXiv, Apr 2021. [[Paper](https://arxiv.org/abs/2204.00598)] [[Code](https://socraticmodels.github.io/#code)] [[Website](https://socraticmodels.github.io)]

* **PIGLeT**: "PIGLeT: Language Grounding Through Neuro-Symbolic Interaction in a 3D World", ACL, Jun 2021. [[Paper](https://arxiv.org/abs/2201.07207)] [[Code](https://github.com/rowanz/piglet)] [[Website](https://rowanzellers.com/piglet/)]

## Planning <a name="research-planning"></a>
* **LLM-GROP**: "Task and Motion Planning with Large Language Models for Object Rearrangement", arXiv, Mar 2023 [[Paper](https://arxiv.org/abs/2303.06247)]

* **Bio Lab Task Planning**: "LLMs can generate robotic scripts from goal-oriented instructions in biological laboratory automation", arXiv, April 2023 [[Paper](https://arxiv.org/abs/2304.10267)]

* **PromptCraft Robotics**: "ChatGPT for Robotics: Design Principles and Model Abilities", Microsoft, 2023, [[Paper](https://www.microsoft.com/en-us/research/uploads/prod/2023/02/ChatGPT___Robotics.pdf)], [[Website](http://aka.ms/ChatGPT-Robotics)], [[Code](https://github.com/microsoft/PromptCraft-Robotics)]

* **CLARIFY** "Errors are Useful Prompts: Instruction Guided Task Programming with Verifier-Assisted Iterative Prompting", arXiv, March 2023 [[Paper](https://arxiv.org/abs/2303.14100)][[Code](https://github.com/ac-rad/xdl-generation)][[Website](https://ac-rad.github.io/clairify/)]

* **LM-Nav**: "Robotic Navigation with Large Pre-Trained Models of Language, Vision, and Action", arXiv, July 2022. [[Paper](https://arxiv.org/abs/2207.04429)] [[Pytorch Code](https://github.com/blazejosinski/lm_nav)] [[Website](https://sites.google.com/view/lmnav)]

* **InnerMonlogue**: "Inner Monologue: Embodied Reasoning through Planning with Language Models", arXiv, July 2022. [[Paper](https://arxiv.org/abs/2207.05608)] [[Website](https://innermonologue.github.io)]

* **Housekeep**: "Housekeep: Tidying Virtual Households using Commonsense Reasoning", arXiv, May 2022. [[Paper](https://arxiv.org/abs/2205.10712)] [[Pytorch Code](https://github.com/yashkant/housekeep)] [[Website](https://yashkant.github.io/housekeep/)]

* **LID**: "Pre-Trained Language Models for Interactive Decision-Making", arXiv, Feb 2022. [[Paper](https://arxiv.org/abs/2202.01771)] [[Pytorch Code](https://github.com/ShuangLI59/Pre-Trained-Language-Models-for-Interactive-Decision-Making)] [[Website](https://shuangli-project.github.io/Pre-Trained-Language-Models-for-Interactive-Decision-Making/)]

* **ZSP**: "Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents", ICML, Jan 2022. [[Paper](https://arxiv.org/abs/2201.07207)] [[Pytorch Code](https://github.com/huangwl18/language-planner)] [[Website](https://wenlong.page/language-planner/)]

## Manipulation <a name="research-manipulation"></a>
* **MOO** "Open-World Object Manipulation using Pre-trained Vision-Language Models" arXiv, March 2023 [[Paper](https://arxiv.org/abs/2303.00905)] [[Website](https://robot-moo.github.io)]

* **TidyBot**: "TidyBot: Personalized Robot Assistance with Large Language Models", arXiV, May 2023, [[Paper](https://arxiv.org/abs/2305.05658) [Website](https://tidybot.cs.princeton.edu) [Paper Website](https://huggingface.co/papers/2305.05658)]

* **DIAL**:"Robotic Skill Acquistion via Instruction Augmentation with Vision-Language Models", arXiv, Nov 2022, [[Paper](https://arxiv.org/abs/2211.11736)] [[Website](https://instructionaugmentation.github.io)]

* **CLIP-Fields**:"CLIP-Fields: Weakly Supervised Semantic Fields for Robotic Memory", arXiv, Oct 2022, [[Paper](https://arxiv.org/abs/2210.05663)] [[PyTorch Code](https://github.com/notmahi/clip-fields)] [[Website](https://mahis.life/clip-fields/)]

* **VIMA**:"VIMA: General Robot Manipulation with Multimodal Prompts", arXiv, Oct 2022, [[Paper](https://arxiv.org/abs/2210.03094)] [[Pytorch Code](https://github.com/vimalabs/VIMA)] [[Website](https://vimalabs.github.io)]

* **Perceiver-Actor**:"A Multi-Task Transformer for Robotic Manipulation", CoRL, Sep 2022. [[Paper](https://peract.github.io/paper/peract_corl2022.pdf)] [[Pytorch Code](https://github.com/peract/peract)] [[Website](https://peract.github.io)]

* **LaTTe**: "LaTTe: Language Trajectory TransformEr", arXiv, Aug 2022. [[Paper](https://arxiv.org/abs/2208.02918)] [[TensorFlow Code](https://github.com/arthurfenderbucker/NL_trajectory_reshaper)] [[Website](https://www.microsoft.com/en-us/research/group/autonomous-systems-group-robotics/articles/robot-language/)]

* **Robots Enact Malignant Stereotypes**: "Robots Enact Malignant Stereotypes", FAccT, Jun 2022. [[Paper](https://arxiv.org/abs/2207.11569)]  [[Website](https://sites.google.com/view/robots-enact-stereotypes/home)] [Washington Post](https://www.washingtonpost.com/technology/2022/07/16/racist-robots-ai/)] [[Wired](https://www.wired.com/story/how-to-stop-robots-becoming-racist/)] (code access on request)

* **ATLA**: "Leveraging Language for Accelerated Learning of Tool Manipulation", CoRL, Jun 2022. [[Paper](https://arxiv.org/abs/2206.13074)]

* **ZeST**: "Can Foundation Models Perform Zero-Shot Task Specification For Robot Manipulation?", L4DC, Apr 2022. [[Paper](https://arxiv.org/abs/2204.11134)]

* **LSE-NGU**: "Semantic Exploration from Language Abstractions and Pretrained Representations", arXiv, Apr 2022. [[Paper](https://arxiv.org/abs/2204.05080)]

* **Embodied-CLIP**: "Simple but Effective: CLIP Embeddings for Embodied AI ", CVPR, Nov 2021. [[Paper](https://arxiv.org/abs/2004.14973)] [[Pytorch Code](https://github.com/arjunmajum/vln-bert)]

* **CLIPort**: "CLIPort: What and Where Pathways for Robotic Manipulation", CoRL, Sept 2021. [[Paper](https://arxiv.org/abs/2210.06407)] [[Pytorch Code]()] [[Website](https://interactive-language.github.io)]

## Instructions and Navigation <a name="research-instructions-and-navigation"></a>

* **Text2Motion**: "Text2Motion: From Natural Language Instructions to Feasible Plans", arXiv, Mar 2023 [[Paper](https://arxiv.org/abs/2303.12153)]

* **ChatGPT Robot Collaboration**: "Improved Trust in Human-Robot Collaboration with ChatGPT", arXiv, April 2023. [[Paper](https://arxiv.org/abs/2304.12529)]

* **ADAPT**: "ADAPT: Vision-Language Navigation with Modality-Aligned Action Prompts", CVPR, May 2022. [[Paper](https://arxiv.org/abs/2205.15509)]

* **Pre-Trained Vision Models for Control**: "The Unsurprising Effectiveness of Pre-Trained Vision Models for Control", ICML, Mar 2022. [[Paper](https://arxiv.org/abs/2203.03580)] [[Pytorch Code](https://github.com/sparisi/pvr_habitat)] [[Website](https://mahis.life/clip-fields/)]

* **CoW**: "CLIP on Wheels: Zero-Shot Object Navigation as Object Localization and Exploration", arXiv, Mar 2022. [[Paper](https://arxiv.org/abs/2203.10421)]

* **Recurrent VLN-BERT**: "A Recurrent Vision-and-Language BERT for Navigation", CVPR, Jun 2021 [[Paper](https://arxiv.org/abs/2011.13922)] [[Pytorch Code](https://github.com/YicongHong/Recurrent-VLN-BERT)]

* **VLN-BERT**: "Improving Vision-and-Language Navigation with Image-Text Pairs from the Web", ECCV, Apr 2020 [[Paper](https://arxiv.org/abs/2004.14973)] [[Pytorch Code](https://github.com/arjunmajum/vln-bert)]

* **Interactive Language**: "Interactive Language: Talking to Robots in Real Time", arXiv, Oct 2022 [[Paper](https://arxiv.org/abs/2210.06407)] [[Website](https://interactive-language.github.io)]

## Simulation Frameworks <a name="research-simulation-frameworks"></a>
* **MineDojo**: "MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge", arXiv, Jun 2022. [[Paper](https://arxiv.org/abs/2206.08853)] [[Code](https://github.com/MineDojo/MineDojo)] [[Website](https://minedojo.org)] [[Open Database](https://minedojo.org/knowledge_base.html)]

* **Habitat 2.0**: "Habitat 2.0: Training Home Assistants to Rearrange their Habitat", NeurIPS, Dec 2021. [[Paper](https://arxiv.org/abs/2106.14405)] [[Code](https://github.com/facebookresearch/habitat-sim)] [[Website](https://aihabitat.org)]

* **BEHAVIOR**: "BEHAVIOR: Benchmark for Everyday Household Activities in Virtual, Interactive, and Ecological Environments", CoRL, Nov 2021. [[Paper](https://arxiv.org/abs/2108.03332)] [[Code](https://github.com/StanfordVL/behavior)] [[Website](https://behavior.stanford.edu)]

* **iGibson 1.0**: "iGibson 1.0: a Simulation Environment for Interactive Tasks in Large Realistic Scenes", IROS, Sep 2021. [[Paper](https://arxiv.org/abs/2012.02924)] [[Code](https://github.com/StanfordVL/iGibson)] [[Website](https://svl.stanford.edu/igibson/)]

* **ALFRED**: "ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks", CVPR, Jun 2020. [[Paper](https://arxiv.org/abs/1912.01734)] [[Code](https://github.com/askforalfred/alfred)] [[Website](https://askforalfred.com)]

* **BabyAI**: "BabyAI: A Platform to Study the Sample Efficiency of Grounded Language Learning", ICLR, May 2019. [[Paper](https://openreview.net/pdf?id=rJeXCo0cYX)] [[Code](https://github.com/mila-iqia/babyai/tree/iclr19)]

## Perception <a name="research-perception"></a> 
* **Matcha agent**: "Chat with the Environment: Interactive Multimodal Perception Using Large Language Models", IROS 2023. [[Paper](https://arxiv.org/abs/2303.08268)]  [[Poster](https://matcha-agent.github.io/img/matcha-poster.pdf)] [[Code](https://github.com/xf-zhao/Matcha-agent)] [[Video](https://youtu.be/rMMeMTWmT0k)] [[Website](https://matcha-agent.github.io/)]

* **LGX**: "Can an Embodied Agent Find Your "Cat-shaped Mug"? LLM-Based Zero-Shot Object Navigation", arXiv, Mar 2023. [[Paper](https://arxiv.org/abs/2303.03480)]

* **Robots Acquire Skills With VLMs**: "Robotic Skill Acquisition via Instruction Augmentation with Vision-Language Models" arXiv, Nov 2022. [[Paper](https://arxiv.org/abs/2211.11736)]

* **From Occulation To Insight**: "From Occlusion to Insight: Object Search in Semantic Shelves using Large Language Models", arXiv, Feb 2023, [[Paper](https://arxiv.org/abs/2302.12915)]

## Project Demos <a name="project-demos"></a> 
* **RobotGPT Pt.2** "Twitter Video Of Voice-Input LLM-Powered Robot Arm", Orangewood Labs, 2023, [[Video](https://twitter.com/Abhindas1/status/1651625638485446657)]

* **SPOT GPT**: "Boston Dynamics Integration of ChatGPT into SPOT Robot", Boston Dynamics, 2023, [[Video](https://www.youtube.com/watch?v=XyCKe3rrYik)] 

* **RobotGPT**: "Orangewood Labs RoboGPT Demo", Orangewood Labs, 2023, [[Video](https://www.youtube.com/watch?v=56Ip4CBfX-E)]

* **Mona**: "Vitruvian Works Robot Demonstration", Vitruvian Works, 2023, [[Video](https://www.youtube.com/watch?v=xZ7ROSxcako)]

* **Ameca**: "Ameca Expressions with GPT-3 / 4", Engineered Arts, 2023, [[Video](https://www.youtube.com/watch?v=yUszJyS3d7A)]

* **Sarcastic Robot**: "Sarcastic Robot powered by GPT-4", Gabrael Levine (Hackathon Project), 2023, [[Video](https://www.youtube.com/watch?v=PgT8tPChbqc)] 

* **DroneFormer**: "DroneFormer: Controlling UAVs with natural language!", Brian Wu (Hackathon Project), Stanford University, 2023 [[Video](https://www.youtube.com/watch?v=8dJcT7-VHNs)]

## Thoughtful Twitter Threads <a name="thoughtful-twitter-threads"></a>
* **Bitter Lesson 2.0**: *@hausman_k, 2023* [[Thread](https://twitter.com/hausman_k/status/1612509549889744899 
)] 

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
