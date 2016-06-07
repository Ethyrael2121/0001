# 0001
S016716_v1prophecy
#poelootfilter



#simple loot
#chance recipe

#quest
Show
    Class "Quest Items"

#Currency
Show
    BaseType "Mirror of Kalandra" "Rhoa Feather" "Divine Orb" "Exalted Orb"
    SetTextColor 175 96 37
    SetBorderColor 175 96 37
Show
    BaseType "Portal Scroll" "Scroll of Wisdom"
    SetTextColor 170 158 130 
Show
    Class Currency
    SetTextColor 51 204 51

#link sockets
Show
    LinkedSockets > 5
    SetTextColor 51 204 51
    SetBorderColor 51 204 51
Show
    Sockets 6
    SetBorderColor 51 204 51
Show
    SocketGroup RGB
    SetBorderColor 51 204 51
#egg
Show
    Class "Fishing Rod"
    SetTextColor 255 0 204 

#gems
Show
    Class Gem
    Quality > 0
    SetBorderColor 175 96 37
    SetTextColor 175 96 37
Show
    Class Gems

#unique and jewel
Show
    Rarity Unique
Show
    Class Jewel
    SetTextColor 255 153 51
    SetBorderColor 255 153 51

#75+ Regal
Show
    Rarity Rare
    ItemLevel >= 75
    SetTextColor 0 230 230

#60+ Chaos
Show
    ItemLevel >= 60
    Rarity Rare
Show
    Rarity Rare
 
#flasks
Show
    BaseType "Flask"
    BaseType "Amethyst" "Diamond" "Granite" "Jade" "Quartz" "Quicksilver" "Ruby" "Sapphire"  "Topaz"
    SetBackgroundColor 0 0 0
Show
    BaseType "Flask"
    Quality >= 4
    SetBackgroundColor 40 40 40

#maps
Show
    Class Maps
Show
    Class Maps "Map Fragments"
 
#quality items
Show
    Quality 20

#divination
Show
    Class "Divination Card"
    SetTextColor 175 96 37
    SetBorderColor 175 96 37

#jewels
Show
    BaseType "Talisman"
Show
    Class "Amulets" "Ring"
    ItemLevel >= 75

#chisel recipe
Show
    BaseType "Gavel" "Rock Breaker" "Stone Hammer"

Hide
