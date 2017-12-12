# Class 21

# How to prevent arrow keys from scrolling page

add this code to your sketch

```
window.addEventListener('keydown', (event) => {
    if(event.key === 'ArrowLeft' ||
       event.key === 'ArrowRight' ||
       event.key === 'ArrowDown' ||
       event.key === 'ArrowUp') {
    event.preventDefault();
    }
```
