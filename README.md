## Hello there 👋

```csharp
using System;
using System.Collections.Generic;

public class Person
{
    public string Nickname = "Korgie";
    public int Age = 17;
    public string HomeCountry = "Czech Republic";
    private string CurrentlyStudying = "High School";
    
    public Dictionary<string, string[]> Languages = new()
    {
		["Human"] = ["Czech (Native)", "English (B2+)", "Japanese (In progress)"],
        ["Computer"] = ["C#", "Somewhat Python"]
    };
    
    public string[] Hobbies = 
    [ 
        "Reading (Witcher, Wheel of Time)", 
        "Programming (Backend, Algorithms)",
        "Learning languages (Japanese)",
        "Logical thinking and learning new exciting things." 
    ];

    public void ExecuteIntroduction()
    {
        Console.WriteLine("I gladly welcome thee to my humble abode, and hope thou wilt enjoy thy stay.");
    }
}

Person me = new();
me.ExecuteIntroduction();

```
<!--
**Korgie8/korgie8** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
