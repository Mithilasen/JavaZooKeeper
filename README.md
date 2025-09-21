Zoo Viewer (Console)

A tiny Java console app that lets you “switch on” cameras for different animal habitats (camel, lion, deer, goose, bat, rabbit) and display ASCII-art scenes. Type a habitat number (0–5) to view it; type exit to quit.

✨ Features

Simple CLI with prompt loop (while) until user types exit

Uses Java text blocks ("""...""") for neat multi-line ASCII art

Input validation via equals (no != for strings)

Clean separation of data (animals[]) and logic (prompt/loop)

🚀 Run it

Requirements: Java 17+ (text blocks)

Enter a number (e.g., 3) to print that animal. Enter exit to finish.
At the end you’ll see: See you later!

🧠 How it works (quick tour)

Animal scenes are stored as six String text blocks.

They’re collected into String[] animals.

The program prompts once, then loops:

If the input is "exit" → break and print goodbye.

Otherwise Integer.parseInt(input) → print animals[index], prompt again.



