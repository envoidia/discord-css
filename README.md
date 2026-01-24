# Currently partially broken, will be fixed soon

Custom CSS to make Discord better. Can be used with the website or any modded client (I recommend [Vesktop](https://github.com/Vencord/Vesktop)). Contributions welcomed

# debloat.css

Removes bloat and ads from Discord

Sections are commented, so you can easily edit anything you don't like

Anything that uses aria-label will only work in English. If you use another language, you'll have to modify it yourself (just replace the text with whatever it says in your language)

Todo:
  - Replace uses of aria-label with language-agnostic counterparts where possible
  - Hide top bar
  - Fix the Discover tab still having popup text when hovered despite being invisible
  - Settings:
    - Hide Payment Settings header
    - Hide Server Boost tab
  - Server:
    - Hide Server Boost tab
  
# gradients.css

Adds gradients to several elements

Todo:
  - Gradients in more places
    - Selected DMs
    - Scrollbars
    - Figure out if gradient text is possible
  - Fix some minor missing animations
  - Fix some minor artifacts on the edges of gradients

# names.css

Changes the style of specific user's names

Add all your friends with their favorite colors, or give them special backgrounds and other edits

Todo:
  - Figure out if gradient text is possible
  - Target user ID instead of username, and make it work on profiles and typing indicators

# theme.css

My own modified version of [ClearVision](https://github.com/ClearVision/ClearVision-v7/blob/master/ClearVision-v7-Vencord.css)
