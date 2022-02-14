# Typing Loading

---

## HTML :sparkles:

We need a div with the **_loader_** class.

Inside the div, we will place 4 **span** tags and an **h3** tag.

```html
<div class="loader">
  <span></span>
  <span></span>
  <span></span>
  <span></span>
  <h3>Loading...</h3>
</div>
```

_\*Don't forget to put your link tag_

```html
<link rel="stylesheet" href="style.css" />
```

---

## CSS :nail_care:

This part is quite easy.

First we must reset the _styles_

```css
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
```

The loader div is the one that will contain everything

Each span represents one of the load lines. That's why we will have 4.

```css
.loader span:nth-child(n) {
  background: linear-gradient(90deg, transparent, #03e9f4);
  height: 5px;
  left: -100%;
  top: 0;
  width: 100%;
  animation: animate1 2s linear infinite;
  animation-delay: 0s;
}
```

We position each line in its corresponding place

The text typing effect is done with the following animation.

```css
.loader h3 {
  border-right: 1px solid #03e9f4;
  color: #03e9f4;
  font-family: consolas;
  letter-spacing: 2px;
  overflow: hidden;
  transition: 0.5s;
  animation: typing 5s steps(10) infinite;
}
@keyframes typing {
  0%,
  90%,
  100% {
    width: 0px;
  }
  30%,
  60% {
    width: 123.89px;
  }
}
```

Steps of 10 are the number of characters that the word _Loading..._ has.

---

# Social Media :dizzy:

## TikTok

<a href="https://www.tiktok.com/@razvimx" target="blank"><img align="center" src="tiktok.png" alt="razvimx" height="40" width="40" /></a>

<!-- [![Tiktok](tiktok.png "Tiktok")](https://www.tiktok.com/@razvimx) -->

## Instagram

<a href="https://instagram.com/razvimx" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="razvimx" height="30" width="40" /></a>

**By Razvi** :heart:
