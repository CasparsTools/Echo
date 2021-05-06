# Echo Spigot Plugin
Echo is a screenshare tool for catching cheaters in minecraft. This plugin allows you to more efficently run scans through echo directly through the server.

To download the plugin, visit: https://github.com/Cowings/Echo/releases

Features:
* **Staff API Keys** - each staff member must use their own API key, this data is stored in a json file.
* **Automatic Screensharing** - run a simple /freeze command and it will automatically generate a download link and keep you updated on the status of the scan.
* **Freezing** - completely freezes a player and runs a variety of tasks that any regular freeze plugin would have.
* **Configurable** - almost every message and aspect of the plugin is configurable via a config.yml
* **Free** - available for download and usage at no cost, and permissively licensed so it can remain free forever.

## Building
Echo Plugin uses Maven to handle dependencies & building.

#### Requirements
* Java 8 JDK or newer
* Git

#### Compiling from source
```sh
git clone https://github.com/Cowings/Echo
cd Echo/
mvn clean install
```

## Contributing
#### Pull Requests
If you make any changes or improvements to the plugin which you think would be beneficial to others, please consider making a pull request to merge your changes back into the upstream project. (especially if your changes are bug fixes!)

Echo Plugin loosely follows the [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html). Generally, try to copy the style of code found in the class you're editing. 

Please make sure to have bug fixes/improvements in seperate pull requests from new features/changing how features work.

## License
Echo Plugin is licensed under the permissive MIT license. Please see [`LICENSE.txt`](https://github.com/lucko/Echo/blob/master/LICENSE.txt) for more info.

## Other
Credits to Luckperm for the layout of this readme file.
