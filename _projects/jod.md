---
layout: page
title: Jod
description: a videoconferencing platform for mixed hearing groups
img: assets/img/Jod_cover.jpeg
importance: 3
category: work
---

# <i>Jod</i>: A Videoconferencing Platform for Mixed Hearing Groups
<i>Jod</i>’s features were iteratively designed using a combination of findings from prior work examining accessibility barriers in current videoconferencing platforms and feedback received from the participants in the first user study session. 

## Prior work
Three primary challenges faced by Deaf and Hard of Hearing (DHH) individuals when using existing videoconferencing platforms:

1. **Limited Layout Customization**: Current platforms offer minimal options for customizing layouts and often automatically adjust and distribute video thumbnails, making visual communication difficult.

2. **Communication Difficulties**: DHH individuals often struggle to capture the attention of others, and in mixed hearing videoconferencing scenarios, both hearing and DHH participants face challenges in remembering appropriate communication accommodations.

3. **Audio-Centric Design**: Existing platforms predominantly prioritize audio, and do not highlight signing individuals’ video tile.

## <i>Jod</i> Features
1. **Customizable Visual Layout**: Users can easily resize, add, remove, and reposition video tiles, captions, and screen share windows, enabling them to reorganize their visual layout to suit their personal preferences. Refer to Figure <a href="#videotile">2a</a>.

2. **Preset Feedback Messages**: Users can send predefined feedback messages like <i>“Please look at me”</i>, <i>“Please keep your upper body visible”</i>, <i>“Please turn on some lights”</i>, <i>“Please speak slower”</i>, <i>“Please use easier language”</i>, and <i>“Please repeat what you said”</i> by hovering over a participant's video tile, promoting effective communication. Refer to Figure <a href="#videotile">2a</a>.

3. **Active Signer Identification**: <i>Jod</i> uses a Wizard of Oz method to identify the active signer.

4. **Accessibility Indicators**: Users can specify their participant type (Deaf, Hearing, or Interpreter) upon joining a call, denoted by colors, icons, and labels in the user interface.

5. **Enhanced Transcription**: <i>Jod</i> improves audio transcriptions and captions by including preset feedback messages, emoji reactions, and indicating when a DHH user begins or stops signing. Transcriptions also display the accessibility indicator of each participant. Refer to Figure <a href="#transcription">2b</a>.

6. **Gesture Recognition**: To enhance feedback options while muted, users can use four emoji-based gestures: clap, hand raise, okay, and thumbs-up, which can be enabled by clicking on "Enable Gestures" in the gesture control bar. Refer to Figure <a href="#ui_interface">1</a>.

Here are some screenshots of Jod: 

<div class="row">

<div class="col-sm mt-3 mt-md-0 d-flex justify-content-center">

{% include figure.html id="ui_interface" path="assets/img/UI-Interface.png" title="question interface" class="custom-img rounded z-depth-1" height="350 px" alt="A full-screen screenshot of the user interface of Jod with six participants (3 DHH, 1 ISL interpreter, 2 hearing individuals) on a simulated video call. The background is dark, and the text is white. Three participants (Priya P, Interpreter Indira I, and Neel N) have their videos turned on, and their faces are blurred for anonymity. The top panel contains icons for the gesture and call controls. The right panel has three tabs: People, Chat, and Transcription. The people tab is selected and lists the six participants' names vertically: Priya P, Neel N, Indira I, Meera M, Anna A, and Shreya S. There is a mike and video icon to the arranged horizontally to the right and an accessibility indicator icon to the left of each participant name. Shreya S's video tile has been removed, so there is an Add button to the right of her video icon in the People tab. The remaining visual space on the left is used for rendering video tiles and a captions box centered under them. The interpreter Indira's video tile is the largest and in the center. To the left of it are two equally sized video tiles for DHH participants -  Priya vertically followed by Meera. On the right of the interpreter are two equally sized video tiles for hearing participants -  Neel N vertically followed by Anna A."%}
</div>
</div>
<div class="caption">
Figure 1: User Interface of <i>Jod</i> with six participants on a simulated video call. 6 participants comprise 3 DHH, 2 Hearing, and 1 Interpreter.
</div>

<div class="row d-flex justify-content-center">

<div class="col-sm-5 mt-3 mt-md-0 " style="margin-right: 40px;">

{% include figure.html id="videotile" path="assets/img/Video-Tile-Hover.png" title="Video Tile Hover State" class="custom-img rounded z-depth-1" height="160 px" alt="Jod's video tile hover state with labeled icon buttons and corners using which a person can resize the video tile. The video tile is of the simulated participant Neel N. In the top-left corner, there are three icons labeled (a) Lock/Unlock video Tile, (b) Remove Video tile, and (c) Turn Neel N's video feed on or off. In the bottom-right corner are 6 icons, one for sending each preset message. From left to right, they are labeled as: (e) Request Neel N to look at you, (f) Request Neel N to keep their upper body visible, (g) Request Neel N to turn on lights, (h) Request Neel N to speak slowly, (i) Request Neel N to use easier language, and (j) Request Neel N to repeat what they said." caption="(a) Video Tile Hover State"%}

