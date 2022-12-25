# Ex16_StylesAndThemes
Lecture 02 - Development of Graphical User Interfaces (GUI)

The app does not have any functionality, as its aim is just show how to use themes and styles. 
- Theme.MaterialComponents.DayNight.DarkActionBar is extended (in /res/values/themes.xml) and set as the main app's theme in the Manifest. All text will be set to 24sp.
- A custom style is declared in /res/values/styles.xml and set for on a TextView in the activity's layout.
- Three buttons are included, each one with a different style:
  - First one, an AppCompatButton, has the default Button style.
  - Second one presents the Material2 theme (set as style by default by the app's theme)
  - The third one has the Material3 theme set as style in the activity's layout.