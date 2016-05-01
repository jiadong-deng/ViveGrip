# Vive Grip

The HTC Vive is an amazing platform that enables you to make amazing content. However, [SteamVR for Unity](https://www.assetstore.unity3d.com/en/#!/content/32647) leaves controller interaction up to you and has sparse documentation. Compounding this, Unity's [ConfigurableJoint](http://docs.unity3d.com/Manual/class-ConfigurableJoint.html) is the best way to simulate object grabbing but also lacks documentation for how complex it is.

Vive Grip handles these for you. A few simple scripts let you can create immersive interactions with game objects. It lets you worry about your awesome game logic instead of boilerplate interaction code.

## Usage

1. Import the [SteamVR Plugin](https://www.assetstore.unity3d.com/en/#!/content/32647) and place their prefab rig in your scene
2. Import the latest [Vive Grip release]()
3. Add Vive Grip's `Grip Point` prefab under a controller object where objects will attach to
4. Set the prefab's `Tracked Object` in the Inspector to the appropriate `SteamVR_TrackedObject`

The [API](API.md) is showcased in the [Demo Scene]().

## Why use Vive Grip?

- Fully supports Unity's physics systems for realistic interactions
- Smooth grab pathing prevents disruptive movements
- Configurable options support your unique interaction needs
- Supports both grabbable objects and interaction hooks

## [Support]()

If you like Vive Grip and want to show your support, please leave a review on [the Asset Store page](). It makes a huge difference in helping others find this package.

If you found Vive Grip helpful then also consider purchasing it on [the Asset Store]() to show your appreciation. It takes a lot of time and effort to work on this package and your donations help me keep it free on GitHub.