# Create custom callouts for solo gaming

## Example of custom callouts

![Image of custom callouts](custom-callouts.png)

## CSS Code

```css
/* Oracle Callout */
.callout[data-callout="oracle"] {
  --callout-color: 0, 255, 255;
  --callout-icon: '<svg width="100%" height="100%" viewBox="0 0 22 26" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" xmlns:serif="http://www.serif.com/" style="fill-rule:evenodd;clip-rule:evenodd;stroke-linejoin:round;stroke-miterlimit:2;"><g><path d="M10.75,0c-5.933,0 -10.75,4.817 -10.75,10.75c0,5.933 4.817,10.75 10.75,10.75c5.933,0 10.75,-4.817 10.75,-10.75c0,-5.933 -4.817,-10.75 -10.75,-10.75Zm0,1.5c5.105,0 9.25,4.145 9.25,9.25c0,5.105 -4.145,9.25 -9.25,9.25c-5.105,0 -9.25,-4.145 -9.25,-9.25c0,-5.105 4.145,-9.25 9.25,-9.25Z"/><path d="M20.496,25.903l-19.492,0l4.873,-6.741l9.746,0l4.873,6.741Z"/><path d="M4.735,8.556c-1.322,3.017 0.054,6.54 3.071,7.863c3.017,1.322 6.54,-0.054 7.862,-3.071c-1.572,1.109 -4.245,1.398 -6.664,0.337c-2.42,-1.06 -4.019,-3.221 -4.269,-5.129Z"/><rect x="0.962" y="23.082" width="19.917" height="2.733"/></g></svg>';
}

/* Dice Roll Callout */
.callout[data-callout="roll"] {
  --callout-color: 255, 0, 255;
  --callout-icon: "lucide-dices";
}
```

## Callout Markdown

```md
> [!oracle] What event happens now?
> Befriend, Portals

> [!roll] Roll 3d6 against difficulty 5
> 3d6: [4, 2, 5] = 11
```
