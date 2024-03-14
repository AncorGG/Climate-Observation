# Climate Observation

XML Schema validation of a climate observation xml

## About App

This App would be usefull for climate observant enthusiants who are passioned to spread a Daily observation of their surroundings. User's may be able to add their report which is saved and evaluated in an xml file.

## How It Works

The user may add information using a form on the App filling the main fields ( key, reference, scale and units, value, width ) the other information ( code, index ) will be automatically filled by the app. Once submited, the information will be composed as a new <'element'> and added at the end of the file insed the <'messages'> tab.

### Validation

Lets check how the validation occurs

Elements may be composed in one of these three ways

[Basic Elements](https://github.com/AncorGG/Climate-Observation/blob/master/img/BasicElements.png)

Key elements may only be composed of a key and a value

[Key Elemet](https://github.com/AncorGG/Climate-Observation/blob/master/img/KeyElement.png)

The Extended elements can have the value with the 'null' atributte but in either case it always has to exist.

[Extended Element](https://github.com/AncorGG/Climate-Observation/blob/master/img/ExtendedElement.png)


## Built With

* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2#file-readme-template-md) - The amazing template!
* [AEMET](https://opendata.aemet.es/centrodedescargas/inicio) - Open Data xml file
* [Visual Studio Code](https://code.visualstudio.com) - Used for developing the code.
* [Git](https://code.visualstudio.com) - Used for source code management.
* [W3Schools](https://www.w3schools.com/) - Great Info explanation

## Authors

* **Ancor García Guedes** - (https://github.com/AncorGG)

## Acknowledgments

* Open Data xml
* Climate enthusiasts
* Fabulous Teachers
