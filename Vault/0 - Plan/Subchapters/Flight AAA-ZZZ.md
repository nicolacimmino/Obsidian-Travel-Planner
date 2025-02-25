---
Planned At: 2025-01-24T07:20
Origin: AAA
Destination: ZZZ
Departure: 2025-01-24T09:20
Arrival: 2025-01-24T12:35
Flight No: FR 6145
PNR: ABCABC
Type: Flight
tags:
  - itinerary
---
`= elink(join(list("https://www.flightradar24.com/data/flights/",lower(replace(this.flight-no, " ", ""))), ""), join(list("Live Info",this.flight-no), " "))`

### Tickets
Drop here links to tickets PDFs. I generally both embed them `![[ticket.pdf]]` and link them `[[ticket.pdf]]`. The first is useful for a quick peek, the second if we want to open it full screen or share it.