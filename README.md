# Ex09 Event Registration Web Application
## Date:11-10-2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
````
import React from "react";
import screenshot202510072258581 from "./screenshot-2025-10-07-225858-1.png";
import star1 from "./star-1.svg";
import star2 from "./star-2.svg";
import star3 from "./star-3.svg";
import star4 from "./star-4.svg";
import star5 from "./star-5.svg";
import star6 from "./star-6.svg";
import star7 from "./star-7.svg";
import star8 from "./star-8.svg";
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="cbg" src="img/cbg-1.png" />
      <img class="logo" src="img/logo.png" />
      <div class="CM-TROPHY">&nbsp;&nbsp;&nbsp;&nbsp;CM&nbsp;&nbsp;TROPHY</div>
      <img class="screenshot" src="img/screenshot-2025-10-08-231458-1.png" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="LOGIN">&nbsp;&nbsp;LOGIN</div>
      <div class="div"></div>
      <div class="text-wrapper">USERNAME:_________</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">PASSWORD:_________</div>
    </div>
  </body>
</html>
export const AndroidMedium = () => {
  return (
    <div className="bg-white w-full min-w-[700px] min-h-[840px] relative">
      <img
        className="absolute top-0 left-0 w-[700px] h-[840px] aspect-[1.74] object-cover"
        alt="Screenshot"
        src={screenshot202510072258581}
      />

      <img
        className="top-[298px] absolute left-[113px] w-[55px] h-[53px]"
        alt="Star"
        src={star2}
      />

      <img
        className="top-[205px] absolute left-[113px] w-[55px] h-[53px]"
        alt="Star"
        src={star3}
      />

      <div className="absolute top-[77px] left-[75px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-[#ffcc00] text-[64px] tracking-[0] leading-[normal]">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; EVENTS
      </div>

      <img
        className="absolute top-[408px] left-[113px] w-[55px] h-[53px]"
        alt="Star"
        src={star1}
      />

      <img
        className="absolute top-[408px] left-[113px] w-[55px] h-[53px]"
        alt="Star"
        src={star4}
      />

      <img
        className="top-[518px] absolute left-[113px] w-[55px] h-[53px]"
        alt="Star"
        src={star5}
      />

      <img
        className="top-[518px] absolute left-[113px] w-[55px] h-[53px]"
        alt="Star"
        src={star6}
      />

      <img
        className="top-[628px] absolute left-[113px] w-[55px] h-[53px]"
        alt="Star"
        src={star7}
      />

      <img
        className="top-[738px] absolute left-[113px] w-[55px] h-[53px]"
        alt="Star"
        src={star8}
      />

      <div className="absolute top-[213px] left-[202px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-[#34c759] text-4xl tracking-[0] leading-[normal]">
        LONG JUMP
      </div>

      <div className="absolute top-[306px] left-[202px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-white text-4xl tracking-[0] leading-[normal]">
        200M RUNNING
      </div>

      <div className="absolute top-[416px] left-[205px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-[#cb30e0] text-4xl tracking-[0] leading-[normal]">
        CHESS
      </div>

      <div className="absolute top-[533px] left-[205px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-[#00c3d0] text-4xl tracking-[0] leading-[normal]">
        CARROM
      </div>

      <div className="absolute top-[636px] left-[202px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-[#6155f5] text-4xl tracking-[0] leading-[normal]">
        HUDDLES JUMPING
      </div>

      <div className="absolute top-[753px] left-[205px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-m-3refsecondarysecondary-70 text-4xl tracking-[0] leading-[normal]">
        SWIMMING
      </div>
    </div>
  );
};
import React from "react";
import screenshot202510072036031 from "./screenshot-2025-10-07-203603-1.png";

export const Image = () => {
  return (
    <div className="w-[721px] h-[884px]">
      <img
        className="fixed top-0 left-0 w-[700px] h-[837px] aspect-[0.82] object-cover"
        alt="Screenshot"
        src={screenshot202510072036031}
      />
    </div>
  );
};

````

## OUTPUT:
![alt text](<Screenshot 2025-10-11 093418.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
