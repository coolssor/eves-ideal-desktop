> [!IMPORTANT]
> - **Plaintext:** Regular entry
> - **[Square brackets]:** User-interactable entry

# Games

**Shortcut:** Super + G

## Sections
- **\[Search\]**
    - Give textbox immediately, show suggestions below
    - Search by name or genre
        - Installed games show `✓`
        - Uninstalled games show no icon
    - Suggestions based on:
        - Genre (Shooter, RPG, puzzle, etc)
        - Setting (Sci-fi, fantasy, historical, etc)
        - Length (Short, medium, long, specific time)
            - Based on HowLongToBeat API
        - Popularity (Trending, top rated)
        - APIs:
            - IGDB
            - HowLongToBeat
    - Shortcuts:
        - **Descending (Z-A):** CTRL + PgDn
        - **Ascending (A-Z):** CTRL + PgUp

- **Launchers**
    - Steam
    - Lutris
    - Heroic Games Launcher
    - Bottles
    - Native Linux games

- **Installed games**
    - List of all installed games
    - Display game details:
        - Cover art
        - Description
        - Playtime tracking
        - Achievements
        - Launch options (native, via launcher, custom arguments)
        - Add to favorites
    - Shortcuts:
        - **Descending (Z-A, highest to lowest playtime, newest to oldest played, newest to oldest installed):** CTRL + PgDn
        - **Ascending (A-Z, lowest to highest playtime, oldest to newest played, oldest to newest installed):** CTRL + PgUp

- **Settings**
    - See [/Launcher/Settings/README.md](/Launcher/Settings/README.md)

## Example user flows

- **Check if a game is installed, and open its menu entry**  
    1. Press **Super + G**
    2. Select **\[Search\]**
    3. Type the name of the game
    4. Select the 1st option (shows `✓`)
    5. Select Launch or other menus.

- **Track achievements:**  
    1. Press **Super + G**
    2. Select **Installed games**
    3. Select the game
    2. Select **Achievements**

- **Discover new games:**  
    1. Press **Super**
    2. Select **Games**
    3. Select **\[Search\]**
    4. Filter by "Short" length and "Puzzle" genre
    5. Browse results.