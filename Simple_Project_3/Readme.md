# Working with Bootstrap Grid

## Instructions

**Introduction** <br>

In this exercise, you will practice building a webpage using the Bootstrap Grid. <br><br>

**Goal** <br>
- Create a two-column food menu for Little Lemon.<br><br>

**Objectives**<br>
- Set up the Bootstrap container.

- Display the Little Lemon logo in the top center of the webpage using Bootstrap.

- Display the food menu in two columns using Bootstrap Grid. <br><br>

**Instructions** <br>

**Step 1:** Open index.html

**Step 2:** Add a div element inside the body element. This div will be the Bootstrap container. 

**Step 3:** Add the class attribute to this element with the value container. 

```html
<body>
    <div class="container">
    </div>
</body>
```
<br><br>
**Step 4:** Add three div elements to the Bootstrap container element. Each of these div elements will be a Bootstrap row. Add the class attribute to this element with the value row.
```html
<body>
    <div class="container">
        <div class="row">
        </div>
        <div class="row">
        </div>
        <div class="row">
        </div>
    </div>
</body>
```
<br><br>

**Step 5:** The first row will contain the Little Lemon logo. Add a div element to the first row. 

**Step 6:** Add the class attribute to this element with the value col-12. This will take up 12 column spaces.

```html
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
            </div>
        </div>
        <div class="row">
        </div>
        <div class="row">
        </div>
    </div>
</body>
```
<br><br>

**Step 7:** Add another div element to the col-12 element. 

**Step 8:** Add the class attribute to this element with the value text-center. This will allow you to center the logo.

```html
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                </div>
            </div>
        </div>
        <div class="row">
        </div>
        <div class="row">
        </div>
    </div>
</body>
```
<br><br>

**Step 9:** Add an image element in the text-center element with the img-fluid class applied to it.

```html
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
        </div>
        <div class="row">
        </div>
    </div>
</body>
```

<br><br>
**Step 10:** In the second row, add another div element with the class col-12.

```html
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
            </div>
        </div>
        <div class="row">
        </div>
    </div>
</body>
```

<br><br>

**Step 11:** Add a div element to the column and apply the class text-center.

```html
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                </div>
            </div>
        </div>
        <div class="row">
        </div>
    </div>
</body>
```

<br><br>

**Step 12:** Inside the element, add an h1 element with the text Our Menu.

```html
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <h1>Our Menu</h1>
                </div>
            </div>
        </div>
        <div class="row">
        </div>
    </div>
</body>
```
<br><br>

**Step 13:** Add two div elements in the final row. 

**Step 14:** Add a class attribute to each element with the value col-12 col-lg-6.

```html
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <h1>Our Menu</h1>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12 col-lg-6">
            </div>
            <div class="col-12 col-lg-6">
            </div>
        </div>
    </div>
</body>
```

<br><br>

**Step 15:** Add the following elements in the first col-12 col-lg-6 element: 

- An h2 element containing the text Falafel.

- A paragraph element containing the text Chickpea, herbs, spices.

- An h2 element containing the text Fried Calamari.

- A paragraph element containing the text Squid, buttermilk.

**Step 16:** Add the following elements In the second col-12 col-lg-6 element:

- An h2 element containing the text Pasta Salad.

- A paragraph element containing the text Lettuce, vegetables, mozzarella.

- An h2 element containing the text Greek Salad.

- A paragraph element containing the text Cucumbers, onion, feta cheese.

```html
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <h1>Our Menu</h1>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12 col-lg-6">
                <h2>Falafel</h2>
                <p>Chickpea, herbs, spices.</p>
                <h2>Fried Calamari</h2>
                <p>Squid, buttermilk.</p>
            </div>
            <div class="col-12 col-lg-6">
                <h2>Pasta Salad</h2>
                <p>Lettuce, vegetables, mozzarella.</p>
                <h2>Greek Salad</h2>
                <p>Cucumbers, onion, feta cheese.</p>
            </div>
        </div>
    </div>
</body>
```

<br><br>

## Video Resources:

- [Using Bootstrap styles  @Coursera](https://www.coursera.org/learn/introduction-to-back-end-development/lecture/ETatJ/using-bootstrap-styles)
- [Bootstrap grid @Coursera](https://www.coursera.org/learn/introduction-to-back-end-development/lecture/JcTk4/bootstrap-grid)
