### Requirements
[TikFinity](https://tikfinity.zerody.one/downloads/TikFinity_installer.exe)

[Clash Overlay App](https://github.com/Sythrine/Clash-Overlay-App/releases/latest/download/ClashOverlayApp.exe)

### Setup

1. Run the Clash Overlay App. (You will likely need to select more info and then Run Anyway as it is a third party app.)
2. Click the Copy button in the Control Panel.
3. Make an account and sign in to TikFinity.
4. Go to Actions & Events.
5. Create new Action.
6. Name it something like Clash Integration.
7. Select Trigger Webhook and paste the URL there.
8. Create or edit events for Likes (set it to minimum 1.), Gifts (set coin minimum value to 1 as well.), Follows, and Shares. Set all of these to trigger your Clash Integration action.
9. Create events for commenting commands. You can have the commands be anything, such as `!review` and `!queue`. Have these events also trigger your Clash Integration action.
> [!Tip]
    - I highly recommend setting these to followers only, but if you want to allow everyone to join the queue, that's up to you.\
    - These are case sensitive, so you may want to add variants that people will likely use, such as `!Review` and `!REVIEW`.
10. Your integration is setup now. Just make sure to have to connect TikFinity to your stream the next time you go live and have it run in the background.
11. If you are using Display capture in your streaming software, you can resize the three windows by holding CTRL and clicking then dragging on the three floating windows. Click and drag to position them.
> [!Tip]
    - You can also use Window Capture in your streaming software to capture each window and position them where you want them.\
    - If you use Window Capture this way, resize the real floating windows, but use the streaming software to choose the position.\
    - If using Window Capture, you will need to configure the three windows each time you open them.
