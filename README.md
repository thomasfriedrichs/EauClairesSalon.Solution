# _{Eau Claires Salon}_

#### _{A client and stylist organizing tool for the salon}_

#### By _**{Thomas Friedrichs}**_

## Technologies Used

* _C#_
* _.NET_
* _SQL_
* _vsCode_

## Description

_{This program uses one to many relationships to create and track stylists along with the clients they have.}_

## Setup/Installation Requirements

* _Clone this repository https://github.com/thomasfriedrichs/EauClairesSalon.Solution_
* _Do a dotnet restore in the terminal_
* _Create an SQL database using mySQL: create schema using 'firstname underscore lastname', create sylists table, create clients table_
* _Make sure to jot down your user id and password, along with any other critical info you may need in the settings config below_
* _make an appsettings.json file._
* _paste the following in your appsettings:_
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=[portnumber];database=[Schema-name];userid=[your-id];pwd=[your-password];"
  }
}
* _run the app by typing 'dotnet watch run' in the terminal_
* _visit the app via localhost:5000/_

## Known Bugs

* _Having trouble entering the stylist index_

## License

MIT License

Copyright (c) [year] [fullname]

_{If you have any questions or concerns please feel free to contact me!}_

## Contact Information

_{Thomas Friedrichs friedrichs.tommy@gmail.com}_