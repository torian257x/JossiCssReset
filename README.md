# JossiCssReset

As eric meyer's 2.0 css reset and normalize css reset lack resetting of the iphone and ipad views of input buttons, I added it to my own css reset.

It is eric meyer's 2.0 css reset with the added 
```css
input, textarea {
    border-radius: 0;
    -webkit-border-radius:0px;
}
input {
    -webkit-appearance: none;
}
```