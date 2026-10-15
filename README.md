# Kozhikode Car Hunt

A single-page, filterable comparison of used cars for sale around Kozhikode, Kerala.

**Filters applied:** petrol · true manual · 1st owner · 2020 onwards · under 70,000 km · ₹4–6.5 lakh

Data was collected on **15 October 2026** from the public listing APIs of OLX, CarDekho,
CarWale and Cars24, anchored on Kozhikode, Malappuram, Kannur and Thrissur, then
de-duplicated across portals and benchmarked against the median price of the same
model and year within the matched set.

289 cars. The page is a self-contained HTML file — no build step, no dependencies
beyond Google Fonts.

### Caveats

- Prices are **asking** prices and negotiable.
- Odometer, owner count and service history are **seller-declared**.
- Listings turn over within days; this is a snapshot, not a live feed.
- Rows marked `check odo` have an odometer implausible for the car's age.
- Distances marked `≈` are approximations inherited from the search anchor.
