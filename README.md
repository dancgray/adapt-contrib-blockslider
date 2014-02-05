adapt-contrib-blockslider
=========================

Contributed block slider extension for the Adapt Learning framework

Installation
------------

First, be sure to install the [Adapt Command Line Interface](https://github.com/cajones/adapt-cli), then from the command line run:-

    adapt install adapt-contrib-blockslider

Usage
-----
Once installed, the component can be used to transform an article into a horizonally scrolling container, that allows users to navigate
between the blocks within it.

Both tab and arrow controls are provided to facilitate the navigation of the blocks.

For example JSON format, see [example.json](https://github.com/LearningPool/adapt-contrib-blockslider/blob/master/example.json)

Settings overview
-----------------

_arrows - settings for the arrow navigation controls
  _isActive - set to true/false to display/hide arrow navigation controls

_tabs - settings for tab navigation controls
  _isActive - set to true or false to display/hide tabbed navigation

_useBlockTitle: set to true to display the block title text within tabs. Set to false to display an icon for each tab.

_initial - which block to show on initial load ie: 2 will show the 2nd block

_height - fix the height of the blockslider to this value ie: 600 will set the blockslider to 600px high. This will be 'auto' if not specified.