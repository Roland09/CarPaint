Assign Textures

* import Standard Assets
* import CarPaint.unitypackage
* open Scene Assets/SampleScenes/Scenes/Car.unity
* assign the materials in Car/Materials

  SkyCarBody -> SkyCarBody
  SkyCarBody -> SkyCarSuspensionFrontLeft
  SkyCarBody -> SkyCarSuspensionFrontRight
  SkyCarBody -> SkyCarMudGuardFrontLeft
  SkyCarBody -> SkyCarMudGuardFrontRight
  
  SkyCarWheel -> SkyCarWheelFrontLeft
  SkyCarWheel -> SkyCarWheelFrontRight
  SkyCarWheel -> SkyCarWheelRearLeft
  SkyCarWheel -> SkyCarWheelRearRight
  
  SkyCarComponents has 2 Materials, replace 
	SkyBarBodyGrey with SkyCarBody
	SkyCarLightCoversGrey with SkyCarLightCovers

Extract the Car out of the Standard Assets

* drag Car from Hierarchy to your Prefabs folder
* drag Cameras from Hierarchy to your Prefabs folder
* disable CarCameraRig and enable Free Look Camera Rig

When you use this setup, make sure you add your own Camera to the Free Look Camera Rig and assign the Car to the Target of Free Look Cam in the Inspector

