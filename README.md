# HookRun

Concept demo for a bike workshop parts-request flow.

- **Workshop:** a mechanic picks their hook (1–40) from a dropdown, scans part barcodes (any USB/Bluetooth scanner that types like a keyboard works) or searches by name, and sends the request.
- **Logistics:** sees all open requests grouped per hook and can print a parts list per hook. There is also one combined pick list sorted by shelf location, ready to print. Requests move from *To pick* → *Ready to deliver* → *Delivered*.

Replaces: scan → Slack → Google Form → export & print → delivery.

This demo keeps data in the browser (localStorage). Part numbers, names and shelf locations are examples. In production it would run on a company server with a shared database and the real parts catalogue.

Live demo: https://thijm-dev.github.io/HookRun/
