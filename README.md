# Orthodox Christian Liturgical Calendars

## Purpose
The purpose of this repository is to store annual Orthodox Christian liturgical calendars in a modern format (.ics) for use across various internet and device platforms. This project aims to make the rich liturgical heritage of Orthodox Christianity more accessible to both laypeople and developers.

## Current Focus
The current focus of the project is the **Antiochian Western Rite** liturgical calendar. However, the vision includes adding other liturgical calendars for specific churches, regions, or master calendars with variations in implementation. For example:
- The Book of Common Prayer has a master calendar but varies in local implementation.
- Capturing these variations and master versions will help Orthodox Christians integrate liturgical calendars into their devices and allow developers to implement them in Orthodox digital products.

## Intended Audience
- **Developers:** This GitHub repository is primarily for developers who want to contribute, review, or utilize the .ics files programmatically.
- **Clergy, Laypeople, and Orthobros:** The .ics files hosted in Supabase storage buckets are intended for Orthodox Christians who wish to subscribe to these calendars on their personal devices.

## Contribution Guidelines
We welcome contributions from individuals who can provide accurate data and demonstrate proper sourcing for their contributions. Examples include liturgical calendars from:
- Russian Orthodox Church
- Greek Orthodox Church
- Eastern Antiochian Orthodox Church
- Other canonical Orthodox jurisdictions

If you would like to contribute, please:
1. Submit a pull request with your changes.
2. Include detailed documentation of your sources for verification.

## Hosting and Deployment
The .ics files are hosted in **Supabase Storage Buckets**, with separate buckets for:
- **Development**: LiturgicalCalendarsDev
- **Staging**: LiturgicalCalendarsStaging
- **Production**: LiturgicalCalendarsMain

A CI/CD pipeline is set up to automatically deploy from the `main` branch to the **Production bucket**. Other branches (e.g., `staging` and `dev`) can target their respective buckets as needed.

## How to Use
1. Subscribe to the calendar URL provided for the desired jurisdiction or focus area.
2. Integrate the calendar into your device or application to view and use the liturgical schedule.

## License
This project is open-source and released under the [MIT License](./LICENSE). You are free to use, modify, and distribute the content, provided attribution is given.

---

For questions, issues, or contributions, feel free to open a GitHub issue or submit a pull request.
