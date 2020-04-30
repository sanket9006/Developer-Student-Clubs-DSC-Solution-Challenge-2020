
> This repository contains the submission for Developer Student Clubs [DSC] Solution Challenge 2020.
## <p align="center"> Project Title :- AR in Anatomy </p>


<p align="center">
 <img  src="https://github.com/sanket9006/Developer-Student-Clubs-DSC-Solution-Challenge-2020/blob/master/222.png">
</p>



**Team Member's Email :-**

          1) sanket.9006@gmail.com      
          2) prasad323122@gmail.com
          3) maheshparkour265512@gmail.com
          4) chaitanyaabhang9299@gmail.com

**University Name:-**

           JSPM's Jayawantrao Sawant College Of Engineering


**Please share about DSC related activities you participated in-**
          
          I have participited in two workshops hosted by DSC VIT, Pune one on Google Cloud using Qwiklabs 
    and Another Flutter (Android) Development

**When was this project started?**
          
          12-04-2020

**Solution/Project Name**

          AR (Augmented Reality) in Anatomy
          
**Share link to project**
          
          https://github.com/sanket9006/Developer-Student-Clubs-DSC-Solution-Challenge-2020
        
          
**Please select one or more products/platform utilized in your solution?**

          1) Google AR Core
          2) Firebase
          3) Unity Editor
          4) Sketchfab Unity Plugin
          
          
<p align="center">
 <img  src="https://github.com/sanket9006/Developer-Student-Clubs-DSC-Solution-Challenge-2020/blob/master/Unity + Arcore + Firebase  + Sketchfab.png">
</p>


**Please share a 2 minute or less video showing off the user journey of your solution**

[![IMAGE ALT TEXT HERE](https://github.com/sanket9006/Developer-Student-Clubs-DSC-Solution-Challenge-2020/blob/master/Picture1.png)](https://youtu.be/P3JJLimJYjw)
 


**Please clearly describe the challenge you are looking to solve with technology and how this solution addresses the challenge at hand**

          Currently, a student who wants to study Anatomy of different parts (organs) of the Human Body has to look and 
    understand everything from a picture or diagram.
          AR in Anatomy is an app that lets students explore the human body to understand how it works. By using this 
    app Users can see Anatomy of different Human body parts in action, rotate them, zoom in and out. The app also 
    gives labeling of small parts too. AR helps the student better remember the information they have just learned. 

**Walk us through the steps you took to test your solution**
             
           When we were creating this app, at that time we were creating APK of our project simultaneously for testing
    almost we have created APK 40 times. Out of which 20 were regarding the screen resolution problem related to 
    multiple devices. Also, I have distributed this app among my friends for suggestions and testing. During this, I
    have come across several issues that I fixed in my Final App.


**Please share the outcome of your testing strategy. What specific feedback did you receive from users? What specifically 
did you maintain or iterate based on that feedback?**
                
                When we were creating our Project (App) at that we were distributing that app to users (Beta testers 
       - Medical Student) where they suggested us to include labels on the diagram (3D Model) so that it will be 
       easy for them to      understand and study that diagram (3D model)
                Also, they told us to arrange the differents topics (3D models) according to the system. e.g  Heart 
       comes under the cardiovascular system.
                After that, we made changes to our project as per user feedback.

<p align="center">
 <img  src="https://github.com/sanket9006/Developer-Student-Clubs-DSC-Solution-Challenge-2020/blob/master/95.PNG">
</p>



<p align="center">
 <img  src="https://github.com/sanket9006/Developer-Student-Clubs-DSC-Solution-Challenge-2020/blob/master/96.PNG">
</p>


**How will or has your solution improved the lives of people in your community?**
         
         When our users (mostly Medical student) were stydying Anatomy they had to go through diagrams avaliable in books
         during which they found it defficult to study with the help of those diagrams because those diagrams contains
         a lot od different small parts and it was hard to understand or learn by just looking at diagram.
                   But by using our app they are now able to explore and interact with those diagrams.Because of which
         they were able to understand and visualize those diagrams in their mind easily as well as strongly.

**Please walk us through the steps you took to build your solution. Include which products or platforms you used and why. Please include guidance on how to run your code.**

Steps took to build solution :-

       1) Create New Unity3D project.
          (Platform - Unity 3D Editor) 
          
       2) Import 3D models using Sketchfab's Unity Plug
       
       3) Prepare AR Scene (This scene consist of ARCamera, Scripts, Prefab-3D Model) 
          (Platform - Google AR Core)
          
       4) Made multiple copies of ARScene, in my project I was having 15 3D objects that why I made 15 copies of the 
          AR scene.
          
       5) To place different objects in AR I replaced prefab present in each scene with respected 3D object.
       
       6) Created a c# script for changing scenes in order to switch to a different scene after clicking on different 
          buttons.
          (Platform - Using Visual Code Studio)
          
       7) Created the Main menu scene where 15 buttons were made available for the user to select as per his wish.
       
       8) Created Login / SignUp page (scene) for user.
          (Platform - Firebase)
       
       9) Created APK of project.
    
    
<p align="center">
<img  src="https://github.com/sanket9006/Developer-Student-Clubs-DSC-Solution-Challenge-2020/blob/master/s.png">
</p>

How to run your code
   
    To run our project you just have to install the APK in your smartphone and thats it.
          
    If want to open our project in unity editor and you have all required software like Unity Editor, ARCore Package 
    then by simple clicking Menu.unity file present in Assets\Scenes folder you can open this project
    
    
<p align="center"> Following Image shows 3D Files Imported using Sketchfab's Unity Plugin </p>
       
  
<p align="center">
<img  src="https://github.com/sanket9006/Developer-Student-Clubs-DSC-Solution-Challenge-2020/blob/master/9999999999999999.png">
</p>



**What do you see as the future / next steps for your project? What will take your project to the next level?**

                   Till now the app that we have developed is completely offline there is no need to worry about 
    internet connection in order to see Anatomy of different parts because by default 13 (Body parts) 3D objects 
    are already there. To take the app to the next level I would like to connect it to the cloud so that user 
    can select any part from many available options he wants to see using our app. Also to give VR capability 
    to our app.                
          
**What specific support do you need to achieve that?**
                    
                    I need help in two things one in editing code of ARCore for placing only one object in a 
    single scene which requires someone's expertise in coding and familiarity with Google ARCore and the second
    one is to give users the option to download new models which I will add to the app in future so someone's 
    expertise in Unity as well as Firebase storage will be helpful.

**Describe your favorite component (s) /feature (s) of your technical infrastructure and why you chose it/them for your solution.**
                    
                    My favorite technical infrastructure of my App is whatever 3D models (Anatomy of Parts) are
    available user can explore/see them in real-world (Augmented Reality)  Normally 3D models are available on 
    internet on different sites but the user is able to explore them using Laptop/Desktop, normally they don't 
    support mobile phones.
