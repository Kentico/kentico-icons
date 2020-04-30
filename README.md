# Kentico Icons

Kentico icons are the official icon set from Kentico that we use in our products — [Kentico CMS/EMS](https://www.kentico.com/) and [Kentico Kontent](https://kontent.ai/).

## Getting Started

### Using the icons in your app
**production/** directory holds all sources you need. **production/fonts/** contains font files and **production/icon-variables.less** is mapping between icon font symbol and icon name. We recommend using icon-variables as font symbols can be subject to change. Do not forget to set up your [css font-face](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face).

You can either:
* generate your own icon set (see instructions in the section below),
* use [icons-processor](https://github.com/Kentico/icons-processor) to generate the list of LESS icon variables for your app,
* or create your own generator to create your LESS/SASS/CSS file out of selection.json

### Adjusting source icons
Source icons are located in **design** folder as SVG files. Feel free to adjust or expand the set according to your needs.

### Generating your own icon set
In the **production** folder there is **selection.json** file. Use **selection.json** to import it as a Project into [Icomoon's app](https://icomoon.io/app/#/projects). By loading a project you'll be able to select and eventually generate your own icon set with corresponding font and CSS files.


## License

We have made these icons available for you to incorporate them into your products or web apps under the [MIT License](https://opensource.org/licenses/MIT). Feel free to remix and re-share these icons and documentation in your products.
We'd love attribution in your app's *about* screen, but it's not required. The only thing we ask is that you do not re-sell these icons.

![Analytics](https://kentico-ga-beacon.azurewebsites.net/api/UA-69014260-4/Kentico/kentico-icons?pixel)
