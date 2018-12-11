# Saturn Tower
A webserver that collects temperature, pressure and humidity data from Raspberry Pis.

## Getting Started

### Prerequisites

To get the system running you need to install some packages first. 
Use package manager for install:

macOS: [Home Brew](https://brew.sh) install recommended 
Linux: [yum]()
Windows: Use link.

#### Node.js

Please install [Node.js](https://nodejs.org/en/download/). (Currtenly tested with v8.6.0)

#### MongoDB

Please install [MongoDB](https://www.mongodb.com/download-center?ct=false#community). (Currently tested with v3.4.9)

### Installing

Please verify the correct install of MongoDB. Make sure you have created the database folder.

Unsing command line (Mac: Terminal app.) start MongoDB server with default data base location:

```
mongod
```

The weatherstation server can be started form any folder on your system.
Before starting up the server, modify the main.json file at the folder 'config/main.json' according to your network settings (PORT).

Unsing a second command line window start weatherstation server:

```
node app
```


## Deployment

Add additional notes about how to deploy this on a live system

## Authors

* **Alexander Auer** - *Initial work* - [GitHub](https://github.com/alexauer)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

