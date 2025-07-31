 <div id="header">
  <h1>Paul Bernard-Hall</h1>
  <h3>
    Game Developer <br />
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <sub>Unity, C#, TypeScript, Node, Ubuntu</sub>
  </h3>
</div>

<div id="bio">
  <p>Year 1 Student of George Brown Game Programming<br /><sup>Entering Year 2</sup></p>
  <p>Luxembourg Dual Citizen - Looking to move to the EU after graduating</p>
</div>

<hr />

# July 30, 2025

Weeks of dev indoors
I step outside, sun burns my skin
Nice tree LOD's

<hr />

# June 22, 2025

I *think* my Linear Algebra and Geometry midterm went OKAY ish. I did arrive 3 hours early to spend some time preparing and write out my formula sheet again. One was provided but I wanted to make sure I understood it. This is way less intense than the first semister math at least!

<img
  src="https://github.com/user-attachments/assets/f14a22a9-56d2-4e98-979a-f663be870775"
  width="500"
/>

Still working on getting RAM integrated with MicroVerse terrain, the carving and adjusting terrain height around the lake is giving me trouble right now. You can see my little combat test area in the bottom left.

![lake_attempt_1_ram](https://github.com/user-attachments/assets/967addbe-4b3a-4d83-af12-38e70db32b05)

I found a breakable wall asset that works with the UCC based character. However, the model I tried to setup has a few issues with its animation / collider so its not quite accurate. Getting there though, and I would love to use a few destructible walls to lead to secrets...

https://github.com/user-attachments/assets/1c02e526-d5a5-4613-9e3d-1d1f38ae36b1

Started looking at Dungeon Architect. Very excited to set this up with my own theme.

https://github.com/user-attachments/assets/28677034-ac06-4874-98a3-cc17fce256e1

I picked up this village pack mainly for the modular buildings, but was pleasantly surprised to find a ton of food as well.

![food_display_2](https://github.com/user-attachments/assets/0089e447-483a-4b37-8ae4-84b2d1b10ee2)

<a href="https://assetstore.unity.com/packages/3d/environments/fantasy/fantastic-village-pack-152970?srsltid=AfmBOoqu_hyVNm_nY5x6i7wntFHaP0kRb4hQR6dXZLNvfu-9I4zxqrDD">Fantastic Village Pack - Unity Asset Store</a>



<hr />

# June 19, 2025

It's all splines man. Trying to get River Auto Material 3 working alongside microverse, Rowlans Genesis Integration helps with that. I love how it adjusts the flow depending on the slope of the spline. It's also possible for it to snap to terrain and carve out a path.

https://github.com/user-attachments/assets/a6b58912-306d-4916-b1b5-a8f29e89305e

<hr />

# June 18, 2025

Math midterm soon. I actually feel prepared for it.

Figuring a bit more out about MicroVerse + The Visual Engine. Need to get Foliage Renderer 2 also added in properly...

![bigger_forest](https://github.com/user-attachments/assets/adb6da67-7d61-463a-9aaa-8136519e42b5)

<hr />

# June 16, 2025

Month going by too fast!

https://github.com/user-attachments/assets/580b35e8-1e83-4a6d-a2a7-3063460f19e2

Got a model from the store working with UCC default animations. One thing I learned is all the demo animations are setup as (I think) state machines. This character controller is one of the most complicated assets I have learned so far, but its obvious how powerful of a base this is.

https://github.com/user-attachments/assets/c2245b4e-cb6b-4b63-a3d1-c58a7805b6d4

<hr />

# June 06, 2025

Getting a UCC character interacting with a Crest water body with SphereWaterInteraction components placed on the ankles, along torso and on wrists. Next steps to try and rig up a custom model with UCC and get it working with the default / demo animations and items.

https://github.com/user-attachments/assets/808c9857-9591-4f73-8148-d20b3110c29d

<hr />

# June 01, 2025

While trying to learn the Crest 5 - Portals addon, I was inspired to make this diorama.\

https://github.com/user-attachments/assets/0a90d48f-0d5c-43be-8ad7-a8de44107993

Crest 5 + Crest 5 Portals\
&nbsp;&nbsp;&nbsp;&nbsp;"Portal Mode - Volume (Fly-Through)" on a Sphere mesh.\
Humpback Whale: Free on Unity store\
Boat: DWP2 and using integration with Crest.\
Clouds: Enviro 3\
Trees, grass, scaffolding, and ruin arch:\
&nbsp;&nbsp;&nbsp;&nbsp;Toon Adventure Island\
Seagulls: Bird Flock Bundle

<hr />

# May 31, 2025

Dynamic Water Physics 2 - Advanced Ship Controller

Crest 5 - Dynamic Waves + Surface Input Foam

https://github.com/user-attachments/assets/b3060a1a-6b67-4859-9b9b-57cf5d01f3d5

<hr />

# May 29, 2025

Created a really basic rigid body controller to turn the Duck (with a DWP2 water object component). I want to figure out the Advanced Ship Controller with the custom engines and rudders eventually, but for now, Submarine next.

https://github.com/user-attachments/assets/11838150-daf4-4391-9969-6674327768d5

<hr />

# May 28, 2025

I have started figuring out Dynamic Water Physics 2. It integrates so easily with Crest. 

https://github.com/user-attachments/assets/18ccf30a-bced-4145-b8af-0ff78f749ff3

The accuracy is really impressive\
<sup>!remindme - Replace this with a beach ball</sup>

https://github.com/user-attachments/assets/2962a016-fb5a-406c-bf89-3813e3b471eb



<hr />

# May 26, 2025

Formation Movement mostly working. One thing I have not been able to do, is adjust the orientation of the formation. I think this might be a current limitation of the 2D implementation.

<sup>A* Pathfinding Project, Behavior Designer Pro + Formations, 2D, URP</sup>

https://github.com/user-attachments/assets/1b25c026-d840-4ab9-a360-25c94b8972e1

<hr />

# May 25, 2025

Making progress with Formations for Behavior Designer Pro. Took me a day before I realized the documentation links on the website are for a previous version for Formations for the old Behavior Designer 🫠 I think I just need to be able to dynamically set the Vector 3 used for the formation destination during runtime, so the formation will follow a moving target like the player.

https://github.com/user-attachments/assets/20f4385c-2e48-4bab-a14f-255460e746b8

<hr />

# May 23, 2025

I remade the "Behavior Designer Pro - Formations" demo scene with astar project instead of navmesh. Still need to add the UI, and ability to reset in different formations. There is also an RVO Controller on each AI for local avoidance.

I tried to edit the existing formations demo to use astar project, except they had some functions wrapped for warp and a couple others that explicitly checked for a navmesh agent, and had a pain trying to swap em out properly.... This was much easier.

There is a massive amount to learn about behavior trees... Next steps are getting a formation to move to an arbitrary point, or follow an object, as a formation.

I think once this is done I will go back to working on Opsive Character Controller, then I can get some AI powered by that and Behavior Designer working in a 3d environment on an A* project grid.

https://github.com/user-attachments/assets/eebace51-b0ec-45c9-b137-b15f2b8c1083

<hr />

# May 21, 2025

Formations working!

https://github.com/user-attachments/assets/014e5c4c-c362-478c-bd14-001ccd832941

The behavior tree for this sequence.

Start to Repeater, so when thing under repeater fails or succeeds it just goes again. Repeater to main sequence. This runs everything underneath from left to right.

There are 3 sequences under our main sequence. Each one will first, until success, try and make the formation underneath it (triangle, circle, or grid) and then wait 2 seconds. After the wait cycle finishes, it passes success up the chain, and the next formation runs.

![behavior_designer_formations_rotation](https://github.com/user-attachments/assets/4ade6eac-65dd-4878-af94-be0e5c115a4f)

The "Until Success" node is there because if one of the child nodes fails (like making a formation) it will cause our main sequence to repeat from the beginning, instead of moving on to the next formation. And I was having issues where formations were occasionally failing.

I narrowed this down to the "Time Stuck" setting on each formation, increasing this from 0.2 to 1 allows enough time for npc's move around each other without triggering a "Formation Failure".

<hr />

# May 21, 2025

Replaced PolyNav2D with A* Pathfinding Pro and Behavior Designer Pro + Senses & Movement.

Next to get formations working.

https://github.com/user-attachments/assets/4e9a4d1a-fbf0-490e-9ac0-a49aacbab9f3

<hr />

# May 20, 2025

Finally stylable foldout headers. Inspector / editor UI coding is a bit confusing. I definitely appreciate having OdinInspector though as this solution extends OdinInspectors group drawer.

![stylable_foldout_headers](https://github.com/user-attachments/assets/c8cac9bf-36a4-4abb-a2fc-3eb9a830c566)

<hr />

# May 18, 2025

### ~~~ Brainstorming Session ~~~
#### ~~~~ Unique Shield Properties ~~~~~~

Equippable items. Rare drops or quest rewards. Lost upon death.

Percentage values in brackets may be variable.

---

<ins>Unique Shield Properties</ins>

**Strong Surface**
- Reduced incoming shield damage for first (15%) of energy capacity
- Increased incoming shield damage for last (25%) of energy capacity

**Focused Matrix**
- Damage to shield does not drain energy (normally drains energy 1:1)
- Disabled for ({0.5} seconds) when activating weapons

**Energy Vampire**
- Damage to shield boosts damage output by (%) temporarily
- (90%) increased shield drain amount
  - (x = drain amount) = (x + x * 0.9)

**Boost Bubble**
- (x = 15%) Increased speed for the first ({y = 3} seconds) while shielded
- Cooldown equal to ({y} * 2 seconds), starting after deactivation
  - Does not prevent normal shield functionality
 
**Turtle**
- Doubles shield capacity
- Reduces max thrust & boost by (30%)

**Stalker**
- Cannot be tracked by the following while active:
  - Turrets
  - Homing Missiles, Suicide Drones
  - Sensor Beacons
- Slight scramble to enemy "Aim Skill" (lead calculations)
  - May disrupt aim calculations to cause over or undershoot
  - ( + - 2%) would be enough to seriously disrupt aim
- (50%) shield damage bleedthrough to ship (normally 0%)

**Second Life**
- Upon running out of energy, refill energy to 100%
- Prevent energy regeneration for ({10} seconds) when activated
- Cooldown of ({45} seconds)

<hr />

# May 17, 2025

Finally getting around to some AI improvements. I want to have some difficulty scaling for NPCs, and one way I have implemented this is using two properties, "Rotation Speed" and "Aim Skill". The first is self-explanatory, while "Aim Skill" controls how well the NPC can track you and lead their shots. When you are orbiting an NPC, you may have a high angular velocity relative to them, and since my weapons currently have a travel time (not hit-scan), both player and NPC have to do this (leading shots) to actually hit.

I can also adjust this during runtime, so a skilled NPC might still have some miss streaks, and the inverse for a weaker NPC. This will help make the AI feel more natural. 

You can see below one NPC can track and hit quite well while the other struggles.

https://github.com/user-attachments/assets/e3def120-e68c-495e-90be-411744261e7d

I got vHierarchy/Folders/Inspector 2 during the sale and just got around to actually trying it, now I cant go back. It just a few pure QOL enhancements, a couple I particularly like are bookmarking things at the top of any tab, and the back/forward buttons in the inspector. vFavorites and vTabs are pretty handy too.

![vFolders2_vInspector2_vHierachy2_features](https://github.com/user-attachments/assets/6f1c4280-ff44-43f7-929a-66e27d11aaad)

Also trying to figure out how the inspector labels and styling work. My goal is collapsible Header sections, not quite there yet.

![editor_inspector_labels](https://github.com/user-attachments/assets/db0e1780-4b75-417c-94ba-66b8c23fa875)

<hr />

# May 13, 2025

New laser with glow effect, added extra trail effects when boosting.

https://github.com/user-attachments/assets/47f807b9-12da-49ca-94af-bd918ae67e56

AI overhaul underway. Followed by the long overdue upgrade system, and some scaling enemies.

Not 100% sure how I will handle actual equipment. I think there might be some base upgrades you can do to your ship that will never be lost (even upon death) but then you could acquire special parts with large bonuses or unique effects, but that WILL be lost upon death.

Here is a closer look at the updated ships so far. This is using All in One Sprite Shader.

They all have normal AND emissive maps.

The cockpits are made with a simple SpriteShape, and a colored light under them.

https://github.com/user-attachments/assets/8e1cbefa-803c-43cd-b23e-dbcf49829b8f

And a look at the system again. I made the asteroid belt rotate once more since I kinda have the player moving correctly as a child of the moving belt, thanks to using Extrapolation instead of Interpolation on the players rigidbody.

https://github.com/user-attachments/assets/28acc411-6d7b-4774-9efc-509e04bbc7d9

Also made an emissive map (although the shader really didnt requireee it...) to make this hazard in the race glow nicely (and some heavy chromatic abberation)

https://github.com/user-attachments/assets/4061e1c5-0d5b-461f-98cb-3a0443ccabe0

<hr />

# May 13, 2025

Figured out how to use the reflection probe that comes with Enviro 3 setup, and how to enable reflections & planar reflections on the Crest water system as well.

Also enabled ACES tonemapping in postprocessing.

https://github.com/user-attachments/assets/3ed4cee1-cdf1-48b7-bab8-a4bc0507a4ba

<hr />

# May 11, 2025

Got a nice beach setup to show off the stunning Crest Shallow Water System.\
It uses fluid dynamic simulation for shorelines, shallows, or rivers with real flow.\
MicroSplat/Verse Terrain.

https://github.com/user-attachments/assets/7106341c-3f19-4acd-a731-8c5f708f2248

<hr />

# May 11, 2025

Getting comfortable with MicroVerse/MicroSplat, Crest, and Enviro. Really loving Unity so far.

Creating gameplay / player controllers / npc next, now that I can create the environments I want.

..But I might just sit here a bit longer.

https://github.com/user-attachments/assets/d8a75768-6538-4a75-9ed6-fa6208723dd5

<sub>Crest 5, Crest 5 Shallow Water<br />Enviro 3 ( + Reflection Probe)<br />MicroSplat/MicroVerse<br /></sub>

<hr />

# May 7, 2025

Passed math 😎\
Linear Algebra and Geometry is much simpler so far.. phew..

Here are some projects from Semester 2:

https://paulbh.com/leapknight/

https://paulbh.com/sonic/

https://paulbh.com/state/

Here is a larger space game (Work in Progress!)\
More of a tech demo right now, but not much left to implement to finish the game loop\
Windows & Linux Builds only - Mac build on the way..\
[itch.io/orions](https://strideralpha.itch.io/orions)

## Here are some things I am working on
<sup>and some examples from projects</sup>

MicroSplat + MicroVerse, Enviro 3, Crest 5

https://github.com/user-attachments/assets/a1b935aa-16ed-4f7d-82f8-d5a8319e616a

https://github.com/user-attachments/assets/aad45f2c-a03c-48fb-a2b7-ed821b522732

https://github.com/user-attachments/assets/0a0701cb-1a3e-457b-a626-9f4dc24a9a26

https://github.com/user-attachments/assets/cc010a47-b2b3-4721-aeb4-65e00397bb99

![tiling_vs_stochastic](https://github.com/user-attachments/assets/f676469c-57f4-41d4-8d4a-3eb739e9d5a6)

https://github.com/user-attachments/assets/0433a060-983d-4052-b288-eee88cbf8a4b

Opsive Ultimate Controller + Crest 5

https://github.com/user-attachments/assets/31e29a22-7047-451f-88f0-83f7e73e4aa1

For Orions Shore

All in 1 Sprite Shader for Normal + Emissive\
Used Laigter for the normal map: azagaya.itch.io/laigter\
Used Krita to manually paint the emissive map\
Created transparent SpriteShape with a light underneath for the cockpit

https://github.com/user-attachments/assets/34c5c556-e94d-4028-8a28-14c54014ab81

The dynamic particle system was a bit overkill since removed\
Base sun + sprite sheet prominence still in though

https://github.com/user-attachments/assets/3dc37e20-c738-4694-a116-296b12e8066e

Early Earth before upscaling:\

https://github.com/user-attachments/assets/9927c146-1cb4-45b0-b7cc-e15acc8d2821

From LeapKnight\
The attack was an extra I added and not requirement\
It also has its own achievement for jumping over or killing the slime\

https://github.com/user-attachments/assets/71aa3dd6-ec47-47bc-a0eb-01832917b2d2

Attack Animation from State Machine

https://github.com/user-attachments/assets/c77ca120-6c9b-4760-92f3-90b74ab36dfb

<hr />

<!--

<div id="music">
  <sub>
    🎵 A Squire Of the
    <a href="https://www.youtube.com/@ScholastumProvost">Scholastum</a>
    at Castle Libratus 
  </sub><br />
  <sub>
    🎵 Planeswalking across the endless
    <a href="https://www.youtube.com/@chronoscapes_">Chronoscapes</a>
  </sub><br />
  <sub>
    🎵 Fellow Human
    <a href="https://www.youtube.com/watch?v=R47uzn-qFRY">Weather Channel</a>
    enjoyer
  </sub><br />
  <sub>
    🎵 Riding the
    <a href="https://www.youtube.com/watch?v=pJH7GuhqOcs">Monorail</a>
    through ዪ̵̝̠̇̄ሃ̴̧̛̣̹̽ረ̴̰̱͎̈́̍͝ቹ̷͖̲̈́͊ⶴ̴̛̻̣ͅ
  </sub>
  <details>
    <summary><h4>Expand for Much More Music</h4></summary>
    <sub>
      🎵 Marching to Bran Castle with the Great
      <a href="https://www.youtube.com/channel/UCILwGv6CVLn4B4oYdzzeUOQ">VINNTASH</a>
    </sub><br />
    <sub>
      🎵 Brooding in
      <a href="https://www.youtube.com/@OpalVessel">Opal Vessel's</a>
      Dark Ambience & Barber Beats
    </sub><br />
    <sub>
      🎵 Entirely Consumed by
      <a href="https://www.youtube.com/watch?v=GENZTmioPyU">t e l e p a t h</a>
      &nbsp; テレパシー能力者 - 星間性交
    </sub><br />
    <sub>
      🎵 At peace where the
      <a href="https://www.youtube.com/watch?v=dxO-DeAEZDM">desert sand feels warm at night</a>
      &nbsp; 夢の砂漠
      </sub><br />
    <sub>
      🎵 What is
      <a href="https://www.youtube.com/@What_Is_Mabisyo">Mabisyo</a>
    </sub>
    <br /><br />
  </details>
</div>

<hr />

<div id="tech">
  <h3>Here are some of the things I use the most:</h3>

  <p>
    <a href="https://javascript.info/">JavaScript</a> /
    <a href="https://www.typescriptlang.org/">TypeScript</a>
  </p>
  <p>
    Game Dev with <a href="https://phaser.io/">Phaser</a>
    and <a href="https://react.dev/">React</a>
  </p>
  <p>
    Image Editing with <a href="https://krita.org/en/">Krita</a> and
    <a href="https://www.aseprite.org/">Aesprite</a>
  </p>
  <p>
    2D Skeletal Animation with
    <a href="https://esotericsoftware.com/">Spine 2D</a>
  </p>
  <p>Map Editing with <a href="https://www.mapeditor.org/">Tiled</a></p>
  <p>
    Normal Map Creation with
    <a href="https://azagaya.itch.io/laigter">Laigter</a>
  </p>
  <p>Android & iOS with <a href="https://capacitorjs.com/">Capacitor</a></p>
  <p>
    Hosting on <a href="https://ubuntu.com/">Ubuntu</a> with
    <a href="https://nodejs.org/">Node.js</a>,
    <a href="https://nginx.org/">NGINX</a>, and
    <a href="https://pm2.keymetrics.io/">PM2</a>
  </p>
  <p>
    Protected with <a href="https://www.cloudflare.com/">Cloudflare</a> and
    <a href="https://certbot.eff.org/">Certbot</a>
  </p>
</div>

<div id="blog">
  <hr />
  <details open>
    <summary><h3>Blog</h3></summary>
    <hr />
    <div class="latest-post blog-post" id="Sat,Feb,1,2025">
      <h3>&nbsp;&nbsp;&nbsp;&nbsp; Sat Feb 1, 2025</h3>
    	<p>I wanted to make a post at the end of first semester, but ended up getting a very bad cold along with the kids, and by the time it went away, the second semester was starting!</p>
    	<p>First semester went really well, I got A's in everything except B in English, and I did not pass math (which I was kind of expecting from the start). However, when I realized it would be best to just retake it, it let me put a lot more work in some other courses, and I am really happy with what I was able to learn and create in them. Retaking math this semester and doing one in the summer term is not so bad.</p>
    	<p>I made a 1 min 30 second trailer for a game concept. I created 3 levels, made a navmesh and setup agents, made waypoints based on where I wanted to film, and manually recorded it. You can tell it was controlled by me holding the right mouse in edit mode because it's a little shaky. Also learned about materials, lighting, importing and modifying 3d models, and a bunch more.</p>
      <h3>Click the image below to view the video on YouTube:</h3>
      <a href="http://www.youtube.com/watch?feature=player_embedded&v=DSr4jr6KHEI" target="_blank">
        <img src="http://img.youtube.com/vi/DSr4jr6KHEI/0.jpg" alt="" width="500" />
      </a>
      <br /><br />
      <p>Another thing I have been having a lot of fun learning about is the HDRP. I am honestly surprised my laptop can handle it (mostly...) and the built in cloud and water systems are breathtaking. The ship floating is a bit shaky here because it is just matching the position / rotation of a sample of the water surface, instead of actually using buoyancy. The underwater caustics, and fog... I thought at first I didn't care about high fidelity graphics as much, until making stuff with them myself.</p>
      <table>
        <tr>
          <td width="500">
            <video src="https://github.com/user-attachments/assets/4b47b91b-4ff1-47f1-af83-357b94724dbe" controls="controls"></video>
          </td>
          <td width="0%">
          </td>
          <td width="0%">
          </td>
        </tr>
      </table>
      <br />
      <p>Overall I have spent maybe an equal amount of time between 2D and 3D. The 2D lighting system and 2DShadowCaster components are sweet. Laigter is still the perfect tool for quickly generating some normals. However, I have started to notice situations where it would be handy to know how to manually edit or tweak one.</p>
        <table>
        <tr>
          <td width="500">
            <video https://github.com/user-attachments/assets/fc31269e-efb3-4c52-a1e0-5e89fd4039cf" controls="controls"></video>
          </td>
          <td width="0%">
          </td>
          <td width="0%">
          </td>
        </tr>
      </table>
      <br />
      <p>Now what I really want to learn is multiplayer. I have had success getting one multiplayer netcode-for-gameobjects example working, and I *think* I was able to create a build I could run headless that would automatically start a server. However, I was not able to get it running on my Ubuntu VPS and connect to it... In fact I think it might have crashed the server (it's a micro vps so pretty limited resources..) </p>
    <p>Eventually my goal will be to learn Unity ECS and Netcode-For-Entities, but it does seem a lot more complicated, so that will be a long term goal. I am thinking a 2D multiplayer game built with ECS could get some impressive scaling.</p>
      <p>But for now I will be really focusing 100% of any extra time on Math. Because of a conflict, and needing to redo Math 1, I am only taking 5 courses this semester, and will take 2 in the summer term. That should make it easier to ensure I do well in Math.</p>
    </div>
    <hr />
    <details id="older-posts">
      <summary><h3>Click for Older Posts</h3></summary>
      <hr />
      <div class="blog-post" id="Fri,Nov,8,2024">
        <h3>&nbsp;&nbsp;&nbsp;&nbsp; Fri Nov 8, 2024</h3>
        <p>Math is kicking my ass 🥲</p>
        <p>Ran out of time and did not make good use of available resources. I should have asked for more help from the start of the class. Trying to "catch up" on all of high school math essentially from scratch has also been a lot of work. All of my other classes are going well though, I think I am around a 70-80% in them. Personal Finance is one of the more tricky ones, but I actually did enjoy the learning about Time-Value-Money calculations, and taxes.</p>
        <p>I am really enjoying learning Unity and C#. Domain reloads, even on a lightweight 2D project feel really slow sometimes. I have to mess around with a couple of the fast reload packages out there. I know there are some other limitations to using those, such as it wont pick up changes to certain levels of code unless a full domain reload is done still. Being able to save changes made in inspector during play mode / have them save when play mode is left would be nice too.</p>
        <p>I was able to get one of the small mainly UI-Based games built for WebGL and hosted on my server / website though so that was cool! Now we are starting to get into sprites, player controllers, collisions, and enemies.</p>
        <p>I honestly did not think I would go back to school, and I am loving it so far. I know if I refocus my efforts around Math I can learn it.</p>
      </div>
      <hr />
      <div class="blog-post" id="Sun,Sep,29,2024">
      <h3>&nbsp;&nbsp;&nbsp;&nbsp; Sun Sep 29, 2024</h3>
      <p>Really happy with the server setup so far:</p>
      <ul>
        <li>Firebase with Google OAuth</li>
        <li>Firebase RTDB for token revocation status</li>
        <li>Express server for Sign Up, HTTP</li>
        <li>Local MariaDB for my User Data</li>
        <li>uwsjs websocket server</li>
        <li>
          Redis for
          <ul>
            <li>Websocket Message Brokering</li>
            <li>Websocket Room Management</li>
            <li>Server Side Active Game Data</li>
          </ul>
        </li>
      </ul>
      <p>
        I already knew to use Redis for room management, but I did not realize it
        could be used to help scale something like uwsjs by brokering messages
        between uwsjs servers running in a cloud environment.
      </p>
      <p>
        I was wanting to use this backend with Phaser, but phaser-on-nodejs only
        supports 3.55 as the highest, and I have not been able to get it working
        with an updated version... yet...
      </p>
      <p>
        While I still want to work on making that happen, for now I will create an
        extremely basic engine to use server and client side. I was thinking about
        using a more minimal framework than phaser (like a stand-aline physics
        engine on the backend and a simpler render engine for client), but this is
        a good opportunity to learn and I am kinda excited to try.
      </p>
      <p>
        I am definitely going to be getting some help from this legendary
        article:<br />
        <a
          href="https://www.gabrielgambetta.com/client-server-game-architecture.html">gabrielgambetta.com/client-server-game-architecture</a>
      </p>
      <p>
        There are 4 main parts the article discusses, each being critical for a
        multiplayer game:
      </p>
      <ul>
        <li>Client Side Prediction</li>
        <li>Server Side Reconciliation</li>
        <li>Entity Interpolation</li>
        <li>Lag Compensation</li>
      </ul>
      <p>
        I only have a vague understanding of these things, so trying to implement
        them myself will be really fun. Here is one excerpt from the article I
        thought was really interesting on entity interpolation:
      </p>
      <blockquote>
        "...;the trick is how to show the player what happens inbetween. The key
        to the solution is to show the other players in the past relative to the
        user’s player."
      </blockquote>
      <p>
        I found this interesting becuase as a long time MMORPG player, I would
        occasionally play with someone sitting right next to me. And I would
        notice if we were running "together" sometimes, on my screen they would
        appear slighly behind me, while on their screen I would appear slightly
        behind them.
      </p>
      <p>
        I can only assume this could have something to do with the aforementioned
        entity interpolation implementation.
      </p>
    </div>
    <hr />
      <div class="blog-post" id="Mon,Sep,23,2024">
        <h3>&nbsp;&nbsp;&nbsp;&nbsp; Mon Sep 23, 2024</h3>
        <p>
          I recently setup a login/auth system using Node.JS, MariaDB, Firebase,
          and Sign in with Google. Initially I was going to setup the systems
          directly, but realizing Firebase could handle a lot of the work, and I
          wouldn't need to pay the Google/Apple developer account fees made me
          give it a try.
        </p>
        <p>
          It is very weird having a user system and database and not storing any
          passwords for them! I also love not having to worry about password reset
          systems and all the other things required for a secure and functional
          login system. I managed to get the checks for token revokation to be
          done through a Firebase Realtime Database. Since it's just a key/value
          store, I am thinking i could move this to a local REDIS server instead,
          but it's working quite well so far.
        </p>
        <p>
          Now to setup the actual websocket server which I will be using
          uwebsockets.js for.
        </p>
      </div>
      <hr />
      <div class="blog-post" id="Thu,Sep,23,2024">
        <h3>&nbsp;&nbsp;&nbsp;&nbsp; Thu Sep 19, 2024</h3>
        <p>Trying to catch up on math 🫠</p>
        <p>
          This has also given me an opportunity to look into LaTeX. I first
          discovered it when looking to document some formula for a space games
          physics.
        </p>
        <p><sub>Some notes I am making</sub></p>
        <img
          src="https://github.com/user-attachments/assets/58204d07-2909-43a8-9376-916df3585ae3"
          width="500"
        />
        <br />
        <br />
        <p>
          Play with LaTeX in-browser here:
          <a href="https://latex.js.org/playground.html"
            >latex.js.org/playground</a
          >
        </p>
      </div>
      <hr />
      <div class="blog-post" id="Fri,Sep,06,2024">
        <h3> &nbsp;&nbsp;&nbsp;&nbsp; Fri Sep 6, 2024</h3>
        <img
          src="https://github.com/user-attachments/assets/1b91753c-b0c3-4207-a904-0459c3e83293"
          width="500"
        />
        <br />
        <h1>🇺🇦 💔</h1>
      </div>
      <hr />
      <div class="blog-post" id="Tue,Sep,03,2024">
        <h3> &nbsp;&nbsp;&nbsp;&nbsp; Tue Sep 3, 2024</h3>
        <p>
          College Day 1. Game Programming at George Brown. It feels a bit surreal,
          but I am extremely excited.
        </p>
        <p>
          I have wanted to make a post over the past two weeks on a multi-part
          dragon I am drawing and then animating, but every time I started a post,
          I noticed something I wanted to change.
        </p>
        <p>
          Here it is with a quick background added. Creating varied landscapes and
          backgrounds is one of the next things I want to start practising.
        </p>
        <p>
          The final step is rigging and animating in Spine 2D. I have raised and
          lowered wings for each side, so I will be able to make flying animation.
          Pictured are the resting wings.
        </p>
        <img
          src="https://github.com/user-attachments/assets/782fb17b-d800-4c40-8967-3b01d4dfb16e"
          width="500"
        />
        <p>When I get some more time I will upload some progress pictures.</p>
      </div>
      <hr />
      <div class="blog-post" id="Tue,Aug,20,2024">
        <h3>&nbsp;&nbsp;&nbsp;&nbsp; Tue Aug 20, 2024</h3>
        <p>
          Sadly noticed my nib was dead on Monday, thanfully replacements are
          coming.
        </p>
        <img
          src="https://github.com/user-attachments/assets/62e88103-7365-499f-afcd-32813b288dc6"
          width="500"
        /><br /><br />
        <p>
          I found out that I could apply gradient map to textures on brushes,
          which adds a lot of depth and shading in a single stroke. While all
          these examples are of "Texture - Reptile", the gradients look very
          similar applied to other textures. These are beautiful, and this is
          definitely going to help for metallic surfaces too.
        </p>
        <p>
          Find the Gold / Pearl gradients here:
          <a
            href="https://krita-artists.org/t/gold-and-pearl-gradients-set-for-krita/85040"
          >gold-and-pearl-gradients</a>
        </p>
        <img
          src="https://github.com/user-attachments/assets/bb0fe4bb-3c28-41b5-b169-4f47cfcf3dd1"
          width=""
        />
        <br /><br />
        <p>Made a rainbow cloud brush:</p>
        <img
          src="https://github.com/user-attachments/assets/55f7ed5e-e7d1-4b5e-b7d1-7f11fdad1016"
          width="500"
        />
        <br />
        <br />
        <p>
          I found a brush pack that really captures the thick paint amazingly. You
          can see it in the background undr my name.
        </p>
        <p>
          Find the brush pack here:
          <a href="https://krita-artists.org/t/memileo-impasto-brushes/92952"
            >Memileo Impasto Brushes</a
          >
        </p>
        <img
          src="https://github.com/user-attachments/assets/b6cf75e8-db07-4aef-afaa-1e16942a2d46"
          width="500"
        />
        <br /><br />
      </div>
      <hr />
      <div class="blog-post" id="Sat,Aug,17,2024">
        <h3>&nbsp;&nbsp;&nbsp;&nbsp; Sat Aug 17, 2024</h3>
        <p>
          Lots of updates. This week I have been working on clouds, skin, plants
          and trees.
        </p>
        <h3>Cloud Study</h3>
        <img
          src="https://github.com/user-attachments/assets/758d4d52-9a00-428e-9570-a91a4634cc47"
          width="500"
        />
        <p>These are my two favorites from the cloud study:</p>
        <img
          src="https://github.com/user-attachments/assets/f9cd0a9d-046b-494a-809d-ff2a8270db42"
          width="250"
        />
        <img
          src="https://github.com/user-attachments/assets/ddc8a289-5a64-4327-a5ca-13d33c30ca9b"
          width="250"
        />
        <p>
          I also had a lighter background ready so I can see how that changes
          them. It made me realize I can't rely on the background for shading the
          clouds and need to mix in the light/darker shade myself if I want it to
          show on both light/dark backgrounds.
        </p>
        <p>
          You can see here is where I realized the white cloud didn't really have
          any darker shades because I was relying on the black background for
          that. However the purple cloud I added the shading myself.
        </p>
        <img
          src="https://github.com/user-attachments/assets/905171ea-db59-4e93-b89c-7a60ecba1d3f"
          width="250"
        />
        <img
          src="https://github.com/user-attachments/assets/d505eab8-2fd3-44af-a7cb-68b537217e30"
          width="250"
        />
        <h3>Skin Study:</h3>
        <p>
          I need to play with the different pore brushes, but I am getting an idea
          of how to make skin.
        </p>
        <img
          src="https://github.com/user-attachments/assets/204ab961-3d37-486d-aad4-6120d9a76443"
          width="500"
        />
        <h3>Greenery Study</h3>
        <p>
          I got a good start on trees and bushes. I want to make a little personal
          library of pre-made assets.
        </p>
        <img
          src="https://github.com/user-attachments/assets/4612412e-76bf-4df6-a87b-8c94ffb19909"
          width="500"
        />
        <p>
          I am going to do some bushes or trees with a separate branch layer, so
          if I wanted to let you gather from a bush I could use a particle effect
          during the gatherng and then remove the leaf layer to represent a
          depleated resource
        </p>
        <img
          src="https://github.com/user-attachments/assets/c3b59ae0-3f06-4b5a-89ab-f00e712213f8"
          width="250"
        />
        <img
          src="https://github.com/user-attachments/assets/5ce4ea8c-7bdd-4305-a38a-71db98256e44"
          width="250"
        />
        <h3>Cloth / Fabric</h3>
        <p>
          Along with Metal this has been a tricky one so far... While there are
          some canvas textures, there is no canvas brush by default or in any
          brush pack I found so far.
        </p>
        <p>
          So I created my own canvas texture brushes. Selecting the texture, and
          then changing the TEXTURE blend mode to "Lightness Map" was all I needed
          to do to get this effect. Pixel Engine. (Blend mode under the brush
          texture pattern options, not general brush blend mode)
        </p>
        <p>
          Left Texture: "Woof Tissue" for Burlap - Right texture: "01 Canvas" for
          a finer thread appearance
        </p>
        <img
          src="https://github.com/user-attachments/assets/ab71cf47-8526-4073-8e30-1a644db98d9f"
          width="250"
        />
        <img
          src="https://github.com/user-attachments/assets/4800cbeb-b1a8-4f86-954e-2d23cc15193b"
          width="250"
        />
        <h3>Drawing, rigging, and animating a full model</h3>
        <p>
          I decided to draw a model as if it was an artists poseable mannequin. I
          figure this will be the easiest way to start learning how to make
          human-ish movements.
        </p>
        <p>
          First I drew each separate part in Krita, and exported it to another
          file where I merged each body part as a single layer or group. Then I
          imported each part into Spine, create a skeleton, and attached the parts
          to the skeleton.
        </p>
        <img
          src="https://github.com/user-attachments/assets/bb34e109-daa4-456e-8f24-c07fd5d51da3"
          width="369"
        />
        <img
          src="https://github.com/user-attachments/assets/00e3d58c-8339-49b5-b705-b9fa46f6b129"
          width="200"
        />
        <p>
          Then I was able to get a (very rudimentary) wave animation keyed out.
        </p>
        <img
          src="https://github.com/user-attachments/assets/73c3a0f4-a0a0-4a29-9cd6-d7d989b8637d"
          width="300"
        />
        <h3>Dragon Skin Reborn</h3>
        <p>
          I added a few more colors to the dragon skin pattern. I also realized I
          will need to come up with something else for actual scales. I reawlly
          love this texture and how this is coming along. Can't wait to actually
          draw and animate the dragon.
        </p>
        <p>Dragon Skin Purple & Green</p>
        <img
          src="https://github.com/user-attachments/assets/0c581166-4370-495f-af60-7e794ce1062b"
          width="250"
        />
        <img
          src="https://github.com/user-attachments/assets/d96a051a-ce4b-40b9-90e9-7a22a719d0aa"
          width="250"
        />
       <br /><br />
        <h3>What's next...</h3>
        <p>
          The coming week I will be focusing more on character models and
          animation. I need to make side-profile versions, and then try making
          walk/run/jump animations. Also dragons. And fire.
        </p>
        <br />
      </div>
      <hr />
      <div class="blog-post" id="Mon,Aug,12,2024">
        <h3>&nbsp;&nbsp;&nbsp;&nbsp; Mon Aug 12, 2024</h3>
        <p>
          I am getting familiar with different brushes in Krita, and hoarding any
          good bundles I can find. Advanced brushes can make certian things,
          particuarilly textures and hair, a lot easier.
        </p>
        <p>
          I have been trying a few different methods to make dragon scales, this
          one being made with a reptile texture brush and a few layers underneath.
        </p>
        <img
          src="https://github.com/user-attachments/assets/cdb8e77b-32a5-40e7-b1cf-4c0ae6581d45"
          width="500"
        />
        <br /><br />
        <p>I also found a cloud brush makes nice looking clouds very easily.</p>
        <img
          src="https://github.com/user-attachments/assets/cfce4486-276a-461d-9a08-c088f2899dee"
          width="500"
        />
        <br /><br />
        <p>Here are some of my favorite brush packs so far:</p>
        <p><a href="https://krita-artists.org/t/rakurri-brush-set-v2-free-krita-brushes/33709">
          Rakurri Brush Set V2
        </a></p>
        <p><a href="https://krita-artists.org/t/fizzyflowers-essential-brushset-version-2-with-400-brushes-cloud-paint-hair-fur-fx-foilage-trees-leaves-texture-smudge-and-more/38580">
          FizzyFlowers Essential Brushset V2
        </a></p>
        <p><a href="https://krita-artists.org/t/grass-and-fields-brush-pack/60253">
          Grass and Fields Brush Pack - KMC Visuals
        </a></p>
        <p><a href="https://krita-artists.org/t/basic-cloud-brushes/66120">
          Basic Cloud Brushes - Bea2
        </a></p>
      </div>
      <hr />
      <div class="blog-post" id="Fri,Aug,09,2024">
        <h3>&nbsp;&nbsp;&nbsp;&nbsp; Fri Aug 9, 2024</h3>
        <p>
          For the past month or so I have been learning
          <a href="https://esotericsoftware.com/">Spine 2D</a>. Spine lets you
          create skeletal based animations, which can greatly reduce filesize
          compared to using spritesheets. It also makes it easier to create
          natural feeling animations, as it can interpolate between keyframes for
          you. Spine pro also supports meshes and mesh deformation, which can be
          weighted to bones so moving a bone can deform specific vertices
        </p>
        <p>Here is a small example of making a butterfly animation</p>
        <h3>1: Source Image</h3>
        <img
          src="https://github.com/user-attachments/assets/72dee77a-6efa-4630-aef6-8e731454a696"
          width="500"
        />
        <h3>2: Dissecting it in Krita</h3>
        <img
          src="https://github.com/user-attachments/assets/69d8de10-b5b6-40dc-b278-2bce7fbac0a9"
          width="500"
        />
        <h3>3: Rigging each part together in Spine with a skeleton</h3>
        <img
          src="https://github.com/user-attachments/assets/b3685bcb-bee5-4c06-b5fe-b84788293908"
          width="500"
        />
        <h3>4: Keying the animation in Spine</h3>
        <img
          src="https://github.com/user-attachments/assets/a08c02c2-9082-4c69-b0e2-3d647219542f"
          width="500"
        />
      </div>
      <hr />
    </details>
    </div>
    
<div id="tech-icons">
  <br />
  <img src="icons\html5-original.svg" alt="" width="75" height="75" />&nbsp;
  <img src="icons\css3-original.svg" alt="" width="75" height="75" />&nbsp;
  <img
    src="icons\javascript-original.svg"
    alt=""
    width="75"
    height="75"
  />&nbsp;
  <img
    src="icons\typescript-original.svg"
    alt=""
    width="75"
    height="75"
  />&nbsp;
  <br />
  <img
    src="icons\phaser-web-sm_added-padding.png"
    alt=""
    width="75"
    height="75"
  />&nbsp;
  <img
    src="icons\tiled-white_added-bg.png"
    alt=""
    width="100"
    height="75"
  />&nbsp; <img src="icons\laighter.png" alt="" width="135" height="75" />&nbsp;
  <br/>
  <img
    src="icons\nodejs-original-wordmark.svg"
    alt=""
    width="75"
    height="75"
  />&nbsp;
  <img
    src="icons\react-original-wordmark-cropped.svg"
    alt=""
    width="75"
    height="75"
  />&nbsp;
  <img
    src="icons\capacitor-original-wordmark.svg"
    alt=""
    width="75"
    height="75"
  />&nbsp;
  <img
    src="icons\ubuntu-original-wordmark.svg"
    alt=""
    width="75"
    height="75"
  />&nbsp;
  <img src="icons\nginx-original.svg" alt="" width="75" height="75" />&nbsp;
  <img
    src="icons\cloudflare-original-wordmark.svg"
    alt=""
    width="75"
    height="75"
  />&nbsp;
</div>

-->

<!-- Notes & Others

  <img src="icons\aesprite-with-icon_added-padding.png" alt="" width="100" height="75">&nbsp;
  <img src="icons\npm-original-wordmark.svg" alt="" width="75" height="75">&nbsp;
  <img src="icons\express-original-wordmark.svg" alt="" width="75" height="75">&nbsp;
  <img src="icons\socketio-original-wordmark.svg" alt="" width="75" height="75">&nbsp;
  <img src="icons\mysql-original-wordmark.svg" alt="" width="75" height="75">&nbsp;
  <img src="icons\mongodb-original-wordmark.svg" alt="" width="75" height="75">&nbsp;
  <img src="icons\redis-original-wordmark.svg" alt="" width="75" height="75">&nbsp;
  <img src="icons\electron-original.svg" alt="" width="75" height="75">&nbsp;
  <img src="icons\git-original-wordmark.svg" alt="" width="75" height="75">&nbsp;
  <img src="icons\github-original-wordmark.svg" alt="" width="75" height="75">&nbsp;
  <img src="icons\vscode-original-wordmark.svg" alt="" width="75" height="75">&nbsp;
  <img src="icons\postman-original-wordmark.svg" alt="" width="75" height="75">&nbsp;
  <img src="icons\ssh-original-wordmark.svg" alt="" width="75" height="75">&nbsp;

  For the cursed text I used "Sous Cheffe" from
  https://glyphy.io/font-generator/cursed-text
  then put the result of that into this with a lower crazyness level
  with cursed enabled for top middle and bottom
  https://cursedtext.com/

  To get proper folding with HTML in this .md file I had to change
  Editor: folding strategy = "Indentation"
-->
