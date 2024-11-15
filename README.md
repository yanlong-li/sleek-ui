# Slint UI Component Library

>

Color scheme from element UI

### Button Example

![img.png](images/buttons.png)

#### Attributes

| Attribute | Description         | type        | Default | Accepted values                             |
|-----------|---------------------|-------------|---------|---------------------------------------------|
| size      | size                | ButtonSize  | Default | Default,Medium ,Small ,Mini                 |
| type      | Preset color        | ButtonType  | Default | Default,Primary,Success,Info,Warning,Danger |
| round     | Round corner        | ButtonRound | Default | Default,Round,Circle                        |
| disabled  | Is it disabled      | bool        | false   |                                             |
| plain     | Is it plain         | bool        | false   |                                             |
| text      | Button display text | string      |         |                                             |
| icon      | Button display icon | @image-url  |         |                                             |

```slint
component example{
    Button {
        text: "Button";
        size: ButtonSize.Default;
        type: ButtonType.Default;
        plain: false;
        disabled: false;
        clicked => {}
    }
}
```