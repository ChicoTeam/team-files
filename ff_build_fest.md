Firefox Build-Fest Resources
Mozilla Community

    IRC Chat:   

    Mibbit web-based chat: https://chat.mibbit.com/?url=irc%3A%2F%2Firc.mozilla.org%2F%23introduction

    URL for IRC clients: irc://irc.mozilla.org/introduction

    Forums/Mailing Lists: http://www.mozilla.org/about/forums/#general-development

Development Documentation

    Developer Guide: https://developer.mozilla.org/en-US/docs/Developer_Guide

    Overview-- "Contributing to the Mozilla Codebase": https://developer.mozilla.org/en-US/docs/Introduction

    Building...

    Simple Firefox Build: https://developer.mozilla.org/en-US/docs/Simple_Firefox_build

    In-Depth Build Instructions: https://developer.mozilla.org/en-US/docs/Developer_Guide/Build_Instructions

    Incremental Build: https://developer.mozilla.org/en-US/docs/Incremental_Build

    Automated Testing: https://developer.mozilla.org/en-US/docs/Mozilla_automated_testing

    Mozilla Developer Cheat-sheet: http://www.brianbondy.com/mozilla/cheatsheet/

    Bugs ahoy!: http://www.joshmatthews.net/bugsahoy/

    Initial Interaction With A Developer http://www.mozilla.org/en-US/contribute/  (Submit your email and area of interest)

Other Ways to Contribute

    All Volunteer Opportunities: https://www.mozilla.org/contribute/areas.html

    Quality Assurance: https://developer.mozilla.org/en/QA

    Documentation: https://developer.mozilla.org/Project:en/How_to_Help

    Cutting-edge Mozilla Projects: http://labs.mozilla.org

Troubleshooting the Build Process

    If you get "*** Couldn't find..." or "configure: error: ... not found in $PATH", then you need to install the dependencies.

    If you already installed dependencies, then you need to specifically install the item that is missing (on linux, it's sudo apt-get install program_name_here )

    If you get "collect2: ld terminated with signal 9 [Killed]", it means you don't have enough free RAM memory. Try increasing "swap" space to at least 2gb: https://help.ubuntu.com/community/SwapFaq

Build Tips

    Don't rebuild the entire project every time! Use incremental builds: https://developer.mozilla.org/en-US/docs/Incremental_Build

    To speed up builds, use ccache: https://developer.mozilla.org/en-US/docs/ccache

    Configure build options using the .mozconfig file: https://developer.mozilla.org/en-US/docs/Configuring_Build_Options

    For debugging:

    ac_add_options --enable-debug 

    ac_add_options --disable-optimize 

