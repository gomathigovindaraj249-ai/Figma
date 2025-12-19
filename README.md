# Ex09 Event Registration Web Application
## Date:19-12-2025

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
```
HOME PAGE
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="rectangle"></div>
      <div class="text-wrapper">REGISTER</div>
      <img class="screenshot" src="img/screenshot-2025-12-18-215144-1.png" />
      <img class="img" src="img/rectangle-2.svg" />
      <div class="LOGIN">&nbsp;&nbsp;&nbsp;&nbsp;LOGIN</div>
      <div class="div">SPORTS DAY EVENTS</div>
      <img class="screenshot-2" src="img/screenshot-2025-12-19-092854-1.png" />
    </div>
  </body>
</html>

.iphone-pro-max {
  border: 15px solid;
  border-color: #000000;
  background-image: url(./img/iphone-16-pro-max-1.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 592px;
  min-height: 1105px;
  position: relative;
}

.iphone-pro-max .rectangle {
  top: 609px;
  height: 93px;
  background-color: #f19edc;
  position: absolute;
  left: 102px;
  width: 389px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 608px;
  left: 124px;
  width: 342px;
  text-shadow: 0px 4px 4px #00000040;
  -webkit-text-stroke: 1px #f1f5fd;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .screenshot {
  position: absolute;
  top: 29px;
  left: 17px;
  width: 553px;
  height: 87px;
  aspect-ratio: 6.33;
  object-fit: cover;
}

.iphone-pro-max .img {
  top: 492px;
  height: 90px;
  position: absolute;
  left: 102px;
  width: 389px;
}

.iphone-pro-max .LOGIN {
  position: absolute;
  top: 498px;
  left: 127px;
  width: 352px;
  text-shadow: 0px 4px 4px #00000040;
  -webkit-text-stroke: 1px #f1f5fd;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .div {
  position: absolute;
  top: 371px;
  left: 47px;
  width: 428px;
  text-shadow: 0px 4px 4px #00000040;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .screenshot-2 {
  position: absolute;
  top: 129px;
  left: 151px;
  width: 223px;
  height: 216px;
  aspect-ratio: 1.03;
  object-fit: cover;
}

EVENT PAGE
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <p class="EVENTS"><span class="text-wrapper">&nbsp;&nbsp;&nbsp;&nbsp;</span> <span class="span">EVENTS</span></p>
      <div class="element-CRICKET">
        1.CRICKET<br /><br />2.VOLLEYBALL<br /><br />3.BASKETBALL<br /><br />4.THROWBALL<br /><br />5.BADMINTON<br /><br />6.4*100
        RELAY<br /><br />7.HOCKEY<br /><br />8.KABBADI
      </div>
    </div>
  </body>
</html>

.iphone-pro-max {
  border: 15px solid;
  border-color: #000000;
  background-image: url(./img/iphone-16-pro-max-4.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 650px;
  min-height: 1105px;
  display: flex;
  flex-direction: column;
  gap: 47px;
}

.iphone-pro-max .EVENTS {
  margin-left: 81px;
  width: 401px;
  height: 76px;
  margin-top: 81px;
  text-shadow: 0px 4px 4px #00000040;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper {
  font-weight: 800;
}

.iphone-pro-max .span {
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
}

.iphone-pro-max .element-CRICKET {
  margin-left: 51px;
  width: 386px;
  height: 684px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

REGISTRATION PAGE
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <div class="rectangle"></div>
      <div class="div">FULL NAME :</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle-2"></div>
      <div class="rounded-rectangle"></div>
      <div class="rectangle-3"></div>
      <div class="rounded-rectangle-2"></div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-2">REGISTER NUMBER:</div>
      <div class="text-wrapper-3">GENDER:</div>
      <div class="text-wrapper-4">AGE :</div>
      <div class="text-wrapper-5">EMAIL ID :</div>
      <div class="text-wrapper-6">PHONE NO:</div>
      <div class="rounded-rectangle-3"></div>
      <div class="text-wrapper-7">REGISTER</div>
    </div>
  </body>
</html>


.frame {
  overflow: hidden;
  border: 15px solid;
  border-color: #000000;
  background-image: url(./img/frame-2.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 656px;
  min-height: 1107px;
  position: relative;
}

.frame .text-wrapper {
  position: absolute;
  top: 83px;
  left: 35px;
  width: 455px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle {
  top: 192px;
  left: 25px;
  width: 391px;
  height: 55px;
  border-color: #2d1590;
  position: absolute;
  background-color: #ffffff;
  border-radius: 10px;
  border: 1px solid;
}

.frame .div {
  position: absolute;
  top: 202px;
  left: 43px;
  width: 368px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}
.frame .text-on-a-path {
  position: absolute;
  top: 302px;
  left: -19px;
  width: 389px;
  height: 57px;
}
.frame .rectangle-2 {
  top: 358px;
  left: 26px;
  width: 389px;
  height: 46px;
  border-color: #8a226f;
  position: absolute;
  background-color: #ffffff;
  border-radius: 10px;
  border: 1px solid;
}
.frame .rounded-rectangle {
  position: absolute;
  top: 430px;
  left: 23px;
  width: 388px;
  height: 51px;
  background-color: #ffffff;
  border-radius: 10px;
  border: 1px solid;
  border-color: #8a226f;
  transform: rotate(-0.06deg);
}
.frame .rectangle-3 {
  top: 504px;
  left: 18px;
  width: 405px;
  height: 55px;
  border-color: #57184a;
  position: absolute;
  background-color: #ffffff;
  border-radius: 10px;
  border: 1px solid;
}
.frame .rounded-rectangle-2 {
  position: absolute;
  top: 580px;
  left: 13px;
  width: 405px;
  height: 53px;
  background-color: #ffffff;
  border-radius: 10px;
  border: 1px solid;
  border-color: #8a226f;
  transform: rotate(-0.13deg);
}

.frame .rectangle-4 {
  top: 274px;
  left: 26px;
  width: 389px;
  height: 56px;
  border-color: #3f1536;
  position: absolute;
  background-color: #ffffff;
  border-radius: 10px;
  border: 1px solid;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 290px;
  left: 43px;
  width: 345px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 362px;
  left: 43px;
  width: 328px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}
.frame .text-wrapper-4 {
  position: absolute;
  top: 432px;
  left: 35px;
  width: 366px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}
.frame .text-wrapper-5 {
  position: absolute;
  top: 504px;
  left: 23px;
  width: 348px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}
.frame .text-wrapper-6 {
  position: absolute;
  top: 584px;
  left: 26px;
  width: 324px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rounded-rectangle-3 {
  position: absolute;
  top: 753px;
  left: 203px;
  width: 402px;
  height: 101px;
  background-color: #8a226f;
  border-radius: 14px;
}

.frame .text-wrapper-7 {
  position: absolute;
  top: 777px;
  left: 287px;
  width: 270px;
  text-shadow: 0px 4px 4px #00000040;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

THANK YOU PAGE 
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="text-wrapper">THANK YOU</div>
      <p class="div">We are excited for conducting this event and we are waiting to meet you all.</p>
    </div>
  </body>
</html>

.iphone-pro-max {
  border: 15px solid;
  border-color: #0e0e0e;
  background-image: url(./img/iphone-16-pro-max-3.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 623px;
  min-height: 1105px;
  display: flex;
  flex-direction: column;
  gap: 44.9px;
}

.iphone-pro-max .text-wrapper {
  margin-left: 56px;
  width: 432px;
  height: 105px;
  margin-top: 246px;
  text-shadow: 0px 4px 4px #00000040;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  margin-left: 26.2px;
  width: 477.54px;
  height: 168.06px;
  transform: rotate(0.42deg);
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

```
## OUTPUT:
![alt text](<event registration.png.png>)
![alt text](<Screenshot 2025-12-19 104155.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
