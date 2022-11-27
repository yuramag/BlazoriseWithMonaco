# BlazoriseWithMonaco

When adding `Blazorise` to a project that already contains [Monaco Editor](https://github.com/serdarciplak/BlazorMonaco) I get the following exception in the browser console:

```
Microsoft.JSInterop.JSException: Can only have one anonymous define call per script file
Error: Can only have one anonymous define call per script file
```

Seems like there is some sort of conflict between the JS code backing `Tooltip` component and `BlazorMonaco` internals.
