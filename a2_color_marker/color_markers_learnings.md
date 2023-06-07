# Color Markers learnings

# Defining colors

```css
/*We can define colors in CSS in different ways */

/*By keyword */
.red{
    color:red;
}
/*By Hexvalue the Hexadecimal System is used here*/
/*00 is the lowest and FF is the highest on scala*/
.red{
    color: #FF0000;
}
/*With the RGB function (0 lowest and 255 highest on scala)*/
.red{
    color: rgb(255, 0, 0)
}
/*RGBA function*/
/*Same as RGB but with the alpha channel Value*/
/*Defining the transperancy of the color*/
/*Values go from 0-1 or 0%-100%* smaller value = less color*/
.red{
    color: rgba(255, 0, 0, .1)
}

/*HSL Hue Saturation Lightness*/

/*Shown in a circle wherby Hue is the degree*/
for further information:
http://web.simmons.edu/~grovesd/comm244/notes/week3/css-colors

/*Step 53*/
/*linear-gradient function*/
/*90deg = gradient direction, 75% = the red color will fill up 75%*/
.red {
  background: linear-gradient(90deg, rgb(255, 0, 0) 75%, rgb(0, 255, 0), rgb(0, 0, 255));
}

```

