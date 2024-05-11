```cs
// Hello World :)   

internal class Profile
{
    internal string FirstName { get; set; }
    internal string LastName { get; set; }
    internal int YearBirth { get; set; }
    internal int MonthBirth { get; set; }
    internal int DayBirth { get; set; }
    internal string Contry { get; set; }
    internal string City { get; set; }
    internal string About { get; set; }
    internal List<string> Skills { get; set; }

    internal Profile()
    {
        FirstName = "Faridreza";
        LastName = "Bidkham";
        YearBirth = 1382;
        MonthBirth = 05;
        DayBirth = 28;
        Contry = "Iran";
        City = "Mashhad";
        About = "Junior Backend Programmer , Love Open Source";
        Skills = new()
        {
            "CSharp",
            "Python",
            "ASP.NET [ Razor Pages , MVC ]",
            "Data Base [ Sql Server , Sqlite ]",
            "Telegram Bot [ Cli , Api ]",
            "Git"
        };
    }
}

```