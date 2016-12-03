##`onSelect(cb)`

This function is called whenever a tab is selected.

####Arguments
1. `cb` (_Function_): A function that is passed the **selected** tab index and the **last** tab index as arguments.

####Example
```
<Tabs 
  onSelect={(firstTab, lastTab) => console.log(`${firstTab}, ${lastTab}`)} 
/>
```