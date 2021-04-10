# Project Title

This is the client side application for the myFlix API

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have node installed and a package manager like npm.

### Installing

Clone project by navigation to the directory where you would like to clone the project.

```
git clone https://github.com/julianegoe/CF_myflix_client.git
```

Then install all dependencies running

```
npm install
```

To build the app run

```
npm start
```
## Build Process

The build is done with [Parcel v2](https://www.npmjs.com/package/parcel#transformers)

## Components

The hirarchy of the components is as follows:

- MainView
    - MovieView
       - MovieCard
            - MovieView
                - GenreView
                - DirectorView
        - MovieCard
            - MovieView
                - GenreView
                - DirectorView
        - MovieCard
            - MovieView
                - GenreView
                - DirectorView
    - ProfileView
        - EditView
        - FavoritesView
    - ...