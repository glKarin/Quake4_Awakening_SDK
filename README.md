# Quake4 Awakening game SDK

------------

Quake4 Awakening SDK  
Building or porting your mod and make it run on idTech4A++

------------

> State
|:-:|:-:|:-:|
|Class|File|Status|
|riVCWMissileTurret|[VehicleParts.cpp](neo/game/vehicle/VehicleParts.cpp ':include')|TODO|
|riVCWPulseCannon|[VehicleParts.cpp](neo/game/vehicle/VehicleParts.cpp ':include')|TODO|
|riVehiclePartSplineTether|[VehicleParts.cpp](neo/game/vehicle/VehicleParts.cpp ':include')|Unused|
|riVehiclePartBoost|[VehicleParts.cpp](neo/game/vehicle/VehicleParts.cpp ':include')|Simple|
|riVehicleSpeederBike|[VehicleSpeederBike.cpp](neo/game/vehicle/Vehicle_SpeederBike.cpp ':include')|Simple|
|rvWeaponFreezeGun|[WeaponFreezeGun.cpp](neo/game/weapon/WeaponFreezeGun.cpp ':include')|Simple|
|WeaponSpikeGun|[WeaponSpikeGun.cpp](neo/game/weapon/WeaponSpikeGun.cpp ':include')|Simple|
|WeaponGoobGun|[WeaponGoobGun.cpp](neo/game/weapon/WeaponGoobGun.cpp ':include')|Same as Napalm gun|
|riProjectileSpaceRocket|[Projectile.cpp](neo/game/Projectile.cpp ':include')|TODO|
|idTarget_ObjectiveBeacon|[Target.cpp](neo/game/Target.cpp ':include')|Simple|
|riFireFX|[FireFX.cpp](neo/game/FireFX.cpp ':include')|Simple|
|riMonsterRetch|[Monster_Retch.cpp](neo/game/ai/Monster_Retch.cpp ':include')|TODO|
|riMonsterPainLord|[Monster_PainLord.cpp](neo/game/ai/Monster_PainLord.cpp ':include')|TODO|
|riMonsterTank|[Monster_Tank.cpp](neo/game/ai/Monster_Tank.cpp ':include')|TODO|
|riMonsterWalker|[Monster_Walker.cpp](neo/game/ai/Monster_Walker.cpp ':include')|TODO|
|riMonsterValkaryne|[Monster_Valkaryne.cpp](neo/game/ai/Monster_Valkaryne.cpp ':include')|TODO|

------------

> Fixes
* Ice wall destroy in game/m08
* Player kill counter in game/m03

------------

> Features
* Full body awareness mod
* View body mod
* Bot in Multiplayer game

------------

### Android build  

> Build apk
#### 1-1: Build all
```gradlew assembleRelease```
#### 1-2: Build arm64 only
```gradlew assembleRelease -Pabifilters=arm64-v8a```
#### 1-3: Build arm32 only
```gradlew assembleRelease -Pabifilters=armeabi-v7a```
#### 2: target libraries on `quake4/build/outputs/apk/release`

------------

> Build library only
#### 1. enter source folder
```cd neo```
#### 2-1. Build arm64
```build_arm64.bat```
#### 2-2. Build arm32
```build_arm32.bat```
#### 3. target libraries on `neo/build`

------------
