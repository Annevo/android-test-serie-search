# Kotlin Home Assignment - Serie Search

The task is to create an Android application that enables the user to search for information about TV series using the TV Maze API, which is public and free to use.

It should display the search results in a list and allow the user to view more detailed information in another view. The app should adhere to the provided design.

## Requirements
The requirements are quite open; however, the app must be completely responsive and work on any Android device.

The app should consist of two views: one for detailed information about the series and one for the search and results.

The application should be written in Kotlin. Whether you choose to build views programmatically, use XML layouts, or utilize Jetpack Compose is entirely up to you. The time you spend on this assignment is at your discretion.

### Must-haves:
- A search screen where the user can enter a query for the [TV maze API].
- The search results should be presented in a RecyclerView or ScrollView with the show's name, a summary of a maximum of 2 lines, and the average score on a scale from 1-10 rounded to the closest half number.
- When tapping a result, you should navigate to a more detailed view where the same information is presented in a ScrollView, but without the limitation of 2 lines, and an image from the API.
- The app should resemble the [linked design].

### Nice-to-haves:
- The ability to add favorites, which should be saved locally.
- Search should be triggered when the user hasn't typed for 0.5 seconds to minimize unnecessary API requests.

## Delivery
When you are done, simply create a pull request. If you prefer to start your own project from scratch, that's perfectly fine. In that case, create a new repository and share it with us.

The assignment will be assessed based on the code's readability, structure, and the ability to create a UI matching the design. We prefer clean, self-documenting code that is thoroughly tested. Feel free to reach out if you have any questions about the assignment.

[TV maze API]: https://www.tvmaze.com/api
[linked design]: https://www.figma.com/file/q5onZTjSjMWYrzqvE23iyU/Series-Search?type=design&node-id=0:1&mode=design&t=LwagVwjuRI9un48F-1

