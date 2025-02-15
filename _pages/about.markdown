---
title: About Me
permalink: /about/
---

# About Me
![](/_assets/images/AboutMePhoto.jpg)

Hello! My name is Gary Seah and I am a aspiring software developer. I am adept at C, C++ and C#, with numerous game projects done within Unity as well as in custom written engines. 

Whilst most of my projects and experience are game projects, I typically take on a technical lead role, writing the backend low-level systems as well as tools in order to support my team in game creation. Examples would be robust debugging tools which logs engine components performance and an audio system with plug and play functionality to support audio clip transitions via the bpm and time signature of the audio clip. 

I am always seeking to better myself, choosing to tackle different aspects of projects to further my knowledge and experience. Areas I have tackled in past projects are:

<ul>
    <li> Virtual, Augmented and Mixed Reality </li>
    <li> Entity Component Systems via ENTT </li>
    <li> Networking </li>
    <li> Cloud Computing via Amazon Web Services </li>
    <li> Audio Systems via FMOD </li>
    <li> Game Editor utilising ImGUI and custom C++ engine </li>
    <li> Scripting via C# by utilizing .net integration in custom C++ engine </li>
</ul>

For my game development experience, I seek to create game experiences with unique gameplay mechanics. Some examples of these are:

<ul>
    <li> Local Multiplayer Smash-Style game where players move via the knockback of their gun, creating a chaotic gameplay experience as players fly around the screen in an attempt to both knock out other players while keeping themselves alive </li>
    <li> Fast-paced bullet hell boss rush game where players defeat the boss by typing out a passage, having to juggle between dodging bullets and typing </li>
    <li> 2D action game where the player utilises the keyboard to move the character by hitting keys that is mapped to a game area on the screen </li>
</ul>

In my free time, I enjoy photography and some bouldering. I am also a fan of board games, enjoying a quick game to wind down after a long day. 

# Qualifications
{% for item in site.data.qualifications %}
<span style='font-weight: bold;'>{{item.details.name_full}}</span>
<ul>
    <li><a href="{{item.details.website}}"> {{item.details.from}} </a></li>
    <li> {{item.details.year_start}} - {{item.details.year_end}} </li>
</ul>
{% endfor %}

# Notable Achievements
{% for item in site.data.achievements %}
<span style='font-weight: bold;'> {{item.achievementname}} </span>
<p> {{item.details.eventname}} | {{item.details.when}} <br> Issued by {{item.details.issuedby}} </p>
<hr>
<p> {{item.details.description}} <br> <br> </p>
{% endfor %}

    
