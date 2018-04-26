# actindo-toggle-button
Wrapper of ```paper-toggle-button```.  
Returns true/false as values.

## Example
Example will create a toggle button with the label *My Label* and uses different iron-icons on
toggled and untoggled state. Using  ```use-primary-color``` turn label and icons to primary color when button is toggled 

<actindo-toggle-button
    name="mybutton"
    checked
    use-primary-color
    label="My label"
    icon="chevron-left"
    toggled-icon="chevron-right">
</actindo-toggle-button>
