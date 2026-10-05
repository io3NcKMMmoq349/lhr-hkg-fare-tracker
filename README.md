# LHR → HKG Fare Tracker

Public dashboard for daily Economy fare observations from London Heathrow (LHR) to Hong Kong (HKG), targeting April 2027 departures and 55–70 day stays.

## Publish
Enable GitHub Pages from the `main` branch and repository root.

## Data
The dashboard reads `fares.json`. Append one object per observed itinerary/check and update `updated_at`.

The existing ChatGPT daily fare-watch task researches fares, but automatic website updates require a workflow that writes each daily result back to this repository.