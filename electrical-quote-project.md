# Prompt 2 — Per Job Quote

Run this for every new job. Upload your existing quote PDF and your branded base template — Claude reads the PDF, extracts all the job data, and rebuilds the HTML automatically.

---

## Instructions

1. Open [claude.ai](https://claude.ai)
2. Upload two files:
   - Your existing quote PDF (from ServiceM8, Simpro, Xero, or wherever you quote from)
   - Your branded base template HTML (the one you created with Prompt 1)
3. Paste the prompt below and hit send
4. Save the output as `quote-[client]-[date].html`

---

## The Prompt

```
I have uploaded two files:
1. A PDF quote from my quoting software
2. My branded electrical quote template in HTML

Please read the PDF and extract the following job-specific data:
- Client name
- Client address
- Quote number
- Quote date
- All line items (description of work and price for each)
- Total amount (inc GST)
- Any special notes, conditions, or exclusions listed

Then rebuild the HTML template using that extracted data:
1. Replace the client name and address wherever they appear
2. Update the quote number and date
3. Replace all scope of works line items with the ones from the PDF, keeping the same visual layout and formatting
4. Update the total to match
5. If there are any notes, conditions, or exclusions in the PDF, add them to the footer or terms section
6. Do not change anything else — keep all branding, colours, photos, reviews, and business details exactly as they are

Output the complete HTML file. I will save it and share it with my client.
```

---

## Tips

- Works with any quoting software that can export to PDF — ServiceM8, Simpro, Xero, Fergus, AroFlo, etc.
- If your quote is in an email or a Word doc instead of a PDF, just upload that instead — Claude can read those too
- You can ask Claude to adjust wording after the first output: "rewrite line item 3 to be less technical" or "add a note that the quote is valid for 30 days"
- To send to a client: save the HTML, open it in your browser, and either screenshot it or share the file directly
