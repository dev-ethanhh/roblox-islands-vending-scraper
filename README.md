### Quick explanation
<hr> 
This program, when injected into Roblox using a proper executor, scans the entire workspace for vending machines.

For each vending machine, it extracts:
- The listed item
- Whether the machine is in Selling, Buying, or Inactive mode
- The item price

All this data is saved into a CSV file.
A separate Python script then organizes both the new and old scan data in alphabetical order.

After scanning a few shop islands, you’ll end up with a large CSV file (like the example one in this repo, though it's a bit outdated), showing the current state of the market, super useful for setting your own prices accurately.

*I didn’t make this script to exploit the game, but simply to save time. Manually checking each vending machine, often over 500 per island, is extremely tedious, so I made this tool to automate the process.*

If you need help:
- The script was originally made using Synapse X, which is now discontinued.
- The game probably hasn’t changed much, but you might need to tweak a few things depending on your executor. Nothing too complex.

If you're really stuck, feel free to contact me, my email is in my profile.
