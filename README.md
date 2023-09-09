
# Introduction

I am a full-stack programmer from Colombia with 3 years of experience and I am on the platform since 2017 (starting from another account) contributing 12.5M+ visits to the platform.

My motivations and focus are always in creating complex, optimized, functional and expandable systems.

I count on experience in sections such as:
- Implementing and working with VFX (I don't create them)
- I work very well with the user interface experience, and I know how to use libraries like **[Blend](https://quenty.github.io/NevermoreEngine/api/Blend/)** and [**Fusion**](https://elttob.uk/Fusion/)
- I am also good with data structures; I know how to work with libraries like [**Datastore2**](https://kampfkarren.github.io/Roblox/) and [**ProfileService**](https://madstudioroblox.github.io/ProfileService/), but I usually do my own implementations.
- I am familiar with [**Promises**](https://eryn.io/roblox-lua-promise/), and I use them a lot on my projects with things like DataStores, HTTP requests, etc.
- I know how to work with frameworks such as [**Knit**](https://sleitnick.github.io/Knit/) and [**Nevermore Engine**](https://quenty.github.io/NevermoreEngine/).
- I normally work with Rojo and Git.

## What can I do?

I can do a variety of systems; however, I have my limitations.

My forte is backend, but as I said, I am a full-stack programmer. I can do a lot of what you want me to do; I am good at mathematics like trigonometry and physics.

Like the effect I did in my basic VFX implementation sample to give that effect of moving the dummy with your mouse.

```
local direction = (ray.Position - towerToSpawn:GetPivot().Position) * 16
				local rotationRadian = math.rad(rotation)
				local cosR = math.cos(rotationRadian)
				local sinR = math.sin(rotationRadian)
				local relativeDir = Vector3.new(
					direction.X * cosR - direction.Z * sinR,
					direction.Y,
					direction.X * sinR + direction.Z * cosR
				)

				towerToSpawn:PivotTo(towerToSpawn:GetPivot():Lerp(
					CFrame.new(ray.Position.X, y, ray.Position.Z) *
					CFrame.Angles(0, rotationRadian, 0) *
					CFrame.Angles(math.rad(-relativeDir.Z), 0, math.rad(relativeDir.X)),
					.25
				))
```

I am always willing to keep good communication with my team and be motivated (I like money) to deliver all my assigned tasks.

In this repository, you can find samples of my code, in case you know about programming and are directly interested in seeing how my programming style and practices work.
## VFX demo and basic optimization showcase

[Here's](https://www.roblox.com/games/11596954214/VFX-work-showcase) a place with basic VFX implementation:

![AnotherGif](https://github.com/RenKa001/Portfolio-WIP/assets/119909665/b6751df4-aa7b-4f23-9463-f0cace1b04d0)

**Game controls:**
- **1, 2, 3, 4, 5** to select a dummy or clicking on the hotbar.
- **Q** to cancel placement.
- **Left click** to select or place a tower.

*The place will be updated soon.*

Mini showcase of a interesting menu UI effect.
https://streamable.com/lzaono

## DataStore
[Here's](https://github.com/RenKa001/Code-showcase/blob/main/StandardDataStoreExample.lua) a code showcase of my basic way to work with DataStores using [Promises](https://eryn.io/roblox-lua-promise/)
## Pending list

- Add Knit and Nevermore Engine examples.
- More Promises examples.
- Blend and Fusion Examples.
