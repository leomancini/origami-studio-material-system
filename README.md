# Origami Android Components

#### Done
- Notification (Samsung)
- Share Sheet
- Bottom Navigation Bar
- Button
- Top App Bar
- System Navigation Bar

#### To clean + add to repo
- Notification (Standard Android)
- Action Sheet
- Tabs

#### To Do
- Organize inside of Bottom Navigation Bar

# Documentation

&nbsp;

## Bottom Navigation

### Layer Inputs

* **Enable**&nbsp;&nbsp; A boolean that is true when the tab bar is displayed.
* **Position Y**&nbsp;&nbsp; The vertical position of the bottom navigation relative to the bottom of its parent group or screen.
* **Opacity**&nbsp;&nbsp; The opacity of the tab bar.
* **Only Show Label on Selected Tab**&nbsp;&nbsp; A boolean that determines if labels should be only shown on the selected tab or on all tabs.
* **Number of Tabs**&nbsp;&nbsp; A number representing the number of items in the bottom navigation.
* **Switch to Tab**&nbsp;&nbsp; The index of the tab to switch to, starting at 0.
* **Switch Tab**&nbsp;&nbsp; A pulse that changes the currently selected tab.
* **Background**&nbsp;&nbsp; The background color of the bottom navigation.
* **Unselected Tabs Icon Color**&nbsp;&nbsp; The color of the icons of the unselected tabs.
* **Unselected Tabs Label Color**&nbsp;&nbsp; The color of the labels of the unselected tabs.
* **Selected Tab Icon Color**&nbsp;&nbsp; The color of the icon of the selected tab.
* **Selected Tab Label Color**&nbsp;&nbsp; The color of the label of the selected tab.
* **Pressed Indicator Enable**&nbsp;&nbsp; A boolean that determines if a pressed indicator is shown on tabs when tapped.
* **Pressed Indicator Use Auto Color**&nbsp;&nbsp; A boolean that determines if the pressed indicator color is automatically generated based on the background and tab icon colors.
* **Pressed Indicator Manual Color**&nbsp;&nbsp; The color of the pressed indicator if Use Auto Color is not set to true.

### Layer Outputs

* **Selected Tab Index**&nbsp;&nbsp; An index that represents the currently selected tab, starting at 0.
* **Selected Tab Label**&nbsp;&nbsp; A text string that represents the label of the currently selected tab.
* **Any Tab Tapped**&nbsp;&nbsp; A pulse that represents when any tab is tapped.
* **Tab 1 Tapped**&nbsp;&nbsp; A pulse that represents when the first tab is tapped.
* **Tab 2 Tapped**&nbsp;&nbsp; A pulse that represents when the second tab is tapped.
* **Tab 3 Tapped**&nbsp;&nbsp; A pulse that represents when the third tab is tapped.
* **Tab 4 Tapped**&nbsp;&nbsp; A pulse that represents when the fourth tab is tapped.
* **Tab 5 Tapped**&nbsp;&nbsp; A pulse that represents when the fifth tab is tapped.
* **Tab 6 Tapped**&nbsp;&nbsp; A pulse that represents when the sixth tab is tapped.

&nbsp;

## System Navigation Bar 

### Layer Inputs

* **Enable**&nbsp;&nbsp; A boolean that is true when the navigation bar is displayed.
* **Theme**&nbsp;&nbsp; Determines the color theme of the navigation bar.
* **Switch to Light**&nbsp;&nbsp; A pulse that switches the color theme to dark.
* **Switch to Dark**&nbsp;&nbsp; A pulse that switches the color theme to dark.

### Layer Outputs

* **Any Button Tapped**&nbsp;&nbsp; A pulse that represents when any button is tapped.
* **Back Button Tapped**&nbsp;&nbsp; A pulse that represents when the back button is tapped.
* **Home Button Tapped**&nbsp;&nbsp; A pulse that represents when the home button is tapped.
* **App Switcher Button Tapped**&nbsp;&nbsp;A pulse that represents when the app switcher button is tapped.
* **Height**&nbsp;&nbsp;A number representing the height of the navigation bar, in points.