## Card Drop Rate Multiplier for Sky Force Reloaded

### **What Does This Mod Do?**

The **Card Drop Rate Multiplier** mod allows you to **adjust how often you receive cards** in **Sky Force Reloaded**. By modifying a simple setting in a configuration file, you can **increase or decrease the chances** of obtaining different cards during your gameplay experience.

### **Installation Instructions**

1. **Download the Mod:**
   
   - Visit the [Nexus Mods Page](#) or [Releases](https://github.com/RobThePCGuy/Card-Drop-Rate-Multiplier/releases) to download the **Card Drop Rate Multiplier** mod.

2. **Backup Existing File:**
   
   - Before extracting, backup the existing `Assembly-CSharp.dll` located at:
   
     ```
     Sky Force Reloaded/
     └── Sky Force Reloaded_Data/
         └── Managed/
             └── Assembly-CSharp.dll
     ```

3. **Extract the Files:**
   
   - Extract the contents of the mod archive to the game's root directory; overwrite existing files.

4. **Configure the Multiplier:**
   
   - Follow the **Configuration** steps below to set your desired multiplier.

5. **Launch the Game:**
   
   - Start **Sky Force Reloaded** and enjoy your customized card drop rates!

### **How to Configure the Drop Rates**

1. **Locate the Configuration File:**
   
   After installing the mod, navigate to the following directory in your game folder:

   ```
   Sky Force Reloaded/
   └── Sky Force Reloaded_Data/
       └── Managed/
           └── Mods/
               └── CardDropRateMultiplier/
                   └── config.json
   ```

2. **Open the `config.json` File:**
   
   - Use a text editor like **Notepad** to open the `config.json` file.
   - You will see a setting that looks like this:
     
     ```json
     {
         "Multiplier": 1
     }
     ```

3. **Adjust the Multiplier Value:**
   
   - **Multiplier = 1:** 
     - **What It Means:** The card drop rates remain **unchanged** from the game's original settings.
     - **Who Should Use It:** Perfect for players who want to **experience the game as intended** without any modifications to card drop frequencies.
   
   - **Multiplier > 1:** 
     - **What It Means:** **Increases** the probability of receiving cards.
     - **Example:** Setting the multiplier to `2` will **double** the chances of getting each card.
     - **Who Should Use It:** Ideal for players who want to **collect cards more quickly** and enjoy enhanced rewards.
   
   - **Max Multiplier = 10:** 
     - **What It Means:** **Max** amount of probability of receiving cards.
     - **Example:** Setting the multiplier to `10` will give the **max** amount of chances of getting each card.
     - **Who Should Use It:** Suitable for players seeking a **free ride** by making cards drop every time.

4. **Save and Apply:**
   
   - After setting your desired multiplier, **save** the `config.json` file.
   - **Restart** **Sky Force Reloaded** to apply the changes.

### **Troubleshooting**

- **Drop Rates Not Changing:**
  
  - **Check `config.json`:** Ensure that the multiplier value is set correctly and saved.
  - **Reinstall the Mod:** If issues persist, try reinstalling the mod and repeating the configuration steps.

- **Game Crashes or Errors:**
  
  - **Backup Restoration:** Restore the original `Assembly-CSharp.dll` from your backup.
  - **Verify File Paths:** Ensure that all mod files are placed in the correct directory.

### **Support and Feedback**

I strive to provide the best modding experience for **Sky Force Reloaded** players. If you encounter any issues, have suggestions, or need assistance, please visit my [GitHub](https://github.com/RobThePCGuy/Card-Drop-Rate-Multiplier) to open an issue, or the [Nexus Mods Page](#) and leave a comment.
