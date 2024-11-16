---
layout: page
permalink: /schedule/
title: Schedule
nav: true
nav_order: 2
---
# Schedule

| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;|
|-------------|:-------------|
|__AM__&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;||
| 9:00-9:15 | Opening Remarks |
| 9:15-10:00 | Invited Talk 1 - Diyi Yang (Stanford) |
| 10:00-10:45 | Invited Talk 2 - Hanna Kirk (Oxford) |
| 10:45-11:00 | Coffee Break |
| 11:00-12:00 | Poster Session |
|-------------|:-------------|
|__PM__||
| 13:10-14:00 | Invited Talk 3 - Jared Roesch (Nvidia) |
| 14:00-14:45 | Invited Talk 4 - Manling Li (Northwestern) |
| 14:45-15:30 | Invited Talk 5 - Maartje Ter Hoeve (Apple)  |
| 15:30-16:00  | Coffee Break |
| 16:00-16:30 | Outstanding Papers Oral Presentations (10 min each) |
| | 1. Constructing Domain-Specific Evaluation Sets for LLM-as-a-judge |
| | 2. Trustful LLMs: Customizing and Grounding Text Generation with knowledge bases and Dual Decoders |
| | 3. Customizing LLM Generation in Safety Scenarios with Active Learning for Enhanced Representativeness and Robustness |
| 16:30-17:00 | Best Paper Award + Closing Remarks |

# Speakers
<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/diyi.jpg" alt="Diyi Yang">
            <p><a href="https://cs.stanford.edu/~diyiy/">Diyi Yang</a>
            <br>Stanford University</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/hannah.jpeg" alt="Hannah Rose Kirk">
            <p><a href="https://www.hannahrosekirk.com/">Hannah Rose Kirk</a>
            <br>University of Oxford</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/jared.jpg" alt="Jared Roesch">
            <p><a href="https://jroesch.github.io/">Jared Roesche</a>
            <br>Nvidia, ex-Octo AI, University of Washington</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/manling.jpg" alt="Manling Li">
            <p><a href="https://limanling.github.io">Manling Li</a>
            <br>Northwestern University</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/maartje.jpg" alt="Maartje Ter Hoeve">
            <p><a href="https://maartjeth.github.io">Maartje ter Hoeve</a>
            <br>Apple ML Research</p>
        </div>
    </div>
</html>

## Customizing Language Models for Social Interactions (Diyi Yang)
For large language models to work effectively in everyday social interactions, customization is essential. This talk explores recent approaches to tailoring LLMs for realistic social scenarios, from simulating mental health interactions to aligning outputs with specific preferences and styles. The first part introduces Roleplay-doh, a human-LLM collaboration pipeline that translates expert feedback into actionable principles, enabling more realistic roleplay experiences for counselor training.  The second part presents Demonstration Iterated Task Optimization (DITTO), a technique for personalizing model responses using only a few demonstrations. Finally, we discuss the potential of LLMs enabling personalized interactions across different applications.

## One Size Fits None? Interrogating Personalised AI Alignment (Hanna Kirk)
Current AI alignment approaches typically represent either a statistical mean of human behaviour or an institutional stance while claiming broader universality. This talk examines the limitations of such approaches and explores personalisation as a potential pathway toward more nuanced adjudication of alignment norms. Key data gaps are identified that have limited our understanding of interpersonal variations in human preferences for AI behaviour. The PRISM alignment dataset is presented as a new resource that collects preferences from a diverse pool, explicitly accommodates subjective disagreement, and contextualises human feedback to a personalised profile. While personalisation shows promise for enabling more natural and free human-AI interaction, it also presents risks of systems that may optimise for individual preferences in potentially problematic ways. The talk concludes by examining open questions in personalised AI alignment that merit further investigation.

