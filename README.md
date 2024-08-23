## *Pokemon app*

#### *Aim of the project:*
To create an iOS mobile application that will fetch data from the public https://pokeapi.co/ and render a list of Pokemons and its details to the user. 

#### *Description:*
- The app shows a list of Pokemons with its name. 
- The app will also allow selection of a pokemon to view it's details such as name, height, weight, type, images and statistics. 
- Users can also search for a pokemon to view its details. 


#### *On launching:*
The app loads by displaying the splash screen which then lands on the home page. The home page will then list the pokemon names. 
Initially 20 pokemons will be rendered on the screen but as the user reaches the end of the list, additional list of pokemons will be shown as pagination has been implemented.
There is a search bar which will do a local search of pokemons based on the search text entered by the user. On clicking each pokemon, the app will navigate to the selected pokemon's detailed page.

#### *Frameworks used:*
- Alamofire: To handle the networking task seamlessly. Alamofire fire will abstract many details of networking calls, JSON serialization, response validation, parameter encoding. These alongwith with error handling are done automatically by Alamofire. Makes the code more readable and maintainable when the app scales

#### *Supported OS:*
iOS 16

#### *Architecture:*
1. UI
- SwiftUI
2. Language
- Swift
3. Handling asynchronous events
- Combine 
4. Design pattern
- MVVM, POP
5. Networking
- Alamofire
6. Unit testing
