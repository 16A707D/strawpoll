# Modified Strawpoll plugin for Discourse

This is a modified strawpolls plugin that shows the usernames of everyone that selected each option.

It has all the same basic features that are included in the default poll plugin, such as single
and multiple choice signups, and min/max number of selections for multiple signups.

There are also some additional goodies, like the ability to remove your vote and unsignup for
an event. There's also a button to automatically start a private message with everyone that
has signed up.

It also adds a calendar button to the text editor that automatically adds the markup for a
signup sheet to the post you're editing.

## Usage
Pretty much identical to the official polls plugin, just with 'signup' substituted for 'poll'

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

   There are options for the singular and plural version of the noun, which will be used
   for the English translations, which are the only ones included. The default is person/people,
   but you can see that it has been changed to rider/riders in the screenshots above.
