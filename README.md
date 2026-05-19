# NYC Asian Mental Health Directory

A community-maintained directory of nonprofit mental health and behavioral health resources serving Asian communities in New York City.

🌐 **Live site:** https://YOUR-USERNAME.github.io/nyc-asian-mh-directory/

## About

This directory exists because mental health resources for Asian communities in NYC are scattered across many websites, often only in English, and hard to navigate when someone needs help. It aims to bring them together in one searchable place — organized by community, language, and service type.

**This is not a crisis service.** If you or someone you know is in crisis, please call or text **988** (Suicide & Crisis Lifeline) or **1-888-NYC-WELL**.

## How to use

Visit the site, search by keyword, or filter by community (Chinese, Korean, South Asian, Filipino, Southeast Asian, LGBTQ+ Asian, Pan-Asian). Each listing shows location, languages, services, and a link to the organization.

## How to contribute

Found an outdated listing, want to add an organization, or have a correction?

1. **Easiest:** [open an issue](../../issues/new) describing the change.
2. **For developers:** fork the repo, edit the `organizations` array in `index.html`, and open a pull request.

### Adding a new organization

Each entry follows this format:

```js
{
  name: "Organization Name",
  community: "Chinese", // Pan-Asian, Chinese, Korean, South Asian, Southeast Asian, Filipino, LGBTQ+ Asian
  location: "Borough / Neighborhood",
  services: "Short description of what they offer.",
  languages: "Languages spoken",
  website: "https://example.org"
}
```

### What we look for in a listing

- A registered nonprofit (or program of one)
- Offers mental health, behavioral health, counseling, or peer support
- Serves an Asian community in NYC (or virtually for NYC residents)
- Currently active and reachable

## Disclaimer

This directory is informational only and not a substitute for professional medical or mental health care. Information is community-sourced and may change — please verify directly with each organization before reaching out. The maintainers are not affiliated with the listed organizations unless otherwise noted.

## License

The directory data is shared under a Creative Commons Attribution 4.0 license. The site code is MIT-licensed. Feel free to fork this and build similar directories for other regions or communities.
