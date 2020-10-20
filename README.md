# Boldo - Server

Boldo can be found in any Paraguayan household. It is a magic team that can calm all kind of stomache ache.

This is the server for Boldo - a telemedicine solution for doctors and patients.
The server exposes APIs that are consumed by the web app and the mobile app.

## Getting Started

1. This project has the following dependencies:

   - node.js (v12 or newer)

2. Install dependencies: `npm i`

3. Create a `.env` file in the project's root folder and add these contents:

   ```
   # ###################### Online ######################
   # CLIENT_ADDRESS = https://boldo.penguin.software
   # SERVER_ADDRESS = https://api.boldo.penguin.software
   # KEYCLOAK_REALM_ADDRESS = https://sso-test.pti.org.py/auth/realms/iHub

   # ###################### Local ######################
   CLIENT_ADDRESS = http://localhost:3000
   SERVER_ADDRESS = http://localhost:8008
   KEYCLOAK_REALM_ADDRESS = http://localhost:8080/auth/realms/iHub
   ```

4. `npm run dev` - to start server on [localhost:8008](http://localhost:8008)

## Contributing

The project is currently under heavy development but contributors are welcome. For bugs or feature requests or eventual contributions, just open an issue. Contribution guidelines will be available shortly.

## Authors and License

This project was created as part of the iHub COVID-19 project in collaboration between [Penguin Academy](https://penguin.academy) and [PTI (Parque Tecnológico Itaipu Paraguay)](http://pti.org.py).

This project is licensed under
[AGPL v3](LICENSE)