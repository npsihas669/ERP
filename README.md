# ERP
Clase Avanzada

JAJAJAJA hola

Clase Usuario 

HEADER 

```
#include <string>
#include <iostream>
#include <ctime>



class Usuario {
    
    
public:
    Usuario();
    
    
private:
    
    
protected:
    int id = 0;
    std::string username = "";
    std::string password = "";
    std::string role = "";
    std::string name = "";
    std::string lastname = "";
    std::time_t date_joined = std::time(0);
    
};
```

CPP
````
#include <string>
#include "Usuario.hpp"
#include <iostream>

using namespace std;


Usuario::Usuario()
{
    
    ;
    
}

````

Clase Regimen Fiscal

HEADER
````
#include <iostream>

class RegimenFiscal {
private:
    
protected:
    int id = 0;
    int code = 0;
public:
    RegimenFiscal();
    
};
````

CPP
`````
#include "RegimenFiscal.hpp"

RegimenFiscal::RegimenFiscal()
{
    ;
}
`````