</div>

<div class="col-sm-3 mt-3 mt-md-0">

{% include figure.html id="transcription" path="assets/img/Enhanced-Transcription.png" title="Transcriptions Panel" class="custom-img rounded z-depth-1" height="160 px" alt="A zoomed-in screenshot of the participant Priya P's transcription panel showing a snippet of conversation between Priya, Indira, and Neel. The UI background is dark, and the text is white. Three are three accessibility indicator icons to the left of each participant's name: a green-colored DHH icon for Priya, a red-colored icon for interpreter Indira, and a blue-colored hearing icon for Neel. The user interface components are labeled to show (a) when Priya P started signing, (b) a sample ASR output 'We are going to game.', a preset feedback message 'Please speak slower' which Priya sent to Neel, (c) an okay emoji reaction from Neel, and (d) when Priya P stopped signing." caption="(b) Transcription Panel"%}

</div>

</div>

<div class="caption">
Figure 2: Jod’s System Features: Customizable Visual Layout, Preset Feedback Messages, and Enhanced Transcriptions
</div>

## User Study 
Using Jod, we conducted **six mixed hearing group sessions**, with four held in person and two conducted remotely, with a total of 34 participants. This group comprised **18 d/Deaf or hard of hearing participants, 10 hearing participants, and six sign language interpreters**.

Each study session lasted approximately **2.5 hours** and included three DHH signers, one or two interpreters, two hearing individuals, and two hearing researchers. Our sessions had the following structure:
<ul>
<li>10-minute <i>Jod</i> tutorial</li>
<li>30-minute task-based explorations to acquaint participants with Jod's features</li>
<li>Unstructured conversations on topics like food and festivals</li>
<li>Modified version of the charades game to promote direct communication</li>
<li>Presentation round incorporating screen sharing.</li>
</ul>

The study culminated in a **focus group discussion** aimed at comprehending participants' general perceptions of Jod, collecting detailed feedback on its key features, and gathering suggestions for potential future enhancements.

The study protocol maintained consistency across both remote and in-person sessions. During remote sessions, we conducted initial introductions, <i>Jod</i> onboarding, and focus group discussions on Zoom, while all other study-related activities took place on Jod.

### Some Findings
<ol>
<li> DHH participants chose to allocate significant visual space to the interpreter, while some opted to keep all participants on the screen, minimizing the visual presence of hearing participants. Others even removed hearing participants from their view. However, manually resizing video tiles proved time-consuming. </li>

<li> Interpreters adjusted the size of DHH participants' and researchers' video tiles, making them larger than others. </li>

<li> A valuable "started signing" message in captions and transcriptions helped interpreters and hearing participants identify signers. DHH participants used transcriptions to follow conversations and captions to verify interpretations or continue conversations when the interpreter wasn't available. </li>

<li> Concerning preset messages, a DHH participant appreciated capturing the attention of the interpreter with ease. A hearing participant directly conversed with a DHH participant without the interpreter. However, participants noted two issues: notification messages required manual dismissal, and there was no acknowledgment of receipt. </li>
</ol>

### Design Recommendations
These are some of the design recommendations from the paper:
<ol>
  <li>Providing quick layout options like one-click actions for adding/removing video tiles based on hearing ability, a revert button for layout changes, and dynamic templates to suit various conversation needs.</li>
  <li>Making preset message notifications less obstructive and allowing recipients to acknowledge them. It is also important to consider priority of the notification based on the communication context.</li>
  <li>Videoconferencing platforms may improve user profiles by enabling users to add sign names through short self-recorded videos.</li>
</ol>


### Insights from In-Person Sessions
The in-person study sessions, especially the charades game, played a crucial role in fostering camaraderie among participants. It helped them get more comfortable with each other and encouraged direct communication. The focus group discussions allowed for productive conversations between hearing and DHH participants and provided valuable feedback on feature suggestions. I believe that the these sessions proved more effective than individual interviews would have been.

<hr/>

Please find the full paper - <a href="/assets/pdf/assets23_5.pdf">Jod Paper</a>

We’d like to express our sincere thanks to the [WinVinaya foundation](https://winvinayafoundation.org/) for their invaluable support in this study. I encourage you to support their mission of providing employment opportunities for people with disabilities. On a personal note, it was a great experience to collaborate with [Anant Mittal](https://anantmittal.github.io/#/) and [Meghna Gupta](https://gupta-meghna64.github.io/) for the first time on this research. I learned a lot from them and was truly inspired by their dedication, hard work, and kindness.
