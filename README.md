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
html {-webkit-text-size-adjust: 100%; -moz-text-size-adjust: 100%; -ms-text-size-adjust: 100%;}
```

webkit-text-size-adjust is basically that the browser does not change the font-size when rotating the device, but letting our css be in control.


just copy paste the JossiCssReset.css file to your project