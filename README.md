# Northway Logistics platform prototype

A clickable prototype of a courier platform: a customer tracking portal, a driver app with digital proof of delivery and an operations dashboard. All views share the same live sample data, so a POD submitted in the driver app shows up in the customer portal and the ops dashboard straight away.

Live demo: https://patil-vinay.github.io/northway-demo/

## What's in it

- Customer portal: per-customer login, live tracking, delivery history, POD downloads, a booking form and an inbox of automatic emails
- Driver app: job list, collection photos, recipient name and signature, failed delivery reporting and an offline mode that syncs later
- Automatic POD: a branded document is generated on submit and emailed to the customer with the photos
- Operations dashboard: live fleet map, driver allocation, exceptions, job search and an email log
- Public tracking page that needs no login
- 3D map made with three.js (the vans, lorry, towns and roads are all built in code)

## Running it

It is a single static file. Open `index.html` in a browser or serve the folder:

```
python -m http.server 8000
```

Everything is sample data kept in the browser (localStorage). Use Reset demo in the top bar to start again.
