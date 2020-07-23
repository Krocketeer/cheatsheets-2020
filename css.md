# css

### selectors

**elements**
```css
img {
    /* all these styles apply to every <img> */
}
```
**classes**
`.class-name{}`
**id**
`#my-element{}`

**rules**
```css
.my-wrapper .my-class{
    /* will apply only to "my-class" elements that are WITHIN "my-wrapper" */
}
.class-one, .class-two{
    /* applies to both classes */
}
.class-one > .child {
    /* only direct children */
}
.class-one.class-two {
    /* must have BOTH of these classes */
}
```

### pseudoselectors
```css
.my-class:hover{}
.my-class:focus{}

.my-class:first-child{
    /* only the first child WITHIN my-class */
}
.my-class:nth-child(3){
    /* only the 3 child in my-class */
}
```

### units
- `px`
- `%`: percentage of the elements parent
- `vw`/`vh`: percentage viewheight or viewwidth
- `rem`: ratio of the root font-size

### some basic css rules
```css
.class{
    color: blue; /* for text color */
    background: red; /* background color */
    width: 10px;
    height: 10%;
    margin: 20px; /* outside the element */
    padding: 20px; /* inside */
    font-size: 10px;
    font-family: 'Avenir', Helvetica;
}
```

### position
- `relative`: They will be arranged based on their siblings.
- `absolute`: removes the element from the "flow" of sibling elements. Instead, it becomes positioned based on its closest parents that has "relative" positioning. You can use `top`,`bottom`,`left`, and `right` to move it around precisely. 
- Note: either "relative" or "absolute" positioning gives you the ability to use `z-index`

### display

- `block` (default)
- `inline-block` (stack horizontally)
- `none` (hide)
- `flex` !!!!!!!!!!!!!!!!!

### flexbox
```css
.parent{
    display:flex;
    flex-direction:column; /* or row */
    align-items:center; /* or flex-start, flex-end, space-between, space-around, space-evenly */
    justify-content:center;
}
.child{
    flex:1; /* the ratio of how much space to take up */
}
```
- `align-items` aligns opposite the direction axis
- `justify-content`: aligns items on the direction axis