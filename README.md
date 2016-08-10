# Berlin Trams

JS-canvas application that imitates moving of trams on different routes with crossroad.
Trams pass through crossroad depending on its priority. Tram`s priority defined by number of passengers.

### TODO
* Try WebWorkers (BUT they don't have thread priority API).
* Try using dedicated pole-less polar coordinate system for each tram.
  The trick is to use polar system with pole is placed in the first stop of the route.
  Pros: we can throw out complicated pole-passing logic.
  Cons: we have to make additional coordinates conversion for each tram.
