# Machine Learning Notebook

This project tries to predict perceived usefulness of a Yelp review based on its text.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites & Installing

First, if you have [git](https://git-scm.com/) already installed, clone this repository by typing the following commands in a terminal:

```
cd $HOME  # or any other development directory you prefer
git clone https://github.com/tatianae2/ml
cd ml
```

Alternatively, you can download [master.zip](https://github.com/tatianae2/ml/archive/master.zip), unzip it, rename the resulting directory to `ml` and move it to your development directory.

Next, if you have [Docker](https://docs.docker.com/install/#releases) already installed, type the following command in the terminal:

```
docker run -p 8888:8888 jupyter/scipy-notebook:2c80cf3537ca
```

This command will check the local host if the jupyter/scipy-notebook image tagged 2c80cf3537ca is present and pull it from Docker Hub if it is not the case. 
A container running a Jupyter Notebook server is then started and the server is exposed on host port 8888. 
The terminal prints the server logs: 

```
Copy/paste this URL into your browser when you connect for the first time,
    to login with a token: [http://<hostname>:8888/?token=<token>]
```

Opening in the web browser on http://<hostname>:8888/?token=<token>, you'll see the Jupyter Notebook dashboard page, where hostname is the name of the computer running docker. 
For more details, check [Jupyter Docker Stacks](https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html).

This will enable you to see Jupyter's tree view, with the contents of the working directory.

## Running the tests

--

### Break down into end to end tests

--

### And coding style tests

--

## Deployment

--

## Built With

--

## Contributing

--

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Tatiana Ermakova** - *Initial work* - [tatianae2](https://github.com/tatianae2)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* https://gist.github.com/PurpleBooth/109311bb0361f32d87a2
* https://github.com/ageron/handson-ml
* etc
