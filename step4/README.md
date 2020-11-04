# CSS basics

## Step 4 - Themes

### Dark mode

<img src="https://github.com/Thinkmill-learning-paths/css-basics/blob/main/assets/card-theme.gif" width="374px" alt="An animation showing what the task result should look like">

Use the HTML below to create a card component that can be placed in a `.light` or `.dark` section and will magically change from light to dark mode.
There should be no `.dark .card` or `.light .card` styles specified. Use css variables.

```html
<section class="light">
	<h2>Light</h2>

	<a class="card" href="#0">
		<img class="card-img" src="https://picsum.photos/id/100/600/350" alt="A placeholder image">
		<div class="card-body">
			<h2 class="card-headline">A headline</h2>
			<p class="card-text">
				Lorem ipsum dolor sit amet consectetur adipisicing elit.
				Porro sunt saepe et quae cum dolore neque,
				ea vero quasi odio quod fugit, aperiam corporis.
				Tenetur ipsam veniam alias corporis deserunt?
			</p>
		</div>
	</a>
</section>

<hr>

<section class="dark">
	<h2>Dark</h2>

	<a class="card" href="#0">
		<img class="card-img" src="https://picsum.photos/id/100/600/350" alt="A placeholder image">
		<div class="card-body">
			<h2 class="card-headline">A headline</h2>
			<p class="card-text">
				Lorem ipsum dolor sit amet consectetur adipisicing elit.
				Porro sunt saepe et quae cum dolore neque,
				ea vero quasi odio quod fugit, aperiam corporis.
				Tenetur ipsam veniam alias corporis deserunt?
			</p>
		</div>
	</a>
</section>
```

For the colors use the below specified set for each section respectively.

Light

```
bg: #fff
text: #383E48
alt-bg: #212529
alt-text: #eee
selection: #005fcc
selectionText: #fff
```

Dark

```
bg: #212529
text: #eee
alt-bg: #fff
alt-text: #383E48
selection: #cce4ff
selectionText: #383E48
```
