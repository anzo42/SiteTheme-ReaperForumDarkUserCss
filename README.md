# Dark style for Cockos/Reaper forum
![Preview](https://raw.githubusercontent.com/frantick/ReaperDarkUserCss/main/Reaper_preview.JPG)

This css style was created and tested on Firefox with [Stylus addon](https://github.com/openstyles/stylus), but should be compatible with any similar extensions as long as they support the [Stylus](https://stylus-lang.com) css preprocessor. Although, to access the customization menu where you can change colors and font size, you may need the mentioned extension.

![Settings](https://raw.githubusercontent.com/frantick/ReaperDarkUserCss/main/Reaper_settings.png)
# Note:
For a better experience, I don't recommend using this css on the "Reaper 5" forum theme because it has some colors that I couldn't change with css without messing up the look of the forum, the most prominent of which is the background color.

If for some reason you don't mind, you can try pasting the following text in line 29 for example.

`
    div
    {
        background: var(--backgroundColorMain) !important;
    }
`
