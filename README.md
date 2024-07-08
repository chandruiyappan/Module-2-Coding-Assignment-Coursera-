### Module-2-Coding-Assignment-Coursera-:

### HTML CODE:
```
<!DOCTYPE html>
<html lang="en">
    <link rel="stylesheet" href="style.css">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Layout</title>
</head>
<body>
    <div class="container">
        <h1>OUR MENU</h1>
        <div class="section">
            <div class="section-title">Chicken</div>
            <div class="section-content">
                Chicken tastes a bit like a mild sourdough bread but denser, more moist, more fine grained, more proteiny and stringy.
            </div>
        </div>
        <div class="section">
            <div class="section-title">bread omlete</div>
            <div class="section-content">
                Bread omelette is a popular street food recipe all over india. This bread omelette recipe shown here is made three ways.
            </div>
        </div>
        <div class="section">
            <div class="section-title">chicken rice</div>
            <div class="section-content">
                Recipe for chicken rice, a popular street side special where the fried chicken, eggs and veggies are tossed in rice and spices.
            </div>
        </div>
    </div>
</body>
</html>
```
### CSS CODE:
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.container {
    width: 100%;
    padding: 10px;
    box-sizing: border-box;
}
h1 {
    text-align: center;
    font-size: 2.5em;
}
.section {
    border: 1px solid black;
    padding: 10px;
    margin: 10px 0;
    background-color: #f0f0f0;
    position: relative;
}
.section-title {
    position: absolute;
    top: 10px;
    right: 10px;
    background-color: #333;
    color: #fff;
    padding: 5px;
    border: 1px solid black;
    font-size: 1.25em;
}
.section-content {
    padding-top: 40px;
}

/* Desktop layout */
@media (min-width: 992px) {
    .section {
        float: left;
        width: 32%;
        margin: 10px 1%;
    }
}

/* Tablet layout */
@media (min-width: 768px) and (max-width: 991px) {
    .section:nth-child(1),
    .section:nth-child(2) {
        float: left;
        width: 48%;
        margin: 10px 1%;
    }
    .section:nth-child(3) {
        clear: both;
        width: 98%;
        margin: 10px 1%;
    }
}

/* Mobile layout */
@media (max-width: 767px) {
    .section {
        width: 98%;
        margin: 10px 1%;
        clear: both;
    }
}
```
### OUTPUT:

### For Desktop View:

![Screenshot (26)](https://github.com/chandruiyappan/Module-2-Coding-Assignment-Coursera-/assets/123877158/ebb0144e-a56a-46b1-9e87-753af6f7b883)

### For Tablet View:

![Screenshot (27)](https://github.com/chandruiyappan/Module-2-Coding-Assignment-Coursera-/assets/123877158/736d94de-d34d-4316-9a85-73bbf0d83322)

### For Mobile View:

![Screenshot (28)](https://github.com/chandruiyappan/Module-2-Coding-Assignment-Coursera-/assets/123877158/e1bddecc-9030-498c-8ed9-cfc860c8756d)
