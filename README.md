# Event Pixels website

The live site for **Event Pixels Ltd**: sound, screens and stage for events across Birmingham. *Seen and heard.*

The whole site is one file, `index.html`. Every change saved here goes live on eventpixels.co.uk within about a minute (via Netlify).

## Making a change

**Easiest:** ask Claude in the Event Pixels project, for example "change the Ramadan weekends" or "add a testimonial". Claude updates this repository and the site refreshes.

**Small text fixes yourself:**
1. Open `index.html` here on GitHub and click the pencil icon (Edit).
2. Press Ctrl+F (Cmd+F on a Mac) and search for the words you want to change.
3. Change only the words between the tags, not the `<` `>` parts around them.
4. Click **Commit changes**, add a short note (e.g. "Fix FAQ typo"), and confirm.

If something breaks, open **History** on `index.html`, find the last good version and ask Claude to put it back.

## Settings near the bottom of index.html

Search for `Settings: edit these` to find them:

| Setting | What it does |
|---|---|
| `FORM_ENDPOINT` | Where the enquiry form sends: info@eventpixels.co.uk via FormSubmit |
| `WHATSAPP_URL` | The WhatsApp link, with the pre-filled quote message |
| `WHATSAPP_DISPLAY` | The number as shown on the page |

## The enquiry form

Enquiries go to **info@eventpixels.co.uk** through FormSubmit (free, no account). The first enquiry from a new address triggers an activation email to that inbox; click the link once and every enquiry after that arrives as a table.

## Brand rules that apply to every edit

- **No prices** anywhere on the site, including image descriptions.
- The pillars are **Sound, Screens and Stage**. Never "lighting" as a pillar.
- **Aqeel and Nasim** in full, Aqeel first.
- Violet is for emphasis only, never a button or background. Amber only in small amounts on purple.
- No exclamation marks.

The full brand pack (colours, type, icons, the website compositions in section 10) lives in the Event Pixels design system on Claude.

## Still to fill in

- Company number in the footer (search for `Company number`).
- Hero photo: replace with a wide shot of a real event when one is available.
