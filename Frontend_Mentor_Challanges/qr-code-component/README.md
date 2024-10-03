# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### Screenshot
![mobile-view](image.png)
![desktop-view](image-1.png)

### Links

- Solution URL: [Add solution URL here](http://127.0.0.1:5500/index.html)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### What I learned

Major Learning:
I learned that using width: 100% with object-fit: cover helps make images responsive while keeping them looking good.

Reason:
width: 100%: This makes the image stretch to fit the full width of its container, so it adjusts to different screen sizes.

object-fit: cover: This keeps the image's shape and avoids stretching or squishing. If the container's size changes, the image will crop a bit but still look right.

```html
<img src="\images\image-qr-code.png" id="image-qr-code">
```
```css
#image-qr-code{ 
  border-radius: 10px; 
  width: 100%; 
  object-fit: cover;}
```
### Continued development
Looking forward to next challenges to upskill my development skill