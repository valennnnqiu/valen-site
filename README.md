# VALEN

Website for VALEN, a Toronto DJ playing open format and fun, happy drum & bass.

Static site: `index.html` plus the `img/` folder. No build step.

## Booking form
The form sends through [Web3Forms](https://web3forms.com). Put your access key in `index.html`:

```js
var FORM_KEY='YOUR_WEB3FORMS_ACCESS_KEY';
```

## Adding a gig
Add a row to the right list in `index.html`. Give upcoming gigs a date and they turn orange/white and move to the top until the date passes:

```html
<li data-date="2026-11-20"><span class="n">IDK Social Club DJ Night</span><span class="h">Event</span></li>
```
