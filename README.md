# CSS-Snippets

![GitHub License](https://img.shields.io/github/license/SEELE1306/Modular?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/supports-vesktop-red?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/supports-vencord-red?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/supports-betterdiscord-navy?style=for-the-badge)

> [!IMPORTANT]
> Until further notice, this repository will only be maintained to a minimum, since I need to concentrate on other personal projects. This means no further new snippets will be uploaded and existing ones may not get design changes, rather bug fixes with a considerable delay.
> 
> Thank you for your understanding.

> [!WARNING]
> A recent Discord update has completely revamped the profile popouts and sections, making the following snippets no longer usable: **BetterProfiles, UserOptions**. These will be removed for the time being.

A compilation of CSS snippets for Discord and its custom clients.

See [Update Checklist](./Update%20Checklist.md) to see which snippets have been fixed/updated.


## List of available snippets

| Snippet    | Changes | Image |
| -------- | ------- | ------- |
| [BetterProfiles-v1 (Deprecated)](Snippets/BetterProfiles/v1) | Improves general layout of user profiles, improving readability and visual appeal. Credits to [Saltssaumure](https://github.com/Saltssaumure) for the role pills. | <img valign='middle' alt='BetterProfiles' src='./docs/_media/BetterProfiles.png' height='200px'/> |
| [BetterQuotes](Snippets/BetterQuotes/) | Improves blockquotes styling to make it more visible and appealing. | <img valign='middle' alt='BetterQuotes' src='./docs/_media/BetterQuotes.png'/> |
| [AccentColor](Snippets/ChangeColor/AccentColor/) | Replaces the Blurple [<img valign='middle' alt='blurple' src='https://readme-swatches.vercel.app/5865F2?style=circle&size=10'/>#5865F2] accent color with one of your choice. | <img valign='middle' alt='AccentColor' src='./docs/_media/AccentColor.png'/> |
| [ClientColor](Snippets/ChangeColor/ClientColor/) | Replaces the Grey [<img valign='middle' alt='grey' src='https://readme-swatches.vercel.app/313338?style=circle&size=10'/>#313338] client color with one of your choice. | <img valign='middle' alt='ClientColor' src='./docs/_media/ClientColor.png'/> |
| [OtherColors](Snippets/ChangeColor/OtherColors/) | Replace other Discord colors (red, yellow, green, etc.) with Blurple [<img valign='middle' alt='blurple' src='https://readme-swatches.vercel.app/5865F2?style=circle&size=10'/>#5865F2].| <img valign='middle' alt='OtherColors' src='./docs/_media/OtherColors.png'/> |
| [ChannelSelections](Snippets/ChannelSelections/) | Allows for more spacing for channel icons & colored unread notifiers. | <img valign='middle' alt='ChannelSelections' src='./docs/_media/ChannelSelections.png' height='200px'/> |
| [ChatBubbles](Snippets/ChatBubbles/) | Adds a chat bubble around messages. Different colours are available for normal, replying, mentioned and automod messages. | <img valign='middle' alt='ChatBubbles' src='./docs/_media/ChatBubbles.png'/> |
| [GuildBoost](Snippets/GuildBoost/) | Replaces the boost bar in guilds with a more appealing indicator | <img valign='middle' alt='GuildBoost' src='./docs/_media/GuildBoost.png' height='200px'/> |
| [MessageSection-v2](Snippets/MessageSection/v2/) | Aligns the "Message Section" better and hides its icons a hover menu | <img valign='middle' alt='MessageSection-v2' src='./docs/_media/MessageSection-v2_01.png'/> <img valign='middle' alt='MessageSection-v2' src='./docs/_media/MessageSection-v2_02.png'/> |
| [MessageTypes](Snippets/MessageUltilities/MessageTypes/) | Includes the message types & actions with the username. Currently available in English and German | <img valign='middle' alt='MessageTypes' src='./docs/_media/MessageTypes.png'/> |
| [TimestampBubbles](Snippets/MessageUltilities/TimestampBubbles/) | Applies a bubble styling to message timestamps | <img valign='middle' alt='TimestampBubbles' src='./docs/_media/TimestampBubbles.png'/> |
| [Username](Snippets/MessageUltilities/Username/) | Applies a bubble to usernames that abide by role color | <img valign='middle' alt='Username' src='./docs/_media/Username.png'/> <img valign='middle' alt='Username' src='./docs/_media/Username_ext.png'/>|
| [OnekoDM](Snippets/OnekoDM/) | Replaces the discord logo with Oneko! | <img valign='middle' alt='OnekoDM' src='./docs/_media/OnekoDM.png'/> |
| [UserOptions-v1 (Deprecated)](Snippets/UserOptions/v1) | Replaces the profile popout with more streamlined options | <img valign='middle' alt='UserOptions' src='./docs/_media/UserOptions.png' height='200px'/> |
| [UserPanel](Snippets/UserPanel/) | Replaces the user panel with a customizable, more appealing version. | <img valign='middle' alt='UserPanel' src='./docs/_media/UserPanel.png'/> |
| [ToolbarHide](Snippets/ToolbarHide/) | Hides the toolbar at the top for a cleaner layout. | <img valign='middle' alt='ToolbarHide' src='./docs/_media/ToolbarHide.png'/> |
| [StaffTags](Snippets/StaffTags/) | Applies styling to different staff tags for easier identification. | <img valign='middle' alt='StaffTags' src='./docs/_media/StaffTags.png'/> |
| [Titlebar](Snippets/Titlebar/) | Changes the default Discord titlebar to a more visually appealing one. You can customize the text and background color to your liking. | <img valign='middle' alt='Titlebar_01' src='./docs/_media/Titlebar_01.png'/> <img valign='middle' alt='Titlebar_02' src='./docs/_media/Titlebar_02.png'/> |
| [SpotifyControls](Snippets/SpotifyControls/) | Redesign for Spotify Controls with album image. | <img valign='middle' alt='SpotifyControls' src='./docs/_media/SpotifyControls.png'/> |

## Apply

There are several methods to apply these snippets. The methods below are for Vencord, however other clients have similar methods.

If your client is not [Vesktop](https://github.com/Vencord/Vesktop), the snippets `import.css` might not work properly. In that case, use `import-legacy.css` instead.

<details>
  
<summary>Via Local Themes:</summary>

+ Click on the folders (and possibly subsequent folders) of the snippet you want until you see the file `import.css`
+ Download the file `import.css` from the folders
+ Open Settings > Vencord > Themes > Local Themes > Open Themes Folder
+ Paste the downloaded file into the **themes** folder

</details>

<details>
  
<summary>Via Online Themes</summary>

+ Click on the folders (and possibly subsequent folders) of the snippet you want until you see the file `import.css`
+ Click on that file, then click on the **Raw** button
+ A file will open on your browser, now copy the URL
+ Open Settings > Vencord > Themes > Online Themes
+ Paste the following link into **Theme Links**: `URL HERE`
+ Enter or mouse-click outside the Online Themes box to apply

</details>

<details>

<summary>Via QuickCSS</summary>

+ Click on the folders (and possibly subsequent folders) of the snippet you want until you see the file `import.css`
+ Click on that file, then click on the **Raw** button
+ A file will open on your browser, now copy the URL
+ Open Settings > Vencord > Vencord > Open QuickCSS File
+ Paste the following line as your **first line (ahead of any other custom CSS)**: `@import url(URL HERE);`

</details>

## Special thanks to

[ant0n-0x0000](https://github.com/ant0n-0x0000) for helping out with the snippets' descriptions!

[Saltssaumure](https://github.com/Saltssaumure), [Lexia](https://github.com/exterpolation) for various elements within the snippets
