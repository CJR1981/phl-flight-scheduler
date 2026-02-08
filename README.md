# phl-flight-scheduler

PHL AA Commissary Flight Scheduler as a single-page web app.

## Run locally

Because this app is a static HTML file, you can run it with any local web server.

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

## Main workflow

1. Upload arrivals CSV.
2. Upload departures CSV.
3. Select the schedule date.
4. Process CSV data to build turns and terminators.
5. Run scheduling.
6. Export the matched schedule with team assignments.
