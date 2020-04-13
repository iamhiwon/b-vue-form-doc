#   Between

```
 <FormulateInput
  type="range"
  min="5"
  max="35"
  name="Age"
  label="How old are you?"
  validation="between:10,18,value"
  :show-value="true"
  :value="15"
  error-behavior="live"
/>
```

![](images\between.png)

```
<FormulateInput
  type="password"
  name="password"
  label="Pick a new password?"
  validation="between:8,20,length"
  error-behavior="live"
/>
```

![](images\between2.png)
 