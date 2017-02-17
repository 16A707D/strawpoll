# Modified Strawpoll plugin for Discourse

This is a modified strawpolls plugin that display the list of usernames who selected each option.

It has all the same basic features that are included in the default poll plugin, such as single
and multiple choice signups, and min/max number of selections for multiple signups.

Additional features include to the function to remove user's vote from the strawpoll and unsignup for the event. There is also a button to automatically start a private message with everyone that has signed up.

It also adds a calendar button to the text editor that automatically adds the markup for a signup sheet to the post that a user is editing.

## Usage
Example:
```bbcode
[signup type=multiple min=2 max=3]
- option 1
- option 2
- option 3
- option 4
[/signup]
```

Type, min, and max can all be ommitted, and you'll get a signup sheet that only allows one
option to be selected. Min and max are both optional for `type=multiple`.

## Configuration
There are three Configuration options that can be changed from the admin settings page.

1. You can enable or disable the signups plugin (default enabled).
2. You can limit the maximum number of options in each signup sheet (default 4).
3. You can change the noun used to describe the people that have signed up for the event.
