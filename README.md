# BIC4 Project

This project can be used as abase for further development with laravel and vue.

## Development Stack installation

Only the installation on Windows10 will be described. For detailed instructions of setting up development stack in
other operating systems follow links in description.

Documentation and more information about the used framework can be found on the following websites:
- [Laravel](www.laravel.com)
- [Laracasts](www.laracasts.com)

### Download and install 

Required:
 - [Git](https://www.git-scm.com/)
 - [PHP 7.3](https://www.php.net/)
 - [Composer](https://getcomposer.org/)
 - [Node.js LTS Version](https://nodejs.org/)

Recommended IDE:
 - [PHPStorm IDE](https://www.jetbrains.com/de-de/phpstorm/)
 
   Get [education license](https://www.jetbrains.com/community/education/) for all [JetBrains Developer Tools](https://www.jetbrains.com/).<br>
   **Apply with technikum mail address!**

#### Windows PHP installation

1. To use php on windows following installation need to be done first if it’s not already installed:
  - [64 bit OS](https://aka.ms/vs/16/release/VC_redist.x64.exe) 
  - [32 bit OS](https://aka.ms/vs/16/release/VC_redist.x86.exe)
2. [Download PHP](https://gitlab.hathor.at/fh-technikum/BIC4BaseProject/-/wikis/uploads/67a0d6bc914363d93af0e0b5f6519de5/php.zip)
2. Extract downloaded ```php.zip``` file and move the folder to ```C:\Program Files```
3. Press the button ``` windows and R ```
4. Type ```sysdm.cpl``` and press enter
5. Click on ```Advanced``` and open ```EnvironmentVariables...```
6. Select ```Path``` in ```Systemvariables``` and click on ``edit``
7. Add the path ``C:\Program Files\php`` to the list
8. If everything went successful running the command ``php -v`` in windows command line will give result

#### Other OS

* OSX:
   - [Valet](https://laravel.com/docs/7.x/valet)
* Linux:
   - [Homestead](https://laravel.com/docs/7.x/homestead)
 
### Prepare project for development

1. Fork this or one of the following Repositories:
    * [Klingon in 10 tupmey - A dictionary for every ghot](https://github.com/AVAtric/BIC4KlingonDictionary)
    * [The Peruvian cookbook](https://github.com/AVAtric/BIC4PeruvianRecipe)
    * [The register of exotic animals](https://github.com/AVAtric/BIC4ExoticAnimals)
    * [The magic almanac](https://github.com/AVAtric/BIC4MagicAlmanac)
    * [The library of bizarre inventions](https://github.com/AVAtric/BIC4BizarreInventions)
    * [The films about the unknown](https://github.com/AVAtric/BIC4FilmsUnknown)
2. Clone with ```git clone``` the forked repository to the PHPStorm project directory.
3. Download and move 
[SQLite database file](https://gitlab.hathor.at/fh-technikum/BIC4BaseProject/-/wikis/uploads/6175ab189c5bcd0b38283c658dfe56b7/database.zip) to ```database``` directory in cloned project.
4. Run ```composer install``` and ```npm install``` in project folder.
5. Open project with PHPStorm 
