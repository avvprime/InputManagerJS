# InputManagerJS
Simple keyboard input manager to check key "is pressed" or "is just pressed"

```
if ( InputManager.pressed.KeyA ) {
  // go left
  // returns true while pressed A
}

if ( InputManager.justPressed.Space ) {
  // jump
  // returns true only once, then returns false for next checks
  // user must press Space again in order to return true
}


```
