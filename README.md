# UnityAndroidPoc
Poc to use an Android native UI and interact with a Unity scene

In UnityPlayerActivity
- Add a native view over the Unity scene
- Interact from native UI to Unity with `UnityPlayer.UnitySendMessage("Sphere", "Left","");` where `Sphere` is the object and `Left` the method.

![](https://github.com/laurentlr/UnityAndroidPoc/blob/main/unityGif.gif)
