# Shipping

1. Open a request with the form. Pick your region: US, UK/EU, or elsewhere.
2. The request is reviewed on its issue. A yes gets the `approved` label, a no is
   closed with the reason.
3. An approved request gets `needs-postage` and a comment with the postage steps for
   the stock it ships from (US stock for `region-us`, UK stock for `region-uk`).
   Follow them on the issue.
4. Once postage is covered the connector goes out, the issue gets `shipped`, and it
   is closed.

Requests from outside the US, UK and EU are reviewed the same way; the postage
comment says which stock they ship from.

When your board works, a photo or a link on the issue is welcome.
