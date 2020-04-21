# CSS pseudo-element challenge

[Pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements) are a way to define new HTML elements from within your CSS. They are very handy for lots of different styling tasks.

For example if we had this HTML:

```html
<p>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
  incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
  nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
  Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore
  eu fugiat nulla
</p>
```

and this CSS:

```css
p::first-line {
  font-weight: bold;
}
```

the HTML would act as though there was a `<span>` wrapped around just the first line of the `<p>`. We can then target it with CSS rules—in this case making just the first line bold. Note that this is dynamic: if the window resizes the content inside the pseudo-element will change to make sure it only ever targets the first line.

## Setup

1. Clone this repo
1. `npm install`
1. `npm run dev` to start a live-reloading server

The instructions for each task are on the page. Write your CSS in `challenge/challenge.css` and try to make each task look like the solution screenshots below.

## Solution screenshots

### Task 1: drop caps

![]()

### Task 2: input placeholders

![]()

### Task 3: quotation marks

![]()

### Task 4: offset underline

![]()

### Task 5: clickable cards

![]()
