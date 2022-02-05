# Clean Hugo Blog Theme

## Features
- Responsive
- Honors dark and light color preference 
   - Syntax highlighting for dark and light colors
- Left and bottom navigation
- Layout for an archive page

## Demo

  - https://hugodemo.hoogi.eu

## Screenshot

 - Dark mode

[![](images/darkmode.png)](images/darkmode.png)

 - Light mode
 
[![](images/lightmode.png)](images/lightmode.png)

- Mobile

[![](images/mobile.png)](images/mobile.png)


## Installation 

 - Clone repository: 
   - `git clone https://github.com/lhooge/hugo-theme-hoogi.git`
 - To see the example site run command from exampleSite directory: 
   - `hugo server -t ../../  -D`
 - For detailed theme installation see:
   - https://gohugo.io/getting-started/quick-start/
   
   
# Configuration

To inject custom HEAD elements create a "head-custom.html" in '<YOUR_SITE>/layouts/partials'.

For changing colors see the overridden link visited example for the dark theme in 'exampleSite/layouts/partials/head-custom.html'.

```
[params]
    # If set to 'true' a summary will be shown on list overview, otherwise the complete post is shown.
    useSummary = true | false
    # Shows a right sidebar with all categories.
    sidebar = true | false
```

## License

Code License: Released under the [MIT](https://github.com/lhooge/hugo-theme-hoogi/blob/master/LICENSE) license.

## Third party 
 
 - Rubik font designed by Hubert and Fischer, Meir Sadan, Cyreal
   - https://fonts.google.com/specimen/Rubik