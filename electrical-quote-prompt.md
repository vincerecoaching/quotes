# Electrical Quote — AI Customisation Prompt

## How to use this

1. Open the template file and copy all the HTML code inside the code block
2. Open [claude.ai](https://claude.ai)
3. Copy the prompt below, fill in your details, then paste the HTML at the bottom
4. Hit send — Claude will rebuild the entire page for your business
5. Copy the output, save it as `quote.html`, open it in your browser

---

## The Prompt

```
I have an electrical quote template in HTML. I need you to customise it for my business.

My website: [PASTE YOUR WEBSITE URL HERE]

Please visit my website and extract:
- My business name
- Phone number
- Suburb and state
- Brand colours (hex codes if visible, otherwise choose something professional that suits my brand)
- Any tagline or slogan

Then update the HTML template with the following changes:

1. Replace every reference to "Journey Electrical" with my business name throughout the entire file
2. Update all phone numbers and location details wherever they appear
3. Update the CSS colour variables at the top of the code to match my brand colours
4. Replace the scope of works with these line items:

   1. [Describe the work] — $[price]
   2. [Describe the work] — $[price]
   3. [Describe the work] — $[price]

5. Update the total to match
6. Client name: [client name, or leave as "Your Client"]
7. Client address: [client address, or leave blank]
8. Quote number: [e.g. QU-0042, or leave as is]

Output the complete HTML. I will save it as quote.html and open it in my browser.

---

[PASTE THE HTML TEMPLATE CODE HERE]
```

---

## Tips

- Claude Pro (paid) can browse your website automatically — free accounts work too but you may need to type your details in manually
- After the first output, you can ask Claude to make changes: "update the headline", "add another line item", "make the button red"
- Save each version as you go — you can use the same template for every job, just swap the client details and scope
