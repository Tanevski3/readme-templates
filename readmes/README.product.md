# Project name
> **Project** is ..., description, what does it solve, etc.

![Image](header.png)

## Getting started 
To get a local copy up and running follow these simple example steps.

### Prerequisites
This section will describe requirements needed to satisfy the installation or running of the project.

 - Java 1.8
 - Maven
 
### Nice to have
 - Intellij

### Build
 - `git clone https://github.com/Tanevski3/caa-experimentation.git`
 - `cd ./caa-experimentation`
 - `mvn clean install`
 
### Run
 - Find `MainEntry.java`, then right click and run
 
### Test
 - Run `mvn test`
 
### Deploy
 - `cd gui`
 - `mvn jfx:jar`
 - `mv gui/target/jfx/app/caa-experimentation-gui-${version}-jfx.jar gui/target/jfx/app/caa-experimentation-gui-${version}.jar`
 - `zip gui/target/jfx/app/. caa-experimentation-gui-${version}`
 - `rm -rf dist/*`
 - `mv caa-experimentation-gui-${version}.zip ../dist/`

## Usage guide
Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.  

## Download
 - The application is now available as a JAR file. Within the `dist/` directory of this repository the executable JAR file can be found.

## Future changes
 - Increase unit test coverage for `caa-lib` to 100% (current is 90%)
 - Support for other formats then `graphml`
 
## Contact

For contact, you can reach me at [marjantanevski@outlook.com](marjantanevski@outlook.com).

## License

MIT © [Marjan Tanevski](marjantanevski@outlook.com)