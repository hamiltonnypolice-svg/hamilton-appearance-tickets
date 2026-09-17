# Hamilton Appearance Tickets

Scanner-enabled web version of the Hamilton Appearance Tickets application.

## Shared database

The front end uses `config.js` to connect to the existing Google Apps Script web-app backend. Replace the placeholder value in `config.js` with the Apps Script deployment URL ending in `/exec`.

## Serial scanner

Open the published site in current desktop Microsoft Edge or Google Chrome. Choose **Scan ID → Connect serial scanner**, then select the scanner COM port and matching baud rate. Web Serial requires HTTPS.

## GitHub Pages

Publish the repository from the `main` branch and repository root in **Settings → Pages**. The expected site address is:

`https://hamiltonnypolice-svg.github.io/hamilton-appearance-tickets/`

## Important

The repository is public. Do not commit defendant records, exports, database contents, passwords, API secrets, or other protected law-enforcement data. The repository contains only the application code and blank configuration.
