# craft-comb-calebhsu

Parameterized comb model.

### Usage
```html
<craft>
    <craft name="comb" module="craft-comb-calebhsu"/>
	<comb></comb>
</craft>
```

### Parameters
- width: adjusts width of comb
- length: adjusts length of comb
- height: adjusts thickness of comb

### Example
```html
<craft>
    <craft name="comb" module="craft-comb-calebhsu"/>
    <row spacing="2">
        <comb transform="scale(2 2 2)"></comb>
        <comb length="40" width="20"></comb>
        <comb></comb>
    </row>
</craft>
```

![example](example.png)