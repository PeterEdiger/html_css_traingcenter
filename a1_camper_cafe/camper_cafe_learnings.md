# Learnings from the project camper cafe

---

# Naming and Structure

```html

```



---

# Using a background image for the whole body: 

```css
body{
    background-image: url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg);
}    

```

---

# Display: block

```css
img{
    display: block; /*An element that has the display property set to block starts on a new line and takes up the available screen width */
    margin-left:auto;
    margin-right: auto;
/*The auto keyword will give the left side a share of the remaining space. When combined with margin-right: auto , it will center the element, if a fixed width is defined*/    
    margin-top: -25px;
 /*By setting a negative margin the element will be pushed up*/
}
```

---

# HR -- Horizontal rule

```css
hr {
    height: 2px;
    background-color: brown;
    border-color: brown;
}
/*A border color needs to be defined if we want to have the hr all in one color.*/

```

---

# Defining a Tag after a class.

```css
.item p {
    /*By defining a class like that
    Every tag  <p> in this class will have the defined attributes
    */
	
}
```

