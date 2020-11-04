# CSS basics

## Step 5 - Stacking context

## Create new context

Given the below HTML and CSS, move the `One` div into the background, but:

- Do not alter the HTML markup in any way
- Do not add/change the `z-index` property of any element
- Do not add/change the `position` property of any element

```html
<div><div class="one">One</div></div>
<div><div class="two">Two</div></div>
<div><div class="three">Three</div></div>
```

```
.one,
.two,
.three {
	position: absolute;
	padding: 1.5rem;
}
.one {
	background: red;
	z-index: 1;
	top: 0;
	left: 0;
}
.two {
	background: green;
	top: 2rem;
	left: 2rem;
}
.three {
	background: blue;
	top: 4rem;
	left: 4rem;
}
```

## Logo scroll

<img src="https://github.com/Thinkmill-learning-paths/css-basics/blob/main/assets/logo-scroll.gif" width="318px" alt="An animation showing how the scroll behaves">

Use the below HTML and re-create the scroll shown above. Do not use JavaScript.

```html
<header></header>
<main>
	<aside>
		<div class="logo"></div>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit.
			Deleniti beatae distinctio quaerat eveniet cumque quis natus quod ut nobis illo,
			libero, recusandae consequuntur consectetur, veniam minus.
			Earum nostrum praesentium odit?
		</p>
		<p>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit.
			Provident possimus asperiores alias!
			Placeat corporis ipsum repellat in dolor amet incidunt dolorum, accusamus ab!
			Laudantium quas ipsam vitae, optio rerum harum? Lorem ipsum dolor sit amet, consectetur adipisicing elit.
			Iure ipsa suscipit repellat molestias facere architecto labore a, rem impedit voluptates sed officiis,
			numquam perferendis eligendi quidem similique quasi eum corporis.
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit.
			Deleniti beatae distinctio quaerat eveniet cumque quis natus quod ut nobis illo,
			libero, recusandae consequuntur consectetur, veniam minus.
			Earum nostrum praesentium odit?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit.
			Ut doloremque sit expedita quibusdam ipsa quos quidem.
			Ut, fugiat ea veritatis veniam tenetur aut exercitationem maiores.
			Obcaecati corrupti dolores sint dolor. Lorem ipsum dolor sit amet consectetur adipisicing elit.
			Eos qui labore, quidem similique odio consequatur rerum sint autem?
			Maxime sapiente omnis repellat? Alias ducimus voluptatum rem distinctio vitae deleniti repellendus?
		</p>
	</aside>
</main>
```
