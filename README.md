## So you want to enhance your FixyText experience?
FixyText has a diverse range of problems that frustrate people, and it's time that some of them are addressed. However, rather than completely remolding the game like many wish, I've only added settings to solve the most simple problems prevalent in FixyText. These being some all new balancing and character limit settings! Let me walk you through...

# Balancing Settings
## Uneven Favourite Balancing
This setting allows you to configure the favourite vote multiplier that the larger group of a FixyText game receives when the groups are uneven sizes. Its options are as follows:
| Option | Description |
| --- | --- |
| 1.5x | Applies a flat 1.5x multiplier to favourite votes given to the larger group, if applicable. The default behaviour. |
| 1.333 (reccuring)x | Applies a flat 1.333 (reccuring)x multiplier to favourite votes given to the larger group, if applicable. |
| Dynamic | Applies a multiplier to favourite votes given to the larger group depending on the size of both groups, if applicable. |
| None | Favourite vote value remains the same across both groups. |

## Uneven Co-author Balancing
This operates in much the same way as the previous setting, but applies to co-author bonuses instead. Its options are as follows:
| Option | Description |
| --- | --- |
| 1.5x | Applies a flat 1.5x multiplier to co-author bonuses given to the larger group, if applicable. |
| 1.333 (reccuring)x | Applies a flat 1.333 (reccuring)x multiplier to co-author bonuses given to the larger group, if applicable. |
| Dynamic | Applies a multiplier to co-author bonuses given to the larger group depending on the total number of players, if applicable. |
| None | Co-author bonus remains the same across both groups. The default behaviour. |

# Character Limit Settings
## Character Limit Determiner
This allows you to configure how the character limit for each global text box in a round is distributed among the currently writing players. Its options are as follows:
| Option | Description |
| --- | --- |
| Sum | Character limit per player is determined by a sum integer that is divided by the number of players in a group. The default option. |
| Individial | Character limit per player is based off a static integer referenced in the **Individual Determiner Character Limit** setting below, regardless of the number of players in a group. |

## Sum Determiner Character Limit
If Character Limit Determiner is set to Sum, sets the total sum character limit to this number. 320 is the default. Its options are as follows:
- 215
- 320
- 460
- 650
- 663
## Individual Determiner Character Limit
This operates in much the same way as the previous setting, but applies to the Individual character limit determiner instead. Its options are as follows:
- 80
- 106
- 160
- 165
- 200

### Note: All settings can be found in the new "Modifications" tab in FixyText's Settings menu; and these can all be adjusted in the menu and the lobby, but not after a game has started.

# Bonus
One all-new completely custom episode in the *FLIRTY* category and one all-new completely custom conversation in the *FRIENDS & FAM* category have been added to this utility mod as an added bonus. This content addition brings the total number of unique conversations in every category to 36 each. This unfortunately is not divided proportionally across all round numbers, but content is content.

# Installing this mod
As with installing any mod, *it is strongly recommended that you backup any files you plan to replace and/or modify.* Keep this in mind throughout the installation process.
To install the main utility settings into FixyText, go to you local files for The Jackbox Party Pack 10. Then navigate to `...\The Jackbox Party Pack 10\games\RiskyText` and replace its versions of `RiskyText.swf`, `Localization.json`, and `settings.json` with the respective versions in this very mod directory. This will enable the utility settings.

For installing the bonus content, it's a little different. First, go to this mod's directory and navigate to `.../content/{{locale}}*`, open `RiskyTextConversationsModded.jet` in a text editor, and copy its contents. Next, go your local files for The Jackbox Party Pack 10, and navigate to `...\The Jackbox Party Pack 10\games\RiskyText\content\{{locale}}*` and open its `RiskyTextConversations.jet` in a text editor.
Once you have opened your current locale's `RiskyTextConversations.jet` in a text editor, you'll notice that it starts with a structure that looks something like this:
```
{
 "content": [
```
Once you have located this code, create a new line directly after this first opening square bracket, and paste the modded content on the new line you created. Save the changes made to the current `RiskyTextConversations.jet` you are working with, and congratulations! You have successfully installed the bonus content for one locale. Repeat this process for all locales supported by this utility mod.

# And, that's everything!
### Special thanks to Inkyst for translating this utility mod into Español latinoamericano! (es-XL)
### Special thanks to HastagGuigui for translating this utility mod into Français! (fr)

Thank you again for stopping by and looking over this FixyText balancing utility mod! Please let me know if you encounter any bugs specific to this utility mod once properly installed. And if you haven't already, consider browsing my Youtube channel! Enjoy this mod, everyone. Take care.

\* {{locale}} refers to the current locale ID you'll be working with. Currently supported locale IDs include **en**, **fr** and **es-XL**. Remember to keep working with the same locale ID until you are finished with it.
