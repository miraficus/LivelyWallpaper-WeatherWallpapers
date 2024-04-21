# LivelyWallpaper-WeatherWallpapers
Basically a website that gets pictures from [Unsplash](https://unsplash.com/t/wallpapers) and then overlays [Wttr.in](https://github.com/chubin/wttr.in) over it.

- [Website](https://miraficus.github.io/LivelyWallpaper-WeatherWallpapers/)
- [Website with URL parameters](https://miraficus.github.io/LivelyWallpaper-WeatherWallpapers/?lang=cs&city=Brno&refresh=1800&category=nature&width=1920&height=1080&widget=topleft)

## TODO
### Add URL parameters.
Example: ?lang=cs&city=Brno&refresh=1800&category=nature&width=1920&height=1080&widget=topleft

- [x] lang: Language of the weather widget.
- [x] city: Name of city to check weather for.
- [ ] refresh: After how many seconds you want to refresh the website. (To get new weather information and new wallpaper)
- [x] category: Select the category of pictures you want to see. Example: nature, mountains, cars...
- [x] width: Width of unsplash wallapaper.
- [x] height: Width of unsplash wallapaper.
- [ ] widget: Position of the weather widget. Options: topleft, topright, bottomleft, bottomright.

Variable called resolution shouldnt change just the resolution of the wallpaper but also the size of iframe and div!!


### Links for me
[Getting a URL Parameter](https://www.sitepoint.com/get-url-parameters-with-javascript/)