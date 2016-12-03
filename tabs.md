#`Tabs`

A composite component that acts as the main container


##`selectedIndex`
The tab with this index (zero-indexing) will be selected; defaults to 0.

####Example
`<Tabs selectedIndex={1} />`

##`forceRenderTabPanel`
By default, react-tabs will only render the selected tab's contents. Setting this property to true allows you to override the default behavior, which may be useful in some circumstances (such as animating between tabs).

####Example
`<Tabs forceRenderTabPanel={true} />`

##`setUseDefaultStyles(false)`
You can disable the default styling of react-tabs by calling this static method once.

####Example
`Tabs.setUseDefaultStyles(false);`

##`className`
The class name to be added to the Tabs main component.

####Example
`<Tabs className="foobar" />`