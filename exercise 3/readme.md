# Event delegation

## Instructions
Show an alert per button clicked, but only use one event.

### Acceptance criteria
- The only event handler should be on the element div#buttons.
- All buttons should respond to the click event. This means that you cannot have something like:

```javascript
const btn1 = document.getElementById('btn1').onclick = somefunction();
const btn2 = document.getElementById('btn2').onclick = somefunction();
const btn2 = document.getElementById('btn2').onclick = somefunction();
```

- The message in the alert should say: "You clicked button {button number}" meaning that if you click button 1 it should say "you clicked button 1"
