```bash
#!/bin/bash

#Define the Attributes class
class Attributes {
    # The contact method
    contact() {
        discord="櫻井孝宏#8124"
        telegram="t.me/rg_mechanic"
        gmail="yehor.redhat@gmail.com"
        
        echo "$discord $telegram $gmail"
    }
    
    # The life method
    life() {
        langs=('English' 'Polish' 'Russian' 'Ukrainian')
        nationalities=('Ukrainian')
        age=18
        
        echo "${langs[*]} ${nationalities[*]} $age"
    }
    
    # The coding method
    coding() {
        declare -A langs=(
            ['intermediate']='bash'
            ['learning']='c++ java python'
        )
        specialities=('computer network administrator' 'systems security')
        
        echo "${langs[*]} ${specialities[*]}"
    }
}

#Create an instance of the Attributes class and call its methods
attr=new Attributes
attr.contact
attr.life
attr.coding
```
[![My Skills](https://skillicons.dev/icons?i=bash,py,mysql,wordpress,linux,)](https://skillicons.dev)
