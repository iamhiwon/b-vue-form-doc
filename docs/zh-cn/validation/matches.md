#   Matches

```
 <FormulateInput
  type="text"
  name="color"
  placeholder="#00ff00"
  label="Enter a hexidecimal color value"
  :validation="[['matches', /^#[a-fA-F0-9]{6}$/]]"
  error-behavior="live"
  v-model="color"
/>
<FormulateInput
  type="color"
  label="Or pick one"
  v-model="color"
/>
```

![](images\matches.png)

 ```
<FormulateInput
  type="text"
  name="language"
  placeholder="node, php, java..."
  label="What is your favorite server side language?"
  validation="matches:node,php,java"
  error-behavior="live"
  v-model="color"
/>
```

![](images\matches2.png)