I made this in first-year uni. It's a very simple web app, that demonstrates Diffie-Hellman key exchange.
It's probably not secure, however the underlying usage of the Diffie-Hellman key exchange is correct, and the app is a good demonstration of how it works -- with a little message system and friend request because why not.

The message encryption itself is secure, and the private keys are never stored on the server (but in local storage). The server is only ever exposed to the public keys, and the encrypted messages.

## Dependencies:

- [Python3](https://www.python.org/downloads/)

### Pip:

- SQLAlchemy `pip install flask-sqlalchemy`
- Flask `pip install flask`


## To run the server

You must have the above dependencies installed. Once this is done, simply run
`python3 server.py <PORT>`, where <PORT> is your desired port number (default 8000)


