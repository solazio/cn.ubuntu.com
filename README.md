ubuntu-china.cn
===

The Django project behind <http://ubuntu-china.cn>.

Local development
---

First build the Docker image, ready to run the site:

``` bash
make build  # Build the docker image to run the site
```

Then run the local development server:

``` bash
make run  # watch sass files and run the site from Docker images
...

Now visit <http://127.0.0.1:8004>

Fenchurch dependency
---

This site depends on [Fenchurch](https://bitbucket.org/nottrobin/fenchurch) - which is currently a private repository. Make sure you have SSH access to the above repository before attempting to install dependencies.
