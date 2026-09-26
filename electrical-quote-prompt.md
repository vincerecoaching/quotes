# Prompt 1 — Business Setup

Run this once to build your branded quote template. You'll use the output as your base template for every future quote.

---

## Instructions

1. Copy the prompt below and fill in your website URL
2. Open [claude.ai](https://claude.ai)
3. Paste the prompt, then paste the full HTML template code underneath it
4. Claude will rebuild the template using your real business data
5. Save the output as `my-quote-template.html` — this is your branded base for all future quotes

---

## The Prompt

```
I have an electrical quote template in HTML. I need you to set it up for my business by pulling real data from my website.

My website: [PASTE YOUR WEBSITE URL HERE]

Please visit my website and extract the following, then apply it to the HTML template:

BUSINESS DETAILS
- Business name (replace every instance of "Journey Electrical" throughout the file)
- Phone number (replace all instances)
- Suburb and state (replace all location references)
- Any tagline or slogan (update the hero headline)

BRANDING
- Primary brand colour — find the hex code from the website CSS or visuals. If you can't extract it exactly, choose the closest match. Update all CSS colour variables at the top of the file.
- Secondary colours if present
- Any logo URL found on the site — embed it or reference it in the topbar

PHOTOS
- Find 3 to 5 real images from the website (job site photos, team photos, work examples)
- Use these image URLs to replace the placeholder images in the gallery and hero sections of the template

REVIEWS
- Find 3 to 5 real customer reviews or testimonials from the website
- Replace the placeholder testimonials in the reviews section with these real ones, including the reviewer name if available

SCOPE OF WORKS
- Clear the existing line items and replace with placeholder rows:
  - [Work description] — $[price]
  - [Work description] — $[price]
  - [Work description] — $[price]
- Set the total to $0.00 as a placeholder
- Client name: [Client Name]
- Client address: [Client Address]
- Quote number: QU-0001

The output should be a complete, self-contained HTML file I can save and use as my base template. I will fill in the actual scope and client details separately for each job.

Here is the template:

[PASTE THE HTML TEMPLATE CODE HERE]
```

---

## Tips

- Claude Pro can browse websites directly. Free Claude works too — if it can't access your site, paste your phone number, suburb, brand colour and a few review quotes manually in the prompt
- If your photos aren't publicly accessible, describe what imagery you want and Claude will source relevant placeholder images instead
- Once you have your branded base template, use **Prompt 2** for each new job
