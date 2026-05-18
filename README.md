# 🌤️ Weather-API

**Primitive / Simple** C# Windows Forms application for fetching and displaying current weather data.

---

## 📁 Project Structure

```bash
Weather-API/
├── Pogoda/                             # Main Project Folder
│   ├── Form1.cs                        # Main Windows Form
│   ├── Form1.Designer.cs
│   ├── Form1.resx
│   ├── JObject.cs                      # JSON handling
│   ├── Program.cs                      # Application entry point
│   └── Pogoda.csproj                   # Project File
│
├── Pogoda.sln                          # Visual Studio Solution
├── .gitignore
├── .gitattributes
└── README.md
```
## ✨ Features

* Fetching weather data from API
* Simple graphical user interface (WinForms)
* JSON response processing
* Basic weather information display


## 🛠 Technologies

* C#
* Windows Forms (WinForms)
* JSON parsing
* API integration


## ▶️ How to Run
1. Clone the repository
```
clone https://github.com/Izikini/Weather-API.git
cd Weather-API
```
2. Run the application
Recommended way (Visual Studio):

Open Pogoda.sln in Visual Studio
Press F5 or click Start button

### Alternative way (via .NET CLI):
```
cd Pogoda
dotnet restore
dotnet run
```

## 🎯 Purpose
* A primitive educational project created to learn:
* Working with external APIs
* JSON data processing in C#
* Building simple desktop applications with WinForms
