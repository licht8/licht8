#!/bin/bash

# Define the Attributes class
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

# Create an instance of the Attributes class and call its methods
attr=new Attributes
attr.contact
attr.life
attr.coding





<div id="header" align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOWVmNmY5N2Y1M2YwMmNmNmMyNTcxZTNjMWViN2IyNTg1ZjMzNTZkYSZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/3o6ZsTLGsWNxoTNULm/giphy.gif" width="150"/>
<div id="badges">
  <a href="https://loremlte.space/">
    <img src="https://img.shields.io/badge/Blog-yellow?logo=linux&logoColor=black&style=for-the-badge" alt="Blog Badge"/>
  </a>
  <a href="https://www.instagram.com/yehorcheg/">
    <img src="https://img.shields.io/badge/Instagram-ff69b4?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge"/>
  </a>
  <a href="https://t.me/yehor_14">
    <img src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Badge"/>
  </a>
</div>
  <h1>
  hey there
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>
</div>
