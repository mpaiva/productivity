# Mac OSX - Dock Dividers

How to add space dividers on the dock? To create 1 divider enter the following on `terminal`:

`defaults write com.apple.dock persistent-apps -array-add '{tile-data={}; tile-type="spacer-tile";}'`
   
Then

`killall Dock`

Repeat these steps to create additional dividers.
