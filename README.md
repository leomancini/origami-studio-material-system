# Origami Android Components

- [Bottom Navigation Bar](https://github.com/leomancini31/origami-android-components#bottom-navigation-bar)
- [Bottom Sheet](https://github.com/leomancini31/origami-android-components#bottom-sheet)
- [Button](https://github.com/leomancini31/origami-android-components#button)
- [Floating Action Button](https://github.com/leomancini31/origami-android-components#floating-action-button)
- [Icon (Layer)](https://github.com/leomancini31/origami-android-components#icon-layer)
- [Icon (Patch)](https://github.com/leomancini31/origami-android-components#icon-patch)
- [Menu](https://github.com/leomancini31/origami-android-components#menu)
- [Notification](https://github.com/leomancini31/origami-android-components#notification)
- [Share Sheet](https://github.com/leomancini31/origami-android-components#share-sheet)
- [Slider](https://github.com/leomancini31/origami-android-components#slider)
- [System Navigation Bar](https://github.com/leomancini31/origami-android-components#system-navigation-bar)
- [Tabs](https://github.com/leomancini31/origami-android-components#tabs)
- [Top App Bar](https://github.com/leomancini31/origami-android-components#top-app-bar)

<br>

<b>How to Use</b>
In Origami Studio, open <i>Preferences</i>. Select <i>Systems</i> in the toolbar and then click the + in the bottom right. In the file browser, navigate to "Origami Material System", select "System", and then "Material" and click </i>Open<i>.
  
Now, in Origami files that have an Android device selected, the components will appear in the layer insertion popover or the Patch Library.

## Bottom Navigation Bar

An Android bottom navigation with customizable tabs.
<br>
Use the Touch button on the component to get information about the selected tab.

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Bottom%20Navigation%20Bar.gif" width="360">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Bottom%20Navigation%20Bar.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Bottom%20Navigation%20Bar%20%E2%80%93%20Example.origami) 

### Inputs

* **Enable**: A boolean that is true when the tab bar is displayed.
* **Bottom Margin**: A number representing the relative distance from the bottom of the screen. Useful for offsetting the position of the bottom navigation bar when a system navigation bar is present.
* **Opacity**: The opacity of the tab bar.
* **Only Show Label on Selected Tab**: A boolean that determines if labels should be only shown on the selected tab or on all tabs.
* **Number of Tabs**: A number representing the number of items in the bottom navigation.
* **Switch to Tab**: The index of the tab to switch to, starting at 0.
* **Switch Tab**: A pulse that changes the currently selected tab.
* **Background Color**: The background color of the bottom navigation.
* **Unselected Tabs Icon Color**: The color of the icons of the unselected tabs.
* **Unselected Tabs Label Color**: The color of the labels of the unselected tabs.
* **Selected Tab Icon Color**: The color of the icon of the selected tab.
* **Selected Tab Label Color**: The color of the label of the selected tab.
* **Pressed Indicator Enable**: A boolean that determines if a pressed indicator is shown on tabs when tapped.
* **Pressed Indicator Use Auto Color**: A boolean that determines if the pressed indicator color is automatically generated based on the background and tab icon colors.
* **Pressed Indicator Manual Color**: The color of the pressed indicator if <b>Use Auto Color</b> is not set to true.

### Outputs

* **Selected Tab Index**: An index that represents the currently selected tab, starting at 0.
* **Selected Tab Label Text**: A text string that represents the label of the currently selected tab.
* **Any Tab Tapped**: A pulse that represents when any tab is tapped.
* **Tab 1 Tapped**: A pulse that represents when the first tab is tapped.
* **Tab 2 Tapped**: A pulse that represents when the second tab is tapped.
* **Tab 3 Tapped**: A pulse that represents when the third tab is tapped.
* **Tab 4 Tapped**: A pulse that represents when the fourth tab is tapped.
* **Tab 5 Tapped**: A pulse that represents when the fifth tab is tapped.
* **Tab 6 Tapped**: A pulse that represents when the sixth tab is tapped.

&nbsp;

## Bottom Sheet

An Android bottom sheet with a list of actions.
<br>
Use the Touch button on the component to capture which row was tapped.

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Bottom%20Sheet.gif" width="360">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Bottom%20Sheet.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Bottom%20Sheet%20%E2%80%93%20Example.origami) 

### Inputs

* **Present**: A pulse that displays the bottom sheet.
* **Number of Rows**: A number that represents the number of visible rows.
* **Bottom Margin**: A number representing the relative distance from the bottom of the screen. Useful for offsetting the position of the share sheet when a system navigation bar is present.
* **Row Icon Color**: The color of the icon in each row.
* **Row Text Color**: The color of the text label in each row.
* **Row Background Color**: The color of the background of each row.

### Outputs

* **Tapped Row Index**: An index that represents which row is tapped, starting at 0.
* **Tapped Row Label Text**: A text string that represents the value of the label of the row which is tapped.
* **Any Icon Tapped**: A pulse that represents when any row is tapped.
* **Row 1 Tapped**: A pulse that represents when the first row is tapped.
* **Row 2 Tapped**: A pulse that represents when the second row is tapped.
* **Row 3 Tapped**: A pulse that represents when the third row is tapped.
* **Row 4 Tapped**: A pulse that represents when the fourth row is tapped.
* **Row 5 Tapped**: A pulse that represents when the fifth row is tapped.
* **Row 6 Tapped**: A pulse that represents when the sixth row is tapped.

&nbsp;

## Button

A button with customizable style and text. Supports Text, Outlined, and Contained button types.
<br>
Use the Touch button on the component to capture when the button was tapped.

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Button.gif" width="500">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Button.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Button%20%E2%80%93%20Example.origami) 

### Inputs

* **Enable**: A boolean that is true when the button is displayed.
* **Position**: The position to display the button.
* **Anchor**: The anchor point to position the button relative to.
* **Margin**: The width and height of the margin around the button.
* **Use Auto Width**: A boolean that determines if the width should be automatically set based on the width of the label text.
* **Manual Width**: A number that represents the width of the button, if <b>Use Auto Width</b> is not set to true.
* **Background Color**: The background color of the button.
* **Label Text**: A string that represents the text of the label of the button.
* **Label Use Auto Text Color**: A boolean that determines if the label color is automatically generated based on the button's background color.
* **Label Manual Text Color**: The color of the label if <b>Use Auto Text Color</b> is not set to true.

### Outputs

* **Button Tapped**: A pulse that represents when the button is tapped.
* **Button Down**: A boolean that is true when the button is pressed.

&nbsp;

## Floating Action Button

An Android floating action button that can be displayed in various formats (icon only, icon and text, centered, full-width, etc). Optionally, secondary buttons can appear when the floating action button is tapped.
<br>
Use the Touch button on the component to capture when the button is tapped or which secondary button was tapped.

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Floating%20Action%20Button.gif" width="160">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Floating%20Action%20Button.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Floating%20Action%20Button%20%E2%80%93%20Example.origami) 

### Inputs

* **Enable**: A boolean that is true when the floating action button is displayed.
* **Bottom Margin**: A number representing the relative distance from the bottom of the screen. Useful for offsetting the position of the floating action button when a system navigation bar is present.
* **Show Icon**: A boolean that determines whether the floating action button includes an icon.
* **Show Label**: A boolean that determines whether the floating action button includes a text label.
* **Full Width**: A boolean that determines whether the floating action button stretches to the full width of the device screen.
* **Center**: A boolean that determines whether the floating action button is centered within the width of the device screen.
* **Icon**: An image that represents the icon displayed on the floating action button.
* **Icon Color**: The color of the icon displayed on the floating action button.
* **Background Color**: The color of the floating action button.
* **Label**: A text string that represents the value of the label on the floating action button.
* **Label Color**: The color of the label on the floating action button.
* **Show Secondary Buttons on Tap**: A boolean that determines whether a list of secondary buttons is displayed when the floating action button is tapped. Secondary buttons are identified from bottom to top (the secondary button closest to the primary button is "Secondary Button 1" and the secondary button the furthest from the primary button is "Secondary Button 6".)
* **All Secondary Buttons - Icon Color**: The color of the icons displayed on each of the secondary buttons.
* **All Secondary Buttons - Number of Buttons**: A number that determines how many secondary buttons are visible. The minimum is 3 and the maximum is 6, determined by Material Design guidelines.
* **All Secondary Buttons - Show Labels**: A boolean that determines whether a text label is shown next to each of the secondary buttons.

### Outputs

* **Primary Button Tapped**: A pulse that represents when the floating action button is tapped.
* **Any Secondary Button Tapped**: A pulse that represents when any secondary button is tapped.
* **Tapped Secondary Button Index**: An index that represents which secondary button is tapped, starting at 0.  Secondary buttons are identified from bottom to top (the secondary button closest to the primary button is 0 and the secondary button the furthest from the primary button is 5.
* **Tapped Secondary Button Label Text**: A text string that represents the value of the label next to the secondary button which is tapped.
* **Secondary Button 1 Tapped**: A pulse that represents when the secondary button closest to the primary button is tapped.
* **Secondary Button 2 Tapped**: A pulse that represents when the secondary button second closest to the primary button is tapped.
* **Secondary Button 3 Tapped**: A pulse that represents when the secondary button third closest to the primary button is tapped.
* **Secondary Button 4 Tapped**: A pulse that represents when the secondary button fourth closest to the primary button is tapped.
* **Secondary Button 5 Tapped**: A pulse that represents when the secondary button fifth closest to the primary button is tapped.
* **Secondary Button 6 Tapped**: A pulse that represents when the secondary button sixth closest to the primary button is tapped.

&nbsp;

## Icon (Layer)

An icon from [the baseline Material icon set](https://material.io/tools/icons/?style=baseline).
<br>
Requires an active Internet connection (icons are requested from the Google [GitHub repository](https://github.com/google/material-design-icons) of Material icons).

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Icon.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Icon%20(Layer)%20%E2%80%93%20Example.origami) 

### Inputs

* **Enable**: A boolean that is true when the icon is displayed.
* **Secure Request**: A boolean that determines if the network request to get the icon image is made over HTTPS.
* **Position**: The position to display the icon.
* **Anchor**: The anchor point to position the icon relative to.
* **Category**: A list of options that determines the category of the specified icon. These labels correspond to the top-level folder structure in [the GitHub repository](https://github.com/google/material-design-icons)</a>.
* **Icon Identifier**: A text string that determines which icon is requested. These correspond to the string in between the 'ic' and the color in the URL to be loaded. For example, a value of '3d_rotation' would load <https://github.com/google/material-design-icons/blob/master/action/drawable-xxhdpi/ic_3d_rotation_black_18dp.png>
* **Size**: A number, in Density Independent pixels, that determines the size of the specified icon. The value can be either 18, 24, 36, or 48.
* **Use Auto Resolution**: A boolean that determines if resolution to be specified is automatically set based on the screen scale of the device.
* **Resolution**: The resolution of the icon, if <b>Use Auto Resolution</b> is not set to true. The value can be either MDPI, HDPI, XHPDI, XXHPDI, or XXXHPDI.
* **Color**: The color of the icon.

### Outputs

* **Image**: An image that represents the specified icon.
* **Size**: A width and height representing the size of specified icon, in points.

&nbsp;

## Icon (Patch)

This version of Icon can be used in the Patch Editor to output an icon image to another patch or layer.

An icon from [the baseline Material icon set](https://material.io/tools/icons/?style=baseline).
<br>
Requires an active Internet connection (icons are requested from the Google [GitHub repository](https://github.com/google/material-design-icons) of Material icons).

Download: [Patch Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Patches/Icon.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Icon%20(Patch)%20%E2%80%93%20Example.origami) 

### Inputs

* **Secure Request**: A boolean that determines if the network request to get the icon image is made over HTTPS.
* **Category**: A text string that determines the category of the specified icon. These labels correspond to the top-level folder structure in [the GitHub repository](https://github.com/google/material-design-icons)</a>.
* **Icon Identifier**: A text string that determines which icon is requested. These correspond to the string in between the 'ic' and the color in the URL to be loaded. For example, a value of '3d_rotation' would load <https://github.com/google/material-design-icons/blob/master/action/drawable-xxhdpi/ic_3d_rotation_black_18dp.png>
* **Size**: A number, in Density Independent pixels, that determines the size of the specified icon. The value can be either 18, 24, 36, or 48.
* **Use Auto Resolution**: A boolean that determines if resolution to be specified is automatically set based on the screen scale of the device.
* **Resolution**: The resolution of the icon, if <b>Use Auto Resolution</b> is not set to true. The value can be either MDPI, HDPI, XHPDI, XXHPDI, or XXXHPDI.

### Outputs

* **Image**: An image that represents the specified icon.
* **Size**: A width and height representing the size of specified icon, in points.

&nbsp;

## Menu

An Android menu with a list of actions.
<br>
Use the Touch button on the component to capture which item was tapped.

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Menu.gif" width="190">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Menu.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Menu%20%E2%80%93%20Example.origami) 

### Inputs

* **Enable**: A boolean that is true when the menu is able to be displayed.
* **Present**: A pulse that displays the menu.
* **Dismiss**: A pulse that hides the menu.
* **Anchor**: The anchor point to position the menu relative to.
* **Position**: The position to display the menu.
* **Use Auto Width**: A boolean that determines if the width should be automatically set based on the width of the longest item text.
* **Manual Width**: A number that represents the width of the menu, if <b>Use Auto Width</b> is not set to true.
* **Use Auto Number of Items**: A boolean that determines if number of visible items be automatically set based on the amount of items that have a text string assigned.
* **Manual Number of Items**: A number that represents the number of visible items, if <b>Use Auto Number of Items</b> is not set to true.
* **Use Auto Pivot Position**: A boolean that determines if the position where the menu originates from should be automatically set based on where the menu is positioned.
* **Manual Pivot Position**: The position where the menu originates from, if <b>Use Auto Pivot Position</b> is not set to true.
* **Show Icons**: A boolean that determines if an icon is shown on the left side of each item.

### Outputs

* **Tapped Item Index**: An index that represents which item is tapped, starting at 0.
* **Tapped Item Text**: A text string that represents the value of the item which is tapped.
* **Any Item Tapped**: A pulse that represents when any item is tapped.
* **Item 1 Tapped**: A pulse that represents when the first item is tapped.
* **Item 2 Tapped**: A pulse that represents when the second item is tapped.
* **Item 3 Tapped**: A pulse that represents when the third item is tapped.
* **Item 4 Tapped**: A pulse that represents when the fourth item is tapped.
* **Item 5 Tapped**: A pulse that represents when the fifth item is tapped.
* **Item 6 Tapped**: A pulse that represents when the sixth item is tapped.
* **Item 7 Tapped**: A pulse that represents when the seventh item is tapped.
* **Item 8 Tapped**: A pulse that represents when the eigth item is tapped.
* **Item 9 Tapped**: A pulse that represents when the ninth item is tapped.
* **Item 10 Tapped**: A pulse that represents when the tenth item is tapped.
* **Item 11 Tapped**: A pulse that represents when the eleventh item is tapped.
* **Item 12 Tapped**: A pulse that represents when the twelvth item is tapped.

&nbsp;

## Notification

A pushed Android notification with customizable app information and messaging. Visual style most closely aligns with Samsung UI.
<br>
Use the Touch button on the component to capture when the notification was tapped.

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Notification.jpg" width="360">


Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Notification.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Notification%20%E2%80%93%20Example.origami) 

### Inputs

* **Present**: A pulse that displays the notification.
* **Dismiss**: A pulse that hides the notification.
* **App Icon**: An image representing the icon of the app that is delivering the notification.
* **App Name**: A text string that displays the name of the app that is delivering the notification.
* **Title**: A text string that displays the subject.
* **Body Text**: A text string that displays more information.
* **Show Right Image**: A boolean that determines if a thumbnail image is shown on the right side of the notification.
* **Right Image**: An image that represents the thumbnail image.
* **Type**: The type of notification: temporary, persistent.

### Outputs

* **Notification Tapped**: A pulse that represents when the notification is tapped.

&nbsp;

## Share Sheet

An Android bottom sheet with share actions.
<br>
Use the Touch button on the component to capture which icon was tapped.

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Share%20Sheet.gif" width="360">

Icons from 
[Material Design](https://material.io/tools/icons/?style=baseline)

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Share%20Sheet.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Share%20Sheet%20%E2%80%93%20Example.origami) 

### Inputs

* **Present**: A pulse that displays the share sheet.
* **Bottom Margin**: A number representing the relative distance from the bottom of the screen. Useful for offsetting the position of the share sheet when a system navigation bar is present.

### Outputs

* **Tapped Icon Index**: An index that represents which icon is tapped, starting at 0.
* **Any Icon Tapped**: A pulse that represents when any icon is tapped.
* **Icon 1 Tapped**: A pulse that represents when the first icon is tapped.
* **Icon 2 Tapped**: A pulse that represents when the second icon is tapped.
* **Icon 3 Tapped**: A pulse that represents when the third icon is tapped.
* **Icon 4 Tapped**: A pulse that represents when the fourth icon is tapped.
* **Icon 5 Tapped**: A pulse that represents when the fifth icon is tapped.
* **Icon 6 Tapped**: A pulse that represents when the sixth icon is tapped.

&nbsp;

## Slider

An Android slider that can be either continuous or discrete.
<br>
Use the Touch button on the component to get information about the current progress or value.

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Slider.gif" width="280">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Slider.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Slider%20%E2%80%93%20Example.origami) 

### Inputs

* **Position**: The position to display the slider.
* **Width**: A number that represents the width of the slider.
* **Anchor**: The anchor point to position the slider relative to.
* **Type**: The type of slider, either continuous, which allows for selecting any value within a range, or discrete, which limits value selection to a specific set of numbers based on the amount of tick markers specified.
* **Show Tick Marks**: A boolean that determines if tick marks are visible.
* **Number of Tick Marks**: A number that represents how many tick marks are shown. Tick marks are equally spaced within the slider and determine the values that a discrete slider can be set to. Only available when the type of the slider is set to discrete. Minimum value is 2 (one segment, with one tick mark on each side of the slider) and maximum value is 11 (ten segments between tick marks).
* **Color**: The color of the slider handle. The color of the value indicator, background, and tick marks are automatically generated based on this value.
* **Min Value**: A number that represents the minimum value that the slider can be set to.
* **Max Value**: A number that represents the maximum value that the slider can be set to.
* **Show Value Indicator**: A boolean that determines if the indicator that displays the current value is shown when the slider handle is dragged.
* **Progress**: A number that represents a position of the slider handle, from 0 to 1. When this is changed or when <b>Set to Progress</b> is pulsed, the position of the slider will be updated to this value.
* **Set to Progress**: A pulse that sets the progress to the specified value.

### Outputs

* **Progress**: A number that represents the current position of the slider handle, from 0 to 1.
* **Value**: A number that represents the current value of the slider, from the minimum value to the maximum value.

&nbsp;

## System Navigation Bar

An Android system navigation bar. Visual style aligns with Samsung UI.
<br>
Use the Touch button on the component to capture taps on individual buttons.

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/System%20Navigation%20Bar.gif" width="700">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/System%20Navigation%20Bar.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/System%20Navigation%20Bar%20%E2%80%93%20Example.origami) 

### Inputs

* **Enable**: A boolean that is true when the navigation bar is displayed.
* **Theme**: Determines the color theme of the navigation bar.
* **Switch to Light**: A pulse that switches the color theme to dark.
* **Switch to Dark**: A pulse that switches the color theme to dark.

### Outputs

* **Any Button Tapped**: A pulse that represents when any button is tapped.
* **Back Button Tapped**: A pulse that represents when the back button is tapped.
* **Home Button Tapped**: A pulse that represents when the home button is tapped.
* **App Switcher Button Tapped**&nbsp;&nbsp;A pulse that represents when the app switcher button is tapped.
* **Height**&nbsp;&nbsp;A number representing the height of the navigation bar, in points.

&nbsp;

## Tabs

An Android tab bar with customizable items.
<br>
Use the Touch button on the component to get information about the selected tab.

<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Tabs.gif" width="360">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Tabs.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Tabs%20%E2%80%93%20Example.origami)

### Inputs

* **Type**: A list of options that determines if the tab includes text only, icons only, or icons and text.
* **Number of Tabs**: A number representing the number of items in the tab bar.
* **Switch to Tab**: The index of the tab to switch to, starting at 0.
* **Switch Tab**: A pulse that changes the currently selected tab.
* **Tab Background Color**: The background color of the tabs.
* **Shadow**: A boolean that determines if a shadow is visible below the tabs.
* **Position Y**: The vertical position of the tabs.
* **Selected Indicator Color**: The color of the selected indicator of the selected tab.
* **Label and Icon Color (Selected Tab)**: The color of the text label of the selected tab.
* **Label and Icon Color (Unselected Tab)**: The color of the text label of the unselected tab.

### Outputs

* **Selected Tab Index**: An index that represents the currently selected tab, starting at 0.
* **Selected Tab Label Text**: A text string that represents the label of the currently selected tab.
* **Any Tab Tapped**: A pulse that represents when any tab is tapped.
* **Tab 1 Tapped**: A pulse that represents when the first tab is tapped.
* **Tab 2 Tapped**: A pulse that represents when the second tab is tapped.
* **Tab 3 Tapped**: A pulse that represents when the third tab is tapped.
* **Tab 4 Tapped**: A pulse that represents when the fourth tab is tapped.
* **Tab 5 Tapped**: A pulse that represents when the fifth tab is tapped.
* **Tab 6 Tapped**: A pulse that represents when the sixth tab is tapped.

&nbsp;

## Top App Bar

An Android top app bar with customizable left and right actions. It offers regular and prominent sizes.
<br>
Use the Touch button on the component to capture taps on individual icons in the app bar.

<br>
<img src="https://github.com/leomancini31/origami-android-components/blob/master/Screenshots/Top%20App%20Bar.gif" width="360">

Download: [Layer Component](https://github.com/leomancini31/origami-android-components/raw/master/System/Material/Layers/Top%20App%20Bar.origami) · [Example Usage](https://github.com/leomancini31/origami-android-components/raw/master/Examples/Top%20App%20Bar%20%E2%80%93%20Example.origami)

### Inputs

* **Enable**: A boolean that is true when the app bar is displayed.
* **Type**: The size of the app bar: either regular or prominent.
* **Background Image**: The background image of the app bar. If an image is set, the image will cover the background color.
* **Background Color**: The background color of the app bar.
* **Title Text**: A text string that represents the title of the page.
* **Title Color**: The color of the title.
* **Title Alignment**: The text alignment of the title: either left, right, or center.
* **Left Icon Enable**: A boolean that determines if the left icon is shown.
* **Left Icon Image**: The image of the left icon.
* **Left Icon Color**: The color of the left icon.
* **Right Icon Enable**: A boolean that determines if the right icon is shown.
* **Right Icon Image**: The image of the right icon.
* **Right Icon Color**: The color of the right icon.
* **Pressed Indicator Enable**: A boolean that determines if a pressed indicator is shown on icons when tapped.
* **Pressed Indicator Use Auto Color**: A boolean that determines if the pressed indicator color is automatically generated based on the background and icon colors.
* **Pressed Indicator Manual Color**: The color of the pressed indicator if <b>Use Auto Color</b> is not set to true.

### Outputs

* **Left Icon Tapped**: A pulse that represents when the left icon is tapped.
* **Right Icon Tapped**: A pulse that represents when the right icon is tapped.
* **Height**: A number representing the height of the app bar, in points.

&nbsp;