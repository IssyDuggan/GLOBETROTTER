# GlobeTrotter

**This is a prototype for the urban exploration app which has since been renamed ando.**

The idea of the app is to change the way people explore a city, to crowdsource geospatial information and present users with things to do around their immediate location. The app also faciliates social interaction, and allows users to add friends through a unique code. Please see the user testing guide for instructions on how to use. [GlobeTrotter Testing Guide.pdf](https://github.com/IssyDuggan/GlobeTrotter/files/10076777/GlobeTrotter.Testing.Guide.pdf)


## Technical stuff!
 - It uses an RBush spatial index to filter the points around them. https://github.com/mourner/rbush
 - It uses Google's Firebase Realtime data base to store user and POI information. https://firebase.google.com/docs/database
 - It uses Google's Firebase to authenticate users, and the app only works if users have registered with an email and password. https://firebase.google.com/docs/auth
 - It uses an Tiny Encryption Algorithm (TEA) to protect sensitive information (location).https://www.movable-type.co.uk/scripts/tea.html 
 
 

 
