# AV3Code
Build VRChat Avatars 3.0 Gimmick with Coding
This is idea level project now.
Please feedback with Issue.

coding this
```csharp
// Parameter
bool isActiveObject = false;

void Setup() {
  // Toggle Button
  AddButton("Active Object", ButtonType.Toggle, isActiveObject);
}

// Layer
void ObjectActivator() {
  // State 1, Animation Clip 1
  if (isActiveObject) { // Transition 1, Condition 1
    object.SetActive(true);
  }
  // State 2, Animation Clip 2
  else { // Transition 2, Condition 2
    object.SetActive(false);
  }
}
```

after build gimmick
* Add Toggle Button to Expression Menu
* Add isActiveObject parameter (default false) to Expression Parameter and Animator Controller
* Add ObjectActivator layer to Animator Controller
* Add 2 States to ObjectActivator and Set 2 Animation Clips
* Add 2 Transitions to ObjectActivator layer and Set Conditions
