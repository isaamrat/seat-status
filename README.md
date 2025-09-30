# [BRACU Connect Seat Status](https://isaamrat.github.io/seat-status/)

A modern, dark-mode web app for exploring BRAC University course\'s seat status. It presents seat status in an efficient, searchable UI optimized for both desktop and mobile.

---



---

## What it does

- **Live section overview**  
  Displays course code, section, faculty initials, capacity (booked/total), remaining seats, class/lab schedules, and exam dates.

- **Fast search**  
  Filter instantly by **course code** or **faculty initials**.

- **Intelligent sorting**  
  Results are sorted by `Course`, then by `Section` (numeric-aware).

- **Responsive layouts**  
  - **Desktop:** professional, dense **table view** with all columns.  
  - **Mobile:** compact **card view** that prioritizes key info .

- **Details popup**  
  Click any row/card to open a smooth, profile-style modal with full information (class/lab chips, exam date & time, rooms, prerequisites). 

- **Skeleton loading**  
  Friendly shimmer placeholders while data is loading.

- **Client-side pagination**  
  Improves perceived performance and keeps rendering snappy on large datasets.

- **Email action**  
  One-click mail link with a **prefilled subject** to report discrepancies.

---

## Usability & UX

- **Dark, minimal aesthetic** using Tailwind for clarity and focus.  
- **Single-line schedule chips** with horizontal scroll to avoid wrapping.  
- **Accessible interactions** (button-based rows, clear focus styles).  
- **Sticky/scrollable modal** ensures controls are reachable on small devices.  

---

## Performance & Scalability

- **Client-side pagination** limits the number of rendered rows/cards at once.  
- **Memoized filtering/sorting** ensure smooth search even as datasets grow.  
- **Lightweight UI primitives** (no heavy table libraries) to minimize bundle size.

---

## Accessibility Notes

- Interactive rows are actual **buttons** for keyboard focus and semantics.  
- Modal supports scroll on small screens and keeps the close button visible via **sticky positioning**.
- High-contrast text and large touch targets improve readability and tap accuracy.

---

## Acknowledgements

Special thanks to [@Eniamza](https://github.com/Eniamza) for providing the data source for this project.


## Contact

If you find any discrepancy, please contact via the in-app **Email** button (prefilled subject line included) for faster triage.
