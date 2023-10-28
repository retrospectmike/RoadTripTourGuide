# RoadTripTourGuide
This android app automatically tells you about each town you drive through on your road trip as you enter the town!  I always wish I could both know what town I'm crossing threw and learn a little about it during long drives.  This app aims to do that for you and without distracting your eyes from the road.

It is my first Android app and my first Kotlin app so pardon the quality of it all.

## Beta
This app is currently in pre-release and is a work in progress.  When formal releases are made, they will be posted on the repository's **Releases** page.

## Description
During a long drive, have you ever wondered what each of these little (or big) towns you drive through is about?
If so - this app is for you.
Road Trip Tour Guide will audibly tell you about each new town or city you drive into, automatically!

### Limitations
This app currently only works for towns in the U.S. and Canada. The parsing of the town name in other countries and converting the names reported from Android's location service into the names of the Wikipedia articles is currently unimplemented.  So US and Canada work, something like Paris, France works, but most towns I tested in Europe don't at the moment.

## How it Works
The app uses your device's location to figure out what city you are in.  It then looks up that city in Wikipedia and grabs the summary (top) section from the town's wikipedia page.  It then reads this aloud using Text-to-Speech.  
If the app can't discern the corresponding Wikipedia article for the town, or if it doesn't exist, the app won't have any information to read aloud.

## Necessary Permissions
1. This app uses Location services to figure out what town you are in
2. This app uses Network services to retrieve location and and to get the information about your town

## Contributing and Open Source
See the license file.  The original author welcomes people contributing / forking / merge requests / etc. from the community.
This app originally made in October 2023 by Mike and any other contributors noted in the repository records

## Disclaimer
The encyclopedic content on this app (the town information) is derived from Wikipedia, currently the first section of the town's wikipedia article, if it exists.
