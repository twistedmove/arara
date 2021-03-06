![arara](http://i.imgur.com/GwP1AQS.png)

# arara

`arara` is a TeX automation tool based on rules and directives. It gives you subsidies to enhance your TeX experience. The tool is an effort to provide a concise way to automate the daily TeX workflow for users and also package writers. Users might write their own rules when the provided ones do not suffice.

## Current status

The `arara` team is working on the new 4.0 version. The code is ready and we are now focusing on rules, translations and the documentation itself. It might take a while since a lot of things have changed since version 3.0, so the manual has to be completely rewritten. Hopefully, we will release it soon. `:)`

- *Current TL version:* 3.0 (codebase is available in the [releases](https://github.com/cereda/arara/releases) section)
- *Development/upcoming version:* 4.0 (the repository itself holds the last changes)

## Build status

`arara` uses [Travis CI](https://travis-ci.org) as a hosted continuous integration service. For each and every commit, we can see in real time the build status of our application checked against the following Java VM vendors:

- OpenJDK 6.0
- OpenJDK 7.0
- Oracle Java 7.0
- Oracle Java 8.0

More JVM's might be added soon. It is worth noting that `arara` is designed and built to be Java 5.0 compliant, so if you have an old JVM, it is almost sure that you will be able to run our beloved tool in it without any problems.

*Current build status:* [![Build Status](https://travis-ci.org/cereda/arara.svg?branch=master)](https://travis-ci.org/cereda/arara)

## Support

We use a [Gitter](https://gitter.im) chatroom for discussing things related to `arara`. You are more than welcome to come join the fun and say *hi!* to us. We also have the [issues](https://github.com/cereda/arara/issues) section in our repository as a valid channel to report problems, bugs and suggest improvements. 

*Our Gitter chatroom:* [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/cereda/arara?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Localization

Would you like to make `arara` speak your own language? Splendid! We would love to have you in the team! Just send us an e-mail, join our dedicated chatroom or open an issue about it. The localization process is quite straightforward, we can help you! `:)` Any language is welcome!

## Downloads

Binary releases are powered by Bintray and not available in the repository anymore. You can [click here](https://bintray.com/cereda/arara/installers/_latestVersion) or use the button below to get access to the current 3.0 release. Note that you need Java to run both the installer and `arara` itself.

*Download:* [![Download](https://api.bintray.com/packages/cereda/arara/installers/images/download.png)](https://bintray.com/cereda/arara/installers/_latestVersion)

If you want to try out the development version, you need to build it from source. It is actually a straightforward process: just clone this repository, go to the `application/` directory and run `mvn assembly:assembly` (you need [Apache Maven](http://maven.apache.org/) for this); you'll get the resulting `.jar` file in a `target/` directory. Have fun!

## License

This application is licensed under the [New BSD License](http://www.opensource.org/licenses/bsd-license.php).Please note that the New BSD License has been verified as a GPL-compatible free software license by the [Free Software Foundation](http://www.fsf.org/), and has been vetted as an open source license by the [Open Source Initiative](http://www.opensource.org/).

### The core team

- ![Brazil](http://i.imgur.com/If4PQTk.png) Paulo Roberto Massa Cereda *(benevolent `arara` Dictator and Pope, wacky bloke, duck enthusiast, writes coffee and drinks code)*
- ![Germany](http://i.imgur.com/GovD283.png) Marco Daniel *(Cardinal Camerlengo of the Holy Bird, next one in succession, insanely fast driver, writes rules for everything)*
- ![United Kingdom](http://i.imgur.com/Lvp73Wo.png) Brent Longborough *(Cardinal Prefect of the Keming Inquisition, Pope's confessor, `memoir` fanboy, photography enthusiast, regular expression evangelist)*
- ![United Kingdom](http://i.imgur.com/Lvp73Wo.png) Nicola Louise Cecilia Talbot *(Cardinal Prefect of the Congregation for Holy Rules and the Discipline of the Directives, hat enthusiast, fixes Pope's code)*
