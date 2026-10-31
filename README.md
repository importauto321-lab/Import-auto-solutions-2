# Import Auto Solutions 2 LLC website

One-page website for Import Auto Solutions 2 LLC, an auto transport and freight carrier in Greensboro, NC.
Plain HTML and CSS, no build step, published with GitHub Pages from the repository root.

- `index.html`: the page
- `styles.css`: all styling
- `thanks.html`: where the quote form sends people after they submit
- `images/truck.jpg`: hero photo (the page shows a navy background until it's added)

## Quote form

The form posts to [FormSubmit](https://formsubmit.co), which emails each request to the address in the form's
`action`. The first time someone submits, FormSubmit sends a one-time activation email to that address; click the
link in it, and requests are delivered from then on. To change the address, edit the `action` URL in `index.html`.

## Custom domain

When you're ready: Settings → Pages → Custom domain, then add the DNS records GitHub shows. Update the `_next`
URL in the form to the new domain so people land on the thanks page there.
