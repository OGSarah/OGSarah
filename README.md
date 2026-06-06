# Hi, I'm Sarah 👋

**Senior iOS Engineer** with 12 years building Swift and SwiftUI apps shipped to the App Store at enterprise scale.

Most of my production work lives in private, enterprise codebases, so it can't be public. The repositories below are where I keep my hands-on Swift current and where I explore the layers below the UI. They're meant to be read as working samples, not as the scope of what I've shipped.

I work across the whole stack of an iOS product, from the socket up to the polished Apple-platform surface, and I'm comfortable owning a feature end to end.

---

## 🚀 Shipped to the App Store: TossTracker

**[TossTracker](https://apps.apple.com/app/tosstracker/id6758673916)** is a cornhole scoring app I designed, built, and published to the App Store on my own.

It handles cancellation scoring automatically, manages rounds and turn order, and saves every completed match with full team, score, and date detail. Beyond the core scoring it includes searchable and filterable game history, CSV export and sharing, an in-app rules reference, optional sounds and haptics, and a confetti finish.

It's built for everyone, with full VoiceOver support and labels and hints throughout, independent light and dark mode, landscape support, and resumable in-progress games.

Source is private, but it's the clearest example of my work taken all the way from idea to a released, accessible, polished product.

---

## What these repos show, and how they map to my work

### Working both sides of the app and backend boundary
A lot of my professional work pairs a SwiftUI frontend with backend services I also own. These repos make that visible:

- **[Calculator](https://github.com/OGSarah/Calculator)** — a SwiftUI client that logs session data to a Go backend, so the project spans the client, the network layer, and the service.
- **[eCFRProject](https://github.com/OGSarah/eCFRProject)** — a Go service that ingests and analyzes U.S. federal regulation data and surfaces it through a lightweight web dashboard.

### Low-level networking
I like understanding the layer beneath the framework rather than treating it as a black box:

- **[HTTPServer](https://github.com/OGSarah/HTTPServer)** — a custom HTTP/1.1 server written in Swift directly on Darwin sockets, handling request parsing, routing, and concurrency control without a web framework.

### Modern iOS architecture and testing
The patterns I reach for on real products: clear architecture boundaries, structured concurrency, and tests:

- **[Culinary-Catalog](https://github.com/OGSarah/Culinary-Catalog)** — MVVM with dependency injection over a Core Data store, an async/await networking layer, typed error handling, and Swift Testing coverage.
- **[Workout](https://github.com/OGSarah/Workout)** — Swift Charts visualizations driven by derived trends over a dataset, with attention to glanceable, readable state.

### Apple platform depth
- **[QRCodeGen](https://github.com/OGSarah/QRCodeGen)** — a SwiftUI generator built on a Core Image filter pipeline.

---

## Tech I work in

**Languages:** Swift, Go, Objective-C, Python, Java, JavaScript

**Apple platforms:** iOS (incl. iOS 26), iPadOS, watchOS, visionOS

**Frameworks:** SwiftUI, UIKit, Core Data, SwiftData, Swift Charts, Combine, Observation, ActivityKit, HealthKit, CryptoKit, MapKit

**Concurrency:** async/await, Combine, Observation

**Backend and APIs:** Go, REST, GraphQL, WebSockets, PostgreSQL, SQLite

**Quality and tooling:** Swift Testing, XCTest, XCUITest, SwiftLint, Fastlane, Xcode Cloud, GitHub Actions, TestFlight

---

## Find me

- Portfolio: [sarahuniverse.com](https://www.sarahuniverse.com)
- Email: sarah@sarahuniverse.com
