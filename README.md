# Hi, I'm Sarah 👋🏻👩🏼‍💻

**Full Stack Software Engineer** with 10+ years building secure, scalable software at enterprise scale, including five years on backend services, APIs, and full-stack delivery, alongside a decade of polished, accessible Apple-platform work. I'm equally at home in a Postgres transaction, a raw socket, and a SwiftUI view.

I own features end to end, across the whole stack, from backend services and networking to polished client UI. Most of my production work lives in private enterprise codebases, so it can't be public. The repos below are where I keep my skills sharp across Go, Swift, and the web, work with the latest frameworks and tools, and explore the layers beneath the UI. **Read them as working samples, not the full scope of what I've shipped.**

---

## 🧵 Featured Project

**[Weaver](https://github.com/OGSarah/Weaver)** is a DAG-based job scheduler and workflow orchestrator in Go with a React UI, built as a small, readable take on the ideas behind Airflow and Temporal.

- DFS cycle detection and topological scheduling over a **Postgres-backed queue with no broker**, where claims use `SELECT ... FOR UPDATE SKIP LOCKED` so a task goes to one worker at a time
- At-least-once execution with heartbeat leases, and reaper recovery of tasks orphaned by dead workers
- Cron scheduling that backfills every missed slot exactly once, plus retries with exponential backoff, jitter, and per-task timeouts
- A React DAG view with live run status, per-attempt logs, and run history over a REST API
- Runnable end to end via Docker Compose, backed by 88 tests including integration tests against a real Postgres instance in CI

Built with Go · Postgres · React · Docker · REST · JavaScript

---

## 🚀 Shipped to the App Store

**[TossTracker](https://apps.apple.com/app/tosstracker/id6758673916)** is a cornhole scoring app I designed, built, and published to the App Store on my own.

- Automatic cancellation scoring, round management, and turn order, with resumable in-progress games
- Every completed match saved with full team, score, and date detail, searchable and filterable, with CSV export and sharing
- Full VoiceOver support with labels and hints throughout, independent light and dark mode, and landscape support
- In-app rules reference, optional sounds and haptics, and a confetti finish

Source is private, but it's the clearest example of my work taken all the way from idea to a released, accessible, polished product.

---

## 🥞 Full Stack Engineer

End-to-end ownership of clients and the backends they talk to, with clean API contracts and resilience in between. Weaver, above, is the fullest example.

| Repo | What it demonstrates | How it maps to my work |
| --- | --- | --- |
| **[eCFRProject](https://github.com/OGSarah/eCFRProject)** | A Go service that ingests and analyzes federal regulation data, surfaced through a web dashboard | Backend ingestion and analytics with the UI on top, full stack ownership |
| **[Calculator](https://github.com/OGSarah/Calculator)** | MVVM over a protocol-driven service layer with dependency injection. SwiftData persistence syncing to a Go + SQLite backend on background, with an offline retry queue. Unit, UI, and backend test coverage | Owning testable, resilient architecture across a SwiftUI client and its backend |

Built with Go · React · Postgres · SQLite · REST · Docker · JavaScript · Swift · SwiftUI · SwiftData

---

## ⚙️ Backend Engineer

Services, ingestion, and networking below the framework layer, from a from-scratch HTTP server to Go analytics pipelines and the data contracts behind shipped clients.

| Repo | What it demonstrates | How it maps to my work |
| --- | --- | --- |
| **[HTTPServer](https://github.com/OGSarah/HTTPServer)** | A from-scratch HTTP/1.1 server in Swift 6 on raw Darwin sockets with no frameworks, handling its own request framing and routing over an actor-backed store, strict-concurrency-clean throughout | Low-level networking and safe concurrency below the framework layer |
| **[culinary-catalog-data](https://github.com/OGSarah/culinary-catalog-data)** | A zero-infrastructure JSON data service backing Culinary-Catalog, built as a single source of truth fanned out into versioned, schema-validated feeds, auto-published by a GitHub Actions pipeline | Owning the data contract and release automation behind a shipped client |

Built with Go · Gin · C# · Java · Python · REST · GraphQL · WebSockets · Darwin/POSIX sockets · PostgreSQL · SQLite · Docker

---

## 📱 iOS & Apple Platform Engineer

Accessible, offline-capable, testable apps built on protocol-oriented cores under Swift 6 strict concurrency, across iOS, iPadOS, macOS, watchOS, and visionOS.

| Repo | What it demonstrates | How it maps to my work |
| --- | --- | --- |
| **[JSONParser](https://github.com/OGSarah/JSONParser)** | A native macOS app with a hand-written RFC 8259 JSON parser. A custom lexer and recursive descent parser, no `Foundation` `JSONSerialization`. `@Observable` MVVM behind `JSONParsing` and `PasteboardReading` protocol seams. `nonisolated`, thread-agnostic parsing under Swift 6 strict concurrency. AppKit (`NSTextView`) interop for a syntax-highlighting editor. Typed errors carrying line and column. Full VoiceOver support, all backed by Swift Testing, XCTest, and XCUIAutomation suites with hermetic UI tests | Implementing standards-compliant parsing from scratch and shipping testable, accessible Apple-platform UI below the framework layer |
| **[Workout](https://github.com/OGSarah/Workout)** | A pure, deterministic domain core under a Swift 6 strict-concurrency UI. Protocol-based dependency injection over SwiftData. Swift Charts visualizations, all backed by 64 unit and UI tests | Safe concurrency, testable domain design, and Apple framework depth |
| **[QRCodeGen](https://github.com/OGSarah/QRCodeGen)** | A protocol-seam architecture with dependency injection over a Core Image generation pipeline. An off-main, Sendable generator under Swift 6 strict concurrency. Typed errors and SwiftData hidden behind protocols, all mock-tested without UIKit, Core Image, or disk | Testable architecture and Apple framework depth, zero third-party dependencies |
| **[Recipes](https://github.com/OGSarah/Recipes)** | @Observable MVVM behind protocol seams with init-injected dependencies. Swift 6 strict concurrency with off-main, Sendable networking and typed errors. A custom decoder that flattens TheMealDB's parallel ingredient fields. SwiftData favorites that render fully offline. Cached AsyncImage thumbnails over a shared URLCache. Full VoiceOver support, all backed by 31 unit and UI tests across Swift Testing, XCTest, and XCUIAutomation | Building accessible, offline-capable SwiftUI features on a testable, protocol-oriented core |
| **[Culinary-Catalog](https://github.com/OGSarah/Culinary-Catalog)** | MVVM with dependency injection over Core Data, an async/await networking layer, typed errors, and Swift Testing | Modern iOS architecture, structured concurrency, and test coverage |
| **[iOS-Architecture](https://github.com/OGSarah/iOS-Architecture)** | A growing collection of small, standalone Xcode projects, one per architecture or design pattern (MVC, MVVM, VIPER, Coordinator, dependency injection, and more), each with its own README covering when to use it and its tradeoffs | A reference library I maintain for comparing architectural approaches side by side and keeping pattern fundamentals sharp |

Built with Swift · Objective-C · SwiftUI · UIKit · AppKit · SwiftData · Core Data · Swift Charts · Core Image · Combine · Observation · HealthKit · CryptoKit · ActivityKit · MapKit

---

## 🧰 Tech I work in

| Area | Tools |
| --- | --- |
| Languages | Go, Swift, TypeScript, JavaScript, Python, Java, C#, Objective-C |
| Backend and APIs | Go, Gin, REST, GraphQL, WebSockets, Darwin/POSIX sockets, PostgreSQL, SQLite |
| Web | React, HTML5, CSS3, JavaScript |
| Apple platforms | iOS (incl. iOS 27), iPadOS, macOS, watchOS, visionOS |
| Frameworks | SwiftUI, UIKit, AppKit, Core Data, SwiftData, Swift Charts, Core Image, WebKit, PhotosUI/Photos, Combine, Observation, ActivityKit, HealthKit, CryptoKit, MapKit, Core Location, Foundation Models, Vision, Async/Await, Core Graphics, RESTful APIs / URLSession, AVFoundation, WidgetKit |
| Testing, CI/CD, and Tooling | Swift Testing, XCTest, XCUIAutomation, Appium, Selenium, SwiftLint, Fastlane, Jenkins, Xcode Cloud, GitHub Actions, TestFlight, Docker, Docker Compose |
| AI | Claude Code, GitHub Copilot, Cursor, Codex, Xcode Apple Intelligence |

---

## Find me

- Portfolio at [sarahuniverse.com](https://www.sarahuniverse.com)
- Reach me at sarah@sarahuniverse.com
