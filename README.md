<img width="1920" height="1019" alt="image" src="https://github.com/user-attachments/assets/e0ec6508-6320-4f2c-866a-48c8b4429d9e" />


# Game Script — README

> A small helper script to automate/augment the game.  
> Two versions: **desktop** (paste into the browser console) and **mobile** (saved as a bookmarklet).

---

## 📁 Files

| File | Platform | How to use |
| :--- | :--- | :--- |
| `desktop_script.js` | Desktop (Chrome / Firefox / Edge) | Paste into DevTools Console |
| `mobile_script.js` | Mobile (Chrome on Android) | Save as a bookmarklet |

---

## 🖥️ Desktop — Paste into Console

1. Open the game in your browser and wait for the **menu** to load *(don't start the fight yet)*.
2. Open DevTools:
   - **Windows / Linux:** `Ctrl` + `Shift` + `J`
   - **macOS:** `Cmd` + `Option` + `J`
   - *Or right-click → **Inspect** → **Console** tab.*
3. Open `desktop_script.js`, select **all** of it, and copy.
4. Paste it into the Console and press **Enter**.
5. Start the fight.
6. **After every page reload**, repeat steps 2–4 *(the script only runs on the current page)*.

> [!WARNING]
> If Chrome blocks pasting with a warning *("Don't paste code you don't understand")*, type `allow pasting` in the console and press `Enter`, then paste again.

---

## 📱 Mobile — Bookmarklet (Chrome on Android)

1. Open the game and **bookmark any page** *(tap the ⋮ menu → ☆)*.
2. Edit that bookmark:
   - Set the **Name** to exactly `fgscript` *(no extra spaces)*.
   - Set the **URL** to the full contents of `mobile_script.js` *(it must start with `javascript:`)*.
   - Save.
3. Open the game and wait for the **menu** *(don't start the fight yet)*.
4. Tap the **address bar**, type `fgscript`, and tap the **bookmark suggestion** *(the one with a star icon)* — **don't press Enter/Search**.
5. The script runs. Now start the fight.
6. **After every page reload**, repeat steps 4–5.

### ❓ If `fgscript` doesn't show up in the address bar

- [ ] Make sure the bookmark **name** is exactly `fgscript`.
- [ ] Look in the suggestion list for the entry with a **star icon** — don't tap the Google search suggestion.
- [ ] Make sure the URL begins with `javascript:` *(no leading space or line break)*.
- [ ] If it still fails, delete the bookmark and create it again from scratch.

---

## 🔁 Important: Re-run After Every Reload

> [!IMPORTANT]
> Both scripts only affect the **current page**.  
> Once the page reloads, you must **run the script again**.

| Platform | Re-run action |
| :--- | :--- |
| **Desktop** | Paste the script into the Console again |
| **Mobile** | Tap the address bar → type `fgx123script` → tap the bookmark suggestion |

---

## ⚠️ Disclaimer

> [!CAUTION]
> Use at your own risk. Automating a game may violate its Terms of Service.  
> The author is not responsible for any account bans, data loss, or other consequences.
