# ThemeColor

Create a new [Bootstrap](https://getbootstrap.com/) color palette

## Getting Started

This scss file will help you to create new color palettes and apply them whit just one class

### Prerequisites

You must install [Sass](https://sass-lang.com/), then you'll be able to run the sass executable to compile .sass and .scss files to .css files

### Installing

Clone or download

## Usage

Simply create an array in themes.scss file and add it to themes array 

```
$myTheme: (
  "primary":    $blue1,
  "secondary":  $gray-500,
  "success":    $green1,
  "info":       $grenn2,
  "warning":    $yellow1,
  "danger":     $red1,
  "light":      $gray-100,
  "dark":       $gray-800
);

...

$themes: (
  ...
  "myTheme": $myTheme,
  ...
);
```

You can chose any color from colors.scss file or add new colors when create your theme array

## Deployment

Compile style.scss file

```
sass style.scss style.css
```

Add a class to body tag using the name of your theme

```
<body class="myTheme">
    ...
</body>
```

## Authors

* **Sergio Granados** - *Initial work* - [SergioGranSol](https://github.com/SergioGranSol)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* 

