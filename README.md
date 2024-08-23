## *Pokemon app*

#### *Aim of the project:*
To create an iOS mobile application that will fetch data from the public https://pokeapi.co/ and renders a list of Pokemon and Pokemon details to the user. 

#### *Description:*
The app shows a list of Pokemon and it's most relevant data. 
The app will also allow selection of a pokemon to view it's detailed data. 
Users can also search for a pokemon to view its data. 


#### *On launching:*
The app loads by displaying the splash screen which then lands on the home page. The home page will then list the pokemon names. Initially 20 pokemons will be rendered on the screen but as the user reaches the end of the list, additional list of pokemons will be shown as pagination has been implemented.
There is a search bar which will do a local search of pokemons based on the search text entered by the user. 
On clicking each pokemon, the app will navigate to the selected pokemon's detailed page.

#### *Frameworks used:*
- Alamofire: To handle the networking task seamlessly

#### *Supported OS:*
iOS 16

#### *Architecture:*
- The app was developed using SwiftUI and Combine framework and incorporates MVVM architecture.
- Also, this source code makes use of the Protocol Oriented Programming for building the networking layer. 
- In addition, various test cases has been handled to test the accuracy of the functionality implemented.



