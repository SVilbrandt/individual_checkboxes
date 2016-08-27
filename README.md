individual_checkboxes
==================================================
Style your checkboxes and radio inputs individually and crossbrowser safe.
No JS, pure CSS.

JS/jQuery verions may follow...

How to use it?
----------------------------------------------------
Just include the individual_checkboxes(.min).css, that´s all!
After that, you only need to be wary of the HTML structure.

```
<div class="individual_checkboxes">
    <input type="checkbox" id="checkbox1" />
    <div></div>
    <label for="checkbox1">That is it!</label>
</div>
```

Same for radio inputs. Only exception here: add an empty span element to the div.

```
<div class="individual_checkboxes">
    <input type="radio" id="radio1" />
    <div><span></span></div>
    <label for="radio1">That is it!</label>
</div>
```

I also added an demo. There you can see how to easily customize the design. For example adding
Icons instead only changing the background color.

Hope you like this little helper.