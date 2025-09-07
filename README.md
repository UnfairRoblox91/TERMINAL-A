# Terminal-A

Dynamic console application that lets you create, and execute custom commands on spot.

---

## Getting Started

1. **Download Terminal-A**  

   You can download the latest release [here]([#](https://github.com/UnfairRoblox91/TERMINAL-A/blob/main/TERMINAL-A.zip))

2. **Run the application**  

   Double-click `Terminal-A.exe` to launch the terminal.  

3. **Add commands**  

   - Place any JSON command files in the `commands` folder.  
   - Each JSON file must contain:  
     ```json
     {
       "FunctionName": "yourCommand",
       "Description": "What the command does",
       "Code": "C# code to execute, use Arg for input"
     }
     ```  

4. **Use commands**  

   - Type a command name and press Enter to execute it.  
   - Special commands:  
     - `help` — show all available commands  
     - `exit` — quit the terminal  

---

## License

MIT License – see [LICENSE](LICENSE) for details.

---
