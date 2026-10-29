# wish.rayanupadhyay.com

Birthday pages for friends. Fill in a name, copy the link, and send it. Your friend gets their own page with confetti, floating balloons, and a cake they can tap to blow out the candles.

**Live:** [wish.rayanupadhyay.com](https://wish.rayanupadhyay.com)

## Link options

Everything lives in the link, so there's no database.

| Option | Example | What it does |
| --- | --- | --- |
| `name` | `?name=Alex` | Required. Their name, up to 40 characters |
| `age` | `&age=16` | Shows the age on the cake |
| `from` | `&from=Rayan` | Signs it "love, Rayan" |
| `msg` | `&msg=...` | Custom message, up to 280 characters |
| `theme` | `&theme=ocean` | `party` (default), `ocean`, `sunset`, or `night` |

Example: `wish.rayanupadhyay.com/?name=Alex&age=16&from=Rayan&theme=ocean`

Opening the page with no name shows the builder, with copy and WhatsApp share buttons.

## Tech

One `index.html` file. Plain HTML, CSS, and JavaScript. Confetti is drawn on a canvas. Hosted on Vercel.
