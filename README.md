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

![](https://user-images.githubusercontent.com/9408641/79916911-6fa39480-8421-11ea-95fc-10f9628ba060.png)

### Task 2: input placeholders

![](https://user-images.githubusercontent.com/9408641/79916884-631f3c00-8421-11ea-9a8f-14723bf91542.png)

### Task 3: quotation marks

![](https://user-images.githubusercontent.com/9408641/79916853-5995d400-8421-11ea-85b7-9af24751176c.png)

### Task 4: offset underline

![](https://user-images.githubusercontent.com/9408641/79916837-4edb3f00-8421-11ea-9599-cd154a747a2a.png)

### Task 5: clickable cards

![](https://user-images.githubusercontent.com/9408641/79916815-43881380-8421-11ea-9c4d-da6f23998932.png)
