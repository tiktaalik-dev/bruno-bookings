# Set of tests to call the Restfull Booker API using Bruno's CLI tool and the Bruno app.

## Bruno app

The tests on the root folder are meant to be run in the Bruno app, either manually or using the app runner. Ideally, add a 2 seconds delay in between requests.

## Bruno CLI

The tests on the `CLI` folder are meant to be run using the Bruno CLI tool in a terminal (e.g. in your favourite IDE).

The final report where all tests passed was run using the following command line:

```bash
bru run CLI-tests --json-file-path CLI-tests/data-bookings.json --reporter-html reports/report-20260810-094837.html --bail  --reporter-json rep
orts/debug-20260810-094837.json
```
