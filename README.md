LiveSplit.HMA v1.0.1
=====================

LiveSplit.HMA is a [LiveSplit](http://livesplit.org/) component for Hitman: Absolution.

Features
--------
  * Keeps track of Game Time to get rid of loading times.
  * Auto start/reset/stop the timer.
  * Automatically pauses, if the game crashes.
  * Splits after each game section / at result screens (configurable). 

Requirements
------------

  * Hitman: Absolution on GOG or Steam (GOG is preferred)
  * LiveSplit 
  * .NET Framework 4.8.1 Runtime  
------------
! This is a fork of the original repo with the improved GOG Support.
------------
Install
-------
Close LiveSplit completely.

Download the plugin from the [releases page](https://github.com/sqice019/LiveSplit.HitmanAbsolution/releases)

Replace the old LiveSplit.HMA.dll file located in your LiveSplit\Components folder with the new one.

Restart LiveSplit. Your existing layout should pick it up automatically.

Configure
---------
Open your Splits Editor and active the autosplitter. If this is not working, leave it deactivated and manually add it in the Layout Editor. You can configure the settings in whichever editor it has been enabled in.

After configuring everything you'll most likely want to turn on game time as primary timing, so that your splits will run off game time. You can do this by right-clicking LiveSplit and going to Compare Against -> Game Time.


Credits
-------
  * [SuicideMachine](http://twitch.tv/suimachine)
  * [DrTChops](http://twitch.tv/drtchops) 
  * Plugin is based off [LiveSplit.Dishonored](https://github.com/fatalis/LiveSplit.Dishonored) by [Fatalis](http://twitch.tv/fatalis_).
  * sqice
