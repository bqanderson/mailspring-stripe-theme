# Mailspring Stripe

Stripe modifies the layout of the Nylas N1 email client by moving the account sidebar to the bottom of the interface.

![](preview.png)

By moving folders to the bottom, the interface reserves the primary canvas space for messages themselves. That's the idea, anyway. This might not be for you if you regularly use many folders or if you need to toggle between separate accounts a lot.  Still, try it out and let me know what you think.


## Prototype

N1 is designed with an account sidebar in mind. Moving it to the bottom is a CSS hack, which works for the most part, but is nonetheless forcing a square peg into a round hole. Also, there are a lot of nuanced layout use cases. I addressed a bunch of them, but there were far more than I (naively) expected, so beware the thing is a "work-in-progress."


## Installation
1. Download [Mailspring](https://getmailspring.com/download).
2. Download the Stripe theme.
3. From Mailspring, select menu > Install Theme...`.
4. Find the directory for this plugin to install it.

If you want to manually install, use this cheat sheet and move the package to one of these directories (depends on which system you're using)


   | OS           | Location                                                     |
   |--------------|--------------------------------------------------------------|
   | macOS        | ~/Library/Application Support/Mailspring/packages/THEME_NAME |
   | Ubuntu native| ~/.config/Mailspring/packages/THEME_NAME                     |
   | Ubuntu Snap  | ~/snap/mailspring/common/packages/THEME_NAME                 |
   | Windows      | %appdata%\Mailspring\packages\THEME_NAME                     |

