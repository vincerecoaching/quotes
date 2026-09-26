# Prompt 2 — Project Quote

Run this for every new job. Takes your branded base template and fills in the specific client and scope details.

---

## Instructions

1. Open your branded base template (`my-quote-template.html`) — the one you created with Prompt 1
2. Copy all the HTML from that file
3. Fill in your job details in the prompt below
4. Open [claude.ai](https://claude.ai), paste the prompt, then paste your branded HTML underneath
5. Save the output as `quote-[client name]-[date].html`

---

## The Prompt

```
I have my branded electrical quote template in HTML. I need you to fill in the details for a specific job.

CLIENT DETAILS
- Client name: [full name]
- Client address: [full street address]
- Quote number: [e.g. QU-0047]
- Quote date: [e.g. 26 September 2026]

SCOPE OF WORKS
Replace the existing line items with the following:

1. [Description of work] — $[price] inc GST
2. [Description of work] — $[price] inc GST
3. [Description of work] — $[price] inc GST
4. [Description of work] — $[price] inc GST

Total: $[total] inc GST

NOTES (optional)
- [Any job-specific note, special condition, or callout you want included]
- [e.g. "Quote valid for 30 days" or "Site inspection required before works commence"]

Instructions:
1. Replace the client name and address wherever they appear
2. Update the quote number and date
3. Replace all scope line items with the ones above, keeping the same visual layout
4. Update the total
5. Add any notes to the terms/footer section
6. Do not change any branding, colours, photos, reviews, or business details — only update the client and job-specific data

Output the complete HTML file. I will save it and share it with my client.

Here is my branded template:

[PASTE YOUR BRANDED TEMPLATE HTML HERE]
```

---

## Tips

- Keep a copy of each completed quote as its own HTML file — easy reference later
- You can ask Claude to tweak wording after the first output: "make line item 2 more specific" or "add a validity period to the footer"
- To send to a client, you can save the HTML and attach it, share via a link, or take a screenshot of it in your browser
