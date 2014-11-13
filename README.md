Simple-Tooltip
==============

Lightweight jQuery tooltip that gives the ability to show a tooltip on hover and on click ( useful for mobile )

Example Usage
```
<span data-tooltip-wrapper>

    <a data-tooltip-activate>Example Tooltip Point</a>

    <div data-tooltip-content>
	    Tooltip content goes here!
    </div>

</span>
```

If you want to customize the delay when clicking on a tooltip activation point you can do so by adding [data-tooltip-delay="{delay in milisecconds}"] to the [data-tooltip-wrapper] element
  
```
<span data-tooltip-wrapper data-tooltip-delay="1000">

    <a data-tooltip-activate>Example Tooltip Point</a>

    <div data-tooltip-content>
	    1 Second tooltip delay!
    </div>

</span>
```


