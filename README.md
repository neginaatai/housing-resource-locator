# Housing Resource Locator
## Overview

The Housing Resource Locator is a desktop application designed to help Chicago residents find affordable housing resources and support services in their area. Users can search for housing assistance programs, shelters, and community resources by zip code or browse all available options across the city.

This application was built to address the need for accessible, centralized information about housing resources, making it easier for individuals and families to connect with the help they need.

## Purpose

Finding housing assistance can be challenging, especially when information is scattered across multiple websites and organizations. This tool consolidates housing resource data into a single, easy-to-use desktop application that:

- **Simplifies the search process** - Quick zip code lookup
- **Provides comprehensive information** - Contact details, services offered, and locations
- **Works offline** - All data stored locally in SQLite database
- **Runs anywhere** - Cross-platform support for Windows, macOS, and Linux


## Demo
<img width="500" height="400" alt="Screenshot 2025-12-03 at 11 16 37 AM" src="https://github.com/user-attachments/assets/965329f9-5ab0-422e-95f0-45d32896ef0a" />


*Search for housing resources by zip code*

<img width="500" height="400" alt="Screenshot 2025-12-03 at 11 15 08 AM" src="https://github.com/user-attachments/assets/731bad52-c191-4bd3-832f-4e74723facd2" />

## Features
- 🔍 **Zip Code Search** - Find resources in specific Chicago neighborhoods
- 📋 **View All Resources** - Browse complete database of housing services
- 📞 **Contact Information** - Phone numbers and addresses for each resource
- 🏷️ **Categorized Services** - Resources organized by type (shelters, housing assistance, etc.)
- 💾 **Local Database** - Fast, reliable SQLite storage

## Technologies Used
- **C# / .NET 8.0** - Application framework
- **Avalonia UI** - Cross-platform desktop UI framework
- **SQLite** - Lightweight database for resource storage
- **Microsoft.Data.Sqlite** - Database connectivity

### Prerequisites
- .NET 8.0 SDK or later

### Steps
1. Clone the repository:
```bash
   git clone https://github.com/neginaatai/HousingResourceLocator.git
   cd HousingResourceLocator/HousingResourceUI
```

2. Run the application:
```bash
   dotnet run
```

## Future Enhancements
- Add mapping/GPS integration to show resource locations
- Include real-time availability status
- Expand to other cities beyond Chicago
- Add filtering by service type
- Implement favorites/bookmarking feature


