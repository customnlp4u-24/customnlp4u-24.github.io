---
layout: page
permalink: /schedule/
title: Schedule
nav: true
nav_order: 2
---
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

# Schedule

<br>

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