# Chisinau Troleybus Routes Posters
Creating helpful, modern-looking, easy to understand, maps and posters for the stations and troleybuses of Chișinău.

# Types of posters
There are two types of posters to develop and implement, both of them serving specific purposes and helping eachother in guiding the passenger to their desired destinations without being confused or using an electronic device or help from a 3rd person.

## Full Line Posters
**Format**: Custom

*Full Line* Posters are to be found within troleybuses themselves and their purpose is to show where the specific troleybus route travels so that the passenger can understand the consecutivity of stations and to have an idea where they are going to. Additionally, this type of posters tries to inform the passenger of what other routes they can take from each station individually without being too clunky, this is because some destinations may require changing a troleybus and the passenger is informed where can switch to catch another specific troleybus. The poster also shows in which sector is each station placed, based on the Open Street Map of Chișinău and it's sectors' borders, to once again help the user understand where they are and where their destination is.

![ruta8_linia](https://user-images.githubusercontent.com/12870053/153661580-9aeb077d-b4d2-4108-8442-e66e75fb0c64.png)

## Current Station Posters
**Format**: A4

*Current Station* Posters are to be found in stations, most stations being planned to have multiple posters like this, as well as the already existing timetables, and their purpose is to show which stations are next from the specific station from which the user looks until the line completes a circle (when a line reaches a terminus station and the user is sometimes forced to pay again because a new circle starts). The poster is made to be very minimalist and easy to read in a top-to-buttom style without any distractions. The big title as well as the colour of the line are to indicate the route's number so that they can be seen and identified from afar. The station highlighted in background-blue is the station where this poster is present, and each station has it's own variation of the line poster with it's name highlighted.

![frontstations_ruta8_traian](https://user-images.githubusercontent.com/12870053/153662404-f2c648e8-ab24-46ab-8cb8-0b317716e899.png)

# Data
**Timetables for each station of each line**: https://rtec.md/category/transport/
**Map**: https://rtec.md/wp-content/themes/newsup/images/ruta-map.jpg

We get most of our data from pre-existing materials made by RTEC and real-life experience. RTEC already has an up-to-date map of all the lines laid out with station names, but sometimes the station names from the map are not the same as the ones on the timetables or two different stations have the same name, in this case we use/create a name that is best fitted for that station based on what is nearby and what the locals might actually call that specific location. Another part are abreviated names. Name of stations and streets based on famous people will have the first name of that person shorttened to their initial: *Teatrul Mihai Eminescu* becomes *Teatrul M. Eminescu*. Universities and some very long names might be abbreviated, this means *Universitatea de Pedagogie Ion Creangă* becomes *UdP* or *Piața Unirii Principatelor* becomes *PUP*.


# Stylistics
## Colours
The official [RTEC map of Chișinău](https://rtec.md/wp-content/themes/newsup/images/ruta-map.jpg) employs different colours for the troleybus lines. As such, based on that map i have created the Troleybus Line Colour Reference, both in .psd and .png form.
![troleybuscolorref](https://user-images.githubusercontent.com/12870053/153658120-11f19614-651c-49f9-bfe4-3af84d1419bd.png)

For the text colour and different background elements we are using hex ```#313484``` instead of full black because the colour is similar to the one used on most Chișinău troleybuses (blue & white combination) and the station dots are made of pure white with black outline.

## Font
The font used on both types of posters is **Overpass**, and open source serif typeface that is based on Highway Gothic, used in the US, is very readable and has all the additional romanian alphabet characters ```ăîșțâ```. It is used most of the time in it's regular form, except for the title of *Current Station* posters.

![Overpass](https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Overpass_sample_image.png/800px-Overpass_sample_image.png)

