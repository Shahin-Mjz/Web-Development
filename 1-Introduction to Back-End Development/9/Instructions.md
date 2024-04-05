# Instructions

**Introduction**

You will revise your biographical page to use Bootstrap.

**Goal**

- Use Bootstrap to build your biographical page.

**Objectives**

- Add a Bootstrap Grid to the page.

- Set up the grid so that the content will layout correctly on both mobile and desktop.

- Configure your photo to be responsive.

- Change the Meta profile link to use a Bootstrap button style.

**Learner Instructions**

**Step 1:** Open index.html

**Step 2:** Add a `div` element to the `body` element.
```html
<body>
    <div>
    </div>
</body>
```

**Step 3:** Apply the Bootstrap `container` CSS class to the `div`.
```html
<body>
    <div class="container">
    </div>
</body>
```

**Step 4:** Add a `div` element to the `container` element.
```html
    <div class="container">
        <div>
        </div>
    </div>
```

**Step 5:** Apply the Bootstrap `row` CSS class to the `div`.
```html
    <div class="container">
        <div class="row">
        </div>
    </div>
```

**Step 6:** Add two `div` elements to the `row` element.
```html
    <div class="container">
        <div class="row">
            <div>
            </div>
            <div>
            </div>
        </div>
    </div>
```

**Step 7:** On the first div element apply the `id` attribute with the value `bio`.
```html
    <div class="container">
        <div class="row">
            <div id="bio">
            </div>
            <div>
            </div>
        </div>
    </div>
```

**Step 8:** Apply the `id` attribute on the second div element with the value `more`.
```html
    <div class="container">
        <div class="row">
            <div id="bio">
            </div>
            <div id="more">
            </div>
        </div>
    </div>
```

**Step 9:** Apply the correct CSS classes so that each div with be 12 columns wide on mobile and 6 columns wide on desktop.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6">
            </div>
            <div id="more" class="col-12 col-lg-6">
            </div>
        </div>
    </div>
```

**Step 10:** Apply the `text-center` CSS class on the bio div element.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
            </div>
            <div id="more" class="col-12 col-lg-6">
            </div>
        </div>
    </div>
```

**Step 11:**  Add an `h1` heading containing your name as the text inside the bio div element.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
            </div>
            <div id="more" class="col-12 col-lg-6">
            </div>
        </div>
    </div>
```

**Step 12:** Add an `img` element for `photo.jpg` below the `h1` element.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
                <img src="photo.jpg">
            </div>
            <div id="more" class="col-12 col-lg-6">
            </div>
        </div>
    </div>
```

**Step 13:** Apply the `img-fluid` CSS class to the img element.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
                <img src="photo.jpg" class="img-fluid">
            </div>
            <div id="more" class="col-12 col-lg-6">
            </div>
        </div>
    </div>
```

**Step 14:** Add an `h2` heading containing the text Favorite Music Artists inside the more div element.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
                <img src="photo.jpg" class="img-fluid">
            </div>
            <div id="more" class="col-12 col-lg-6">
                <h2>Favorite Music Artists</h2>
            </div>
        </div>
    </div>
```

**Step 15:** Add an unordered list of your favorite music artists below the h2 heading.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
                <img src="photo.jpg" class="img-fluid">
            </div>
            <div id="more" class="col-12 col-lg-6">
                <h2>Favorite Music Artists</h2>
                <ul>
                    <li>Metallica</li>
                    <li>Bob Marley</li>
                    <li>Madonna</li>
                    <li>The Beatles</li>
                    <li>Pink Floyd</li>
                </ul>
            </div>
        </div>
    </div>
```

**Step 16:** Add another `h2` heading containing the text Favorite Films below the favorite music artists list.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
                <img src="photo.jpg" class="img-fluid">
            </div>
            <div id="more" class="col-12 col-lg-6">
                <h2>Favorite Music Artists</h2>
                <ul>
                    <li>Metallica</li>
                    <li>Bob Marley</li>
                    <li>Madonna</li>
                    <li>The Beatles</li>
                    <li>Pink Floyd</li>
                </ul>
                <h2>Favorite Films</h2>
            </div>
        </div>
    </div>
```

**Step 17:** Add an *ordered* list of your top 5 films after the Favorite Films heading.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
                <img src="photo.jpg" class="img-fluid">
            </div>
            <div id="more" class="col-12 col-lg-6">
                <h2>Favorite Music Artists</h2>
                <ul>
                    <li>Metallica</li>
                    <li>Bob Marley</li>
                    <li>Madonna</li>
                    <li>The Beatles</li>
                    <li>Pink Floyd</li>
                </ul>
                <h2>Favorite Films</h2>
                <ol>
                    <li>Pulp Fiction</li>
                    <li>The Godfather</li>
                    <li>The Lord of the Rings</li>
                    <li>Iron Man</li>
                    <li>Inception</li>
                </ol>
            </div>
        </div>
    </div>
