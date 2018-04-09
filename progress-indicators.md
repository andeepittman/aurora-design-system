# Progress Indicators

## Steps Indicator

Progress indicators are key for visibility of system status. They visually represent a path to completion of a particular task or process. Step indicators help the user identify how much of the process the user has completed, and how much is still left.

Step indicators are used for tasks that require multiple steps. To visually represent a page or element that is loading, use a spinner or progress bar rather than a steps indicator.

If a label is required for your step indicator, the label should be placed at the top of the element and left-aligned.

Step indicators should always include a text indicator as well as the visual. This text should be included in the &lt;alt&gt; tag.

Colours for the step indicator can vary, but ensure that contrast requirements are met. Visit the [colour section](colour.md) for more information on choosing accessible colours.

## Progress Bars

Progress bars are used to visually represent a page or feature that is loading or in progress. Progress bars show a percentage as well as the visual representation shown within the bar.

Progress bars show determinate levels of progress, meaning there is a clear point of completion. When the progress bar is filled and hits 100%, the application should complete the process.

Progress bars should always include a text indicator as well as the visual to provide more context. This text should be included in the &lt;alt&gt; tag.

Colours for the progress bar can vary, but ensure that contrast requirements are met. Visit the [colour section](colour.md) for more information on choosing accessible colours.

### Animation

Progress bars start empty and gradually fill with colour using an animation. The percentage shown should match the level of colour that fills the bar.

## Spinners

Spinners are used to indicate that a page or function is loading. A general rule is to use spinners for processes that take less than 4 seconds. Spinners show indeterminate levels of progress, meaning there is no clear completion and the animation loops until the process is complete.

The spinner used in this design system is displayed using the [spinner icon](https://www.gitbook.com/book/gctools-outilsgc/-gcdigital-design-system/edit) from Font Awesome. Font Awesome provides [multiple icons](https://www.gitbook.com/book/gctools-outilsgc/-gcdigital-design-system/edit) that may work well as a spinner, depending on your content. You can refer to [Font Awesome's documentation](https://www.gitbook.com/book/gctools-outilsgc/-gcdigital-design-system/edit) to animate the spinner to demonstrate a loading page or function.
