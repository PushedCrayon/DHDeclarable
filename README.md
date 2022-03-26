```
  _____   _    _  _____               _                     _      _       
 |  __ \ | |  | ||  __ \             | |                   | |    | |      
 | |  | || |__| || |  | |  ___   ___ | |  __ _  _ __  __ _ | |__  | |  ___ 
 | |  | ||  __  || |  | | / _ \ / __|| | / _` || '__|/ _` || '_ \ | | / _ \
 | |__| || |  | || |__| ||  __/| (__ | || (_| || |  | (_| || |_) || ||  __/
 |_____/ |_|  |_||_____/  \___| \___||_| \__,_||_|   \__,_||_.__/ |_| \___|
 
```
## DHDeclarable
[![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2Fdan-hart%2FDHDeclarable%2Fbadge%3Ftype%3Dswift-versions)](https://swiftpackageindex.com/dan-hart/DHDeclarable)
[![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2Fdan-hart%2FDHDeclarable%2Fbadge%3Ftype%3Dplatforms)](https://swiftpackageindex.com/dan-hart/DHDeclarable)
[![run tests](https://github.com/dan-hart/DHDeclarable/actions/workflows/test.yml/badge.svg)](https://github.com/dan-hart/DHDeclarable/actions/workflows/test.yml)
[![codecov](https://codecov.io/gh/dan-hart/DHDeclarable/branch/dev/graph/badge.svg?token=X0G7HAZ7S4)](https://codecov.io/gh/dan-hart/DHDeclarable)
[![GitHub license](https://img.shields.io/github/license/dan-hart/DHDeclarable)](https://github.com/dan-hart/DHDeclarable/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/dan-hart/DHDeclarable)](https://github.com/dan-hart/DHDeclarable/issues)
[![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fdan-hart%2FDHDeclarable)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fdan-hart%2FDHDeclarable)
[![GitHub forks](https://img.shields.io/github/forks/dan-hart/DHDeclarable)](https://github.com/dan-hart/DHDeclarable/network)
[![GitHub stars](https://img.shields.io/github/stars/dan-hart/DHDeclarable)](https://github.com/dan-hart/DHDeclarable/stargazers)
[![Maintainability](https://api.codeclimate.com/v1/badges/4e7c983f2dccaf66dfa4/maintainability)](https://codeclimate.com/github/dan-hart/DHDeclarable/maintainability)
![GitHub last commit](https://img.shields.io/github/last-commit/dan-hart/DHDeclarable)
![Maintenance](https://img.shields.io/maintenance/yes/2022)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/dan-hart/DHDeclarable)
![GitHub followers](https://img.shields.io/github/followers/dan-hart?style=social)
[![Donatecoins](http://donatecoins.org/btc/1HeMeMU2qUFDRZpRQMJ2v27Dw3h3gShJ5b.svg)](http://donatecoins.org/btc/1HeMeMU2qUFDRZpRQMJ2v27Dw3h3gShJ5b)
### 🌉 A bridge from `UIKit` to `SwiftUI`

```Swift
import DHDeclarable
class ViewController: DHDViewController {
    override var titled: String? { "DHDeclarable" }
    override var renderingMode: DHDViewControllerContentRenderingMode { .center }
    
    override var body: UIView {
        get {
            DHDLabel("Hello, World!")
                .tagged(viewTag)
        }
        set { super.body = newValue }
    }
}
```

<img src="https://user-images.githubusercontent.com/13913605/159046409-251ba885-fd6c-48af-a728-a49c85686ae4.JPG" height="500">

### Tired of Storyboards? Not ready for SwiftUI?
* `DHDeclarable` adds declarative syntax to `UIKit`
* No more assigning constraints in Interface Builder
* One source of truth for your user interface code

### Getting Started
* [Introduction](https://dan-hart.github.io/DHDeclarable/)
* [Examples](https://dan-hart.github.io/DHDeclarable/DHDeclarable-Examples.html)
* [API Documentation](https://dan-hart.github.io/DHDeclarable/reference/)

#### Available as a Swift Package: `https://github.com/dan-hart/DHDeclarable`

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/codedbydan)
