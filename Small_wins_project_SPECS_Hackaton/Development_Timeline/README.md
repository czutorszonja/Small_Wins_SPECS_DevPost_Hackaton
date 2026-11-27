# Small Wins: from boxes to a home

How Small Wins, an AR wellbeing app for Snap Spectacles, was designed and built in Lens Studio from 3 to 8 November 2026. Every picture is a screenshot taken inside Lens Studio during the build, and the times match the commit history.

**[Open the full build diary](https://czutorszonja.github.io/Small_Wins_SPECS_DevPost_Hackaton/Small_wins_project_SPECS_Hackaton/Development_Timeline/)** · [Demo video](https://www.youtube.com/watch?v=LoUa37ri7Uc)

![From the first boxy build to the near-final room](preview.jpg)

## 1. Where it started: a room made of boxes

The first working version already had chores, a reward, breathing, a door and a notebook, each with a LEAF test. But the room was flat coloured boxes, and Lens Studio's grey grid floor showed straight through it.

<img src="img/s001.jpg" width="49%" alt="The first room in the Lens Studio editor"> <img src="img/s004.jpg" width="49%" alt="Floor and cabinets as flat colour blocks">

## 2. Building it up: real models and a real home

Every box was replaced with a generated, textured 3D model, one object at a time. The room grew and was arranged into a kitchen, a living area, a dining table and a bedroom, then filled with the details that make a home.

<img src="img/s008.jpg" width="32%" alt="The first generated sofa"> <img src="img/s065.jpg" width="32%" alt="Bookshelf and dresser"> <img src="img/s092.jpg" width="32%" alt="The cat by its bowl">

## 3. Toning it down

The first restyle was too loud: patterned tiles in every colour and a bright teal wall. It was calmed into warm, soft colours, because an app about rest should feel restful. The light was then fixed so the room shows at full brightness without the preview's horizon line.

<img src="img/s026.jpg" width="32%" alt="Too busy: patterned tiles"> <img src="img/s056.jpg" width="32%" alt="Calmer kitchen"> <img src="img/s163.jpg" width="32%" alt="Full brightness in the editor">

## 4. From one crowded notebook to one job per card

Everything started in one big notebook. It was broken up: raising your hand shows three choices, Me-time, Today's wins and To-do list, and each opens its own card.

<img src="img/s058.jpg" width="32%" alt="Everything in one notebook"> <img src="img/s086.jpg" width="32%" alt="Three choices in the hand menu"> <img src="img/s087.jpg" width="32%" alt="To-do list on its own card">

## 5. A planner that is safe to walk with, and easy on the eye

A solid block hides the room, so on real glasses you could walk into a chair or a person. The first see-through version had a dark strip behind every line and looked busy. The fix: one card, one teal, and an outline only on things you can press.

<img src="img/s181.jpg" width="32%" alt="One solid block"> <img src="img/u_planner.jpg" width="32%" alt="See-through but busy"> <img src="img/s308.jpg" width="32%" alt="Final calm see-through card">

## 6. Two bugs that took the longest

A band of "light" crossed the room during box breathing. It took days to trace back to the mouse pointer's ray. Guided drawing floated in the room and once lost its paper, until the guide became one image on a framed sheet.

<img src="img/u_breathing.jpg" width="24%" alt="Box breathing with the light band"> <img src="img/g_08_Box_Breathing.jpg" width="24%" alt="Box breathing fixed"> <img src="img/u_drawing.jpg" width="24%" alt="Floating drawing"> <img src="img/s102.jpg" width="24%" alt="Drawing on a framed sheet">

---

Built in Lens Studio 5.23.2 with TypeScript, the Spectacles Interaction Kit and UI Kit, and 23 LEAF test scenarios. © Szonja Czutor. All rights reserved.
