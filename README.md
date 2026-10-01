# Hello there 👋

```csharp
using System;
using System.Collections.Generic;

public class Person
{
    public string Nickname = "Korgie";
    public int Age = 17;
    public string HomeCountry = "Czech Republic";
    private string CurrentlyStudying = "High School";
    public string OS = "Linux (Fedora)";
    
    public Dictionary<string, string[]> Languages = new()
    {
        ["Human"] = ["Czech (Native)", "English (B2+)", "Japanese (In progress)"],
        ["Computer"] = ["C#", "Python (Familiar)"]
    };
    
    public string[] Hobbies = 
    [ 
        "Reading (Witcher, Wheel of Time)", 
        "Programming (Backend, Algorithms)",
        "Learning languages",
		"Nature",
        "Logical thinking and learning new exciting things" 
    ];

    public void ExecuteIntroduction()
    {
        Console.WriteLine("I bid thee welcome to my humble abode, and hope thou wilt enjoy thy stay.");
    }
}

Person me = new();
me.ExecuteIntroduction();
````

<details>
<summary>More stuff about me</summary>

## What I do

I explore all sorts of technology, from hardware to software engineering. My main focus is heavily backend-oriented — ranging from web APIs and network security to complex algorithms. I genuinely enjoy learning and experimenting across different IT fields. Outside of tech, you'll usually find me reading books or studying new languages.

## My Skills

### Knowledge

- C# .NET
    - PostgreSQL
    - REST APIs
    - SignalR (WebSockets)
- C (Basic & Embedded)
- Python (Familiar)
- Microcontrollers (STM32, Arduino — experience)

### Tools

- Visual Studio Code
- Linux & Git
- Unity
- FreeCAD & PrusaSlicer
- Blender (Basic)
- Obsidian

### Languages

| **Language**  | **Proficiency**     |
| ------------- | ------------------- |
| English (duh) | B2+ (non-certified) |
| Czech         | Native language     |
| Japanese      | A1 (learning)       |

## How to reach me

- **For important stuff:** [ajavtel@gmail.com](mailto:ajavtel@gmail.com)
- **Wanna chat?** Discord: `korgie8`

<p align="center">
  <sup><small><em>As a reward for scrolling this deep, here is a quote: "Life is like a trash can: It might be full of shit, but when you hit the bottom, you discover all the hidden treasures."</em></small></sup>
</p>

</details>
