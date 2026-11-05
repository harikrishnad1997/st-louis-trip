---
layout: default
title: St. Louis Weekend — Road Trip Itinerary, Nov 6–8, 2026
---

# St. Louis Weekend

**Road-trip itinerary · Fri Nov 6 – Sun Nov 8, 2026 · Elmhurst / Lombard → Springfield → St. Louis**
Three NPS passport stamps in one weekend: Lincoln Home, Gateway Arch, and Ulysses S. Grant.

<style>
.trip-fig { margin: 14px 0; }
.trip-fig img { width: 100%; height: auto; border-radius: 10px; display: block; }
.trip-fig figcaption { font-size: 0.85em; color: #606c71; text-align: center; margin-top: 5px; }
.photo-row { display: flex; gap: 12px; flex-wrap: wrap; margin: 6px 0 10px; }
.photo-row .trip-fig { flex: 1 1 260px; margin: 0; }
.photo-row .trip-fig img { height: 220px; object-fit: cover; }
.hero-fig img { max-height: 420px; object-fit: cover; }
</style>

<figure class="trip-fig hero-fig"><img src="https://commons.wikimedia.org/wiki/Special:FilePath/The%20Gateway%20Arch%2C%20Jefferson%20National%20Expansion%20Memorial%2C%20St.%20Louis%2C%20MO%2C%20USA.jpg?width=1280" alt="The Gateway Arch, St. Louis — Saturday afternoon's anchor stop." loading="lazy"><figcaption>The Gateway Arch, St. Louis — Saturday afternoon's anchor stop.</figcaption></figure>

## Contents {#contents}

- [Bookings](#bookings)
- [Weather in St. Louis — live forecast](#weather)
- [Trip map — color-coded by day](#trip-map)
- [Day 1 — Fri Nov 6: Lombard → Lincoln Home → St. Louis](#day-1)
- [Day 2 — Sat Nov 7: Grant, Old Courthouse, Arch & City Museum](#day-2)
- [Day 3 — Sun Nov 8: late breakfast, noon departure](#day-3)
- [Where to eat — vegetarian picks](#where-to-eat)
- [NPS park stores on this route](#nps-stores)
- [Stamp checklist](#stamp-checklist)
- [Know before you go](#know-before-you-go)
- [Packing checklist](#packing-checklist)

## Bookings {#bookings}

### 🚗 Rental car — Enterprise, Lombard
920 E Roosevelt Rd, Lombard, IL 60148 · (630) 916-7700
- Pickup **Fri Nov 6, 2026 @ 12:00 PM**
- Return **Sun Nov 8, 2026 @ 12:00 PM**, same location
- Chrysler Pacifica or similar, automatic, unlimited mileage, 9 additional drivers included
- **$106.75 estimated total** (2 days @ $48.30 + taxes/fees)
- Confirmation number is in the email, not on this public page
- **⚠️ Planning assumption (set Nov 2): Sunday return at 9:00 PM, not noon** — the booking on file still says **12:00 PM**. Two things follow: (1) modify the reservation to a 9 PM return before the trip so the price is quoted up front — returning 9 hours late on a noon booking invites hourly late charges, likely a 3rd day at ~$48.30 + tax/fees (estimate); (2) the Lombard branch is **closed Sundays**, so any Sunday return is an **after-hours drop** — Enterprise's Lombard page lists "After-Hours Returns Available." You're responsible for the car until staff check it in Monday morning, so photo-document everything at drop-off (see Day 3). Day 3's noon departure from St. Louis lands back ~5:00–5:30 PM — comfortably inside the assumed 9 PM return, with hours of buffer.

### 🏨 Hotel — BOOKED: Quality Inn Saint Louis Airport
10232 Natural Bridge Rd, Saint Louis, MO 63134 · (314) 427-5955 · by Lambert Airport, ~20 mins NW of downtown
- Check-in **Fri Nov 6, 2026 after 3:00 PM** — the ~7 PM arrival is fine, but if check-in slips past **9:00 PM, call the hotel** or the reservation may be released
- Check-out **Sun Nov 8, 2026 by 11:00 AM**
- **2 rooms × 2 nights**, each room max 4 guests, booked via **Priceline** in **Krishnan Venkatesan's name** (he booked it and forwarded the confirmation on Nov 4) — confirmation numbers are in that email, not on this public page
- **Breakfast included**, free WiFi, on-site parking (charges may apply), prepaid through Priceline
- Cancellation: fully refundable until **Fri Nov 6, 3:59 PM**; non-refundable after Fri 11:59 PM
- Location note: it's an airport hotel, not downtown — budget ~20 mins each way to Union Station / the Arch and ~25 mins to Grant NHS on Saturday morning

### 🎟️ Gateway Arch tram — BOOKED
- **Sat Nov 7, 2026 @ 1:00 PM — North Tram**, Gateway Arch
- **7 adult tickets** — $17.00 each + $3.00 convenience fee = **$122.00 total, paid** (balance $0)
- E-tickets — retrieval link is in the confirmation email; confirmation number is in the email, not on this public page
- Arrive **~12:30 PM**: enter through the Fourth Street / Old Courthouse-facing entrance and allow time for the airport-style security checkpoint. Time at the top is capped at under 10 minutes
- Parking tip from the confirmation: **Stadium East Garage** (200 S Broadway, two blocks away) is the preferred lot — **$11 for the first five hours**; on a non-event day, validate the garage ticket in the visitor center lobby

## Weather in St. Louis — live forecast {#weather}

Live forecast for St. Louis, MO, powered by [Open-Meteo](https://open-meteo.com)
Backup: the [National Weather Service forecast for St. Louis](https://forecast.weather.gov/MapClick.php?lat=38.6273&lon=-90.1994).

<div id="wx" class="wx-row"><p>Loading the latest forecast…</p></div>
<p id="wx-note" class="wx-note"></p>

<style>
.wx-row { display: flex; gap: 10px; flex-wrap: wrap; margin: 10px 0 4px; }
.wx-card { flex: 1 1 100px; max-width: 128px; border: 1px solid #d6dee3; border-radius: 10px; padding: 10px 6px; text-align: center; background: #f7faf9; }
.wx-card.trip { border: 2px solid #2e5a3c; background: #eef6f0; }
.wx-d { font-weight: 700; font-size: 13px; }
.wx-i { font-size: 26px; line-height: 1.25; }
.wx-t { font-size: 14px; font-weight: 600; }
.wx-c { font-size: 12px; color: #606c71; }
.wx-p { font-size: 12px; color: #1d6fb8; }
.wx-note { font-size: 12px; color: #606c71; margin-top: 0; }
</style>

<script>
(function () {
  var el = document.getElementById("wx");
  var note = document.getElementById("wx-note");
  var TRIP = { "2026-11-06": 1, "2026-11-07": 1, "2026-11-08": 1 };
  function wmo(c) {
    if (c === 0) return ["☀️", "Clear"];
    if (c === 1 || c === 2) return ["🌤️", "Partly cloudy"];
    if (c === 3) return ["☁️", "Overcast"];
    if (c === 45 || c === 48) return ["🌫️", "Fog"];
    if (c === 51 || c === 53 || c === 55) return ["🌦️", "Drizzle"];
    if (c === 56 || c === 57) return ["🌦️", "Freezing drizzle"];
    if (c === 61 || c === 63 || c === 65) return ["🌧️", "Rain"];
    if (c === 66 || c === 67) return ["🌧️", "Freezing rain"];
    if (c === 71 || c === 73 || c === 75 || c === 77) return ["🌨️", "Snow"];
    if (c === 80 || c === 81 || c === 82) return ["🌦️", "Showers"];
    if (c === 85 || c === 86) return ["🌨️", "Snow showers"];
    if (c === 95) return ["⛈️", "Thunderstorm"];
    if (c === 96 || c === 99) return ["⛈️", "Thunderstorm, hail"];
    return ["🌡️", ""];
  }
  function dayName(iso) {
    var p = iso.split("-");
    var d = new Date(p[0], p[1] - 1, p[2]);
    var days = ["Sun", "Mon", "Tue", "Wed", "Thu", "Fri", "Sat"];
    var mons = ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"];
    return days[d.getDay()] + " " + mons[d.getMonth()] + " " + d.getDate();
  }
  fetch("https://api.open-meteo.com/v1/forecast?latitude=38.6273&longitude=-90.1994&daily=weather_code,temperature_2m_max,temperature_2m_min,precipitation_probability_max&temperature_unit=fahrenheit&timezone=America%2FChicago&forecast_days=10")
    .then(function (r) { return r.json(); })
    .then(function (d) {
      var t = d.daily.time, html = "", seen = 0;
      for (var i = 0; i < t.length; i++) {
        var w = wmo(d.daily.weather_code[i]);
        var isTrip = TRIP[t[i]] ? " trip" : "";
        if (TRIP[t[i]]) seen++;
        var pp = d.daily.precipitation_probability_max[i];
        html += '<div class="wx-card' + isTrip + '"><div class="wx-d">' + dayName(t[i]) + (TRIP[t[i]] ? " · TRIP" : "") + '</div><div class="wx-i">' + w[0] + '</div><div class="wx-t">' + Math.round(d.daily.temperature_2m_max[i]) + "° / " + Math.round(d.daily.temperature_2m_min[i]) + '°F</div><div class="wx-c">' + w[1] + '</div><div class="wx-p">' + (pp === null || pp === undefined ? "" : "💧 " + pp + "%") + "</div></div>";
      }
      el.innerHTML = html;
      note.textContent = seen === 0
        ? "Showing the next 10 days. Your trip (Nov 6–8) is still beyond the 10-day forecast window — check back during trip week and those days will be highlighted here."
        : "Your trip days are in this forecast — the green cards are the ones that matter. Friday is a driving day; Saturday is the outdoor day to dress for.";
    })
    .catch(function () {
      el.innerHTML = '<p>Could not load the live forecast right now — use the <a href="https://forecast.weather.gov/MapClick.php?lat=38.6273&lon=-90.1994">National Weather Service forecast for St. Louis</a> instead.</p>';
    });
})();
</script>

## Trip map — color-coded by day {#trip-map}

Every stop on one map: 🔵 **Day 1** (Fri, drive down + Springfield + Union Station) · 🟠 **Day 2** (Sat, St. Louis) · 🟢 **Day 3** (Sun, late breakfast + drive home). Pins are numbered in visit order — tap a pin for the stop and a Google Maps link. The restaurants are pinned too: Shimla Peppers (Fri lunch), Govinda's (Fri dinner option), and Gokul + Bombay Food Junkies (Sat dinner options), plus the Quality Inn hotel by the airport (Day 1 pin 7) — 14 pins in all. **Filter by day:** use the layer checkboxes on the map (top right — on a phone, tap the layers icon). [Open the map full-screen](map.html) for easier browsing on a phone. Note the map shows the St. Louis / Springfield stops in detail; the I-55 drive itself is a straight shot between them.

<iframe src="map.html" width="100%" style="border:1px solid #ccc; border-radius:8px; height:82vh; min-height:620px;" loading="lazy" title="St. Louis weekend map — stops color-coded by day"></iframe>

## Day 1 — Fri Nov 6: Lombard → Lincoln Home → St. Louis {#day-1}

<figure class="trip-fig"><img src="https://commons.wikimedia.org/wiki/Special:FilePath/Lincoln%20Home%20NHS%20at%20Sunset.jpg?width=1280" alt="Lincoln Home National Historic Site, Springfield — the only home Lincoln ever owned." loading="lazy"><figcaption>Lincoln Home National Historic Site, Springfield — the only home Lincoln ever owned.</figcaption></figure>

- **12:00 PM — Pickup: [Enterprise, Lombard](https://www.google.com/maps/search/?api=1&query=Enterprise+Rent-A-Car+920+E+Roosevelt+Rd+Lombard+IL).** Short hop west first — lunch is before the highway, not on it.
- **~12:30–1:30 PM — Lunch: [Shimla Peppers, Naperville](https://www.google.com/maps/search/?api=1&query=Shimla+Peppers+1904+Brookdale+Rd+Naperville+IL)** (1904 Brookdale Rd, Ste 156, ~20–25 mins from Enterprise). Pure-veg North Indian — paneer tikka masala, bhindi masala, Amritsari kulcha, North Indian thali. Friday lunch hours **12:00–3:00 PM**; (331) 226-2992. Keep it to the hour — out by 1:30, because lunch is what makes Springfield a sprint (see below).
- **~1:30 PM — On the road:** Brookdale Rd → I-88 east → I-355 south → I-55 south. Naperville → Springfield is ~190 mi / ~2 hrs 55 mins (estimate).
- **~4:30–4:45 PM — [Lincoln Home National Historic Site, Springfield](https://www.google.com/maps/search/?api=1&query=Lincoln+Home+National+Historic+Site+Springfield+IL) — SPRINT, stamp only** (426 S. 7th St). Visitor Center closes **5:00 PM**, so this is now a 15–30 min stop: **passport stamp + a quick look at the Eastern National bookstore**, nothing more. The house tour is *not* on this trip at all — the last tour starts ~4:00–4:30 PM, its free tickets are first-come, in-person only, so they'd be gone before you arrive, and the Sunday Springfield stop has been removed, so Friday is Lincoln Home's only slot and it's stamp-only. If traffic pushes Springfield past ~4:45 PM, **skip it entirely** — there is no second chance later in the weekend, so Lincoln Home (stamp included) drops off the trip. Don't chase a closing visitor center.
- **~5:00 PM — Leave Springfield** (if you stopped). Springfield → St. Louis is ~96 mi / ~1 hr 35 mins. Sunset is ~4:55 PM, so this leg is after dark.
- **~6:45–7:15 PM — Arrive St. Louis.** The hotel (Quality Inn, by the airport) is ~20 mins NW of downtown — check in on the way in or after the evening downtown, but if it'll be past **9:00 PM, call (314) 427-5955** first so the rooms aren't released. Then **[St. Louis Union Station](https://www.google.com/maps/search/?api=1&query=St+Louis+Union+Station+1820+Market+St)** (1820 Market St). The one downtown spot still fully alive in the evening:
  - **Grand Hall** — free 3D light show on the 65-ft ceiling, **on the hour 5–10 PM daily**
  - **[St. Louis Wheel](https://www.google.com/maps/search/?api=1&query=The+St+Louis+Wheel)** — 200-ft, climate-controlled gondolas, **10 AM–10 PM**, from ~$19
  - **Fire & Light Show** on the lake outside, after dark, free
  - Dinner on site (Train Shed, Soda Fountain, Landry's) — dinner and Union Station are one stop
  - **Veg alternative:** [Govinda's](https://www.google.com/maps/search/?api=1&query=Govindas+Vegetarian+Vegan+Restaurant+3926+Lindell+Blvd+St+Louis) on Lindell Blvd serves its dinner thali **6:30–8:30 PM** — the ~7 PM arrival just makes it, if a sit-down vegetarian dinner beats Union Station food (see Where to eat)
  - The **St. Louis Aquarium (9 AM–7 PM)** is *not* a Friday stop — you arrive as it closes. See the Saturday swap note below.

## Day 2 — Sat Nov 7: Grant, Old Courthouse, Arch & City Museum {#day-2}

- **9:00 AM — [Ulysses S. Grant National Historic Site](https://www.google.com/maps/search/?api=1&query=Ulysses+S+Grant+National+Historic+Site+7400+Grant+Rd+St+Louis)** (7400 Grant Rd, ~25 mins south of the hotel — leave ~8:30 AM). Free, **9 AM–5 PM** — go at opening now that it's the morning stop. Ranger-led White Haven house tour, film, stable museum — and the **passport stamp in the visitor center**, where the JNPA park store also sells America the Beautiful passes. Done by ~10:30 AM.
- **~11:00 AM — [Old Courthouse](https://www.google.com/maps/search/?api=1&query=Old+Courthouse+11+N+4th+St+St+Louis)** (11 N. 4th St, downtown, two blocks west of the Arch). Free, **9 AM–5 PM**. Dred Scott case site. Doing it late-morning keeps it safe — it closes at 5 PM, before the Arch visitor center. Its JNPA shop focuses on Dred Scott and St. Louis history. Quick downtown lunch after.
- **1:00 PM — [Gateway Arch National Park](https://www.google.com/maps/search/?api=1&query=Gateway+Arch+National+Park+St+Louis) — tram BOOKED (North Tram, 7 adults).** Arrive **~12:30 PM** — entrance faces Fourth Street and the Old Courthouse, and everyone goes through an airport-style security checkpoint. Time at the top is under 10 minutes; the whole tram experience runs ~45–60 mins. Visitor Center / Museum **9 AM–6 PM** in fall/winter; the museum underneath is free. **Passport stamp** at the visitor center. **The Arch Store** (JNPA) is in the visitor center, to the right as you exit the museum. Done by ~3:00–3:30 PM, with the museum as buffer if the tram runs late.
- **Late afternoon — this is Forest Park's only window now:** Sunday is a late-breakfast / noon-departure day (see Day 3), so there's no Sunday-morning Forest Park anymore. If Forest Park matters, it's a short version today:
  - [Saint Louis Art Museum](https://www.google.com/maps/search/?api=1&query=Saint+Louis+Art+Museum+1+Fine+Arts+Dr) — free, Sat **10 AM–5 PM**: a ~1 hr highlights visit if you're out of the Arch by 3:30.
  - [Missouri Botanical Garden](https://www.google.com/maps/search/?api=1&query=Missouri+Botanical+Garden+4344+Shaw+Blvd+St+Louis) — **9 AM–5 PM**, last entry 4:30, $16 adults: Climatron + Japanese Garden sprint only.
  - The **Saint Louis Zoo is off the weekend entirely** on this plan — it closes **4 PM** in November, there's no window after an afternoon Arch, and Sunday leaves at noon.
  - Or skip Forest Park and take the **St. Louis Aquarium at Union Station** (9 AM–7 PM, ~$25–30 adults, ~1.5–2 hrs) — the one afternoon option open late enough to do properly.
- **Dinner — vegetarian options before the evening:** [Gokul](https://www.google.com/maps/search/?api=1&query=Gokul+Indian+Restaurant+6101+Delmar+Blvd+St+Louis) in the Delmar Loop (dinner from 4:00 PM, ~10 mins from Forest Park) is the natural pairing with a Forest Park afternoon; [Bombay Food Junkies](https://www.google.com/maps/search/?api=1&query=Bombay+Food+Junkies+12955+Olive+Blvd+Creve+Coeur) out in Creve Coeur (til 8:30 PM) is the deliberate-trip option; Govinda's dinner thali (6:30–8:30 PM) works too. Details in Where to eat below.
- **Evening — [City Museum](https://www.google.com/maps/search/?api=1&query=City+Museum+750+N+16th+St+St+Louis)** (750 N. 16th St). Open late on Saturdays — the after-dinner slot. Climbing, tunnels and a 10-story slide in a former shoe factory; wear shoes you can move in. Only ~0.7 mi from Union Station, so it also pairs with a sunset Wheel ride if Friday ran late.

## Day 3 — Sun Nov 8: late breakfast, noon departure {#day-3}

*A slow Sunday by design: late breakfast, on the road at noon, home with hours to spare before the assumed 9:00 PM return.*

- **Sleep in — but hotel check-out is 11:00 AM.** Pack the car first so it's a clean exit with no backtrack.
- **~10:30 AM — Late breakfast** — breakfast is included at the Quality Inn, so eat there before the 11 AM check-out (or downtown after). Nothing is scheduled against it — that's the point of the day.
- **12:00 PM — Leave St. Louis.** ~288 mi / ~4 hrs 51 mins nonstop, realistically ~5–5.5 hrs with one fuel stop → **Lombard ~5:00–5:30 PM**.
- **~5:00–5:30 PM — Return: Enterprise, Lombard — AFTER-HOURS DROP.** The branch is closed Sundays; Enterprise's Lombard page lists after-hours returns as available — still true even though you're hours early against the assumed 9 PM return. Park in the return area, keys in the drop box per the branch instructions, and **photo-document the drop**: dash photo of odometer + fuel gauge, exterior walk-around video, the parked car in its spot, and the drop-box moment. Keep the fuel receipt. The car stays your responsibility until staff check it in Monday morning — that documentation is your proof of condition and time.
- **What noon costs:** Forest Park. There's no Sunday-morning Zoo / Art Museum / Botanical Garden on this version — their only window is Saturday's short late-afternoon version (see Day 2), and the Zoo (closes 4 PM) doesn't fit anywhere.

## Where to eat — vegetarian picks {#where-to-eat}

Three St. Louis vegetarian restaurants, added as options (nothing reserved). All three are fully vegetarian or vegan, so the whole menu is in play:

- **[Gokul Indian Restaurant](https://www.google.com/maps/search/?api=1&query=Gokul+Indian+Restaurant+6101+Delmar+Blvd+St+Louis)** — 6101 Delmar Blvd, Delmar Loop · (314) 721-1888 · 4.5★. St. Louis's only **100% vegetarian (and kosher)** restaurant — buffet at lunch and dinner, plus chaat, paneer dishes, dosas/idli and Indo-Chinese. **Fri & Sat: 11:30 AM–2:30 PM and 4:00–8:30 PM** (closed Tuesdays). **Best slot: Saturday dinner** — it's ~10 mins from Forest Park, so it pairs with the late-afternoon Art Museum / Botanical Garden window before City Museum. It also works as a Saturday lunch only if the Arch moves — its 11:30–2:30 lunch window collides with the 1:00 PM tram.
- **[Govinda's Vegetarian & Vegan Restaurant](https://www.google.com/maps/search/?api=1&query=Govindas+Vegetarian+Vegan+Restaurant+3926+Lindell+Blvd+St+Louis)** — 3926 Lindell Blvd, Midtown · (314) 666-4234. The ISKCON temple's restaurant: a simple, homestyle **thali** (the menu rotates daily — dal, sabzi, rice, poori), ~10 mins west of downtown. **Tue–Sun, short windows only: lunch 11:30 AM–1:30 PM, dinner 6:30–8:30 PM** (closed Mondays). **Best slots: Friday dinner** — the 6:30–8:30 PM window just fits the ~7 PM arrival, as the sit-down alternative to Union Station — **or Saturday dinner** before City Museum. The windows are tight, so don't wing the timing.
- **[Bombay Food Junkies](https://www.google.com/maps/search/?api=1&query=Bombay+Food+Junkies+12955+Olive+Blvd+Creve+Coeur)** — 12955 Olive Blvd, Creve Coeur · (314) 685-7181 · 4.4★. **100% vegan** Indian street food and fusion — chaat, chik'n sandwiches and bowls, naan pizzas, Oatly soft-serve shakes. **Mon–Sat 11:30 AM–8:30 PM, closed Sundays.** **Best slot: Saturday dinner** as a deliberate ~25-min drive west (it's the farthest of the three); it can't be a Sunday stop, and Friday's late arrival makes it a stretch.

## NPS park stores on this route {#nps-stores}

All three NPS stops have a park store:

| Stop | Store | Operator | Notes |
|---|---|---|---|
| Lincoln Home (Fri) | Bookstore & gift shop, Visitor Center | Eastern National | Same org as America's National Parks / the passport sticker shop. Lincoln-themed books and gifts. |
| Grant NHS (Sat morning) | Park store, Visitor Center, 7400 Grant Rd | Jefferson National Parks Association (JNPA) | 9 AM–5 PM. Books/gifts; also sells and issues America the Beautiful passes. |
| Old Courthouse (Sat late morning) | Old Courthouse Shop | JNPA | Dred Scott case and St. Louis history focus. |
| Gateway Arch (Sat afternoon) | **The Arch Store**, Arch Visitor Center | JNPA | The biggest selection of the weekend — Arch souvenirs, books, western/Jefferson items. Open visitor-center hours (9 AM–6 PM in Nov). Online: shop.jnpa.com |

Union Station, City Museum, the Zoo, the Art Museum and the Botanical Garden all have their own gift shops — they're just not NPS stores. For passport-book merch and stickers, the Arch Store is the best bet.

## Stamp checklist {#stamp-checklist}

Three NPS passport stamps, one per anchor stop:

- [ ] **Lincoln Home National Historic Site** — Visitor Center desk, Springfield (Fri)
- [ ] **Ulysses S. Grant National Historic Site** — Visitor Center, 7400 Grant Rd (Sat morning)
- [ ] **Gateway Arch National Park** — Arch Visitor Center (Sat afternoon)

Plus the free official brochures (unigrids) at each of the three desks — grab them where you stamp.

## Know before you go {#know-before-you-go}

- **Lincoln Home: the Friday stamp sprint is all there is.** The Shimla Peppers lunch pushes Friday's Springfield arrival to ~4:30–4:45 PM against a 5 PM visitor-center close — stamp sprint only, and skip it if you're running past 4:45, because the Sunday Springfield stop has been removed and there is no fallback. The house tour is not on this trip (last Friday tour ~4:00–4:30 PM, first-come tickets gone by then); if the tour matters most of all, the only fix is cutting Friday lunch short or skipping it.
- **The hotel is by the airport, not downtown.** Quality Inn, 10232 Natural Bridge Rd — ~20 mins to Union Station / the Arch and ~25 mins to Grant NHS, so Saturday's 9 AM Grant start means leaving the hotel ~8:30 AM. Friday check-in after 3 PM; if Friday's check-in will be past 9 PM, call (314) 427-5955 so the rooms aren't released. Sunday check-out is 11:00 AM and breakfast is included. The rooms are in Krishnan Venkatesan's name — carry his forwarded Priceline confirmation email for check-in.
- **Arch tram is booked — Sat 1:00 PM, North Tram, 7 adults ($122 total).** Be at the Fourth Street entrance by ~12:30 PM for the security checkpoint; time at the top is capped at under 10 minutes. Driving in: Stadium East Garage (200 S Broadway) is the preferred lot at $11 for the first five hours — validate the ticket in the visitor center lobby on a non-event day.
- **Daylight is short.** Clocks went back Nov 1; sunset in St. Louis is ~4:55 PM on Nov 6–7. Grant (morning) is Saturday's main outdoor stop; the Arch grounds work fine in the last light after the tram.
- **Forest Park is Saturday-short or nothing.** The Arch swap squeezed it out of Saturday afternoon, and Sunday's noon departure removed the Sunday-morning version. The Zoo (closes 4 PM in November) fits nowhere on this plan; the Art Museum (til 5 PM) or Botanical Garden (last entry 4:30) survive only as Saturday short versions.
- **The 9 PM Sunday return is an assumption, not a booking (yet).** The Enterprise reservation on file still says noon — and note Sunday's noon departure from St. Louis does **not** get the car back by noon; you'd land ~5 PM, 5 hours late on the unmodified booking. Modify it before the trip and get the new total in writing (likely a 3rd day, ~$48.30 + tax/fees, estimate).
- **Tolls:** I-55 to Springfield/St. Louis has no tolls on the mainline run south of the Chicago area, but getting to Lombard / onto I-55 may cross I-294 / I-355 tolls — the rental's TollPass is optional; your own I-PASS works if you bring the transponder and add the rental plate for the rental dates (that's what the October dispute was about — add it *before* you drive).
- Carry the passport book in the car Friday — the Lincoln Home stamp is on the drive down, not in St. Louis.

## Packing checklist {#packing-checklist}

- [ ] Passport To Your National Parks Collector's Edition book (+ loose stamp paper backup)
- [ ] Driver's license + payment card in renter's name for Enterprise pickup
- [ ] I-PASS transponder (and add the rental plate to the account for Nov 6–8)
- [ ] Arch tram e-tickets — save the retrieval link / screenshots from the confirmation email (one order, 7 guests)
- [ ] Layers for Saturday — Arch grounds and Forest Park are exposed; Saturday temps from the forecast above
- [ ] Comfortable closed shoes for City Museum (climbing/slides)
- [ ] Phone charger / car charger for the two 5-hour drive days
- [ ] Snacks + water for the car — Friday lunch is covered (Shimla Peppers), dinner isn't until ~7:15 PM in St. Louis

<p style="text-align:center; margin-top:24px;"><a href="#contents">↑ Back to top</a></p>

<style>
#toTopBtn { position: fixed; right: 16px; bottom: 16px; z-index: 9999; background: #7a3b12; color: #fff; border: none; border-radius: 999px; padding: 10px 16px; font-size: 14px; font-weight: 600; cursor: pointer; box-shadow: 0 2px 6px rgba(0,0,0,.35); display: none; }
#toTopBtn:hover { background: #5f2d0d; }
</style>
<button id="toTopBtn" type="button" aria-label="Back to top">↑ Top</button>
<script>
(function () {
  var b = document.getElementById("toTopBtn");
  window.addEventListener("scroll", function () { b.style.display = window.scrollY > 600 ? "block" : "none"; }, { passive: true });
  b.addEventListener("click", function () { window.scrollTo({ top: 0, behavior: "smooth" }); });
})();
</script>
