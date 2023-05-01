```bash
#!/bin/bash

#Define the Attributes class
class Attributes {
    # The contact method
    contact() {
        discord="tekky#1810"
        telegram="t.me/xtekky"
        proton="xtekky@protonmail.com"
        
        echo "$discord $telegram $proton"
    }
    
    # The life method
    life() {
        langs=('French' 'German' 'Spanish' 'English')
        nationalities=('German' 'Spanish' 'Korean')
        age=17
        
        echo "${langs[*]} ${nationalities[*]} $age"
    }
    
    # The coding method
    coding() {
        declare -A langs=(
            ['expert']='python'
            ['intermediate']='go js'
            ['learning']='c c++ c# asm java'
        )
        specialities=('web/app reverse engineering' 'fullstack')
        environnement=('vscode')
        
        echo "${langs[*]} ${specialities[*]} ${environnement[*]}"
    }
}

#Create an instance of the Attributes class and call its methods
attr=new Attributes
attr.contact
attr.life
attr.coding
