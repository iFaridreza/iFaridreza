```cs
// Hello World :)   
internal class Profile
{
    internal string FirstName { get; }
    internal string LastName { get; }
    internal int YearBirth { get; }
    internal int MonthBirth { get; }
    internal int DayBirth { get; }
    internal string Contry { get; }
    internal string City { get; }
    internal string About { get; }
    internal List<string> Skills { get; }

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