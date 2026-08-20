# Vila Anežka

Website for Vila Anežka — a four-bedroom retreat in the hop country
around Žatec, Czech Republic. Three pages, booking flow, English and Czech.

## Pages

| File | What it is |
|---|---|
| `index.html` | Main page: hero, the region, four rooms, dining, experiences |
| `booking.html` | Room selection and booking request |
| `soon.html` | Placeholder for sections still being written |

Both languages (English / Czech) live in one file — English in the markup,
Czech in the `CS` dictionary near the bottom of each page's script.

## Things that still need connecting

- **Hero video** — `index.html` has a commented-out `<source src="hero.mp4">`
  in the hero section. Drop the file next to `index.html` and uncomment.
  The photo currently serves as the poster frame.
- **Booking email** — the request form does not send yet. Set `ACCESS_KEY`
  in `booking.html` (see the comment in the script) to start receiving requests.
- **Guest rating** — `RATING` in `index.html` holds a placeholder score.
  Replace it with real figures before going public.

## Local preview

Any static server works, for example:

```
python3 -m http.server 8080
```
