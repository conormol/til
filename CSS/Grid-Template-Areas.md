# Grid-Template-Areas

The grid-template-areas property allows us to name areas of the grid. The property is declared in a grid container. For example:

## html file:
```
<div class="container">
  <header>Welcome</header>
  <nav>Nav</nav>
  <section class="info">Info</section>
  <section class="services">Services</section>
  <footer>Footer</footer>
</div>
```

## css file:
```
.container {
  grid-template-areas: "header header"
                       "nav nav"
                       "info services"
                       "footer";
  grid-template: repeat(4, 200px)/ repeat 2(200 px);
}
```

Here, there are 4 rows of 200px and 2 columns of 200px. The top row is the header, spanning both columns. The second row is the nav, spanning both columns. The third rwo contains the info and services section, spanning 1 column each. The fourth row is the footer, spanning two columns.