## From Michelin to McDonald's: Mass Market Models, Your Way! (Jared Roesche)
"As artificial intelligence (AI) and machine learning (ML) have shifted from niche applications to mainstream tools, the expectations and expertise of users have transformed significantly. Increasingly, users with limited technical backgrounds are applying powerful models to new tasks, often without clear task formulations or technical guidance.

This talk will share lessons learned at OctoAI while building  infrastructure for customizable models for a diverse, predominantly non-expert audience, grounded in real-world use cases we encountered along the way.

Many longstanding research problems are now emerging in the context of non-expert users, yet they require re-framing to be accessible and usable. Key topics include defining tasks effectively, establishing robust and interpretable model evaluations, and designing datasets and systems for training, fine-tuning, and evaluation. By addressing these challenges, this talk aims to help bridge the gap between research innovation and practical applications, fostering a more accessible and effective use of AI for all.

## Advancing NLP equally for everyone (Maartje ter Hoeve)
As LLMs become more commonplace and play an increasingly important role in people’s lives, it is important to ask how we can make equal progress in NLP for everyone. In this talk, we will cover three angles to address this question: (1) people’s preferences and expectations when interacting with NLP systems, (2) multilingual setups, and (3) low-resource scenarios. Amongst others, we will find that personalization plays a prominent role. We will end with important future directions for NLP researchers to focus on, so that we advance NLP equally for everyone.

## Customizing Large Language Models to Large Agent Models Interacting with Physical World (Diyi Yang)
While Large Language Models excel in language processing, Large Agent Models are designed to interact with the environment. This transition poses significant challenges in understanding lower-level visual details, and long-horizon reasoning for effective goal interpretation and decision-making. Despite the impressive performance of LLMs/VLMs on various benchmarks, these models perceive images as bags of words (semantic concepts). In detail, they use semantic understanding as a shortcut but lack the ability to recognize geometric structures or solve spatial problems such as mazes. To interact with the physical world, we focus on two dimensions: (1) From high-level semantic to low-level geometric understanding: We introduce a low-level visual description language that serves as geometric tokens, allowing the abstraction of multimodal low-level geometric structures. (2) From fast-thinking to slow-thinking: We propose to quantify long-horizon reasoning by incorporating Markov Decision Process (MDP) based decision-making. The key difference between language models and agent models lies in their decision-making capabilities. This fundamental difference necessitates a shift in how we approach the development of large agent models, focusing on both geometric understanding and long-term planning to create more capable embodied AI agents.
 


<style>
    /* Style for the team container */
.team-container {
    display: grid;
    grid-template-columns: repeat(5, 1fr); /* Display 3 members per row */
    gap: 5px;
    max-width: 1000px;
    padding: 20px;
}

@media (max-width: 768px) {
    .team-container {
        grid-template-columns: repeat(2, 1fr); /* Display 2 members per row on smaller screens */
    }
}

/* Style for each team member */
.team-member {
    text-align: center;
    background-color: #fff;
    padding: 0px;
    width: 150px; /* Set a fixed width for consistent circle appearance */
    height: 260px; /* Set a fixed height for consistent circle appearance */
    /* box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1); */
    overflow: hidden; /* Hide any image overflow */
}


.team-member h3 {
    font-size: 16px;
    color: #333;
}

.team-member img {
  object-fit: cover;
  border-radius:50%;
  width: 150px;
  height: 150px;
  padding: 10px;
}

.sponsor-container {
    display: flex;
    gap: 5px;
}

.sponsor {
    flex: 1;
    margin: 10px;
    text-align: center;
    box-sizing: border-box;
    height: 50px;
    width: 50px;
}

.sponsor img {  
    width: 100%; /* Make the image take up 100% of the figure's width */
    height: 100%;
    object-fit: contain; 
}

.caption {
    margin-top: 12px; /* Adjust the margin to control the gap between the figure and the caption */
}

.right-half {
    flex: 1; /* Each figure takes up 50% of the available width */
    height: 500px; /* Set a fixed height for all figures (adjust the value as needed) */
}
</style>
