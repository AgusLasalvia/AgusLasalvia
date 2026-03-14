```csharp

using System;
using System.Collections.Generic;

class Developer
{
    public string Name { get; set; }
    public int Age { get; set; }
    public List<string> Languages { get; set; }
    public string Role { get; set; }
    public string University { get; set; }
    public string Email { get; set; }
    public string LinkedIn { get; set; }
    public string Instagram { get; set; }
    public string Status { get; set; }

    public void Greet()
    {
        Console.WriteLine("Hello There! :)");
    }
}

class Program
{
    static void Main()
    {
        Developer agustin = new Developer
        {
            Name = "Agustin Lasalvia",
            Age = 24,
            Languages = new List<string> { "Spanish", "English" },
            Role = "Junior Developer",
            University = "ORT University",
            Email = "agus.blumenfeld13@gmail.com",
            LinkedIn = "https://www.linkedin.com/in/agustin-lasalvia",
            Instagram = "https://www.instagram.com/agustin.lasalvia",
            Status = "Searching for a Junior Developer Position"
        };

        agustin.Greet();
    }
}
