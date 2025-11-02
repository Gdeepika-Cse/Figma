# NAME: DEEPIKA G
# REG.NO: 212224040060
# Ex09 Event Registration Web Application
## Date: 1-11-25
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
# HTML
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="home-page-1">
<img src="images/node-2.png" class="node-2" alt="idc2cismwr_1762004317717-1" />
<img src="images/opening-reg-1-3.png" class="opening-reg-1-3" alt="opening-reg-1" />
<p class="text-4"><span class="text-white">“BEAUTY OF COLORS”</span></p>
<img src="images/idumo6dtnc_logos-1-5.png" class="idumo6dtnc_logos-1-5" alt="idumo6dtnc_logos-1" />
<p class="text-6"><span class="text-rgb-0-228-245">ART DAY EVENTS</span></p>
<img src="images/union-7.svg" class="union-7" alt="union" />
<p class="text-8"><span class="text-black">LOGIN</span></p>
<div class="rectangle-2-9"></div>
<p class="text-10"><span class="text-black">REGISTER</span></p>
<p class="text-11"><span class="text-black">ON 20th november</span></p>
</div>
</body>
</html>
```
# CSS
```
/* Add font files for Aclonica */
@font-face {
  font-family: 'Aclonica';
  src: url('fonts/aclonica.woff2') format('woff2'),
       url('fonts/aclonica.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Irish Grover */
@font-face {
  font-family: 'Irish Grover';
  src: url('fonts/irish-grover.woff2') format('woff2'),
       url('fonts/irish-grover.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Inria Serif */
@font-face {
  font-family: 'Inria Serif';
  src: url('fonts/inria-serif.woff2') format('woff2'),
       url('fonts/inria-serif.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-inter: 'Inter', sans-serif;
  --font-family-aclonica: 'Aclonica', sans-serif;
  --font-family-irish-grover: 'Irish Grover', sans-serif;
  --font-family-inria-serif: 'Inria Serif', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
  --text-rgb-0-228-245: rgba(0, 228, 245, 1);
  --text-black: rgba(0, 0, 0, 1);
}

.text-white {
  color: var(--text-white);
}

.text-rgb-0-228-245 {
  color: var(--text-rgb-0-228-245);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.opening-reg-1-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-aclonica);
  font-weight: normal;
  font-size: 64px;
  text-decoration: none;
  text-transform: uppercase;
  color: var(--text-white);
}

.idumo6dtnc_logos-1-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-irish-grover);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: uppercase;
  color: var(--text-rgb-0-228-245);
}

.union-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 255, 225, 1);
  border: none;
  outline: none;
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 128px;
  text-decoration: none;
  text-transform: uppercase;
  color: var(--text-black);
}

.rectangle-2-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 255, 234, 1);
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 128px;
  text-decoration: none;
  text-transform: uppercase;
  color: var(--text-black);
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inria-serif);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: uppercase;
  color: var(--text-black);
}

