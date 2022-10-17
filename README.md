# Factory
 
#### By **Kelly Bruce**
 
#### Tracks engineers and machines
 
## Technologies Used
 
* C#
* .NET 5.0 Framework
* HTML
* MySQL
* Entity

 
## Description
 
Stores machines that need maintenance and engineers who are qualified to work on them. 

 
## Setup/Installation Requirements


* Clone the repository to your desktop
* Open the repository in Visual Studio Code
* Open your terminal and navigate to the project folder folder
* Run '$ dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0' in terminal
* Run '$ dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2' in terminal
* Run '$ dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0' in terminal to install Lazy Loading
* Run '$ dotnet restore' in terminal
* Create a file named 'appsettings.json
  * file should include {
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=database_name;uid=root;pwd=YOUR_PASSWORD;"
  }
} 
* In MySQL - Import the data 
* run 'dotnet run' in the terminal to start the program

 
## Known Bugs
 
* No known bugs

## License

[MIT](https://en.wikipedia.org/wiki/MIT_License)

Copyright (c) 2022 Kelly Bruce