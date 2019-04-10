# Portfolio

This portfolio contains the week by week reflections of how I am going on my Visual Condition Project. It contains my personal Professional and Technical proficiencies, as well as thoughts on how well I did. It documents my learning experiences with Unity. 

## Week: 1
### Monday Class:
In this first class of week 1, we were tasked to set up our own workstations. This was most likely used to simulate the real world. We had to pick a spot in the project room, then setup our computers in our workspace. After that, we learnt about how the Projects work, which projects were available, and when we had to decide what project we wished to do. I was interested in doing the SysOps project as that is a career that I am interested in, but I also was very interested in game development. I knew game development was a popular topic so I wary of how long I was wanting to take to decide.

### Thursday Class:
Before the second class, I had an interview with Adon about which project I wanted to do. I had decided I was going to put Game development as my main project, and SysOps as my backup incase Game dev was full.
During our Thursday class, the project teams were announced. I had been put into the Game Development project, however I had been split off into a subgroup due to the number of people wishing to do Game Dev. I was split into a group of 3 with Mitchell Briggs and Nick Mulrooney. For this Thursday class, we just got to know each other. We learnt about who was confident at what things and quite quickly got friendly.

### Reflection:

## Week: 2
### Monday Class:
On the Monday class, we got introduced to the software we would be using. It was game engine known as Unity. This class was primarily focused on getting Unity up and running, then learning how to use it. Our computer were not powerful enough to run some of the basic tutorials so I resorted to going onto Youtube and the Unity documentation to learn how to start development with Unity.

### Thursday Class:
On Thursday, I began practising making scenes in Unity. The group had decided to dedicate the next few classes to primarily learning the fundamentals of Unity, so they began to follow a tutorial of how to make a roll a ball game. I jumped in head first and just started developing a small map with interactable objects. I wanted to learn about physics and colliders. I learnt the differences between the different colliders and which colliders are better for certain situations.

## Week: 3
### Monday Class:
On the Monday class, I wanted to start focusing my attention towards the project, and what I was going to be making. At this point, I had not been assigned an actual project, I just knew that Adon was planning on doing something with Virtual Reality (VR) development on mobile devices. I began looking into how dofficult it is to create VR apps and learnt that it was relatively straight forward. I began by reading up on Google DayDream as I had been given a Google DayDream VR Headset to work with. I read the documentation on how to setup a scene in Unity and watched a few tutorials. Once I had a fair idea of what I was doing, I began creating a scene in which the player just stands infront of a ball and they are able to pick it up and move it around.

### Thursday Class:
On Thurday I got to class and continued work on my VR world. At this point I could pick the ball up and move it around, but once I released the ball, it remained exactly where it was. I decided to add gravity to it. (The code I used here ended up being used later on for the real project). During thi9s class, I learnt that I would be working with visual impairments. Straight away I thought about Colour Blindness. I research some colour blindness plugins and presents and found a perfect one. I quickly implemented it into my Ball scene. I now had a game which you could pick up a ball while simulating different colour blindnesses.

## Week: 4
### Monday Class:
On the Monday class, I decided to dwell deeper into Colour Blindness. I began researching it, learning about which condition effected which colours and how it happened. This gave me a good understanding of the three main types of colour blindness, Protonopia, Deuteranopia and Tritanopia. From here I documented some key details on my Github page. I also played around with the colour blindness plugin I had aquired last class.

### Thursday Class:
With the knowledge I now had from the Monday session, I created a basic showcase in Unity. I created a world with these blocks which were all different colours. The blocks were placed in a way which was able to show how different colours can easily blend together with colour blindness. This was a good starting ground for a visual impairments project. As a group, we also wrote down our README on Github, outlining what we could potentially do with this app. During the creation of this showcase, I wanted to know more about which colours were affected by other colours so I continued to document which colours blended with other colours. By the end of the class, I had a working showcase which did a good job in showing the different colours that blend with different types of colour blindness.

## Week: 5
### Monday Class:
This Monday class was very productive. Our group got split up into 3 solo groups. We were told we would be working with different clients based on the previous information we got told. I got assigned to work with Mary, who wanted to make a Visual Condition simualtion app. This was perfect, as I had already been learning about colour blindness. We met around 2pm, and discussed potential ideas. I showed her what I had been doing with the Colour Blindness and how it looks when in a VR headset. She loved the idea. Originally she had not planned on using colour blindness as one of the simulations but after showing this she said I should potentially implement it later on.
Some of the ideas we discussed were having a kitchen or office space in which the user has to interact with different objects with different levels of visual conditions applied. For example, trying to read an email when the user is suffering from Cataracts (a condition where the person's vision has becomne blurry). We both liked these ideas and I began brainstorming ways to proceed.
After this class, I emailed Mary and got a list of the visual condition she would like to see implemented into the app, as well as a list of visual conditions she might like implemented once the main ones were implemented.

### Thursday Class:
This Thursday class was essentially a research day. I had recieved the day before a list of the visual conditions that Mary wished to see in the game. I began to document on Github what these conditions were. Mary had also suggested getting an app on my iPhone which did a similar simulation but just through the camera. With the help of the app and some research, I was able to document how these different visual conditions affect the patient, while also creating a seperate Github wiki page that documented ways I thought of on how to implement these visual conditions as effects in Unity.
After I had done all this documentation and research, I started making a 3D kitchen in Unity. I imported some kitchen assets, and built a basic Kitchen with a bench and some objects ontop of the bench. All the is able to do at this point is load up into this kitchen and look around.

## Week: 6
### Monday Class:
Over the weekend, I had worked on my Kitchen scene. I had used the code I had created for the Ball game a few weeks earlier, to implement physics into the objects that sat ontop of the kitchen bench. The user was now able to pick up pots and pans on the kitchen table and drop them causing them to fall back onto the bench, onto the floor or even into the kitchen sink. After making this, I encountered a bug. If I was to pick up objects and rub them against the kitchen bench, they would begin to fly out sideways for not reason with no control. I decided it wasn't a huge bug and I will worry about it later. Monday's class did not happen due to it being a Public holiday.

### Thursday Class:
This Thursday class I ebgan looking into how to implement most of my visual effects. I decided that using Post Processing might be the best solution as both Mary and Adon had suggested being able to change the settings of the visual effect in game. I looked over the post processing effects and decided that the easiest one to start with would be Glaucoma as I could just create a Vignette that creates a faded tunnel vision effect. I was able to create the effect, but currently the only way to turn it on and off is outside of the game. I will implement a way later to be able to change it in game through a menu or something. I also realised a way to fix the magical flying pots bug. After watching a tutorial on an unrelated part of unity, I realised that when I turned gravity off, it meant that any force applied to an object would cause that object to fly away on a tangent. It was a simple fix. When the user interacts with an object, the objects gravity is no longer affected, and instead the object is turned to be in a  Kinematic state. This introduces the problem where there is no collision with objects that are being held, however this makes moving objects around a bit easier. I will worry about details like this later.

## Week: 7
### Monday Class:

### Thursday Class:

## Week: 8
### Monday Class:

### Thursday Class:
