# radiodb
Github-based database for radio stations

This database is used for the Id7-themed CarRadio app made for android car headunits.

## Improving the database

Adding missing stations through pull requests is welcomed as long as you follow the format outlined in the format section.  
Images may be uploaded in the 'IMG' subfolders, but please make sure to include a license if required.  
If no such license is available or applicable please link to an external host.

## Formatting stations
The station lists use the following format:
```json
{
  // String: id of the station, use the format XXYY where XX is the country code and YY is the station number.
  "id": "XX1",
  // String: Name of the station.
  "name": "Radio Station 1",
  // String: Country of origin for the station, please make sure you put the station in the correct folder.
  "country": "Country",
  // String: Short (one-line) description of the station.
  "description": "Very Radio Many Music",
  // String: Genre(s), currently unused.
  "genre": "Music, Song, Dance",
  // Double: FM/AM frequency of the station, please make sure to properly format, e.g. 20 becomes 20.0
  "frequency": 69.0,
  // String: Url to MP3 stream for the station, please supply https when available, leave empty ("") when unavailable
  "mp3Stream": "https://host.com/path/to/mp3/stream",
  // String: Url to AAC stream for the station, please supply https when available, leave empty ("") when unavailable
  "aacStream": "https://host.com/path/to/mp3/stream",
  // String: Url to the image for the station, use icons with transparency and of 100kb or less for best results.
  "imageUrl": "https://host.com/path/to/image.png"
}
```

## Attribution

This section will be used for attribution to those who contributed to this database, as well as link to any licenses applicable to the items in this database.
