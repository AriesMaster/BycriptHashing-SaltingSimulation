# BCrypt Hashing and Salting Simulation

A learning project for exploring password hashing and salting. A useful question to bring to the demonstration is why two users who choose the same password can have different stored hashes.

BCrypt can generate a fresh salt for each hash. On login, password verification reads the salt and cost from the stored hash and checks the submitted password using those values.

Start with the [client package configuration](bycryptClient/package.json) or [Angular interface](bycryptClient/src/app/app.html). Use sample values when exploring the demo.
