# DDEV PHPStorm Commandline integration

This plugins provides auto completition for `ddev` in phpstorm.  

## Getting Started

0. Open PhpStorm, install DDev
1. Navigate to Settings | Command Line Tool Support and add custom configuration
2. Add the Framework Name (e.g. "DDev"), the Tool path (e.g. "ddev") and the Alias (e.g. "ddev")
3. Import the XML configuration file available here: https://github.com/4viewture/ddev-phpstorm-cl-xml/ddev-phpstorm-cl.xml by copying in the Custom_ddev.xml provided by phpstorm.
4. you may need to adjust the schema version in the xml intro.

### How to use it

1. Open a DDev project in PhpStorm and press CTRL + SHIFT + X
3. Enter a DDev command by using the alias defined in the configuration (in this example "ddev")

### Prerequisites

* ddev
* phpstorm


## Contributing

Please first create an issue and then the related Pull request. 

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Kay Strobach** - *Initial work* - [PurpleBooth](https://github.com/kaystrobach)

See also the list of [contributors](https://github.com/4viewture/ddev-phpstorm-cl-xml/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details