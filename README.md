# HookRun

Concept demo for a bike workshop parts-request flow.

- **Workshop:** a mechanic picks their hook (1–40) from a dropdown, scans part barcodes (any USB/Bluetooth scanner that types like a keyboard works) or searches by name, and sends the request.
- **Logistics:** works in three stages. **Pick**: one list of everything to take off the shelves, in walking order, tick as you go. **Deliver**: the picked parts grouped per hook, with a printable sheet per hook. **Delivered**: the last 7 days. Everything can be printed at every stage, but it is built to run on a tablet.

Replaces: scan → Slack → Google Form → export & print → delivery.

This demo keeps data in the browser (localStorage). Part numbers, names and shelf locations are examples. In production it would run on a company server with a shared database and the real parts catalogue.

Live demo: https://thijm-dev.github.io/HookRun/
