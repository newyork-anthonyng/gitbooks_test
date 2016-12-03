#`disabledTabClassName

A custom class name given to a `<Tab>` when it is disabled.

####Arguments
1. `class` (__String__): Class name given to a disabled tab.

####Example
```javascript
<TabList disabledTabClassName="myDisabledClass" />
```

A `<Tab>` can be disabled by settings its disabled property.
```javascript
<Tab>Mario</Tab>
<Tab disabled={true}>Bowser</Tab>
```