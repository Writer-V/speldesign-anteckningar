#C-Sharp #teach/CJ-Gribel #Period1-class
Git stuff introduced, but only via *GitHub Desktop*. Then setting up *VS Code* and running *Hello World*.

Work in progress...
```cs
using System.Text;

namespace HangmanDemo
{
	internal class Program	
	{
		static void Main(string[] args)
		{
			const string secretWord = "hangman";
			string displayWord = new string('_', secretWord.Length);
			int attemptsLeft = 6;
			
			Console.WriteLine("Hello, World!");
			Console.WriteLine("Bye");
		}
	}
}
```
