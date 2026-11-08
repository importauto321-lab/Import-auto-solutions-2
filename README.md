# Import Auto Solutions 2 LLC website

One-page website for Import Auto Solutions 2 LLC, an auto transport and freight carrier in Greensboro, NC.
Plain HTML and CSS, no build step, published with GitHub Pages from the repository root.

- `index.html`: the page
- `styles.css`: all styling
- `thanks.html`: where the quote form sends people after they submit
- `images/truck.jpg`, `images/truck-800.jpg`: the truck photo beside the headline (resized, location data stripped)

## Quote form

The form posts to [FormSubmit](https://formsubmit.co), which emails each request to the address in the form's
`action`. The first time someone submits, FormSubmit sends a one-time activation email to that address; click the
link in it, and requests are delivered from then on. To change the address, edit the `action` URL in `index.html`.

## Custom domain

The site is served at https://importautoprivatefleet.com. The `CNAME` file holds the domain; DNS is at Namecheap
(four A records for `@` pointing to GitHub Pages, and a `www` CNAME to `importauto321-lab.github.io`). The form's
`_next` URL and the share image in `index.html` use this domain, so change them too if the domain ever changes.
