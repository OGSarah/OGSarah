# Hi, I'm Sarah 👋🏻
**Senior iOS Engineer** with over a decade of building iOS apps shipped to the App Store at enterprise scale.
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
Each public project below demonstrates a capability I use in professional, private work. They're working samples, not the scope of what I've shipped.

| Repo | What it demonstrates | How it maps to my work |
| --- | --- | --- |
| **[Calculator](https://github.com/OGSarah/Calculator)** | MVVM over a protocol-driven service layer with dependency injection; SwiftData persistence syncing to a Go + SQLite backend on background, with an offline retry queue; unit, UI, and backend test coverage | Owning testable, resilient architecture across a SwiftUI client and its backend |
| **[eCFRProject](https://github.com/OGSarah/eCFRProject)** | A Go service that ingests and analyzes federal regulation data, surfaced through a web dashboard | Backend ingestion and analytics, full stack ownership |
| **[HTTPServer](https://github.com/OGSarah/HTTPServer)** | A from-scratch HTTP/1.1 server in Swift 6 on raw Darwin sockets, no frameworks: request framing, routing, an actor-backed store, and strict-concurrency-clean structured concurrency | Low-level networking and safe concurrency below the framework layer |
| **[Culinary-Catalog](https://github.com/OGSarah/Culinary-Catalog)** | MVVM with dependency injection over Core Data, an async/await networking layer, typed errors, and Swift Testing | Modern iOS architecture, structured concurrency, and test coverage |
| **[culinary-catalog-data](https://github.com/OGSarah/culinary-catalog-data)** | A zero-infrastructure JSON data service backing Culinary-Catalog: a single source of truth fanned out into versioned, schema-validated feeds, auto-published by a GitHub Actions pipeline | Owning the data contract and release automation behind a shipped client |
| **[Workout](https://github.com/OGSarah/Workout)** | A pure, deterministic domain core under a Swift 6 strict-concurrency UI; protocol-based dependency injection over SwiftData; Swift Charts visualizations, all backed by 64 unit and UI tests | Safe concurrency, testable domain design, and Apple framework depth |
| **[QRCodeGen](https://github.com/OGSarah/QRCodeGen)** | A SwiftUI generator built on a Core Image filter pipeline | Apple platform and media framework experience |

---

## Tech I work in
- **Languages:** Swift, Go, Objective-C, Python, Java, JavaScript
- **Apple platforms:** iOS (incl. iOS 27), iPadOS, watchOS, visionOS
- **Frameworks:** SwiftUI, UIKit, Core Data, SwiftData, Swift Charts, Combine, Observation, ActivityKit, HealthKit, CryptoKit, MapKit
- **Concurrency:** async/await, Combine, Observation
- **Backend and APIs:** Go, REST, GraphQL, WebSockets, PostgreSQL, SQLite
- **Quality and tooling:** Swift Testing, XCTest, XCUITest, SwiftLint, Fastlane, Xcode Cloud, GitHub Actions, TestFlight

---

## Find me
- Portfolio: [sarahuniverse.com](http://www.sarahuniverse.com)
- Email: sarah@sarahuniverse.com
