## Beep boop, welcome! 🤖

```csharp
using System;
					
public class GreetingRobot
{
	public string greeting = "Hi there!";
	
    public void Robot()
    {        
        Console.WriteLine("Beep boop, " + greeting + "🤖");
    }
}

public class Introduction : GreetingRobot
{
    public Introduction()
	{
    	greeting = "I am Yena Choi!";
	}
}

public class Program
{
    public static void Main()
    {
        GreetingRobot hi = new GreetingRobot();
        hi.Robot();
        Introduction name = new Introduction();
        name.Robot();
    }
}
```

<!--
**iamyenachoi/iamyenachoi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

[![YENA's GitHub stats](https://github-readme-stats.vercel.app/api?username=iamyenachoi&show_icons=true&theme=catppuccin_mocha&count_private=true)](https://github.com/anuraghazra/github-readme-stats)

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fiamyenachoi%2Fhit-counter&count_bg=%2379E5CB&title_bg=%23555555&icon=github.svg&icon_color=%23FEFEFE&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
