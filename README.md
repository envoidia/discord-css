Custom CSS to make Discord better. Contributions welcomed

# envoidia_debloat.css

CSS that removes bloat and ads from Discord. Can be used with the website or any modded client (I recommend [Vesktop](https://github.com/Vencord/Vesktop))

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
  
# envoidia_clearvision_theme.css

My own modified version of [ClearVision](https://github.com/ClearVision/ClearVision-v7/blob/master/ClearVision-v7-Vencord.css), with gradients and stuff

Todo:
  - Change the name colors of specific users by user ID instead of username, and make it work on profiles and typing indicators
  - Gradients in more places
    - Selected DMs
    - Scrollbars
  - Fix some minor missing animations with gradients
  - Fix some minor artifacts on the edges of gradients
