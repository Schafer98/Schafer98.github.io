# Schafer98.github.io
We were given a project to design an environment in which COVID has changed me.  My scene describes the summer I had than the one I was supposed to have.  I was supposed to have an internship but due to the pandemic it was cancelled and was left with nothing for the summer.


CS 4331 Virtual Reality - Fall 2020

This is my VR Apartment that I created to represent how COVID-19 has effected me.  Over the summer I was my internship was cancelled and I was stuck here in Lubbock.  The objects that I have in my apartment represent a few of the things I would do on a regular basis that I will describe more later on.
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


Coming in you immediately see a custom made table with custom leather chairs surrounding it and a board game on top of it.  A very fun thing my friends and I would do regularly was play board games once a week to keep us sane.
image


Next up where I spent a vast majority of my time was my bedroom.  
image1
image2

I included a dog because I spent a large part of my summer with a sweet puppy.  This object also has the functionality that when pet/clicked it will bark.
image
This is all the required code needed for it to work.  Make sure to include the audio file of your choosing
<a-entity gltf-model="#Dog" scale=".03 .03 .03" position="5.5 0.45 1.3" rotation="0 0 0" sound="src: url(DogBark.mp3); on: click" class="intersectable"></a-entity>

There is also a fan that is animated to make it seem as if it were on.  It was a very hot summer so my fan was never off.
imagefan


Next up is my at home gym.  Since all gyms were closed, including the Rec Center and my apartment's gym, my roommates and I had to improvise.  I was lucky that my one of my roomamates had weights at his house so he brought them up to Lubbock
image
We already had some weights at the apartment before hand so I made a feature to where if you look at the set of weights we did not have it will disappear to represent part of my turning COVID off feature.
All the required code:
<a-entity gltf-model="#WeightRoom" scale="1 1 1" position="-2.5 .6 4.25" rotation="0 -90 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable">


Lastly where I spent the rest of my time was at my computer.  As you can see there are a lot of cups just laying around on the floor.  My friends and I went to sonic regularly so there were times they'd start to build up in my room.  I used similary code above to have them disappear once you look at it because if COVID wasn't a thing I likely wouldn't be this lazy and let it happen.
imagepc
        <a-entity gltf-model="#TrashCup" scale=".9 .9 .9" position="20 0 0" rotation="0 225 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable"></a-entity>
        <a-entity gltf-model="#TrashCup" scale=".9 .9 .9" position="19 0 .5" rotation="0 225 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable"></a-entity>
        <a-entity gltf-model="#TrashCup" scale=".9 .9 .9" position="19.8 0 1" rotation="0 225 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable"></a-entity>
        <a-entity gltf-model="#TrashCup" scale=".9 .9 .9" position="18.5 0 2" rotation="0 225 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable"></a-entity>
        <a-entity gltf-model="#TrashCup" scale=".9 .9 .9" position="18 0 .5" rotation="0 225 0" event-set__makevisible="_event: mouseleave; visible: false" class="intersectable"></a-entity>
