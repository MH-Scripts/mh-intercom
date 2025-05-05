<p align="center">
    <img width="140" src="https://icons.iconarchive.com/icons/iconarchive/red-orb-alphabet/128/Letter-M-icon.png" />  
    <h1 align="center">Hi 👋, I'm MaDHouSe</h1>
    <h3 align="center">A passionate allround developer </h3>    
</p>

<p align="center">
  <a href="https://github.com/MH-Scripts/mh-intercom/issues">
    <img src="https://img.shields.io/github/issues/MH-Scripts/mh-intercom"/> 
  </a>
  <a href="https://github.com/MH-Scripts/mh-intercom/watchers">
    <img src="https://img.shields.io/github/watchers/MH-Scripts/mh-intercom"/> 
  </a> 
  <a href="https://github.com/MH-Scripts/mh-intercom/network/members">
    <img src="https://img.shields.io/github/forks/MH-Scripts/mh-intercom"/> 
  </a>  
  <a href="https://github.com/MH-Scripts/mh-intercom/stargazers">
    <img src="https://img.shields.io/github/stars/MH-Scripts/mh-intercom?color=white"/> 
  </a>
  <a href="https://github.com/MH-Scripts/mh-intercom/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/MH-Scripts/mh-intercom?color=black"/> 
  </a>      
</p>

# MH Intercom
- The best intercom script for fivem.
- Add intercoms in your world for drivein at the mac or burgershot.
- or you can use it in the police HQ as intercom.

## Dependencies:
- [qb-core](https://github.com/qbcore-framework/qb-core) (Required)
- [pma-voice](https://github.com/AvarianKnight/pma-voice) (Required)

## Suports
- pma-voice
- TokoVOIP

# Exports Example
```lua
local job = 'ambulance'                       -- job 
local customerCoords = vector3(0.0, 0.0, 0.0) -- curtimer location
local workerCoords = vector3(0.0, 0.0, 0.0)   -- worker location
local number = 123456                         -- must by a unique number
local drivein = false                         -- is this a drive in
exports['mh-intercom']:AddIntercomLocation(job, customerCoords, workerCoords, number, drivein) -- Add Intercom Location 
```

# LICENSE
[GPL LICENSE](./LICENSE)<br />
&copy; [MaDHouSe79](https://www.youtube.com/@MaDHouSe79)