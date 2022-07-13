# NeumorphicUIKitDark
Dark Neumorphic UI Kit for Power Apps

Welcome to the new world of design in Power Apps! This toolkit has been curated using a fusion of out-of-the-box controls and code to extend the existing control set and take your Power Apps UI to the next level!

The toolkit has a number of components which have various properties that you can customise without going into the code itself. If you do however wish to make any adjustments etc., you have the ability to edit the code directly within the application from the Components pane. Please note that this kit is packaged as a canvas app in a .zip file, so you'll need to import it as a Canvas App.

The toolkit comprises of two screens each – these screens allow you to pick the themes of all your controls without having to change them individually. The first screen has lineal gradients, and the second screen allows you to pick and mix. The values of those are kept in the AppOnStart collections including the Default theme which is stored in a variable.

Please see below a breakdown of the toolkit - I hope you enjoy it and I'd love to hear your feedback! 😊

Lineal gradient colour picker

![image](https://user-images.githubusercontent.com/86930618/178851940-34a4e8db-7f2e-439c-bf36-e64626afd59b.png)

Pick’n’mix
 
![image](https://user-images.githubusercontent.com/86930618/178851945-1c564775-9775-4c63-a268-80b73a4694a0.png)


Button 

![image](https://user-images.githubusercontent.com/86930618/178851964-5b255ebf-3107-4e13-b134-cc329906bf93.png)
![image](https://user-images.githubusercontent.com/86930618/178851975-b0d768d9-02af-4227-9ec0-0e620527714a.png)
![image](https://user-images.githubusercontent.com/86930618/178851979-bedac40d-15b0-426e-8c5d-4a912d519f13.png)

 
 This control is fully scalable so you can extend them both ways. It has the following properties:
-	IconName – to make life easier and save you from having to find SVG code online, I have embedded 24most common icons into the button. So all you need to do in this property is type one of the following names of supported icons:
calendar
bag  
basket
clipboard
upload
download
email
home
user
print
phone
trash
cancel
edit
new
back
next
refresh
filter
settings
chart
notification
bookmark
alarm

-	IconColorActive – this is the colour of the icon if you turn off the lineal gradient property,
-	IconColour – this is the colour of the icon when you haven’t pressed it,
-	LinealGradient – this is a Boolean property. If you toggle this to true, your icons will have lineal gradient applied to them. If you toggle it to false, they will only have a single tone.
-	LinealGradientColor1 – this is the first lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	LinealGradientColor2 – this is the second lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	BorderRadius – allows you to specify the border radius of your button
-	OnSelect – this is where you will put the OnSelect code

Star Rating

![image](https://user-images.githubusercontent.com/86930618/178851988-e732f663-ca62-47cd-bd2f-611d4cc7ec50.png)
![image](https://user-images.githubusercontent.com/86930618/178851993-34d19dab-1d98-4cc7-942b-7be6b8479597.png)
![image](https://user-images.githubusercontent.com/86930618/178851999-818037f8-7b33-4664-9cd3-37aaff1c0bcd.png)

   
 
This control has 5 input properties:
-	Rating – the number of selected stars,
-	MaxRating – this is a static number and at present this control only supports 5 stars.
-	BoxShadow – choose between inset and convex box shadow,
-	LinealGradient1 – this is the first lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	LinealGradient2 – this is the second lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc)

This control has an output value just like the usual star rating. If you’d like to reference it or patch it to a data source, you do it the usual  way – StarRating.Value.

Date Picker 

![image](https://user-images.githubusercontent.com/86930618/178852006-89f97dcc-ada2-4384-a2b9-61e42f94740e.png)
![image](https://user-images.githubusercontent.com/86930618/178852012-2bc28e19-7a11-4bfb-b3db-2b908eadd62d.png)
![image](https://user-images.githubusercontent.com/86930618/178852014-61f4e3cf-daad-4c39-9c7f-25d0f75caf21.png)

 
This control has 2 input properties:
-	LinealGradient1 – this is the first lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	LinealGradient2 – this is the second lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc)
It also has an output property called DateSelected. If you’d like to patch the selected date to a data source, you’ll do it the usual way – DatePicker.DateSelected.

Toggle

![image](https://user-images.githubusercontent.com/86930618/178852022-509d69ee-1c5f-44ab-9a9f-7e93cbe783e9.png)
![image](https://user-images.githubusercontent.com/86930618/178852028-f8855972-0aad-439b-ba80-11dec75f7afe.png)
![image](https://user-images.githubusercontent.com/86930618/178852034-e64211fa-9e74-4868-bc8f-3c63f0113b6f.png)

     
The toggle has 7 properties:
-	LinealGradientColour1 – this is the first lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	LinealGradientColour2 – this is the second lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc)
-	Label – Boolean value defining whether you want the on/off label to be visible,
-	LabelTrueText – just like the usual toggle, this is the true text,
-	LabelFalseText – same as above, this is the false text,
-	FontSize – define the size of the text in your label,
-	IconVisible – define whether you want the ‘power’ icon to be visible on the toggle

The toggle has an output property called Value. If you’d like to patch the value of the toggle to a data source, you will use Toggle.Value.

Checkbox

![image](https://user-images.githubusercontent.com/86930618/178852041-da3476d8-b9c3-4ad5-b745-771a2648dc8d.png)
![image](https://user-images.githubusercontent.com/86930618/178852045-51979731-b52f-4731-9bc3-152e479d56b7.png)
![image](https://user-images.githubusercontent.com/86930618/178852048-c42d7bd3-fe65-45de-8220-861e7b654789.png)

     
Checkbox has the following 6 properties:

-	IconColorActive – this is the colour of the icon if you turn off the lineal gradient property,
-	IconColour – this is the colour of the icon when you haven’t pressed it,
-	LinealGradient – this is a Boolean property. If you toggle this to true, your icons will have lineal gradient applied to them. If you toggle it to false, they will only have a single tone.
-	LinealGradientColor1 – this is the first lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	LinealGradientColor2 – this is the second lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	OnSelect – this is where you will put the OnSelect code
It also has an output property called Checked. If you’d like to patch the value of the checkbox to a data source, you will use Checkbox.Value.

Pill progress bar – animated
   
![image](https://user-images.githubusercontent.com/86930618/178852054-dae95874-7214-4578-9fe7-5b7104c74b83.png)
![image](https://user-images.githubusercontent.com/86930618/178852062-bc6dbc20-2919-4157-a998-0e7dcd13f369.png)
![image](https://user-images.githubusercontent.com/86930618/178852068-e05743e4-633a-470a-b9a4-caad574d1151.png)


This progress bar has the following 5 properties:
-	Value – define the progress that you want to show. This should be an integer without % - the control will automatically calculate the %.
-	MaxValue – this is the total value that you want to calculate the percentage against,
-	LinealGradientColor1 – this is the first lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	LinealGradientColor2 – this is the second lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	LabelSize – text size of the percentage label

Slider 

![image](https://user-images.githubusercontent.com/86930618/178852079-75c30ecc-fce8-4f8f-8911-c72f01a730e2.png)
![image](https://user-images.githubusercontent.com/86930618/178852081-03e0a4ec-a8ea-42f1-904e-7644c2ca5590.png)
![image](https://user-images.githubusercontent.com/86930618/178852085-7d9ddd18-0367-453f-97e7-0c2ea13c5cdf.png)

 
This control has 4 properties:
-	Min – minimum value on the slider,
-	Max – max value on the slider, 
-	LinealGradientColor1 – this is the first lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	LinealGradientColor2 – this is the second lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).

This control has an output property called Value. If you’d like to patch it to a data source, you will use Slider.Value.

Text input

   ![image](https://user-images.githubusercontent.com/86930618/178852093-0b209467-50a2-4a6e-a710-03b0cf55858f.png)
![image](https://user-images.githubusercontent.com/86930618/178852100-630982a9-fec8-408b-a5c4-6c92a4453444.png)

This control has 6 properties:
-	Font size – define the size of the text,
-	HintText – the text that will be visible before any text is entered,
-	Mode – define whether you want the text to be single line, multiline or password. Please use the TextMode function (e.g. TextMode.Multiline).
-	LinealGradientColor1 – this is the first lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	LinealGradientColor2 – this is the second lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).


Card convex, inset, transparent and transparent background
     
![image](https://user-images.githubusercontent.com/86930618/178852112-46c42774-a3d0-487f-addd-54095152a7f3.png)
![image](https://user-images.githubusercontent.com/86930618/178852116-51e32a9a-25c3-412c-ab62-b4a65dea7952.png)
![image](https://user-images.githubusercontent.com/86930618/178852123-28e6dc52-d511-4331-8e99-701d4f238457.png)

These are decorative cards that allow you to group elements into a form etc. They only have one property – BorderRadius. They are fully scalable so you can expand them both ways.

Pill progress bar – responsive

![image](https://user-images.githubusercontent.com/86930618/178852128-ab9419a4-fe49-4bea-b274-92f93c9a3c36.png)
![image](https://user-images.githubusercontent.com/86930618/178852132-4b0e4c7b-ae11-40b1-96fc-33849e2ef9f1.png)

 
 
This control works the same as the animated pill bar, the difference is that although it is not animated, it is fully responsive and can be expanded both ways.
-	Value – define the progress that you want to show. This should be an integer without % - the control will automatically calculate the %.
-	MaxValue – this is the total value that you want to calculate the percentage against,
-	LinealGradientColor1 – this is the first lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).
-	LinealGradientColor2 – this is the second lineal gradient colour. This property accepts the following formats – HEX values, rgb values and color names (blue, green etc).

Mobile navigation menu

  ![image](https://user-images.githubusercontent.com/86930618/178852139-2ee9d08b-3275-42cc-bbd7-70b348534858.png)
 ![image](https://user-images.githubusercontent.com/86930618/178852142-556fcfaf-0959-4542-bbd8-dde0df257246.png)
![image](https://user-images.githubusercontent.com/86930618/178852146-0a3c6716-44da-4cf9-a0cd-5788a7cb7de2.png)

 
This component is based on another component I have previously built. Please follow the instructions here https://github.com/misskristine94/MobileNavigationMenuComponent. 






