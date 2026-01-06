# CNSP Member Map

This directory contains member profiles for Cloud Native Security Pakistan (CNSP). 

## How to Add Yourself

### Option 1: GitHub PR Method (Recommended - Earn Extra Points! ⭐)

1. Create a new file named `YOUR_USERNAME.md` (or `YOUR_USERNAME.json`) in this directory
2. Use the template below or copy from an existing member file
3. Fill in your information
4. Submit a Pull Request
5. Once merged, you'll be promoted to the **Member** team!

**Bonus**: You'll earn extra contribution points for submitting via PR!

### Option 2: Google Form Method

Fill out the [CNSP Member Registration Form](YOUR_GOOGLE_FORM_LINK) and your information will be added automatically.

## File Format

### Markdown Format with YAML Frontmatter (`.md`) - Recommended



```markdown
---
name: Your Full Name
username: YOUR_USERNAME
github: YOUR_USERNAME
location:
  city: City
  province: Province/State
  country: Country
  coordinates:
    latitude: XX.XXXX
    longitude: XX.XXXX
social:
  github: https://github.com/YOUR_USERNAME
  linkedin: "Your LinkedIn URL"
  twitter: "Your Twitter Handle"
interests:
  - Interest 1
  - Interest 2
  - Interest 3
contribution_areas:
  - Contribution area 1
  - Contribution area 2
---

# Member Profile: YOUR_USERNAME

## About Me

Brief description about yourself. This section is for human-readable content.

## Additional Information

You can add more sections here as needed.
```

**Why YAML Frontmatter?**
- Machine-readable for automated processing
- Easy to parse for website map generation
- Follows industry best practices
- Structured format for easy database integration

### JSON Format (`.json`)

```json
{
  "username": "YOUR_USERNAME",
  "name": "Your Full Name",
  "location": {
    "city": "City",
    "province": "Province/State",
    "country": "Country",
    "coordinates": {
      "latitude": XX.XXXX,
      "longitude": XX.XXXX
    }
  },
  "about": "Brief description about yourself",
  "interests": [
    "Interest 1",
    "Interest 2"
  ],
  "contribution_areas": [
    "Area 1",
    "Area 2"
  ],
  "social": {
    "github": "https://github.com/YOUR_USERNAME",
    "linkedin": "Your LinkedIn URL",
    "twitter": "Your Twitter Handle"
  }
}
```

## Finding Your Coordinates

You can find your city's coordinates using:
- [Google Maps](https://www.google.com/maps) - Right-click on your location and copy coordinates
- [LatLong.net](https://www.latlong.net/)
- [OpenStreetMap](https://www.openstreetmap.org/)

## Example: Lahore, Pakistan

- **Latitude**: 31.5204
- **Longitude**: 74.3587

## Notes

- All member information is public and will appear on the CNSP website member map
- Keep your information professional and appropriate
- Update your profile anytime by submitting a new PR
- Both methods (GitHub PR and Google Form) sync to the same database

---

**Questions?** Open an issue or contact an admin!

