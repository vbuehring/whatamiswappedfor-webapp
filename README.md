# What Am I Swapped For

Performance art - victor to fill in blurb here.

## MVP

- Admin area
    - Add note
    - Edit/Archive notes
- Public area
    - Search and view entries
    - Add entry
    - About page

## UI


## Data

### Note
- Serial: (generated at random (unique) when Victor creates note in system EG: AA234)
- Photo: URL
- NoteSerial: Alphanumeric
- Archived: Bool
- Currency: String
- Value: Int
- Launch Date: Timestamp
- Launch Coords: {lat, long}
- FirstEntry
- Entries: []

### Entry
- Date: Timestamp (automatic, allow editing)
- Coords: {lat, long} (auto from address, or browser, or manual entry of address)
- Item: String (mandatory)
- Exchanged: Bool (mandatory)
- Towards: Bool (mandatory)
- Name: String (optional/anonymous)
- PricedAt: Double (mandatory)
- Photos: []
- Video: []

### Pages
- Page: {
    locale: [ en: {
        - Title
        - Blurb
        - Content
        - LastEdited
        - Author
        - UI: {}
    }]
}

## Features to add
- Geolocation (browser)
- Address lookup
- AI to generate easy to remember serial
- Locale (translations)
- Local serial numbers
- Show map of entry movements
- Data visualisation (3d plotting, VR, street view, anything goes)