.home-page-1 {
@media (max-width: 1440px) {
  .home-page-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .home-page-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```

# HTML
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="events-page-1">
<img src="images/2nd-page-1-2.png" class="2nd-page-1-2" alt="2nd-page-1" />
<p class="text-3"><span class="text-black">ART DAY EVENTS</span></p>
<p class="text-4"><span class="text-black">PENCIL ARTS

OIL PASTEL ARTS

ACRYLIC PAINTINGS

WATERCOLOR PAINTINGS

POTRAIT ARTS

DIGITAL ARTS

SPRAY PAINTINGS</span></p>
</div>
</body>
</html>
```
# CSS
```
/* Add font files for IM FELL Great Primer SC */
@font-face {
  font-family: 'IM FELL Great Primer SC';
  src: url('fonts/im-fell-great-primer-sc.woff2') format('woff2'),
       url('fonts/im-fell-great-primer-sc.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Irish Grover */
@font-face {
  font-family: 'Irish Grover';
  src: url('fonts/irish-grover.woff2') format('woff2'),
       url('fonts/irish-grover.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-inter: 'Inter', sans-serif;
  --font-family-im-fell-great-primer-sc: 'IM FELL Great Primer SC', sans-serif;
  --font-family-irish-grover: 'Irish Grover', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.2nd-page-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  backdrop-filter: blur(4px);
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-im-fell-great-primer-sc);
  font-weight: normal;
  font-size: 140px;
  text-decoration: none;
  text-transform: uppercase;
  color: var(--text-black);
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-irish-grover);
  font-weight: normal;
  font-size: 140px;
  text-decoration: none;
  text-transform: uppercase;
  color: var(--text-black);
}

.events-page-1 {
@media (max-width: 1440px) {
  .events-page-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .events-page-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```

# HTML
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="registration-form-1">
<img src="images/3rd-page-1-2.png" class="3rd-page-1-2" alt="3rd-page-1" />
<p class="text-3"><span class="text-rgb-0-17-255">EVENT REGISTRATION FORM</span></p>
<p class="text-4"><span class="text-white">Fill The Details</span></p>
<div class="rectangle-3-5"></div>
<div class="rectangle-4-6"></div>
<div class="rectangle-5-7"></div>
<div class="rectangle-6-8"></div>
<div class="rectangle-7-9"></div>
<div class="rectangle-8-10"></div>
<p class="text-11"><span class="text-black">Name</span></p>
<p class="text-12"><span class="text-black">Register Number</span></p>
<p class="text-13"><span class="text-black">Department</span></p>
<p class="text-14"><span class="text-black">Year</span></p>
<p class="text-15"><span class="text-black">Email ID</span></p>
<p class="text-16"><span class="text-black">Phone Number</span></p>
<div class="rectangle-9-17"></div>
<p class="text-18"><span class="text-black">Events To Register</span></p>
<div class="rectangle-10-19"></div>
<p class="text-20"><span class="text-white">REGISTER</span></p>
</div>
</body>
</html>
```
# CSS
```
/* Add font files for IM FELL Great Primer SC */
@font-face {
  font-family: 'IM FELL Great Primer SC';
  src: url('fonts/im-fell-great-primer-sc.woff2') format('woff2'),
       url('fonts/im-fell-great-primer-sc.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Gurajada */
@font-face {
  font-family: 'Gurajada';
  src: url('fonts/gurajada.woff2') format('woff2'),
       url('fonts/gurajada.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Holtwood One SC */
@font-face {
  font-family: 'Holtwood One SC';
  src: url('fonts/holtwood-one-sc.woff2') format('woff2'),
       url('fonts/holtwood-one-sc.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-inter: 'Inter', sans-serif;
  --font-family-im-fell-great-primer-sc: 'IM FELL Great Primer SC', sans-serif;
  --font-family-gurajada: 'Gurajada', sans-serif;
  --font-family-holtwood-one-sc: 'Holtwood One SC', sans-serif;
  --text-rgb-0-17-255: rgba(0, 17, 255, 1);
  --text-white: rgba(255, 255, 255, 1);
  --text-black: rgba(0, 0, 0, 1);
}

.text-rgb-0-17-255 {
  color: var(--text-rgb-0-17-255);
}

.text-white {
  color: var(--text-white);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.3rd-page-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-im-fell-great-primer-sc);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: uppercase;
  color: var(--text-rgb-0-17-255);
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-gurajada);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: uppercase;
  color: var(--text-white);
}

.rectangle-3-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 247, 247, 1);
}

.rectangle-4-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.rectangle-5-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 250, 250, 1);
}

.rectangle-6-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 247, 247, 1);
}

.rectangle-7-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 249, 249, 1);
}

.rectangle-8-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 120px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 120px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-9-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 252, 252, 1);
}

.text-18 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 120px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-10-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(17, 15, 15, 1);
}

.text-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-holtwood-one-sc);
  font-weight: normal;
  font-size: 120px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.registration-form-1 {
@media (max-width: 1440px) {
  .registration-form-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .registration-form-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```

# HTML
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="contact-page-1">
<img src="images/4th-page-1-2.png" class="4th-page-1-2" alt="4th-page-1" />
<img src="images/node-3.png" class="node-3" alt="idc2cismwr_1762004317717-2" />
<p class="text-4"><span class="text-black">THANK YOU !</span></p>
<p class="text-5"><span class="text-rgb-46-255-4">CONTACT US :</span></p>
<p class="text-6"><span class="text-black">       Email Address
Saveethaartclub@gmail.com</span></p>
<p class="text-7"><span class="text-black">Phone No
9876543210</span></p>
<p class="text-8"><span class="text-black">Lets make a colorful and creative campus
egaerly waiting for your participation in 
the art evnets</span></p>
</div>
</body>
</html>
```
# CSS
```
/* Add font files for Inknut Antiqua */
@font-face {
  font-family: 'Inknut Antiqua';
  src: url('fonts/inknut-antiqua.woff2') format('woff2'),
       url('fonts/inknut-antiqua.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Indie Flower */
@font-face {
  font-family: 'Indie Flower';
  src: url('fonts/indie-flower.woff2') format('woff2'),
       url('fonts/indie-flower.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-inter: 'Inter', sans-serif;
  --font-family-inknut-antiqua: 'Inknut Antiqua', sans-serif;
  --font-family-indie-flower: 'Indie Flower', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
  --text-rgb-46-255-4: rgba(46, 255, 4, 1);
}

.text-black {
  color: var(--text-black);
}

.text-rgb-46-255-4 {
  color: var(--text-rgb-46-255-4);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.4th-page-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inknut-antiqua);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inknut-antiqua);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-46-255-4);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inknut-antiqua);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
  font-family: var(--font-family-inknut-antiqua);
  font-weight: normal;
  font-size: 96px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inknut-antiqua);
  font-weight: normal;
  font-size: 128px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
  font-family: var(--font-family-inknut-antiqua);
  font-weight: normal;
  font-size: 96px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-indie-flower);
  font-weight: normal;
  font-size: 96px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.contact-page-1 {
@media (max-width: 1440px) {
  .contact-page-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .contact-page-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}
```
## OUTPUT:

<img width="1309" height="641" alt="Screenshot 2025-11-01 222105" src="https://github.com/user-attachments/assets/3a0e157d-4050-4ab3-8453-f36c35ed2a94" />

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
