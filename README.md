## Silas Apostol

Computer Science at UNC Charlotte, concentration in AI-Assisted Software Engineering.
Expected May 2028.
I build iOS apps and ship them.

### Strut — [download on the App Store](https://apps.apple.com/us/app/strut-walk-more-scroll-less/id6761438303)

An app that ties phone access to walking. Pick the apps that eat your day and a step
goal, and they stay blocked until you earn them back.

Swift, SwiftUI, HealthKit, the Screen Time APIs, watchOS, StoreKit 2, Firebase. Eight
Xcode targets across five processes. Built and operated solo — design, engineering,
backend, pricing, analytics, and the marketing.

### Pinky — [write-up and architecture](https://github.com/silasapostol13-web/pinky)

An iOS app for two people in a long-distance relationship: four two-player games and
guided date nights you run at the same time on two phones, alongside a FaceTime call.
1.0.0, signed and staged for App Store review.

Every screen is shared state across two devices, and that constraint is what the
codebase is about — a matchmaking race resolved by deriving the session path
deterministically instead of narrowing the window, countdowns arbitrated by a
server-written timestamp so two phones can't race to end a round, in-progress strokes
streamed at 8Hz, and a shared-purchase entitlement enforced by constraining the written
result rather than trusting the client. Source is private; the write-up is public and I
will share read access on request.

### Things I've written up

- **[Data Structures portfolio](https://github.com/silasapostol13-web/data-structures-portfolio)** —
  coursework, plus engineering write-ups on problems from Strut: keeping a step count
  fresh when iOS guarantees you nothing, reading data out of a one-way sandbox, and
  search in a database with no substring queries.
- **[strut-dl](https://github.com/silasapostol13-web/strut-dl)** — Instagram's in-app
  browser silently swallows App Store links, so every install from a bio link was being
  lost. Found the one escape that still works, on a real device across six rounds of
  testing. Every round is preserved in the repo.

### What I'm interested in

Applied AI, mobile, and the measurement side of products — instrumenting something
honestly enough to find out your own conclusion was wrong. Looking for a Summer 2027
internship in Austin or remote.

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/silas-apostol-b377b7293/) · silasapostol13@gmail.com
