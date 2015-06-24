# craft-comb-calebhsu

Parameterized comb model.

### Install
    $ npm install craft-comb-calebhsu

### Parameters
- width: adjusts width of comb
- length: adjusts length of comb
- height: adjusts thickness of comb

### Example
```html
<craft>
    <craft name="comb" module="craft-comb"/>
    <row spacing="2">
        <comb transform="scale(3,3,3)"></comb>
        <comb length="10" width="6" transform="scale(2,2,2)"></comb>
        <comb></comb>
    </row>
</craft>
```

![example](example.png)