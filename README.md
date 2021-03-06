# Pierre's Treats

#### By _**Zoe Weinstein**_

#### A website that allows authorized users to add treats and flavors to a database

## Technologies Used

* SQL
* C#
* .Net
* Razor
* CSS
* HTML

## Description

This application lets an authorized user add flavors and treats. This program uses SQL tables with a many to many relationship for flavors and treats.
## Setup/Installation Requirements

* Go to https://github.com/MxZoe/PierresTreats to clone or download the project. 
* To add the sql server you must create a file named appsettings.json and add it to your .gitignore file
* The appsettings.json file should then have the following:
{
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=zoe_weinstein;uid=root;pwd=[YOUR-PASSWORD-HERE];"
    }
}
* Next, in the terminal run the command "dotnet ef migrations add initial" followed by the command "dotnet ef database update" to get the database connected and updated. You should run these commands whenever you update the models. Simply substitute the "initial" in the dotnet ef migrations command with an appropriate descriptor.
## Known Bugs

## License

https://opensource.org/licenses/MIT

Copyright (c) 2022. Zoe Weinstein