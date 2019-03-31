# Origami Android Components

- [Bottom Navigation Bar](https://github.com/leomancini31/origami-android-components#bottom-navigation-bar)
- [Button](https://github.com/leomancini31/origami-android-components#button)
- [Samsung Notification](https://github.com/leomancini31/origami-android-components#samsung-notification)
- [Share Sheet](https://github.com/leomancini31/origami-android-components#share-sheet)
- [System Navigation Bar](https://github.com/leomancini31/origami-android-components#system-navigation-bar)
- [Top App Bar](https://github.com/leomancini31/origami-android-components#top-app-bar)

#### To clean + add to repo
- Notification (Standard Android)
- Action Sheet
- Tabs

#### To Do

&nbsp;
&nbsp;
&nbsp;

## Bottom Navigation Bar

![Screenshot of Bottom Navigation Bar](https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Bottom%20Navigation%20Bar.jpg "Bottom Navigation Bar")

Download: [Component](https://github.com/leomancini31/origami-android-components/raw/master/Android%20Components/Bottom%20Navigation%20Bar.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Bottom%20Navigation%20Bar%20%E2%80%93%20Example.origami) 

### Inputs

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

### Outputs

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

## Button

![Screenshot of Button](https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Button.jpg "Button")

Download: [Component](https://github.com/leomancini31/origami-android-components/raw/master/Android%20Components/Button.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Button%20%E2%80%93%20Example.origami) 

### Inputs

* **Enable**&nbsp;&nbsp; A boolean that is true when the button is displayed.
* **Position**&nbsp;&nbsp; The position to display the button.
* **Anchor**&nbsp;&nbsp; The anchor point to position the button relative to.
* **Margin**&nbsp;&nbsp; The width and height of the margin around the button.
* **Use Auto Width**&nbsp;&nbsp; A boolean that determines if the width should be automatically set based on the width of the label text.
* **Manual Width**&nbsp;&nbsp; A number that represents the width of the button, if Use Auto Width is not set to true.
* **Background Color**&nbsp;&nbsp; The background color of the button.
* **Label Text**&nbsp;&nbsp; A string that represents the text of the label of the button.
* **Label Use Auto Text Color**&nbsp;&nbsp; A boolean that determines if the label color is automatically generated based on the button's background color.
* **Label Manual Text Color**&nbsp;&nbsp; The color of the label if Use Auto Text Color is not set to true.

### Outputs

* **Button Tapped**&nbsp;&nbsp; A pulse that represents when the button is tapped.
* **Button Down**&nbsp;&nbsp; A boolean that is true when the button is pressed.

&nbsp;

## Samsung Notification

![Screenshot of Samsung Notification](https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Samsung%20Notification.jpg "Samsung Notification")

Download: [Component](https://github.com/leomancini31/origami-android-components/raw/master/Android%20Components/Notification.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Notification%20%E2%80%93%20Example.origami) 

### Inputs

* **Present**&nbsp;&nbsp; A pulse that displays the notification.
* **Dismiss**&nbsp;&nbsp; A pulse that hides the notification.
* **App Icon**&nbsp;&nbsp; An image representing the icon of the app that is delivering the notification.
* **App Name**&nbsp;&nbsp; A text string that displays the name of the app that is delivering the notification.
* **Title**&nbsp;&nbsp; A text string that displays the subject.
* **Body Text**&nbsp;&nbsp; A text string that displays more information.
* **Show Right Image**&nbsp;&nbsp; A boolean that determines if a thumbnail image is shown on the right side of the notification.
* **Right Image**&nbsp;&nbsp; An image that represents the thumbnail image.
* **Type**&nbsp;&nbsp; The type of notification: temporary, persistent.

### Outputs

* **Notification Tapped**&nbsp;&nbsp; A pulse that represents when the notification is tapped.

&nbsp;

## Share Sheet

![Screenshot of Share Sheet](https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Share%20Sheet.jpg "Share Sheet")

Download: [Component](https://github.com/leomancini31/origami-android-components/raw/master/Android%20Components/Share%20Sheet.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Share%20Sheet%20%E2%80%93%20Example.origami) 

### Inputs

* **Present**&nbsp;&nbsp; A pulse that displays the share sheet.

### Outputs

* **Tapped Icon Index**&nbsp;&nbsp; An index that represents which icon is tapped, starting at 0.
* **Any Icon Tapped**&nbsp;&nbsp; A pulse that represents when any icon is tapped.
* **Icon 1 Tapped**&nbsp;&nbsp; A pulse that represents when the first icon is tapped.
* **Icon 2 Tapped**&nbsp;&nbsp; A pulse that represents when the second icon is tapped.
* **Icon 3 Tapped**&nbsp;&nbsp; A pulse that represents when the third icon is tapped.
* **Icon 4 Tapped**&nbsp;&nbsp; A pulse that represents when the fourth icon is tapped.
* **Icon 5 Tapped**&nbsp;&nbsp; A pulse that represents when the fifth icon is tapped.
* **Icon 6 Tapped**&nbsp;&nbsp; A pulse that represents when the sixth icon is tapped.

&nbsp;

## System Navigation Bar

![Screenshot of System Navigation Bar](https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/System%20Navigation%20Bar.jpg "System Navigation Bar")

Download: [Component](https://github.com/leomancini31/origami-android-components/raw/master/Android%20Components/System%20Navigation%20Bar.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/System%20Navigation%20Bar%20%E2%80%93%20Example.origami) 

### Inputs

* **Enable**&nbsp;&nbsp; A boolean that is true when the navigation bar is displayed.
* **Theme**&nbsp;&nbsp; Determines the color theme of the navigation bar.
* **Switch to Light**&nbsp;&nbsp; A pulse that switches the color theme to dark.
* **Switch to Dark**&nbsp;&nbsp; A pulse that switches the color theme to dark.

### Outputs

* **Any Button Tapped**&nbsp;&nbsp; A pulse that represents when any button is tapped.
* **Back Button Tapped**&nbsp;&nbsp; A pulse that represents when the back button is tapped.
* **Home Button Tapped**&nbsp;&nbsp; A pulse that represents when the home button is tapped.
* **App Switcher Button Tapped**&nbsp;&nbsp;A pulse that represents when the app switcher button is tapped.
* **Height**&nbsp;&nbsp;A number representing the height of the navigation bar, in points.

&nbsp;

## Top App Bar

![Screenshot of Top App Bar](https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Top%20App%20Bar%20–%20596792340.jpg "Top App Bar")

Download: [Component](https://github.com/leomancini31/origami-android-components/raw/master/Android%20Components/Top%20App%20Bar.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Top%20App%20Bar%20%E2%80%93%20Example.origami)

### Inputs

* **Enable**&nbsp;&nbsp; A boolean that is true when the app bar is displayed.
* **Type**&nbsp;&nbsp; The size of the app bar: either regular or prominent.
* **Background Image**&nbsp;&nbsp; The background image of the app bar. If an image is set, the image will cover the background color.
* **Background Color**&nbsp;&nbsp; The background color of the app bar.
* **Title Text**&nbsp;&nbsp; A text string that represents the title of the page.
* **Title Color**&nbsp;&nbsp; The color of the title.
* **Title Alignment**&nbsp;&nbsp; The text alignment of the title: either left, right, or center.
* **Left Icon Enable**&nbsp;&nbsp; A boolean that determines if the left icon is shown.
* **Left Icon Image**&nbsp;&nbsp; The image of the left icon.
* **Left Icon Color**&nbsp;&nbsp; The color of the left icon.
* **Right Icon Enable**&nbsp;&nbsp; A boolean that determines if the right icon is shown.
* **Right Icon Image**&nbsp;&nbsp; The image of the right icon.
* **Right Icon Color**&nbsp;&nbsp; The color of the right icon.
* **Pressed Indicator Enable**&nbsp;&nbsp; A boolean that determines if a pressed indicator is shown on icons when tapped.
* **Pressed Indicator Use Auto Color**&nbsp;&nbsp; A boolean that determines if the pressed indicator color is automatically generated based on the background and icon colors.
* **Pressed Indicator Manual Color**&nbsp;&nbsp; The color of the pressed indicator if Use Auto Color is not set to true.

### Outputs

* **Left Icon Tapped**&nbsp;&nbsp; A pulse that represents when the left icon is tapped.
* **Right Icon Tapped**&nbsp;&nbsp; A pulse that represents when the right icon is tapped.
* **Height**&nbsp;&nbsp; A number representing the height of the app bar, in points.

&nbsp;