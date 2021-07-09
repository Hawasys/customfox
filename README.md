# CustomFox

## Installation

1. Copy `userChrome.css` in the Chrome directory in your Firefox profile directory. To find your profile directory, go to about:support.

2. Go to about:config and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.

### 3. Import settings

Follow these steps if you do not have, or want to keep your old configurations for hntp.

1. Go to extensions page > treestyletab > preferences.

2. Scroll all the way down to "Import" and select treestyletab/config.json file.

### 3.1 Manual Installation

Follow these steps if you have want to keep your configurations for hntp.

***This section may be missing some small configurations. Will add them soon***

1. Go to extensions page (ctrl+shift+a) > treestyletab > preferences.

2. Make sure you have "vertigo" theme selected. The CSS doesn't act as desired under any other theme.

3. Make sure you have "Right Side" selected for the setting "Style of contents for the sidebar position".

4. Scroll all the way down to an expandable menu named "All Configs" > Click on the small black triangle to expand the menu if it isn't already > Uncheck the checkboxes `autoAttach` and `syncParentTabAndOpenerTab` (*This disables the branching functionality of tst*).

5. Paste contents of `treestyletab/custom.css` to the textfield under "Advanced" section.

## Optional

1. Background of sidebar is changed based on firefox theme. You can set my theme with [Firefox Color here](https://color.firefox.com/?theme=XQAAAAIfAQAAAAAAAABBqYhm849SCia2CaaEGccwS-xNKlhWuMf61H-qemtFQ7JmIThKEJYbO6BYtxXFN3QVwfgIyLdrYygaud86UIpkiO8YN31rNYQT4wbIyYwCNHU7jaUMww6R7XMYKHXDUCvMW7_0AiLugqKwZ2mhpvOqQw__PRrGb_w5dNZqMUkPfE4UsOjehwu76ZgYlAyi-kcs2o76aC30rqSaUf9RJtUHhA_oQODqn_yh5tM). Setting the background color same as your title bar would give a nice look.

