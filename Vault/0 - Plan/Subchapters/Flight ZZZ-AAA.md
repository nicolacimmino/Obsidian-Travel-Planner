---
Planned At: 2025-02-02T10:30:00
Origin: ZZZ
Destination: AAA
Departure: 2025-02-02T12:30:00
Arrival: 2025-02-03T15:35:00
Flight No: FR 6144
PNR: ABCABC
Type: Flight
tags:
  - itinerary
---
`= elink(join(list("https://www.flightradar24.com/data/flights/",lower(replace(this.flight-no, " ", ""))), ""), join(list("Live Info",this.flight-no), " "))`

### Tickets
Drop here links to tickets PDFs. I generally both embed them `![[ticket.pdf]]` and link them `[[ticket.pdf]]`. The first is useful for a quick peek, the second if we want to open it full screen or share it.
