---
id: dxNumberBox.Options.format
type: Format
default: ''
---
---
##### shortDescription
Specifies the value's display format and controls user input accordingly.

---
[note] With this property specified, a press on Minus Sign (-) inverts the current value instead of entering "-".

[note] If you set this property, the telephone keyboard is used for editing on mobile devices. However, it may not have a point, comma, or other symbols for entering decimals. Set the [mode](/api-reference/10%20UI%20Components/dxNumberBox/1%20Configuration/mode.md '/Documentation/ApiReference/UI_Components/dxNumberBox/Configuration/#mode') property to *"text"* to use the standard keyboard instead.

#include common-demobutton with {
    url: "https://js.devexpress.com/Demos/WidgetsGallery/Demo/NumberBox/Formatting/"
}

#####See Also#####
- [format](/api-reference/50%20Common/Object%20Structures/format '/Documentation/ApiReference/Common/Object_Structures/Format/')