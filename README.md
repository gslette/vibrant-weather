# vibrant-weather

This is a simple web applciation I'm building mainly to to increase my knowledge of React and React Native. 

The intial plan is:
1. Finish initial build with standard React and Matieral UI
2. Add session storage to save preferred locations and cities if not in first version
3. Refactor and add React Native support (if necessary - if my web app is already performant on mobile I will not go down this route)
4. Add three.js (3D) support 

# Intro

I originally started with the simple idea that I wanted to make a web app of some kind. After doing some thinking, I settled on a weather app for a couple reasons:

- Fairly simple, defined requirements and uses
- Will require work on some common patterns found in web apps
    - SPA/Single Page Appliations & Server Side Rendering (I'm going to make the app as standalone as possible)
    - RESTful APIs for grabbing weather data (and everything that involves backend wise)
    - React's UI Components for displaying said data
    - State change
    - Hosting/Deploying/Maintenance

# Design

When I began considering different designs, at first I had thought a simple white and black site ala Google would be great. A lot of weather sites I use are incredibly visually busy - usaully I'm there to check the weather in my area and leave and I don't need a ton of visual clutter making that difficult.

The other day I was checking out a new game coming out called Tetris Effect. It's basically a visually gorgeous love letter to old school Tetris (https://www.youtube.com/watch?v=PFVL6t8IHE8).

While thinking about that, I ended up checking out three.js (threejs.org), a library for rendering things in 3D in browser. I found this AMAZING project (https://demos.littleworkshop.fr/track) and realized I would love to do something like this. 

For now, the 3D aspect will have to wait. But the ascethetic is exactly what I'd like to go for with Vibrant Weather - and that's exactly where the name came from. 

# Mockups

My inital thought was to continue with the idea of Google (incredibly minimal search view) for Weather. Coupled with the idea that I wanted it to be dark but vibrant, I settled on Material UI for the 2D implementation. 
