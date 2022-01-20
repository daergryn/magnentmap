A map that is able to have opperations runn on it to determine mag anomns to see where the spooky spots are

@author - Daergryn

@title - GHOST MAGNUM

uses graphql, react, python, AWS, serverless, and written in visual studio code. utilizez clean Architecture

entities:
    MapDataItem, MapPoint, and object
    MapData and Map objects
    main processes

        development setup:
        A: Ready the Map Data object

        
        A: setup initially
            a0: serve login screen
            a1: logged in splash page
            a2: create map
            a3: display map
            a4: load data into map MapItem objects
            a5: set up area to add enter equation bar for transformation and cross examineation of any number of the data sets values per point 
        B: Add the processing and analytics of the data
            b0: submit equation for analyisis
            b1: validate equation or return an error
            b2: select how to be diplayed
        C: Display Map with processing loaded
            c0: display map with anaylisis points in 3D
            c1: enter street view
            c2: toggle display style
            c3: add another anaylisis
        D: Save to Account