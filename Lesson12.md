Vibe Coding class material
Status: In progress Due date: 06/17/2025 ID: 27 💼 Projects: VTX - Cohort 3 (https://www.notion.so/VTX-Cohort-3-1fa35af00755802fbdf0ec5d149f2c52?pvs=21)
iOS app Vibe Coding
Software required
	•	XCode
	•	XCode Simulator
	•	https://www.cursor.com/
	•	https://brew.sh/
	•	Cursor setup reference
	•	https://dimillian.medium.com/how-to-use-cursor-for-ios-development-54b912c23941

brew install xcode-build-server

brew install xcbeautify

brew install swiftformat

# Sweetpad: Generate Build Server Config

Outline
Environment Setup
	•	Create new project using XCode
	•	Ensure iOS simulator is properly installed
	•	Cursor extension setup
	•	Try to run the project in Cursor
How to ‘teach’ Cursor
	•	Project documentation
	•	Cursor Rules
	•	Pick the right template https://cursor.directory/rules
	•	SwiftUI https://cursor.directory/swiftui-swift-simple-developer-cursor-rules
	•	Documentation
Learning what you’re doing before start
	•	App development process
	•	Low fidelity UI (wireframe)
	•	High fidelity design
	•	UX
	•	Component design
	•	Screen implementation
	•	Software Architecture
	•	https://medium.com/learn-record/mvc-mvp-mvvm%E6%9E%B6%E6%A7%8B%E6%AF%94%E8%BC%83-62b5657d2e21
	•	https://developer.apple.com/documentation/swift/choosing-between-structures-and-classes
	•	https://developer.apple.com/design/human-interface-guidelines
	•	Custom guidelines
	•	iOS version and XCode version
	•	Apple Framework
	•	Project Management
	•	Info.plist
	•	Platform
	•	Minimum iOS version

  You are an expert iOS developer using Swift and SwiftUI. Follow these guidelines:

  # Code Structure

  - Use Swift's latest features and protocol-oriented programming

  - Prefer value types (structs) over classes

  - Use MVVM architecture with SwiftUI

  - Structure: Features/, Core/, UI/, Resources/

  - Follow Apple's Human Interface Guidelines

  

  # Naming

  - camelCase for vars/funcs, PascalCase for types

  - Verbs for methods (fetchData)

  - Boolean: use is/has/should prefixes

  - Clear, descriptive names following Apple style

  # Swift Best Practices

  - Strong type system, proper optionals

  - async/await for concurrency

  - Result type for errors

  - @Published, @StateObject for state

  - Prefer let over var

  - Protocol extensions for shared code

  # UI Development

  - SwiftUI first, UIKit when needed

  - SF Symbols for icons

  - Support dark mode, dynamic type

  - SafeArea and GeometryReader for layout

  - Handle all screen sizes and orientations

  - Implement proper keyboard handling

  # Performance

  - Profile with Instruments

  - Lazy load views and images

  - Optimize network requests

  - Background task handling

  - Proper state management

  - Memory management

  # Data & State

  - CoreData for complex models

  - UserDefaults for preferences

  - Combine for reactive code

  - Clean data flow architecture

  - Proper dependency injection

  - Handle state restoration

  # Security

  - Encrypt sensitive data

  - Use Keychain securely

  - Certificate pinning

  - Biometric auth when needed

  - App Transport Security

  - Input validation

  # Testing & Quality

  - XCTest for unit tests

  - XCUITest for UI tests

  - Test common user flows

  - Performance testing

  - Error scenarios

  - Accessibility testing

  # Essential Features

  - Deep linking support

  - Push notifications

  - Background tasks

  - Localization

  - Error handling

  - Analytics/logging

  # Development Process

  - Use SwiftUI previews

  - Git branching strategy

  - Code review process

  - CI/CD pipeline

  - Documentation

  - Unit test coverage

  # App Store Guidelines

  - Privacy descriptions

  - App capabilities

  - In-app purchases

  - Review guidelines

  - App thinning

  - Proper signing

  Follow Apple's documentation for detailed implementation guidance.

  
SwiftUI Fundamentals
	•	View
	•	Stack
	•	SwiftUI vs. UIKit
	•	CoreData vs SwiftData
	•	Apple Framework: https://developer.apple.com/documentation/
General Development Guideline
	•	Always do UI mockup first, do not implement any code logic until all UI are ready
	•	Always think about the data model when doing UI
	•	Compare data model with corresponding framework data type
	•	Pick the most valuable user journey to implement
	•	Use Mobbin to generate UI idea https://mobbin.com/discover/apps/ios/latest
Prompt Engineering Guideline
	•	General
	•	Prepare project.md
	•	For short term plan, e.g. cleanup, prepare a separate cleanup.md
	•	Talk to Cursor as if he’s working on the same project with you
	•	Discuss and plan on what to do before doing, add do not make code change yet
	•	Provide @docs and @web when discussing on solutions. Reminds Cursor about following best practice
	•	When implement code change, ask to break down in multi-steps
	•	Remind him there is cursor rules to follow
	•	Provide documentation on finding solution
	•	Debugging
	•	How Cursor debug? ⭐
	•	Provide screenshots when debugging
	•	Provide console output when debugging
	•	Add console output for debugging purpose
	•	Code quality
	•	Occasionally ask for clean up and refactoring, usually in actual implementation stage
	•	Watch closely how the code is being implemented, especially whether it complies with MVVM
	•	Question implementation approach when in doubt and request for evidence
	•	Learn along the way ⭐
Reference
https://www.youtube.com/@seanallen

https://www.youtube.com/@ChaoCode

https://youtube.com/playlist?list=PL8h9yRGN7VETh72--p-AUbDNbuk_vTtD9&si=8ySTG5PR6qVbE2-z

