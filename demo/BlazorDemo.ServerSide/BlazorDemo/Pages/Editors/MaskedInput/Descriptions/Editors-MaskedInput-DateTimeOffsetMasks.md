Like date-time masks, [Date-time offset](https://docs.devexpress.com/Blazor/402515/data-editors/masks/date-time-masks#date-time-offset-masks) masks allow users to enter only date and/or time values using a specific format. Users can navigate between mask sections and increase or decrease section values with the Up/Down arrow keys and the mouse wheel. The difference is that date-time offset masks store time offsets from Coordinated Universal Time (UTC) and allow users to change offset values.

The [Masked Input](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxMaskedInput-1) component activates the date-time offset mask type once you bind the component's [Value](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxMaskedInput-1.Value) property to a *DateTimeOffset* object. To enable this mask type in other usage scenarios, set the component's [MaskMode](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxMaskedInput-1.MaskMode) property to `DateTimeOffset`. Once set, assign a mask pattern to the [Mask](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxMaskedInput-1.Mask) property to apply a mask and use the [DxDateTimeOffsetMaskProperties](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxDateTimeOffsetMaskProperties) component to customize mask appearance and behavior.

Use the settings available in this demo to explore different mask modes:

* **Mask** — Specifies the mask pattern.
* **Caret Mode** — Specifies whether to automatically move the caret to the next editable section once you complete input within a mask section (`Advancing` mode) or to move focus manually (`Regular` mode).
* **Culture** — Specifies the current culture. Culture can affect the appearance of a mask pattern.
* **Cascading Section Updates** — Specifies whether to increase or decrease the value of the previous or next mask section once you change a section's value with the Up/Down arrow key (or the mouse wheel) and the value passes the minimum or maximum threshold.