```

**Step 18:** Add an anchor tag after the *ordered* list.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
                <img src="photo.jpg" class="img-fluid">
            </div>
            <div id="more" class="col-12 col-lg-6">
                <h2>Favorite Music Artists</h2>
                <ul>
                    <li>Metallica</li>
                    <li>Bob Marley</li>
                    <li>Madonna</li>
                    <li>The Beatles</li>
                    <li>Pink Floyd</li>
                </ul>
                <h2>Favorite Films</h2>
                <ol>
                    <li>Pulp Fiction</li>
                    <li>The Godfather</li>
                    <li>The Lord of the Rings</li>
                    <li>Iron Man</li>
                    <li>Inception</li>
                </ol>
                <a></a>
            </div>
        </div>
    </div>
```

**Step 19:** Link to your Meta profile in the anchor tag.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
                <img src="photo.jpg" class="img-fluid">
            </div>
            <div id="more" class="col-12 col-lg-6">
                <h2>Favorite Music Artists</h2>
                <ul>
                    <li>Metallica</li>
                    <li>Bob Marley</li>
                    <li>Madonna</li>
                    <li>The Beatles</li>
                    <li>Pink Floyd</li>
                </ul>
                <h2>Favorite Films</h2>
                <ol>
                    <li>Pulp Fiction</li>
                    <li>The Godfather</li>
                    <li>The Lord of the Rings</li>
                    <li>Iron Man</li>
                    <li>Inception</li>
                </ol>
                <a href="https://www.meta.com/user/12"></a>
            </div>
        </div>
    </div>
```

**Step 20:** Set the anchor text to display My Meta Profile.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
                <img src="photo.jpg" class="img-fluid">
            </div>
            <div id="more" class="col-12 col-lg-6">
                <h2>Favorite Music Artists</h2>
                <ul>
                    <li>Metallica</li>
                    <li>Bob Marley</li>
                    <li>Madonna</li>
                    <li>The Beatles</li>
                    <li>Pink Floyd</li>
                </ul>
                <h2>Favorite Films</h2>
                <ol>
                    <li>Pulp Fiction</li>
                    <li>The Godfather</li>
                    <li>The Lord of the Rings</li>
                    <li>Iron Man</li>
                    <li>Inception</li>
                </ol>
                <a href="https://www.meta.com/user/123">My Meta Profile</a>
            </div>
        </div>
    </div>
```

**Step 21:** Apply the button Bootstrap component CSS class to the anchor tag.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
                <img src="photo.jpg" class="img-fluid">
            </div>
            <div id="more" class="col-12 col-lg-6">
                <h2>Favorite Music Artists</h2>
                <ul>
                    <li>Metallica</li>
                    <li>Bob Marley</li>
                    <li>Madonna</li>
                    <li>The Beatles</li>
                    <li>Pink Floyd</li>
                </ul>
                <h2>Favorite Films</h2>
                <ol>
                    <li>Pulp Fiction</li>
                    <li>The Godfather</li>
                    <li>The Lord of the Rings</li>
                    <li>Iron Man</li>
                    <li>Inception</li>
                </ol>
                <a href="https://www.meta.com/user/123" class="btn">My Meta Profile</a>
            </div>
        </div>
    </div>
```

**Step 22:** Apply the primary modifier to the button component.
```html
    <div class="container">
        <div class="row">
            <div id="bio" class="col-12 col-lg-6 text-center">
                <h1>Jane</h1>
                <img src="photo.jpg" class="img-fluid">
            </div>
            <div id="more" class="col-12 col-lg-6">
                <h2>Favorite Music Artists</h2>
                <ul>
                    <li>Metallica</li>
                    <li>Bob Marley</li>
                    <li>Madonna</li>
                    <li>The Beatles</li>
                    <li>Pink Floyd</li>
                </ul>
                <h2>Favorite Films</h2>
                <ol>
                    <li>Pulp Fiction</li>
                    <li>The Godfather</li>
                    <li>The Lord of the Rings</li>
                    <li>Iron Man</li>
                    <li>Inception</li>
                </ol>
                <a href="https://www.meta.com/user/123" class="btn btn-primary">My Meta Profile</a>
            </div>
        </div>
    </div>
```

**Step 23:** Save the file.