# Bus Tracking Application (Backend)

The Bus Tracking application is a comprehensive solution designed to enhance the efficiency and convenience of bus transportation services. The app provides real-time bus tracking, real time updates on map, and timely information to users, ensuring a seamless and reliable travel experience. It leverages advanced technologies, such as Node.js, Android Kotlin and Jetpack Compose, MongoDB, and Socket.IO, to deliver a robust and user-friendly application.

### Frontend -
  https://github.com/deepak252/Bus-Tracking-App-Kotlin

### Favorite Stops API

This backend now supports managing a passenger's favorite bus stops.

- `POST /api/user/addFavoriteStop` – Add a stop to the authenticated user's
  favorites. Provide `{ "stopNo": "<stop number>" }` in the request body.
- `POST /api/user/removeFavoriteStop` – Remove a stop from favorites using the
  same payload as above.
- `GET /api/user/getFavoriteStops` – Retrieve a list of the user's favorite bus
  stops. Requires a valid authentication token in the `Authorization` header.
