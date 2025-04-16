1️⃣ SignOfIntegerNumber ➕➖
Namespace: _1_SignOfIntegerNumber
📌 Description:
Reads an integer and prints whether it is positive, negative, or zero.

📝 Code:
```csharp
int n = int.Parse(Console.ReadLine());

PrintSign(n);

static void PrintSign(int number)
{
    if (number < 0)
    {
        Console.WriteLine($"The number {number} is negative.");
    }
    else if (number > 0)
    {
        Console.WriteLine($"The number {number} is positive.");
    }
    else
    {
        Console.WriteLine($"The number {number} is zero.");
    }
}
```

2️⃣ Grades 📝
Namespace: _2_Grades
📌 Description:
Reads a double number and prints its description in words (Fail, Average, Good, Very good, Excellent).

📝 Code:
```csharp
double grade = double.Parse(Console.ReadLine());

PrintGradeInWord(grade);

static void PrintGradeInWord(double grade)
{
    string gradeInWords = "";

    switch (grade)
    {
        case >= 2 and <= 2.99:
            gradeInWords = "Fail";
            break;
        case >= 3 and <= 3.49:
            gradeInWords = "Average";
            break;
        case >= 3.50 and <= 4.49:
            gradeInWords = "Good";
            break;
        case >= 4.50 and <= 5.49:
            gradeInWords = "Very good";
            break;
        case >= 5.50 and <= 6.00:
            gradeInWords = "Excellent";
            break;
    }

    Console.WriteLine(gradeInWords);
}
```

3️⃣ PrintingTriangle 🔺
Namespace: _3_PrintingTriangle
📌 Description:
Reads an integer and prints a symmetrical triangle pattern with numbers.

📝 Code:
```csharp
int n = int.Parse(Console.ReadLine());

PrintTriange(n);

static void PrintTriange(int n)
{
    for (int row = 1; row < n; row++)
    {
        PrintLine(1, row);
    }

    for (int row = n; row >= 1; row--)
    {
        PrintLine(1, row);
    }
}

static void PrintLine(int start, int end)
{
    for (int i = start; i <= end; i++)
    {
        Console.Write($"{i} ");
    }
    Console.WriteLine();
}
```

📅 Updated Commit Progress:

📅 Current Progress: 386 commits
📊 Progress Bar:
███████████████████████████░ 77.2% (386/500)

📌 Milestones:
✅ 100 commits
✅ 200 commits
✅ 300 commits
🔲 400 commits
🔲 500 commits (🎉)
🎯 Commit Progress Tracker

🚀 Goal: 500 commits in 2025
📅 Current Progress: 386 commits
