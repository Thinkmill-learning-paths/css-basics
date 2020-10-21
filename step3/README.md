# CSS basics

## Step 3 - Logic

### Switch

Use only the below HTML for this switch component and write CSS to make it look like the image.

```html
<label>
  <input type="checkbox" name="switch" id="switch" aria-labelledby="switch-label">
  <span id="switch-label">
    Switch me to do a thing
  </span>
</label>
```

Design

<img src="https://github.com/Thinkmill-learning-paths/css-basics/blob/main/assets/switch.png" width="277px" alt="The switch design enabled and disabled">

### CSS-only Stop watch

Rules:

- Create a CSS-only stop watch.
- You can shape your own HTML.
- No javaScript allowed.
- There should be a display of time that shows `hour`, `minute` and `seconds`.
- There should be a `Stop` button
- There should be a `Continue` button
- There should be a `Reset` button

### SPA

Rules:

- Create an SPA that will only show a single section at a time
- The app should have three pages: `Home`, `About` and `Contact`
- On top of each page there should be a navigation that allows the visitor to navigate between each page
- Use the below HTML

```html
<!DOCTYPE html>
<html>
<head>
	<title>CSS only SPA</title>
</head>
<body>
	<nav>
		<ul>
			<li>
				<a href="#home">Home</a>
			</li>
			<li>
				<a href="#about">About</a>
			</li>
			<li>
				<a href="#contact">Contact</a>
			</li>
		</ul>
	</nav>

	<main>
		<section id="home">
			<h1>Welcome home</h1>
			<p>
				Ut aliquet sit amet urna non porta. Maecenas dignissim, sem eget pulvinar luctus, ex dolor posuere magna, ut elementum quam eros vel nulla. Praesent pulvinar arcu tristique diam luctus condimentum. Suspendisse suscipit in turpis ac facilisis. Aenean blandit tortor quis enim auctor, sed aliquam purus maximus. Proin a dapibus augue, eu porttitor diam. Nulla volutpat metus odio, at mollis ligula imperdiet molestie. Suspendisse potenti. Donec varius, sem vitae tristique varius, metus est semper ligula, sit amet consectetur quam velit ut metus. Nunc mi neque, vulputate id libero vitae, aliquam egestas est.
			</p>
		</section>

		<section id="about">
			<h1>About this page</h1>
			<p>
				Proin ante arcu, hendrerit ac diam sagittis, sollicitudin posuere ante. Etiam egestas eros at nunc venenatis eleifend eu at tellus. Quisque sodales nunc quis fermentum faucibus. Ut porttitor massa non arcu pharetra mollis. Nam sodales, quam sed sagittis molestie, dui metus sodales ex, eu placerat massa lorem nec nisi. Sed nisl est, aliquam quis purus faucibus, interdum pulvinar elit. Pellentesque pharetra blandit dolor et pharetra. Proin efficitur nulla sed dui molestie mollis. Donec gravida neque mauris, ut vulputate augue vehicula id. Suspendisse potenti.
			</p>
		</section>

		<section id="contact">
			<h1>Contact me</h1>
			<p>
				Integer porttitor vitae est vel suscipit. Fusce placerat justo at libero aliquam maximus. Proin vehicula turpis nisl, ac gravida turpis egestas sed. Vestibulum ut magna quis augue hendrerit sagittis semper et lectus. Praesent fermentum aliquet dolor ac molestie. Vivamus ut dui mi. Cras nibh est, aliquam sit amet imperdiet quis, auctor eget felis. Suspendisse varius finibus lorem, pretium suscipit urna sodales ac. Duis lectus ligula, egestas et sodales quis, pellentesque sagittis orci. Vivamus vel blandit justo, eu convallis tortor.
			</p>
		</section>
	</main>
</body>
</html>
```
