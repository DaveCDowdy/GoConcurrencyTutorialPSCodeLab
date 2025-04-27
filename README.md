# GoConcurrencyTutorialPSCodeLab
This repository contains code from a Pluralsight Code Lab exercise focused on learning concurrency in Go.
It serves as a hands-on project to practice key Go concurrency concepts like goroutines, channels, and synchronization techniques.

📚 About
The exercises and code in this project were built while following the Go Concurrency tutorial on Pluralsight.
It covers:

Spawning and managing goroutines

Communicating between goroutines using channels

Using buffered channels

Synchronizing goroutines with sync.WaitGroup

Best practices for safe concurrent programming in Go

The project is structured to show incremental learning, with code examples for each major concept.

🚀 Getting Started
To run the examples:

Make sure you have Go installed (version 1.16 or later recommended).

Clone this repository:

bash
Copy
Edit
git clone https://github.com/DaveCDowdy/GoConcurrencyTutorialPSCodeLab.git
cd GoConcurrencyTutorialPSCodeLab
Run individual .go files to test out concepts:

bash
Copy
Edit
go run filename.go
Each file is generally standalone and demonstrates a specific concurrency technique.

🛠️ Topics Covered
Goroutines — Lightweight threads managed by Go runtime.

Channels — Safe communication between goroutines.

Buffered Channels — Controlling flow with buffered messages.

WaitGroups — Synchronizing multiple concurrent operations.

Select Statement — Waiting on multiple channel operations.

📂 Structure
goroutines.go — Basic example of concurrent execution

channels.go — Sending and receiving data between goroutines

buffered_channels.go — Using buffered channels

waitgroups.go — Waiting for concurrent processes to complete

(Additional files based on exercises)

🧠 Why Concurrency?
Concurrency is a powerful feature in Go, making it easier to build scalable, efficient software.
This project demonstrates the core ideas that allow developers to write fast, concurrent programs without the complexity seen in other languages.
