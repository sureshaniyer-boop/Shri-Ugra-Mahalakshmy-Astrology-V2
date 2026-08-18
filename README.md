# Shri Ugra Mahalakshmy Astrology V2

A private Vedic Astrology consultation-reference system designed to organise and cross-reference Nakshatra, Graha, Bhava, Dosha and Parihara knowledge.

## V2 starter modules

- Consultation Dashboard
- Nakshatra Karmic Master
- Graha Master
- Bhava Karakatva Master

## Data architecture

Reference content is separated from the user interface under `/data` so future source material can be added without rebuilding the pages.

- `data/nakshatras.json`
- `data/planets.json`
- `data/bhavas.json`

## Source handling

V2 is designed to distinguish:

1. **Source** — information preserved from supplied astrology reference documents.
2. **System Derived** — calculations or cross-references performed by the application.
3. **Practitioner Note** — interpretations or working notes added by the astrologer.

Traditional astrological, karmic and health associations in the source documents are presented as source material rather than modern scientific or medical conclusions.
