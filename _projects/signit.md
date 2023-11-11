---
layout: page
title: SignIt!
description: a sign language based quiz platform
img: assets/img/SignIt_project_cover.png
importance: 1
category: work
---

# SignIt! An Android Game for Bilingual Play

SignIt! is a sign language-based quiz platform co-designed with the Indian Deaf and Hard-of-Hearing community. Here, I'll describe the three primary features of SignIt!.

<style>
.custom-img {
  height: 300px;
  width: auto; /* maintain aspect ratio */
  max-width: 100%; /* max width is the width of the parent element */
}
</style>

### Feature 1: Sign language-based quizzes

The quizzes contain a series of multiple-choice questions. The question interface contains the question sign language video and a grid of option sign language videos below it. Each video contains a hint button to toggle the visibility of the corresponding English translation. This interface supports the player in discovering and learning new vocabulary in both languages while playing quizzes.

<div class="row">

<div class="col-sm mt-3 mt-md-0 d-flex justify-content-center">

{% include figure.html path="assets/img/SignQuizzes.png" title="question interface" class="custom-img rounded z-depth-1" height="350 px" alt="Two screenshots showing the question interface of SignIt!. In the first screenshot, the sign language video of the question is at the top with a grid of four option videos below it. In the second screenshot is the same as the first one except the English translation of the Question and third option is shown."%}

</div>

</div>

<div class="caption">

Question Interface of a SignIt! quiz

</div>

### Feature 2: Social Gameplay

There are two modes to play socially:

<ul>
<li> <b>Live mode: </b>The live mode allows multiple players to play a quiz together in real-time.</li>
<li> <b>Group mode: </b> The group members play group quizzes asynchronously and compete on a common leaderboard.</li>
</ul>

<div class="row justify-content-sm-center">

<div class="col-sm-4 mt-3 mt-md-0">

{% include figure.html path="assets/img/SignIt_livemode.jpg" title="Live mode score screen" class="custom-img rounded z-depth-1" height="350 px" alt="A screenshot of a score screen in live mode. It contains the points awarded in the current question, total score, and a leaderboard of three players in descending order of their scores." caption="Live mode score screen"%}

</div>

<div class="col-sm-4 mt-3 mt-md-0">

{% include figure.html path="assets/img/SignIt_groupMode.png" title="Group details screen" class="custom-img rounded z-depth-1" height="350 px" alt="A screenshot of the group details screen. It shows the group image, creator, common leaderboard showing top three players, and a list of group quizzes." caption="Group details screen"%}

</div>

</div>


### Feature 3: Content creation

SignIt! allows players to design their own quizzes based on their interests and knowledge, and share them with others. To create questions, players have two options:

<ul>
<li> <b>Create questions from scratch:</b> The player needs to add the question and the options in both sign language and English. They also need to mark the correct answer among the options. </li>
<li> <b>Find questions from existing sources:</b> The player can select the text of multiple questions from the repository and add them to their quiz. They need to add the corresponding sign language videos for each question and their options. </li>
</ul>

Each question of a quiz must have at least two options. To record the sign language videos, the player will be guided by a video recording interface that helps them position themselves correctly before the recording starts.

Quiz creation leads to labelled sign language data collection. An interesting enhancement to this feature could be to offer customizable avatars for quiz creators. This would add personalization and help maintain anonymity by representing videos through these avatars. 

<div class="row justify-content-center">

<div class="col-sm-4 mt-3 mt-md-0">

{% include figure.html path="assets/img/CreateQuizInterface.jpg" title="Create Quiz Interface" class="custom-img rounded z-depth-1" height="350 px" alt="A screenshot of the create quiz interface with options to change the quiz image, add quiz title, and two buttons to create and find questions respectively." caption="Create quiz screen"%}

</div>

<div class="col-sm-4 mt-3 mt-md-0">

{% include figure.html path="assets/img/CreateQuizRecord.jpg" title="Video Recording Interface" class="custom-img rounded z-depth-1" height="350 px" alt="A video recording interface with the prompt 'Good' to indicate that their upper body is visible" caption="Video recording interface"%}

</div>
</div>

<hr/>

Thank you so much for reading! This work would not be possible without the support of the [National Institute of Speech and Hearing (NISH)](https://nish.ac.in/). NISH is a comprehensive multi-purpose institute focusing on the identification, intervention, rehabilitation and education of individuals with disabilities. 

We're in the process of open-sourcing the code of SignIt! This platform is designed to be language-agnostic, accommodating any sign language and spoken language (both of which need to be specified while creating the quiz). 

We envision organizations setting up their own storage accounts for data and hosting SignIt! independently. The anonymous data from the videos and their labels could be streamlined into an open-source repository. This could serve as a valuable resource for advancing research in sign language recognition using machine learning. 