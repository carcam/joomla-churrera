# joomla-churrera

Phing script to setup joomla extensions from the boilerplate

## Requirements

*nix system

## Usage

1. Clone the Joomla! boilerplate repository to a local folder. The boilerplate can be found at https://github.com/joomla-extensions/boilerplate

2. Clone this repository to another folder

3. Rename the file paths.build.properties.dist to paths.build.properties and fill in the desired values for your extension.

4. Run 

`phing setup`

This command will copy the boilerplate to the destination folder and it will substitute the generic name 'Foo' for your chosen name.

5. Go to the build folder inside the repofolder (location of the new extension files) and run

`phing build`

This command will package the extension files and folders into a *.zip file ready to install.

