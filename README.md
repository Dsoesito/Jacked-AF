Hello! Welcome to JackedAF! This is a web app I made that to allow users to plan workouts! 💪

App Link: https://dsoesito.github.io/Jacked-AF/

## Features

* Landing Page that loads all workouts from firebase and categorized based on movement/body part
* Users can open drop down menus and select exercises and desired number of sets
* Once exercise selection completed, workout can be viewed via button on top right that opens modal
* Exercise sets can be removed as workout is completed
* Finished button clears entire workout

## Architecture
As with many other react apps, this web app is built with "components" in mind. All sections of the app are individual components that can be reused as required. This app was built with React.JS, HTML, CSS, Firebase v9, React Redux, and hosted on GitHub Pages. 

The exercises are stored on Firebase and the app retrieves them when the page loads. No workouts created by the user are stored on a server, as redux stores the planned workout, thus when the page reloads all progress is lost.

## Screenshots
### Home Page
<img width="1710" alt="Screen Shot 2022-08-29 at 5 57 52 PM" src="https://user-images.githubusercontent.com/99083937/187306404-42e4110f-1e9c-4b34-ae75-3b3dacac828b.png">
Home Page that greets users

### Exercise Drop Down Menus
<img width="1710" alt="Screen Shot 2022-08-29 at 5 59 56 PM" src="https://user-images.githubusercontent.com/99083937/187306630-25ea68dd-9e44-4610-a6c4-46afe1d5bbcc.png">
All Exercise categories have a drop down button to reveal exercises

### Workout Modal
![Screen Shot 2022-08-29 at 6 36 06 PM](https://user-images.githubusercontent.com/99083937/187310874-6013b841-0107-4bfd-b5b3-719bac23cdc0.png)
Modal overlay that shows enitre work out and allows adjusments

## Thank you

If you would like to try out my web app, feel free to follow the link at the top of this post 😁

Deployed to GitHub pages.
As with many other react apps, this web app is built with "components" in mind. All sections of the app are individual components that can be reused and 
