# Micro LED

## Toggle an LED

Drag the code to toggle an LED.

```blocks
basic.forever(function () {
    led.toggle(0,0)
})
```
## All the code

```blocks
basic.forever(function () {
    led.toggle(Math.randomRange(0,4), Math.randomRange(0,4))
})
```