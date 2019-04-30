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

### Reflection:

## Week: 3
### Monday Class:
On the Monday class, I wanted to start focusing my attention towards the project, and what I was going to be making. At this point, I had not been assigned an actual project, I just knew that Adon was planning on doing something with Virtual Reality (VR) development on mobile devices. I began looking into how dofficult it is to create VR apps and learnt that it was relatively straight forward. I began by reading up on Google DayDream as I had been given a Google DayDream VR Headset to work with. I read the documentation on how to setup a scene in Unity and watched a few tutorials. Once I had a fair idea of what I was doing, I began creating a scene in which the player just stands infront of a ball and they are able to pick it up and move it around.

### Thursday Class:
On Thurday I got to class and continued work on my VR world. At this point I could pick the ball up and move it around, but once I released the ball, it remained exactly where it was. I decided to add gravity to it. (The code I used here ended up being used later on for the real project). During thi9s class, I learnt that I would be working with visual impairments. Straight away I thought about Colour Blindness. I research some colour blindness plugins and presents and found a perfect one. I quickly implemented it into my Ball scene. I now had a game which you could pick up a ball while simulating different colour blindnesses.

### Reflection:

## Week: 4
### Monday Class:
On the Monday class, I decided to dwell deeper into Colour Blindness. I began researching it, learning about which condition effected which colours and how it happened. This gave me a good understanding of the three main types of colour blindness, Protonopia, Deuteranopia and Tritanopia. From here I documented some key details on my Github page. I also played around with the colour blindness plugin I had aquired last class.

### Thursday Class:
With the knowledge I now had from the Monday session, I created a basic showcase in Unity. I created a world with these blocks which were all different colours. The blocks were placed in a way which was able to show how different colours can easily blend together with colour blindness. This was a good starting ground for a visual impairments project. As a group, we also wrote down our README on Github, outlining what we could potentially do with this app. During the creation of this showcase, I wanted to know more about which colours were affected by other colours so I continued to document which colours blended with other colours. By the end of the class, I had a working showcase which did a good job in showing the different colours that blend with different types of colour blindness.

### Reflection:

