# placement.css
Functional CSS positioning bundle

## setup

```
npm install placement.css
```

```css
@import 'node_modules/placement.css/placement';
```

## classes

### [position.css](https://github.com/ryanve/position.css/tree/v0.1.1)

- `.static`
- `.relative`
- `.absolute`
- `.fixed`
- `.sticky`

### [at.css](https://github.com/ryanve/at.css/tree/v0.2.0)

- `.middle` vertical center
- `.centre` vertical and horizontal center


### [edge.css](https://github.com/ryanve/edge.css/tree/v0.2.0)

- `.edge-0`
- `.edge-auto`
- `.top-0`
- `.left-0`
- `.right-0`
- `.bottom-0`
- `.top-auto`
- `.left-auto`
- `.right-auto`
- `.bottom-auto`

## usage

```html
<div class="relative">
  <p class="absolute centre">I'm centered</p>
</div>
```

```html
<div class="relative">
  <p class="absolute edge-0">I fill my container</p>
</div>
```
