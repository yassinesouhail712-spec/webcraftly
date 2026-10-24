# موقعك — Website Request Site

A responsive multilingual website for collecting website-design requests and preparing a WhatsApp message for the owner.

## Languages
- Arabic: Modern Standard Arabic (العربية الفصحى)
- English
- French

## International audience
The form is not limited to Morocco. It asks for the target country/countries and city/region, accepts international phone numbers, and gives examples from different countries. The base price remains **299 MAD per month**. The pricing section includes a currency selector and attempts to fetch daily reference exchange rates from Frankfurter (no API key required). It displays an estimated equivalent for supported currencies, the rate date when available, and keeps MAD as the fallback if the rate service is unavailable. The displayed conversion is informational only; confirm the final payment currency and amount with each client before starting. This is not a payment processor.

## WhatsApp requests
The request form opens WhatsApp to `+212724628891` with the information entered by the customer. The customer reviews the message and sends it manually. No request is sent automatically.

## Publish
Upload `index.html` to your static hosting provider or replace the old deployed file with this version. Test Arabic, English, and French on mobile, including every conditional form section and the generated WhatsApp message, before sharing the public link.
