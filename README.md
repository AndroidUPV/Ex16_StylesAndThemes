# Ex16_StylesAndThemes
Lecture 02 - Development of Graphical User Interfaces (GUI)

The app does not have any functionality, as its aim is just show how to use themes and styles. 
- Theme.Material3.DayNight.NoActionBar is extended (in /res/values/themes.xml) and set as the main app's theme in the Manifest. All text will be set to 24sp.
- A custom style is declared in /res/values/styles.xml and set for on a TextView in the activity's layout.
- Two buttons are included, each one with a different style:
  - First one, an AppCompatButton, has the default (old) Button style.
  - Second one presents the Material3 Button (set as the style by default by the app's theme)
  - The third one has the Material3 theme set in its style property. It has the same look an feel as the second Button, since regular Buttons are promoted to MaterialButtons when using a MaterialDesign theme.