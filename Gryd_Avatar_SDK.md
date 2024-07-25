# WebView In React Js
Can be used to add dave custom webiew iframe. Which will accept text query , glb file to render avatar and create annimation and speech for the text query.


## Dependencies
**npm install react@18.3.1 react-dom@18.3.1**<br>
**npm install gryd_avatar_sdk**<br>
**npm install**<br>

## Usuage
**import WebView from 'gryd_avatar_sdk'**


```<WebView daveStyle={dStyle} avatarHeight='300px !important' avatarWidth = 'auto' textQuery='Hello I am from test iframe' loadGlb = "load_glb.url"/>```


## Properties


|  Name              |Type                          |  Description              |Example                         |
|----------------|----------------|-------------------------------|-----------------------------|
|daveStyle|`Object`            |`CSS styles can be passed in this prop as an object`            |'{"display":  "flex","flex-direction":  "column","align-items":  "center","justify-content":  "center","position":  "absolute","top":  "unset","bottom":  "0","left":  "unset","right":  "0"}'            |
|avatarWidth|`String`            | `Width of avatar container can be passed in this prop as an string which can be of different units like px , % , etc.`         |`"auto" or 100px"`
|avatarHeight|`String`            | `Height of avatar container can be passed in this prop as an string which can be of different units like px , % , etc.`         |`"300px"`       
|loadGlb|`String`            | `GLB url can be passed here to load the avatar`         |`"load_this_glb.url"` 
|interacted|`Boolean`            | `Can be set true on interaction like click or scroll`         |`"true"`
|customFunctionCall|`Function`            | `Custom Function can be passed here as props which can be executed`         |`"() => {console.log('Sample Function Executed)}" else function name without parenthesis. Exa : sampleFunction where sampleFunction is a function name defined with a body` 
|textQuery|`String`            | `Text to speech query sholud be passed here`         |`"Hello I am Dave. How are you Doing?"` |




