# Leaflet
Leafs
> m <- leaflet() %>%
  +     addTiles() %>%  # Add default OpenStreetMap map tiles
  +     addMarkers(lng=174.768, lat=-36.852, popup="The birthplace of R")
> m  # Print the map
> # add some circles to a map
  > df = data.frame(Lat = 1:10, Long = rnorm(10))
  > leaflet(df) %>% addCircles()
