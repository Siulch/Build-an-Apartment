# Build an Apartment
Starter project for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Course: VR Scenes & Objects
- Project: Build an Apartment
- Submitting for: Android

### How to play
- When you press the Cardboard button or touch the screen, the globe spins until you press the button again
- When you double click the Cardboard button or double touch the screen, the camera teletransport to a different location of the apartment

### Versions Used
- [Unity LTS Release 2017.4.4](https://unity3d.com/unity/qa/lts-releases?version=2017.4)
- [GVR SDK for Unity v1.100.1](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.100.1)

### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated lesson.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.

### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is included.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.100.1, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.


### Related Repositories
- [VR Scenes and Objects - Game Objects](https://github.com/udacity/VR-Scenes-and-Objects_Game-Objects/releases)
- [VR Scenes and Objects - Animations](https://github.com/udacity/VR-Scenes-and-Objects_Animations/releases)
- [VR Scenes and Objects - Cameras](https://github.com/udacity/VR-Scenes-and-Objects_Cameras/releases)
- [VR Scenes and Objects - Lights](https://github.com/udacity/VR-Scenes-and-Objects_Lights/releases)
- VR Scenes and Objects - Build an Apartment

### Credits
- [Sound used](http://soundbible.com/2175-Street.html)
- [Extra Assets used](https://assetstore.unity.com/packages/3d/simple-home-stuff-69129)

### Note
- **How long it took to complete the project:** It took me 3 days to complete the project, dedicating more than 3 hours per day
- **One thing you liked about the project:** I love that i learn a lot of new stuff for VR and mostly on how to do them for my own. I put some extra things so i investigate a lot to make them 
- **One thing that was particularly challenging about the project:** I wanted to put the teleports so it can show all the apartment, but with the animated globe and the teleporters that worked by clicking one time the button they didn't apreciate to much. So i decided to change the teleportes to make them work by double clicking and for that i needed to investigate a lot and to edit the script