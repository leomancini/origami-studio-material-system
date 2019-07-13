# Origami Android Components

- [Bottom Navigation Bar](https://github.com/leomancini31/origami-android-components#bottom-navigation-bar)
- [Button](https://github.com/leomancini31/origami-android-components#button)
- [Icon (Layer)](https://github.com/leomancini31/origami-android-components#icon-layer)
- [Icon (Patch)](https://github.com/leomancini31/origami-android-components#icon-patch)
- [Menu](https://github.com/leomancini31/origami-android-components#menu)
- [Samsung Notification](https://github.com/leomancini31/origami-android-components#samsung-notification)
- [Share Sheet](https://github.com/leomancini31/origami-android-components#share-sheet)
- [Bottom Sheet](https://github.com/leomancini31/origami-android-components#bottom-sheet)
- [System Navigation Bar](https://github.com/leomancini31/origami-android-components#system-navigation-bar)
- [Tabs](https://github.com/leomancini31/origami-android-components#tabs)
- [Top App Bar](https://github.com/leomancini31/origami-android-components#top-app-bar)

<br>

## Bottom Navigation Bar

*An Android bottom navigation with customizable tabs.*
<br>
*Use the Touch button on the component to get information about the selected tab.*

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Bottom%20Navigation%20Bar.gif" width="350">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Bottom%20Navigation%20Bar.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Bottom%20Navigation%20Bar%20%E2%80%93%20Example.origami) 

### Inputs

* **Enable**&nbsp;&nbsp; A boolean that is true when the tab bar is displayed.
* **Position Y**&nbsp;&nbsp; The vertical position of the bottom navigation relative to the bottom of its parent group or screen.
* **Opacity**&nbsp;&nbsp; The opacity of the tab bar.
* **Only Show Label on Selected Tab**&nbsp;&nbsp; A boolean that determines if labels should be only shown on the selected tab or on all tabs.
* **Number of Tabs**&nbsp;&nbsp; A number representing the number of items in the bottom navigation.
* **Switch to Tab**&nbsp;&nbsp; The index of the tab to switch to, starting at 0.
* **Switch Tab**&nbsp;&nbsp; A pulse that changes the currently selected tab.
* **Background Color**&nbsp;&nbsp; The background color of the bottom navigation.
* **Unselected Tabs Icon Color**&nbsp;&nbsp; The color of the icons of the unselected tabs.
* **Unselected Tabs Label Color**&nbsp;&nbsp; The color of the labels of the unselected tabs.
* **Selected Tab Icon Color**&nbsp;&nbsp; The color of the icon of the selected tab.
* **Selected Tab Label Color**&nbsp;&nbsp; The color of the label of the selected tab.
* **Pressed Indicator Enable**&nbsp;&nbsp; A boolean that determines if a pressed indicator is shown on tabs when tapped.
* **Pressed Indicator Use Auto Color**&nbsp;&nbsp; A boolean that determines if the pressed indicator color is automatically generated based on the background and tab icon colors.
* **Pressed Indicator Manual Color**&nbsp;&nbsp; The color of the pressed indicator if Use Auto Color is not set to true.

### Outputs

* **Selected Tab Index**&nbsp;&nbsp; An index that represents the currently selected tab, starting at 0.
* **Selected Tab Label Text**&nbsp;&nbsp; A text string that represents the label of the currently selected tab.
* **Any Tab Tapped**&nbsp;&nbsp; A pulse that represents when any tab is tapped.
* **Tab 1 Tapped**&nbsp;&nbsp; A pulse that represents when the first tab is tapped.
* **Tab 2 Tapped**&nbsp;&nbsp; A pulse that represents when the second tab is tapped.
* **Tab 3 Tapped**&nbsp;&nbsp; A pulse that represents when the third tab is tapped.
* **Tab 4 Tapped**&nbsp;&nbsp; A pulse that represents when the fourth tab is tapped.
* **Tab 5 Tapped**&nbsp;&nbsp; A pulse that represents when the fifth tab is tapped.
* **Tab 6 Tapped**&nbsp;&nbsp; A pulse that represents when the sixth tab is tapped.

&nbsp;

## Button

*A button with customizable style and text. Supports Text, Outlined, and Contained button types.*
<br>
*Use the Touch button on the component to capture when the button was tapped.*

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Button.gif" width="500">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Button.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Button%20%E2%80%93%20Example.origami) 

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

## Icon (Layer)

*An icon from [the baseline Material icon set](https://material.io/tools/icons/?style=baseline).*
<br>
*Requires an active Internet connection (icons are requested from the Google [GitHub repository](https://github.com/google/material-design-icons) of Material icons).*

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Icon.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Icon%20(Layer)%20%E2%80%93%20Example.origami) 

### Inputs

* **Enable**&nbsp;&nbsp; A boolean that is true when the icon is displayed.
* **Secure Request**&nbsp;&nbsp; A boolean that determines if the network request to get the icon image is made over HTTPS.
* **Position**&nbsp;&nbsp; The position to display the icon.
* **Anchor**&nbsp;&nbsp; The anchor point to position the icon relative to.
* **Category**&nbsp;&nbsp; A list of options that determines the category of the specified icon. These labels correspond to the top-level folder structure in [the GitHub repository](https://github.com/google/material-design-icons)</a>.
* **Icon Identifier**&nbsp;&nbsp; A text string that determines which icon is requested. These correspond to the string in between the 'ic' and the color in the URL to be loaded. For example, a value of '3d_rotation' would load <https://github.com/google/material-design-icons/blob/master/action/drawable-xxhdpi/ic_3d_rotation_black_18dp.png>
* **Size**&nbsp;&nbsp; A number, in Density Independent pixels, that determines the size of the specified icon. The value can be either 18, 24, 36, or 48.
* **Use Auto Resolution**&nbsp;&nbsp; A boolean that determines if resolution to be specified is automatically set based on the screen scale of the device.
* **Resolution**&nbsp;&nbsp; The resolution of the icon, if Use Auto Resolution is not set to true. The value can be either MDPI, HDPI, XHPDI, XXHPDI, or XXXHPDI.
* **Color**&nbsp;&nbsp; The color of the icon.

### Outputs

* **Image**&nbsp;&nbsp; An image that represents the specified icon.
* **Size**&nbsp;&nbsp; A width and height representing the size of specified icon, in points.

&nbsp;

## Icon (Patch)

*An icon from [the baseline Material icon set](https://material.io/tools/icons/?style=baseline).*
<br>
*Requires an active Internet connection (icons are requested from the Google [GitHub repository](https://github.com/google/material-design-icons) of Material icons).*

Download: [Patch Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Patches/Icon.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Icon%20(Patch)%20%E2%80%93%20Example.origami) 

### Inputs

* **Secure Request**&nbsp;&nbsp; A boolean that determines if the network request to get the icon image is made over HTTPS.
* **Category**&nbsp;&nbsp; A text string that determines the category of the specified icon. These labels correspond to the top-level folder structure in [the GitHub repository](https://github.com/google/material-design-icons)</a>.
* **Icon Identifier**&nbsp;&nbsp; A text string that determines which icon is requested. These correspond to the string in between the 'ic' and the color in the URL to be loaded. For example, a value of '3d_rotation' would load <https://github.com/google/material-design-icons/blob/master/action/drawable-xxhdpi/ic_3d_rotation_black_18dp.png>
* **Size**&nbsp;&nbsp; A number, in Density Independent pixels, that determines the size of the specified icon. The value can be either 18, 24, 36, or 48.
* **Use Auto Resolution**&nbsp;&nbsp; A boolean that determines if resolution to be specified is automatically set based on the screen scale of the device.
* **Resolution**&nbsp;&nbsp; The resolution of the icon, if Use Auto Resolution is not set to true. The value can be either MDPI, HDPI, XHPDI, XXHPDI, or XXXHPDI.

### Outputs

* **Image**&nbsp;&nbsp; An image that represents the specified icon.
* **Size**&nbsp;&nbsp; A width and height representing the size of specified icon, in points.

&nbsp;

## Menu

*An Android menu with a list of actions.*
<br>
*Use the Touch button on the component to capture which item was tapped.*

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Menu.gif" width="200">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Menu.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Menu%20%E2%80%93%20Example.origami) 

### Inputs

* **Enable**&nbsp;&nbsp; A boolean that is true when the menu is able to be displayed.
* **Present**&nbsp;&nbsp; A pulse that displays the menu.
* **Dismiss**&nbsp;&nbsp; A pulse that hides the menu.
* **Anchor**&nbsp;&nbsp; The anchor point to position the menu relative to.
* **Position**&nbsp;&nbsp; The position to display the menu.
* **Use Auto Width**&nbsp;&nbsp; A boolean that determines if the width should be automatically set based on the width of the longest item text.
* **Manual Width**&nbsp;&nbsp; A number that represents the width of the menu, if Use Auto Width is not set to true.
* **Use Auto Number of Items**&nbsp;&nbsp; A boolean that determines if number of visible items be automatically set based on the amount of items that have a text string assigned.
* **Manual Number of Items**&nbsp;&nbsp; A number that represents the number of visible items, if Use Auto Number of Items is not set to true.
* **Use Auto Pivot Position**&nbsp;&nbsp; A boolean that determines if the position where the menu originates from should be automatically set based on where the menu is positioned.
* **Manual Pivot Position**&nbsp;&nbsp; The position where the menu originates from, if Use Auto Pivot Position is not set to true.
* **Show Icons**&nbsp;&nbsp; A boolean that determines if an icon is shown on the left side of each item.

### Outputs

* **Tapped Item Index**&nbsp;&nbsp; An index that represents which item is tapped, starting at 0.
* **Tapped Item Text**&nbsp;&nbsp; A text string that represents the value of the item which is tapped.
* **Any Item Tapped**&nbsp;&nbsp; A pulse that represents when any item is tapped.
* **Item 1 Tapped**&nbsp;&nbsp; A pulse that represents when the first item is tapped.
* **Item 2 Tapped**&nbsp;&nbsp; A pulse that represents when the second item is tapped.
* **Item 3 Tapped**&nbsp;&nbsp; A pulse that represents when the third item is tapped.
* **Item 4 Tapped**&nbsp;&nbsp; A pulse that represents when the fourth item is tapped.
* **Item 5 Tapped**&nbsp;&nbsp; A pulse that represents when the fifth item is tapped.
* **Item 6 Tapped**&nbsp;&nbsp; A pulse that represents when the sixth item is tapped.
* **Item 7 Tapped**&nbsp;&nbsp; A pulse that represents when the seventh item is tapped.
* **Item 8 Tapped**&nbsp;&nbsp; A pulse that represents when the eigth item is tapped.
* **Item 9 Tapped**&nbsp;&nbsp; A pulse that represents when the ninth item is tapped.
* **Item 10 Tapped**&nbsp;&nbsp; A pulse that represents when the tenth item is tapped.
* **Item 11 Tapped**&nbsp;&nbsp; A pulse that represents when the eleventh item is tapped.
* **Item 12 Tapped**&nbsp;&nbsp; A pulse that represents when the twelvth item is tapped.

&nbsp;

## Samsung Notification

*A pushed Android notification with customizable app information and messaging. Visual style most closely aligns with Samsung UI.*
<br>
*Use the Touch button on the component to capture when the notification was tapped.*

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Samsung%20Notification.jpg" width="362">


Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Notification.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Notification%20%E2%80%93%20Example.origami) 

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

*An Android bottom sheet with share actions*
<br>
*Use the Touch button on the component to capture which icon was tapped.*

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Share%20Sheet.gif" width="300">

Icons from 
[Material Design](https://material.io/tools/icons/?style=baseline)

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Share%20Sheet.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Share%20Sheet%20%E2%80%93%20Example.origami) 

### Inputs

* **Present**&nbsp;&nbsp; A pulse that displays the share sheet.
* **Bottom Margin**&nbsp;&nbsp; A number representing the relative distance from the bottom of the screen. Useful for offsetting the position of the share sheet when a system navigation bar is present.

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

## Bottom Sheet

*An Android bottom sheet with a list of actions.*
<br>
*Use the Touch button on the component to capture which row was tapped.*

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Bottom%20Sheet.gif" width="300">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Bottom%20Sheet.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Bottom%20Sheet%20%E2%80%93%20Example.origami) 

### Inputs

* **Present**&nbsp;&nbsp; A pulse that displays the bottom sheet.
* **Number of Rows**&nbsp;&nbsp; A number that represents the number of visible rows.
* **Bottom Margin**&nbsp;&nbsp; A number representing the relative distance from the bottom of the screen. Useful for offsetting the position of the share sheet when a system navigation bar is present.
* **Row Icon Color**&nbsp;&nbsp; The color of the icon in each row.
* **Row Text Color**&nbsp;&nbsp; The color of the text label in each row.
* **Row Background Color**&nbsp;&nbsp; The color of the background of each row.

### Outputs

* **Tapped Row Index**&nbsp;&nbsp; An index that represents which row is tapped, starting at 0.
* **Tapped Row Label Text**&nbsp;&nbsp; A text string that represents the value of the label of the row which is tapped.
* **Any Icon Tapped**&nbsp;&nbsp; A pulse that represents when any row is tapped.
* **Row 1 Tapped**&nbsp;&nbsp; A pulse that represents when the first row is tapped.
* **Row 2 Tapped**&nbsp;&nbsp; A pulse that represents when the second row is tapped.
* **Row 3 Tapped**&nbsp;&nbsp; A pulse that represents when the third row is tapped.
* **Row 4 Tapped**&nbsp;&nbsp; A pulse that represents when the fourth row is tapped.
* **Row 5 Tapped**&nbsp;&nbsp; A pulse that represents when the fifth row is tapped.
* **Row 6 Tapped**&nbsp;&nbsp; A pulse that represents when the sixth row is tapped.

&nbsp;

## System Navigation Bar

*An Android system navigation bar. Visual style aligns with Samsung UI.*
<br>
*Use the Touch button on the component to capture taps on individual buttons.*

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/System%20Navigation%20Bar.gif" width="700">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/System%20Navigation%20Bar.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/System%20Navigation%20Bar%20%E2%80%93%20Example.origami) 

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

## Tabs

*An Android tab bar with customizable items.*
<br>
*Use the Touch button on the component to get information about the selected tab.*

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Tabs.gif" width="320">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Tabs.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Tabs%20%E2%80%93%20Example.origami)

### Inputs

* **Type**&nbsp;&nbsp; A list of options that determines if the tab includes text only, icons only, or icons and text.
* **Number of Tabs**&nbsp;&nbsp; A number representing the number of items in the tab bar.
* **Switch to Tab**&nbsp;&nbsp; The index of the tab to switch to, starting at 0.
* **Switch Tab**&nbsp;&nbsp; A pulse that changes the currently selected tab.
* **Tab Background Color**&nbsp;&nbsp; The background color of the tabs.
* **Shadow**&nbsp;&nbsp; A boolean that determines if a shadow is visible below the tabs.
* **Position Y**&nbsp;&nbsp; The vertical position of the tabs.
* **Selected Indicator Color**&nbsp;&nbsp; The color of the selected indicator of the selected tab.
* **Label and Icon Color (Selected Tab)**&nbsp;&nbsp; The color of the text label of the selected tab.
* **Label and Icon Color (Unselected Tab)**&nbsp;&nbsp; The color of the text label of the unselected tab.

### Outputs

* **Selected Tab Index**&nbsp;&nbsp; An index that represents the currently selected tab, starting at 0.
* **Selected Tab Label Text**&nbsp;&nbsp; A text string that represents the label of the currently selected tab.
* **Any Tab Tapped**&nbsp;&nbsp; A pulse that represents when any tab is tapped.
* **Tab 1 Tapped**&nbsp;&nbsp; A pulse that represents when the first tab is tapped.
* **Tab 2 Tapped**&nbsp;&nbsp; A pulse that represents when the second tab is tapped.
* **Tab 3 Tapped**&nbsp;&nbsp; A pulse that represents when the third tab is tapped.
* **Tab 4 Tapped**&nbsp;&nbsp; A pulse that represents when the fourth tab is tapped.
* **Tab 5 Tapped**&nbsp;&nbsp; A pulse that represents when the fifth tab is tapped.
* **Tab 6 Tapped**&nbsp;&nbsp; A pulse that represents when the sixth tab is tapped.

&nbsp;

## Top App Bar

*An Android top app bar with customizable left and right actions. It offers regular and prominent sizes.*
<br>
*Use the Touch button on the component to capture taps on individual icons in the app bar.*

<br>
<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Top%20App%20Bar.gif" width="320">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Top%20App%20Bar.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Top%20App%20Bar%20%E2%80%93%20Example.origami)

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