## Week: 5
### Monday Class:
This Monday class was very productive. Our group got split up into 3 solo groups. We were told we would be working with different clients based on the previous information we got told. I got assigned to work with Mary, who wanted to make a Visual Condition simualtion app. This was perfect, as I had already been learning about colour blindness. We met around 2pm, and discussed potential ideas. I showed her what I had been doing with the Colour Blindness and how it looks when in a VR headset. She loved the idea. Originally she had not planned on using colour blindness as one of the simulations but after showing this she said I should potentially implement it later on.
Some of the ideas we discussed were having a kitchen or office space in which the user has to interact with different objects with different levels of visual conditions applied. For example, trying to read an email when the user is suffering from Cataracts (a condition where the person's vision has becomne blurry). We both liked these ideas and I began brainstorming ways to proceed.
After this class, I emailed Mary and got a list of the visual condition she would like to see implemented into the app, as well as a list of visual conditions she might like implemented once the main ones were implemented.

### Thursday Class:
This Thursday class was essentially a research day. I had recieved the day before a list of the visual conditions that Mary wished to see in the game. I began to document on Github what these conditions were. Mary had also suggested getting an app on my iPhone which did a similar simulation but just through the camera. With the help of the app and some research, I was able to document how these different visual conditions affect the patient, while also creating a seperate Github wiki page that documented ways I thought of on how to implement these visual conditions as effects in Unity.
After I had done all this documentation and research, I started making a 3D kitchen in Unity. I imported some kitchen assets, and built a basic Kitchen with a bench and some objects ontop of the bench. All the is able to do at this point is load up into this kitchen and look around.

### Reflection:

## Week: 6
### Monday Class:
Over the weekend, I had worked on my Kitchen scene. I had used the code I had created for the Ball game a few weeks earlier, to implement physics into the objects that sat ontop of the kitchen bench. The user was now able to pick up pots and pans on the kitchen table and drop them causing them to fall back onto the bench, onto the floor or even into the kitchen sink. After making this, I encountered a bug. If I was to pick up objects and rub them against the kitchen bench, they would begin to fly out sideways for not reason with no control. I decided it wasn't a huge bug and I will worry about it later. Monday's class did not happen due to it being a Public holiday.

### Thursday Class:
This Thursday class I ebgan looking into how to implement most of my visual effects. I decided that using Post Processing might be the best solution as both Mary and Adon had suggested being able to change the settings of the visual effect in game. I looked over the post processing effects and decided that the easiest one to start with would be Glaucoma as I could just create a Vignette that creates a faded tunnel vision effect. I was able to create the effect, but currently the only way to turn it on and off is outside of the game. I will implement a way later to be able to change it in game through a menu or something. I also realised a way to fix the magical flying pots bug. After watching a tutorial on an unrelated part of unity, I realised that when I turned gravity off, it meant that any force applied to an object would cause that object to fly away on a tangent. It was a simple fix. When the user interacts with an object, the objects gravity is no longer affected, and instead the object is turned to be in a  Kinematic state. This introduces the problem where there is no collision with objects that are being held, however this makes moving objects around a bit easier. I will worry about details like this later.

### Reflection:

## Week: 7
### Monday Class:
Today I looked into making a menu system for the simulation. I wanted to be able to access the different visual conditions while in the simulation. I looked into the best ways of making menus in virtual reality. One thing I stumbled upon was Google DayDream Elements. This was a package that contained all that was needed to create virtual elements inside of a virtual world specifically for the DayDream headset I was working with. Once I started using it, I quickly realised I would need to remake my project as Google DayDream wanted to reinstall the Google VR package I already had installed. It just ended up breaking my project, so I imported all my models into  anew project that I set Google DayDream Elements in, and went from there. Within about 20 minutes I had caught up to where I was and was ready to start development. I planned out how my menu would look on Paint.net. I made sure to annotate it a bit so that I could show Mary my ideas. Mary was unable to come in today as she was in a meeting, so we arranged a meetup on Tuesday instead.

### Tuesday:
Today I met with Mary. This time we talked more specifically on how to make the simulation more enjoyable. We brainstormed ideas on what we could to do improve the usability and to make it more interesting. We talked about making the simulation into more of a game, rather than just a simple simulation. We brainstormed that we could have a game where the user has to do something specific, then redo something similar with visual conditions applied over top. We discussed about having visual condition stack ontop of each other. I then showed her what i had been working on. I showed her my Glaucoma effects and the kitchen with the objects with physics. She was happy with where I was in development. I clarified some extra details about certain visual impairments with her while she was in person, and now I know exactly where I need to go from here.

### Thursday Class:
After my meeting with Mary on Tuesday, Mary and Adon had a talk about new ideas regarding the simulation. They thought of ways to improve the feel of the game. They came up with an idea of making it more of a game. This time instead having pressured situations with a time limit or something close to that. Adon and I talked about it together and thought of simple ideas such as a pot in a kitchen is about to boil over but then the phone rings. It would be a rather simple fix without any visual conditions applied, but once the conditions are applied it would become much harder. This talk about making it more of a game definitely increased my interest on the topic and increased my performance. I also began work on my Menu system. I decided to follow a 'Constellation Menu' layout, where the menu progressively grows bigger as you choose mroe options. I felt like this way was the best for users in VR.

### Reflection:

## Week: 8
### Monday Class:
Over the weekend I had finished up a basic implementation of my menu system. It was able to print out the games of all of the options that I had in it which meant I simply had to attach things to do on the end. However, once I started trying to do this I was getting a null error which I didn't seem to understand.
On the Monday class, I asked Adon and some of the other game dev students for help. We realised that Unity had tried to instance the Post Processing Module multiple times, thus creating a null version of itself. In the end, it was an easy fix that just took a wee bit of time to find.
Mary was unable to make it for a meeting today, so we arranged to meetup during my Thursday class instead.
After this Monday class, I went home and implented a Glaucoma and a substitute preset for Cataracts in the menu. The menu can now add these effects over the user's screen, and they can stack. There is also a reset button that resets the effects.

### Thursday Class:
Today I was scheduled to meet with Mary but she was unable to attend. So instead, I decided to work on cleaning up my project. I added colourblindness options to the menu as placeholders for future development (and as reminders to do my work). I also went through and removed all duplicate code and just generally cleaned up my code for my scripts. Other than that, I did not do much work as I was expecting Mary to arrive for a meeting and did not want to get too indepth with work and have to pause progress.

### Reflection:

## Holidays:
Over the holidays, I did not have a lot of time to work on my project as I was not home for much of it. In the time I was able to work on it, I focused on cleaning up the game and making it more user friendly, as well as add a few more features to the game.
The first thing I did was add a menu system. At the moment, it simply just has a "play" button which when clicked, activates the objective in the game. I also prevented the user from interactng with objects in the world until the play button has been clicked to prevent them from messing up the scene before they are meant to.
My next part was to add in some missing visual effects. I began by creatign a new blur shader to represent Cataracts as there was no good plugins for Unity which provided the blur I wanted, while also running smoothly on a mobile device. This caused the most problems as mobile devices do not like using shaders, so as it stands, my current blur shader reduces performance rather heavily. This doesn't matter too much when it is used alone, but once you start stacking other visual conditions with it, the game really begins to struggle. With all my visual effects stacked, it reduces performance to around 25-30 fps which is borderline unplayable in a VR situation. For now, I am going to leave it as it is and work on more important features.
Next on the list was to implement colour blindness as I had already played around with it previously. It turns out that the shaders I was using were too performance heavy for mobile devices. I researched some new ways of implementing it and found a much more optimsed mobile shader which worked very similarily, except excluded tritanopia. I have implemented this for now, and will try and find a solution to implement tritanopia in the future.
I wanted there to be more interaction with the environment to make the kitchen feel more realistic. To get this feel, I added in an interactable cupboard below one of the kitchen benches, as well as a drawer that slides out under the sink. This way the user is able to open and close the doors, and put stuff inside of these places. It worked well, however it felt a little clunky to use, so I decided to rework my pointer, and how it interacts with objects. I opted to change my pointer from being a simple GVRpointer, to being more of a manipulation pointer. This means that I added a smoother reticle, as well as the pointer's laser now dynamically moves based on the 'mass' of an object. If you pick up and object, the laser now bends depending on what the object it. It just makes everything feel a little more realistic, and also prevents the reticle from falling off of objects (especially the cupboard and drawer) when using them. While I was adding this feature, I also added in the ability to move and object forward and backwards in the world space simply using the touch pad.
Lastly I just cleaned up the game a little. I changed the way that shadows are rendered in the game. They now look a lot smoother and not as ugly, while running better on mobile than they used to. I also added a simply hover effect that highlights objects when hovering over them.


