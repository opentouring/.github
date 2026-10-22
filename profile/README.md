<!-- SPDX-License-Identifier: CC-BY-4.0 -->

# Open Touring

Open Touring is an open, crowd-contributed database of the places travellers stop at on the road, and of what stands between them and those places.

## Why it exists

Travellers already share what they know about campgrounds, caravan parks, free camps, hostels, drinking water, dump points, showers, points of interest, low bridges and road warnings. Too often that knowledge ends up inside one app, behind a paywall, and owned by whoever runs the app.

Open Touring keeps it in the hands of the people who contribute it. Every record is free to use, copy and build on under CC BY 4.0. The whole dataset, with its full history, lives in public git repositories that anyone can clone without an account or an API key. The project is meant to be owned by its community through a not-for-profit host, so no single company can close it off.

## What it holds

- **Sites:** campsites, caravan parks, free camps, rest areas, dump points, drinking water, toilets, showers, laundries, information centres, ferry terminals, attractions and more, each with its facilities, prices, opening hours and rig limits.
- **Road restrictions:** low bridges and other points with vertical clearance, width, weight and length limits.
- **Road segments:** roads and tracks by surface and vehicle access, from 2WD to 4WD only, with towing and seasonal closures.
- **Ferry services:** vehicle ferries between terminals, with the vehicle classes they carry, fares and hours.

Every fact records where it came from and when, and public IDs never change. Australia comes first, and the schema works for any country.

## How it works

Live data is kept in a public git repository per country, starting with `opentouring/otwd-au`. Every record is a JSON file, and every change is a pull request reviewed by a moderator. Partner apps read the data through an API or as bulk downloads, and send their contributors' new sites and corrections back through the same moderation, so every app that uses the data helps keep it current. Contributing is always free.

## Status

Preview: concept build, not yet accepting outside contributions. Outside contributions open once a not-for-profit host has agreed to take on the project.

## Repositories

- [opentouring](https://github.com/opentouring/opentouring): the platform, the schema, the API spec, the SDKs and the project docs. Issues for data, the schema and the platform all go here.
- `otwd-au`: live data for Australia. Coming soon.

## Licences

| What                                         | Licence       |
| -------------------------------------------- | ------------- |
| Data (records, facts, photos, descriptions)  | CC BY 4.0     |
| Server code                                  | AGPL-3.0-only |
| Schema, API spec, SDKs and sample clients    | Apache-2.0    |

Details are in [LICENSING.md](https://github.com/opentouring/opentouring/blob/main/LICENSING.md). To report a vulnerability, see [SECURITY.md](https://github.com/opentouring/opentouring/blob/main/SECURITY.md).
