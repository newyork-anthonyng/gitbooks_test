##`onSelect`

Accepts a callback that is called whenever a tab is selected.

####Arguments
1. `cb` (_Function_): A function that is passed the **selected** tab index and the **last** tab index as arguments.

####Example
```javascript
<Tabs 
  onSelect={(firstTab, lastTab) => console.log(`${firstTab}, ${lastTab}`)} 
/>
```