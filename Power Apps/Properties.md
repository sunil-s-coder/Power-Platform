# Power Apps Controls – Behavior Functions vs Value vs Properties

This document classifies Power Apps controls by:
- **Behavior Functions** (event handlers)
- **Primary Value Property** (used in formulas/business logic)
- **Other Important Properties** (configuration, appearance, data)

---

## Input & Action Controls

| Control        | Behavior Functions             | Value Property        | Other Important Properties |
|----------------|--------------------------------|-----------------------|----------------------------|
| Button         | OnSelect                       | Text                  | Icon, DisplayMode, Fill, Color, BorderRadius |
| Text Input     | OnChange, OnSelect             | Value                 | Default, Placeholder, Mode, DelayOutput, MaxLength |
| Number Input   | OnChange, OnSelect             | Value                 | Default, Min, Max, Step, DelayOutput |
| Drop Down      | OnChange, OnSelect             | Selected              | Items, Default, AllowEmptySelection |
| Combo Box      | OnChange, OnSelect             | SelectedItems         | Items, DefaultSelectedItems, SelectMultiple, IsSearchable |
| Date Picker    | OnChange, OnSelect             | SelectedDate          | DefaultDate, StartYear, EndYear, Format |
| Checkbox       | OnCheck, OnUncheck, OnSelect   | Value                 | Text, CheckboxSize, Disabled |
| Radio          | OnChange, OnSelect             | Selected              | Items, Default, Orientation |
| Toggle         | OnChange, OnCheck, OnUncheck   | Value                 | TrueText, FalseText, Default |
| Pen Input      | OnSelect                       | ImagePosition         | Color, Fill, Height, Width |
| Tab List       | OnSelect                       | SelectedItems         | Items, DefaultSelectedItems, Alignment |
| Tool Bar       | OnSelect                       | Selected              | Items, Icons, DisplayMode |
| Slider         | OnChange, OnSelect             | Value                 | Min, Max, Default, Step |
| Rating         | OnChange, OnSelect             | Value                 | Max, Default |
| List Box       | OnChange, OnSelect             | SelectedItems         | Items, Default, SelectMultiple |

---

## Display & Media Controls

| Control        | Behavior Functions       | Value Property        | Other Important Properties |
|----------------|--------------------------|-----------------------|----------------------------|
| Text (Label)   | OnSelect                 | Text                  | Font, Size, Color, Align, AutoHeight |
| Icon           | OnSelect                 | Icon                  | Color, BorderThickness, Height, Width |
| Avatar         | OnSelect                 | ImagePosition         | ImagePosition, Size, Shape, FallbackText |
| Badge          | N/A                      | Content               | Appearance, Palette, Size |
| Progress Bar   | N/A                      | Value                 | Max, Indeterminate, Thickness |
| Info Button    | OnSelect                 | Tooltip               | Icon, Color, Visible |
| Spinner        | N/A                      | Visible               | Label, Appearance, Size |
| Image          | OnSelect                 | ImagePosition         | Image, Height, Width, Transparency |
| Timer          | OnTimerStart, OnTimerEnd | Value                 | Duration, Start, AutoStart, Repeat |
| Audio / Video  | OnStart, OnEnd, OnPause  | Position              | Media, AutoStart, Loop, Volume |
| HTML Text      | OnSelect                 | HtmlText              | Padding, AutoHeight |

---

## Container & Form Controls

| Control        | Behavior Functions             | Value Property | Other Important Properties |
|----------------|--------------------------------|----------------|----------------------------|
| Gallery        | OnSelect                       | Selected       | Items, Layout, TemplateSize, WrapCount |
| Edit Form      | OnSuccess, OnFailure, OnReset  | Updates        | DataSource, Item, Mode |
| Data Card      | OnChange                       | Value          | DataField, DisplayName, Required |
| Screen         | OnVisible, OnHidden            | Fill           | ImagePosition, LoadingSpinner |
| Container (V/H)| N/A                            | N/A            | Gap, Align, Justify, FlexibleHeight |

---

## Modern Controls (2026 Reference)

| Control        | Behavior Functions             | Value Property        | Other Important Properties |
|----------------|--------------------------------|-----------------------|----------------------------|
| Modern Table   | OnSelect                       | SelectedItems         | Items, Columns, ShowHeaders |
| Badge          | N/A                            | Content               | Appearance, Palette |
| Progress Bar   | N/A                            | Value                 | Max, Indeterminate |
| Spinner        | N/A                            | Label                 | Appearance, Size |
| Tab List       | OnSelect                       | SelectedItems         | Items, DefaultSelectedItems |

---
