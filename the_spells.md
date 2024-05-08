# Common TailWind CSS 

## Display-flex

`flex`: auto layout (from Figma) 

`flex-col`: makes items go downwards

`justify-between`: Seperates the divs with maximum seperation possible. 

`items-center`: 
> This changes based on if its horizontal or vertical flex
 - `Vertical flex`: Centers all of the items horizontally
 - `Horizontal flex`: Centers all of the items vertically

`justify-center`:
> This changes based on if its horizontal or vertical flex
 - `Vertical flex`: Centers all of the items vertically
 - `Horizontal flex`: Centers all of the items horizontally

`gap-value`: **only flex** the gap between the children

## Sizing

`h-screen`: fills the entire height

`h-value`: increases the height of the element

`h-full`: height full screen (100%)

`w-screen`: fills the entire width

`w-value`: changes width of whatever

`w-full`: width full screen (100%)

`px`: horizontal padding

`py`: vertical padding

## Color  

`text-value`: changes color, **even with icons**. 

`text-[#custom]`: custom color

`bg`: background color. Fill rrdivs

## Text

`text-value`:
 - Changing color of text **500 is min**
 - Numbers:
   - sm: small
   - md: medium
   - lg: large
   - xl: extra large
   - nxl: n is a number between 2-9  

`rounded`: div radius
 - Numbers: Same as **text**

## Misc

Creating a line 
```javascript
<hr></hr>
```
## Icons 

  Download the free version and import the library


```javascript
import {FontAwesomeIcon} from "@fortawesome/react-fontawesome";
import {faMessage} from "@fortawesome/free-regular-svg-icons";
```

Example:

```javascript
import {FontAwesomeIcon} from "@fortawesome/react-fontawesome";
import { faCheck } from "@fortawesome/free-solid-svg-icons";
    <FontAwesomeIcon
            icon = {faCheck}
            classname="fas fa-check"
            style={{color:"red", fontsize:64}}
          />    
```

## Routing 

Create folder with the route name you want and in that folder add page.js (this is where the html goes). localhost:3000/folder_name

## Images

You need 4 required parameters: `src`, `width`, `height`, `alt`. Put the downloaded images into the public folder. 

Example: 

```js
<Image
          src="/goose1.png"
          width={62}
          height={62}
          alt="Company Logo"
        />
```

# Tips

**rfce shortcut for react**


> **WHEN IN DOUBT PUT BORDERS**

# Troubleshooting


