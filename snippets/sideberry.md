## Toggle header title
1. Find your profile folder (hence referred to as ${PROFILE}): go to about:support and look at the line that says "Profile folder".
2. Toggle the relevant about:config flags and restart.
3. Put this in ${PROFILE}/chrome/userChrome.css (create the file if it doesn't already exist):

```css
#TabsToolbar
{
    visibility: collapse;
}
```