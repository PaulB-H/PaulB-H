Sep 15

I think I actually discovered an issue with one of the prototype Unreal assets.

The "BP_DoorFrame" from the FPS arena template has a property for "add door" which can be set to false to remove the door, and true to add it again

However, if you toggle it off, upon toggling back on, the collision does not get set correctly on the door trigger and it can not be opened.

It was not enough to change the collision type to "Query Only" with a set collision enabled node, I had to actually change the profile to "OverlapAllDynamic" using set collision profile name -> This is kinda the weird part to me that I still don't understand, Unreal's AI said it was due to serialization of collision data on BP Instances when using a custom collision profile but thats still over my head...

---

Sep 3

Characters in ~ Looking much better with a Monospaced Japanese font too

https://github.com/user-attachments/assets/4c842473-72b5-4bba-bc31-ee99bf65619a

---

Sep 2

My JavaScript DititalRain effect in HLSL, made by pointing deepseek at the repo and a few rounds of tweaks.

https://github.com/user-attachments/assets/6ce64fa0-ac74-428d-a457-4198af616301

---

Aug 22

Made a track with Spline + Spline Extrude for the road + Spline Instantiate for side details.
Tweaked Radiant GI & some post processing effects.

<img width="1920" height="1080" alt="post_final_MIN" src="https://github.com/user-attachments/assets/fd81cafa-1098-4fca-8b90-bd369decc420" />

---

Aug 20

https://github.com/user-attachments/assets/ee61dfa1-91be-4b5c-8c89-73515544a758

---

Aug 14

Laya Designs, BK, Kronnect

<img width="1920" height="1080" alt="forest_village_final_Reduced_LODS_MIN" src="https://github.com/user-attachments/assets/e3f34272-91fd-47fb-8500-7b7b0ed3f1e6" />

https://github.com/user-attachments/assets/ba057596-6f0e-4da6-9fc0-90bc58fb7c09

---

Aug 12

Spent a few days exploring some Unreal assets, then exporting to FBX & importing and setting them up in Unity.

Here's a scene I made with some of them.

Structures from Laya Designs, Stylized Water 3 w/planar reflections and scaled up ocean quads for view distance, Boxphobic height fog, beautify (aces, sharpen, dither, bloom, dof), TAA, BK cloud shader with extended view matrix.

<img width="1920" height="1080" alt="final_MIN" src="https://github.com/user-attachments/assets/dd0b46bc-5110-4ecf-aab8-1115097443fa" />

---

Aug 4

Wired up player-block-hit reaction, fullscreen blood effect, and tweaked blood splash & decal

The first attack I fail to block cause you need to be facing 60 deg to successfully block (Can tweak this for diff weapons / shields etc)

Its working pretty well so far, there are a few things I would like to add such as multiple NPC's on the same faction detecting each other, and trying to flank the player / staying out of each others way during combat

https://github.com/user-attachments/assets/73376601-267a-44c0-aaf6-c85fe050bbf3

---

jul 28

Blocking Test\
&nbsp;&nbsp;&nbsp;&nbsp; -> 100% chance to react to attack\
&nbsp;&nbsp;&nbsp;&nbsp; -> 100% preference to block\
&nbsp;&nbsp;&nbsp;&nbsp; -> Forced 3 second hold on chose to block

https://github.com/user-attachments/assets/f1470d5e-ce99-4a84-8fe5-e4fbbc9f5f6e

Binding some bracers to this first person rig so I can allow some customization

<img width="863" height="723" alt="image" src="https://github.com/user-attachments/assets/2066e06e-1e91-4377-afbb-50f5df427cf5" />

---

jul 25

bit more behavior for ai

It has a chance to notice a player attack, and has its own reaction speed range that it can use to react (block or dodge)

It listens to stamina draining events from the player, and can use that to identify a good time to attack

https://github.com/user-attachments/assets/ec19d5c4-967c-46e4-8836-0397b4defee1

---
jul 24

npc who circles

this is with 100% chance to dodge

https://github.com/user-attachments/assets/1ed8048f-f7ba-4412-aa54-370d9aeb26d2

---

jul 23

Found some hidden first person sword animations in the FPS - Gun FBX

Having a lot of fun with them ~

https://github.com/user-attachments/assets/9fe47dab-f284-4fa3-94ad-026ec24004b4

https://github.com/user-attachments/assets/41eb4399-0bfd-4ce9-bee1-f62e7e81295c

---

jul 21/2026\
whats new....

Custom EQS like system using unitys navmesh

Breakable Glass: free asset tweaked a bit

FPS Controller: free asset im using to learn first person a bit more\
&nbsp;&nbsp;&nbsp;&nbsp;-> This is only for gun...\
&nbsp;&nbsp;&nbsp;&nbsp;-> Need first person melee animations...
        
Creating custom breakable objects using the Fracture addon in Blender\
&nbsp;&nbsp;&nbsp;&nbsp;-> Need to figure out how to make them hollow before fracture\
&nbsp;&nbsp;&nbsp;&nbsp;-> Amazed the UV data stays intact too

https://github.com/user-attachments/assets/255e40cb-29a9-4cdb-b4c1-c3a95652e493

<img width="906" height="777" alt="blender_fracture_ingame" src="https://github.com/user-attachments/assets/39c6aace-4638-4f6f-ab35-fb5eb048e9db" />

<img width="690" height="619" alt="blender_fracture" src="https://github.com/user-attachments/assets/5802345e-ee4f-4036-ac81-dfffa103e0a7" />

https://github.com/user-attachments/assets/c6c84487-53a7-4666-a579-1ad81debc9ae

https://github.com/user-attachments/assets/8f28fadd-cca4-4a45-99ef-f27e7452e50c

https://github.com/user-attachments/assets/4eb95400-ac9f-4ccf-b851-9eed26ff546d

<img width="678" height="784" alt="no_seeed_glass" src="https://github.com/user-attachments/assets/150247a3-46cd-4cd5-9fd8-5760012ebda9" />

<img width="1433" height="815" alt="seed_glass" src="https://github.com/user-attachments/assets/565c360d-dc0a-461a-b57e-bbfdf1712458" />

https://github.com/user-attachments/assets/76d1d1a7-9418-41e9-b5af-50077f26670a

eqs like system using unitys navmesh\
<img width="695" height="665" alt="unity_eqs" src="https://github.com/user-attachments/assets/b3ae64e6-48f0-4d19-a6d2-9c8756fd1720" />


<!--
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/229ddbba-b281-4883-b139-7e504c8f63e3" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/356f1e13-2192-4c15-8d4a-17de685bed8c" /> 

https://github.com/user-attachments/assets/fe2ddcba-8b8a-4cde-8340-34aa856183a3

https://github.com/user-attachments/assets/8b09d9e5-f082-40a6-a007-5e1258b276d0

-->
