# MusicWiki

### Introduction
MusicWiki is an unofficial Last.fm app that contains information about different music genres, the albums, artists and tracks listed under the genre.

### Specifications of the App:
- Displays the list of genres available.
- Clicking on the genre it take the user to a page which contains information regarding it. It have a genre as the title, description of the genre. In the page it      lists top albums, top tracks and top artists as different sections.
    ○ Each item listed under the album have the cover image if available or
    a default image, the title and artist.
    ○ Each item listed under the artists, have the cover image, if available or
    a default image and the name
    ○ Each item listed under tracks have the cover image if available or a
    default image, the title and artist name.
 - Clicking on the item
     ○ Albums
       ■ It displays the cover image, title and the artist information. It also have the description and the genres. Clicking on the genre it display the details about the genre, similar to the flow in the first screen.

     ○ Artists
       ■ It displays the image, title ,play count and followers, description, a list of top tracks and top albums and the genres. Clicking on the genre it       displays the details about the genre, similar to the flow in the first screen.
       ■ Clicking on the album shows its information.

### Tech Stacks

- Languages
  * Kotlin
  * Java
  
- Android Architectural Pattern
  * Model-View-ViewModel (MVVM)
  * Android Jetpack Components
  * ViewModel and UI Controllers
 
- UI
  * XML
  * Material Design
 
- API
  * last.fm -> https://www.last.fm/api
  * Retrofit + Moshi (for making network(HTTP) calls)

- Other
  * Picasso -> For Image Loading
  * EventBus -> For Communicating Between Fragments



### App UI


- Home Screen (where Top 10 genres are available (collapsed))
<img src="https://user-images.githubusercontent.com/74188230/214108922-0010fbf1-f84f-453c-838b-ee7983e1f2c2.png" width="220" height="500"/>

- Home Screen (Expanded Genres List)
<img src="https://user-images.githubusercontent.com/74188230/214110208-7642b38b-f320-4319-8ac6-bc1badc56fc9.png" width="220" height="500"/>

- Genre Detail Screen (With Rock Genre Selected)
<img src="https://user-images.githubusercontent.com/74188230/214110862-3c981d90-d04a-47f4-ab83-1ec12b1605c9.png" width="220" height="500"/>

- Album Detail Screen
<img src="https://user-images.githubusercontent.com/74188230/214111138-05d6a2ce-67da-412a-b602-650d53ab89a2.png" width="220" height="500"/>

- Artist Detail Screen

<img src="https://user-images.githubusercontent.com/74188230/214111325-5aa6e91e-584c-412c-bac9-d9c9db04afbf.png" width="220" height="500"/>   <img src="https://user-images.githubusercontent.com/74188230/214111494-ba4159f8-2e24-4a72-9e13-8753056278b8.png" width="220" height="500"/>

- Top Tracks and Top Artists


<img src="https://user-images.githubusercontent.com/74188230/214114859-9294e39f-84ab-4b57-8761-d65fec5b52be.png" width="220" height="500"/>   <img src="https://user-images.githubusercontent.com/74188230/214114947-da6adcc1-e377-44ee-83ad-4abb1f295433.png" width="220" height="500"/>

* [Shubham Ghelani](https://github.com/ShubhamG2311)
