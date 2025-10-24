# Conference Booking CLI APP

A simple command-line interface (CLI) application written in Go to manage ticket bookings for the "Go Conference." Users can book tickets by providing their name, email and number of tickets, with basic input validation and simulated email confirmation.

## Features
- Book tickets for the Go Conference (50 tickets total).
- Validates user input (name length, email format, ticket availability).
- Displays remaining tickets and booking details.
- Simulates sending a confirmation ticket via email (with a 10-second delay).
- Uses concurrency with Go routines for ticket sending.

## Prerequisites
- [Go](https://golang.org/dl/) (version 1.18 or later recommended).
- A terminal or command-line interface.

## Installation
1. Install the CLI using Go:
   
   ```bash
   go install github.com/parthava-adabala/booking-app@latest
   ```
3. Ensure `$GOPATH/bin` (or `$HOME/go/bin`) is in your system’s PATH to run the `booking-app` command.

## Usage
Run the CLI and follow the prompts to book tickets:
```bash
conference-booking
```
