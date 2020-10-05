# Schafer98.github.io
We were given a project to design an environment in which COVID has changed me.  My scene describes the summer I had than the one I was supposed to have.  I was supposed to have an internship but due to the pandemic it was cancelled and was left with nothing for the summer.

YouTube Link: https://youtu.be/F-BAtDGqgAw
Demo Link: https://schafer98.github.io./

CS 4331 Virtual Reality - Fall 2020

![Image of GIF](https://github.com/Schafer98/Schafer98.github.io/blob/master/images/ReportImages/AptGIF.gif)


This is my VR Apartment that I created to represent how COVID-19 has effected me.  Over the summer I was my internship was cancelled and I was stuck here in Lubbock.  The objects that I have in my apartment represent a few of the things I would do on a regular basis that I will describe more later on.
![Image of Apartment Outside](https://github.com/Schafer98/Schafer98.github.io/blob/master/images/ReportImages/MyApt.PNG)


Coming in you immediately see a custom made table with custom leather chairs surrounding it and a board game on top of it.  A very fun thing my friends and I would do regularly was play board games once a week to keep us sane.
![Image of TableChairsBoardGame](https://github.com/Schafer98/Schafer98.github.io/blob/master/images/ReportImages/TableAndChairs.PNG)


Next up where I spent a vast majority of my time was my bedroom.  
![Image of RoomPic1](https://github.com/Schafer98/Schafer98.github.io/blob/master/images/ReportImages/RoomPic1.PNG)
![Image of RoomPic2](https://github.com/Schafer98/Schafer98.github.io/blob/master/images/ReportImages/RoomPic2.PNG)

I included a dog because I spent a large part of my summer with a sweet puppy.  This object also has the functionality that when pet/clicked it will bark.
![Image of Dog](https://github.com/Schafer98/Schafer98.github.io/blob/master/images/ReportImages/Dog.PNG)
This is all the required code needed for it to work.  Make sure to include the audio file of your choosing
<a-entity gltf-model="#Dog" scale=".03 .03 .03" position="5.5 0.45 1.3" rotation="0 0 0" sound="src: url(DogBark.mp3); on: click" class="intersectable"></a-entity>

There is also a fan that is animated to make it seem as if it were on.  It was a very hot summer so my fan was never off.
![Image of Fan](https://github.com/Schafer98/Schafer98.github.io/blob/master/images/ReportImages/MovingFan.PNG)


Next up is my at home gym.  Since all gyms were closed, including the Rec Center and my apartment's gym, my roommates and I had to improvise.  I was lucky that my one of my roomamates had weights at his house so he brought them up to Lubbock
![Image of Gym](https://github.com/Schafer98/Schafer98.github.io/blob/master/images/ReportImages/Weights.PNG)
We already had some weights at the apartment before hand so I made a feature to where if you look at the set of weights we did not have it will disappear to represent part of my turning COVID off feature.
All the required code:
<a-entity gltf-model="#WeightRoom" scale="1 1 1" position="-2.5 .6 4.25" rotation="0 -90 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable">


Lastly where I spent the rest of my time was at my computer.  As you can see there are a lot of cups just laying around on the floor.  My friends and I went to sonic regularly so there were times they'd start to build up in my room.  I used similary code above to have them disappear once you look at it because if COVID wasn't a thing I likely wouldn't be this lazy and let it happen.
![Image of PC](https://github.com/Schafer98/Schafer98.github.io/blob/master/images/ReportImages/PCarea.PNG)
        <a-entity gltf-model="#TrashCup" scale=".9 .9 .9" position="20 0 0" rotation="0 225 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable"></a-entity>
        <a-entity gltf-model="#TrashCup" scale=".9 .9 .9" position="19 0 .5" rotation="0 225 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable"></a-entity>
        <a-entity gltf-model="#TrashCup" scale=".9 .9 .9" position="19.8 0 1" rotation="0 225 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable"></a-entity>
        <a-entity gltf-model="#TrashCup" scale=".9 .9 .9" position="18.5 0 2" rotation="0 225 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable"></a-entity>
        <a-entity gltf-model="#TrashCup" scale=".9 .9 .9" position="18 0 .5" rotation="0 225 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable"></a-entity>
        
        
        
        
        
3D Models List:  (28 Objects)

Trees

Welcome mat (Custom)

Building Structure (Custom)

Table (Custom)

Chairs to table (Custom)

Board Game (Custom)

Plant

Benchpress

Dumbbells

Motorcycle Wall Picture (Custom)

PC Desk (Custom)

Monitor (Custom)

Mouse and Keyboard (Custom)

Desk Chair      

PC

Lamp (Custom)

Speakers

Trash Cups (With Custom Implementation - Disappear)

Fan (Custom)  

Bed

Bed Lamp

Dressor    

Books      

TV

TV Stand

Leather Couch

Dog (With Custom Implementation - Bark)  

Lights
        
        
-------------------------------------------------------------------------------------------------


Resources:

Leather for chairs
https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.123rf.com%2Fphoto_39299662_close-up-of-a-color-natural-leather-texture-leather-background.html&psig=AOvVaw3obrpR3DZaYFAvqVoRgju9&ust=1601955301459000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMC6zNbCnOwCFQAAAAAdAAAAABAD

Table Top:
https://cdn.shopify.com/s/files/1/2179/1185/products/32201-SWTACH_1_c800d4c8-3609-41b1-8033-9f51b13446d8.jpg?v=1576044725

Dog:
https://sketchfab.com/3d-models/dog-a89b49b3d9c647a8805d8d5287f47f48

TV:
https://sketchfab.com/3d-models/led-tv-014e75456b4e465b9cecd1b136a0312b

Gaming Computer:
https://sketchfab.com/3d-models/gaming-pc-free-download-dbf9c15333814afa88345312b521ddab

Speakers:
https://sketchfab.com/3d-models/speaker-3456982171f24599b8f25404989d2a6e

Trash Cup:
https://sketchfab.com/3d-models/styrofoam-cup-f78aae905da1484997b27545e70e3f0e
