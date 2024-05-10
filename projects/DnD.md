---
layout: project
type: project
image: img/Dnd/DnDCover.jpeg
title: "DnD Campaign"
date: 2022
published: true
labels:
  - Teamwork
  - Creativity
  - Javascript
summary: "Imagined, organized, and maintained a Dungeons and Dragons campaign for a year with various physical and coded builds to aid our campaign."
---
<div class="text-center p-4">
  <img width="600px" src="../img/DnD/DnD1.jpeg" class="img-thumbnail" >
  <img width="200px" src="../img/DnD/DnD2.jpeg" class="img-thumbnail" >
  <img width="200px" src="../img/DnD/DnD3.jpeg" class="img-thumbnail" >
</div>

## Overview
This project is a year-long Dungeons and Dragons campaign that ran from the spring of 2022 until the spring of 2023. I worked together with the Game Master to build the game, the terrain, and created a program for the game as well.

## My Role
This DnD campaign was one of the first ones I had a hand in creating instead of just participating in. I had just began to learn how to code in Javascript and decided to create a random dice roll program to use for our game just for fun, especially for when our party met remotely instead of physically at the table. In addition to the dice roll program I also created physical terrain builds to aid in immersion and table-top quality during gaming sessions. 

## What Have I Learned?
This project helped me gain experience using Javascript and was part of how I discover how coding can be applicable to real-life scenarios even in small ways. Other than technical skills, this campaign put me in a position of leadership where I had to consistently organize and maintain gaming sessions, story-building, and manage a team of 8 players. This helped me learn how to lead complex projects and foster teamwork and creativity in a group of people new to the game. 

```javascript
function roll(diceType){
    let diceRoll = 0;
    // Roll a D20
    if(diceType === 20){
        diceRoll = Math.floor(Math.random() * 20) + 1;
        return "You rolled " + diceRoll;
    }
    // Roll a D12
    else if(diceType === 12){
        diceRoll = Math.floor(Math.random() * 12) + 1;
        return "You rolled " + diceRoll;
    }
    // Roll a D10
    else if(diceType === 10){
        diceRoll = Math.floor(Math.random() * 10) + 1;
        return "You rolled " + diceRoll;
    }
    // Roll a D8
    else if(diceType === 8){
        diceRoll = Math.floor(Math.random() * 8) + 1;
        return "You rolled " + diceRoll;
    }
    // Roll a D6
    else if(diceType === 6){
        diceRoll = Math.floor(Math.random() * 6) + 1;
        return "You rolled " + diceRoll;
    }
    // Roll a D4
    else if(diceType === 4){
        diceRoll = Math.floor(Math.random() * 4) + 1;
        return "You rolled " + diceRoll;
    }
    else {
        return "That dice type does not exist!";
    }
}

console.log(roll(20));
console.log(roll(12));
console.log(roll(10));
console.log(roll(8));
console.log(roll(6));
console.log(roll(4));
console.log(roll(2));

