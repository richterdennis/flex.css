# flex.css
Easy usage of css3 flexbox

### Usage
#### flex-row and flex-col
Add `flex-row` or `flex-col` to style the element as a flex-box with flex-direction row or column.
Or you can use `flex-box` its the same as `flex-row` with height and width as 100%.

To wrap childs set the value of the html attributes to wrap for e.g. `flex-row="wrap"`

#### flex-layout
To align the childs simply add `flex-layout="MAIN-AXIS CROSS-AXIS"`

Possible values for MAIN-AXIS:
- start
- center
- stretch
- space-between or simply space
- space-around
- end

Possible values for CROSS-AXIS:
- start
- center
- stretch
- baseline
- end

#### flex-content
To align wraped childs on the cross axis.
Values are the same as the values for main axis e.g. `flex-content="space"`

#### flex
To force that an Element use all of the extra space

#### flex-self
You can align flexbox childs on the cross axis by self using `flex-self` it overrides the settings from the parent for this child
Values are the same as the values for cross axis e.g. `flex-self="center"`
