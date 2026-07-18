# Hi, I'm Sarah 👋🏻

**Full Stack Senior Software Engineer** with 10+ years building secure, scalable software at enterprise scale, from raw sockets and backend services up to polished, accessible Apple-platform apps.

I own features end to end, across the whole stack. Most of my production work lives in private enterprise codebases, so it can't be public. The repos below are where I keep my Swift sharp, work with the latest frameworks and tools, and explore the layers beneath the UI. **Read them as working samples, not the full scope of what I've shipped.**

---

## 🚀 Shipped to the App Store: TossTracker

**[TossTracker](https://apps.apple.com/app/tosstracker/id6758673916)** is a cornhole scoring app I designed, built, and published to the App Store on my own.

- Automatic cancellation scoring
- Round management and turn order
- Saves every completed match with full team, score, and date detail
- Searchable and filterable game history
- CSV export and sharing
- In-app rules reference
- Optional sounds and haptics, plus a confetti finish
- Full VoiceOver support with labels and hints throughout
- Independent light and dark mode
- Landscape support
- Resumable in-progress games

Source is private, but it's the clearest example of my work taken all the way from idea to a released, accessible, polished product.

---

## 🔗 Full Stack Engineer

End-to-end ownership: a SwiftUI client and the backend it talks to, with a clean API contract and resilience in between.

| Repo | What it demonstrates | How it maps to my work |
| --- | --- | --- |
| **[Calculator](https://github.com/OGSarah/Calculator)** | MVVM over a protocol-driven service layer with dependency injection. SwiftData persistence syncing to a Go + SQLite backend on background, with an offline retry queue. Unit, UI, and backend test coverage | Owning testable, resilient architecture across a SwiftUI client and its backend |

**Stack:** Swift · SwiftUI · SwiftData · Go · SQLite · REST

---

## 📱 Senior iOS & Apple Platform Engineer

Accessible, offline-capable, testable apps built on protocol-oriented cores under Swift 6 strict concurrency, across iOS, iPadOS, macOS, watchOS, and visionOS.

| Repo | What it demonstrates | How it maps to my work |
| --- | --- | --- |
| **[JSONParser](https://github.com/OGSarah/JSONParser)** | A native macOS app with a hand-written RFC 8259 JSON parser. A custom lexer and recursive descent parser, no `Foundation` `JSONSerialization`. `@Observable` MVVM behind `JSONParsing` and `PasteboardReading` protocol seams. `nonisolated`, thread-agnostic parsing under Swift 6 strict concurrency. AppKit (`NSTextView`) interop for a syntax-highlighting editor. Typed errors carrying line and column. Full VoiceOver support, all backed by Swift Testing, XCTest, and XCUIAutomation suites with hermetic UI tests | Implementing standards-compliant parsing from scratch and shipping testable, accessible Apple-platform UI below the framework layer |
| **[Workout](https://github.com/OGSarah/Workout)** | A pure, deterministic domain core under a Swift 6 strict-concurrency UI. Protocol-based dependency injection over SwiftData. Swift Charts visualizations, all backed by 64 unit and UI tests | Safe concurrency, testable domain design, and Apple framework depth |
| **[QRCodeGen](https://github.com/OGSarah/QRCodeGen)** | A protocol-seam architecture with dependency injection over a Core Image generation pipeline. An off-main, Sendable generator under Swift 6 strict concurrency. Typed errors and SwiftData hidden behind protocols, all mock-tested without UIKit, Core Image, or disk | Testable architecture and Apple framework depth, zero third-party dependencies |
| **[Recipes](https://github.com/OGSarah/Recipes)** | @Observable MVVM behind protocol seams with init-injected dependencies. Swift 6 strict concurrency with off-main, Sendable networking and typed errors. A custom decoder that flattens TheMealDB's parallel ingredient fields. SwiftData favorites that render fully offline. Cached AsyncImage thumbnails over a shared URLCache. Full VoiceOver support, all backed by 31 unit and UI tests across Swift Testing, XCTest, and XCUIAutomation | Building accessible, offline-capable SwiftUI features on a testable, protocol-oriented core |
| **[Culinary-Catalog](https://github.com/OGSarah/Culinary-Catalog)** | MVVM with dependency injection over Core Data, an async/await networking layer, typed errors, and Swift Testing | Modern iOS architecture, structured concurrency, and test coverage |
| **[iOS-Architecture](https://github.com/OGSarah/iOS-Architecture)** | *(Work in progress)* A growing collection of small, standalone Xcode projects, one per architecture or design pattern (MVC, MVVM, VIPER, Coordinator, dependency injection, and more), each with its own README covering when to use it and its tradeoffs | A reference library I maintain for comparing architectural approaches side by side and keeping pattern fundamentals sharp |

**Stack:** Swift · Objective-C · SwiftUI · UIKit · AppKit · SwiftData · Core Data · Swift Charts · Core Image · Combine · Observation · HealthKit · CryptoKit · ActivityKit · MapKit

---

## ⚙️ Backend Engineer

Services, ingestion, and networking below the framework layer, from a from-scratch HTTP server to Go analytics pipelines and the data contracts behind shipped clients.

| Repo | What it demonstrates | How it maps to my work |
| --- | --- | --- |
| **[eCFRProject](https://github.com/OGSarah/eCFRProject)** | A Go service that ingests and analyzes federal regulation data, surfaced through a web dashboard | Backend ingestion and analytics, full stack ownership |
| **[HTTPServer](https://github.com/OGSarah/HTTPServer)** | A from-scratch HTTP/1.1 server in Swift 6 on raw Darwin sockets, no frameworks: request framing, routing, an actor-backed store, and strict-concurrency-clean structured concurrency | Low-level networking and safe concurrency below the framework layer |
| **[culinary-catalog-data](https://github.com/OGSarah/culinary-catalog-data)** | A zero-infrastructure JSON data service backing Culinary-Catalog: a single source of truth fanned out into versioned, schema-validated feeds, auto-published by a GitHub Actions pipeline | Owning the data contract and release automation behind a shipped client |

**Stack:** Go · Gin · C# · Java · Python · REST · GraphQL · WebSockets · Darwin/POSIX sockets · PostgreSQL · SQLite · Docker

---

## 🌐 Web Development

Responsive, accessible, fast web experiences built from scratch. I designed and built my portfolio site, [sarahuniverse.com](http://www.sarahuniverse.com), handling layout, animation, and styling in pure HTML and CSS.

**Stack:** HTML5 · CSS3 · JavaScript

---

## 🧰 Tech I work in

- **Languages:** Swift, Go, Objective-C, Python, Java, JavaScript, C#
- **Apple platforms:** iOS (incl. iOS 27), iPadOS, macOS, watchOS, visionOS
- **Frameworks:** SwiftUI, UIKit, AppKit, Core Data, SwiftData, Swift Charts, Core Image, WebKit, PhotosUI/Photos, UniformTypeIdentifiers, Combine, Observation, ActivityKit, HealthKit, CryptoKit, MapKit, Foundation Models, Vision
- **Concurrency:** async/await, Combine, Observation
- **Backend and APIs:** Go, Gin, REST, GraphQL, WebSockets, Darwin/POSIX sockets, PostgreSQL, SQLite
- **Web:** HTML5, CSS3, JavaScript
- **Quality and tooling:** Swift Testing, XCTest, XCUIAutomation, Appium, Selenium, SwiftLint, Fastlane, Jenkins, Xcode Cloud, GitHub Actions, TestFlight
- **Enterprise IT:** MDM, Active Directory, Exchange Server, PowerShell, Windows Server
- **AI:** Claude Code, GitHub Copilot, Cursor, Codex, Xcode Apple Intelligence

---

## Find me

- Portfolio: [sarahuniverse.com](http://www.sarahuniverse.com)
- Email: sarah@sarahuniverse.com
