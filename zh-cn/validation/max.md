#   Max

```
 <FormulateInput
  type="text"
  name="coupon"
  label="Enter a coupon code"
  validation="max:5,length"
  error-behavior="live"
/>
```

![](images\max.png)

```
<FormulateInput
  type="checkbox"
  name="toppings"
  :options="{
    pepperoni: 'Pepperoni',
    sausage: 'Sausage',
    olives: 'Olives',
    feta: 'Feta',
    mushrooms: 'Mushrooms',
  }"
  label="Select up to 3 pizza toppings"
  validation="max:3"
  error-behavior="live"
/>
```

![](images\max2.png)