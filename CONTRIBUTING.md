# Contributing to Awesome Trajectory Datasets

Thank you for helping grow this list. Please follow the guidelines below to keep the list consistent and high-quality.

## What belongs here

A dataset belongs in this list if it:

1. **Contains trajectory data**: time-stamped positions (x/y or lat/lon) of moving objects
2. **Is publicly accessible**: free download, registration-only, or clearly documented access request process
3. **Has a citable source**: a peer-reviewed paper, technical report, DOI, or an official project website
4. **Has a stated license**: the terms of use are documented

Domains covered: road traffic (vehicles + VRUs) - and maybe soon aerial (UAV/aircraft) and maritime.

## What does NOT belong here

- Purely simulated datasets without real-world counterpart (unless widely used as benchmark)
- Datasets behind a paywall with no free tier
- Private or institutional datasets with no public access path
- Image/video datasets without extracted trajectory annotations

## How to add a dataset

1. Fork this repository
2. Edit `README.md` — add a row to the most appropriate table
3. Follow the row format:

    - **[Dataset Name](https://main-link)** - Year · Location · Sensors · Description · License, Access · [Link1](url) · [Link2](url) · [🔍](https://city.app.sdk-cloud.de/location/??)


4. Choose the category
6. Open a Pull Request with the title `Add: <Dataset Name>`

## Conventions

| Part | What to put |
|--------|-------------|
| **Dataset Name** | Name in bold letters, linking to the main information page |
| **Year** | Year of trajectories |
| **Location** | City/region + country, or "Multi-country", or "Global" |
| **Sensors** | Comma-separated abbreviations: `cam`, `lid`, `rad`, `gnss`, `drone`, `ais`, `ads-b` |
| **Description** | Short description (time range(s), places, special features like traffic lights, size) |
| **License** | Short name: `CC-BY 4.0`, `CC-BY-NC`, `MIT`, `public domain`, `custom (free academic)`, etc. |
| **Access** | Short name: `Direct Download`, `Data on Request`, `Registration Required` |
| **Links** | [Paper](url) and/or [Git](url) and/or [Docs](url) |
| 🔍 | Link to Data View [🔍](url) |

## Requesting a dataset

If you know a dataset should be on the list but don't want to add it yourself, open a GitHub Issue with the label `dataset request` and fill in the details.

## Trajectory Trace integration

If your dataset is available or can be made available on [Trajectory Trace](https://city.app.sdk-cloud.de/), mention it in your PR. We will add the 🔍 badge with a direct link so users can explore the data without downloading anything.

## Code of Conduct

Be respectful. This is a community resource. Treat contributors and maintainers with courtesy.
