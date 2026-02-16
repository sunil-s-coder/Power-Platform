# Task Preformed:

## PDF function:
1. Display in *PDF viewer* control
2. Control following properties:
    1. **DPI:** default(96)
    2. **Size:** PageSize.A1, A2 etc
    3. **Margin:** "Top Left Bottom Right" & Units: in, mm, cm, pt, px
    4. **ExpandContainers:** true or false (to display contents which are not previewed over screen)
    5. **Orientation:** Landscape or Portrait
2. Connectors:
    1. **Office 365 Outlook:** To send email with PDF as attachment
3. **Power Automate:** Create a PDF of gallery control & save it in SharePoint folder.

## Forms:


## Best Practices
1. Follow naming convention for controls
2. PowerFx:
    * Comment(// or /*--*/) the PowerFx formula for easy understanding of the functionality
    * Format the PowerFx formula for better readability
    * Concurrent
    * Cacheing
    * Multiple query to same inform - use Named formula or Variable
    * Delegation
    * Reduce usage on OnStart, instead go for Named formula
6. Reset - Use variable instead of referring reset button in each of the control
9. Save with version notes

## URL functionality:
1. Param()
2. hidenavbar = (true/false) - to hide top PowerApps navigation bar

## Component
1. Types:
    1. Custom Component
    2. Library Component - Global Components - 