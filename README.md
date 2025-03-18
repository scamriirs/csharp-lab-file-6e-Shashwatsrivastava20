using system;

public class Person
{
    private string _name;
    private int _age;

    public string Name
    {
        get { return _name; }
    }

    public int Age
    {
        set { _age = value; }
    }

    public string FullName
    {
        get { return _name; }
        set { _name = value; }
    }
}

class Program
{
    static void Main()
    {
        Person person = new Person();

        person.FullName = "John Doe";
        Console.WriteLine(person.FullName);

        person.Age = 30;
    }
}
