# Education Analysis

This project contains random analyses of education data.

## Getting Started

This project uses Jupyter Notebook. One way to use it is through the Jupyter
extension in VS Code. Another way to use Jupyter Notebook is through
[Docker](https://docs.docker.com/get-docker/). Once you have Docker, run the
following command from the project directory:

```sh
docker run --rm -p 10000:8888 -v ${PWD}:/home/jovyan/work jupyter/datascience-notebook:2023-03-09
```

You can change port 10000 to something else if you like.

The output should provide instructions to connect to the notebook:

```sh
    To access the server, open this file in a browser:
        file:///home/jovyan/.local/share/jupyter/runtime/jpserver-7-open.html
    Or copy and paste one of these URLs:
        http://19eceea2389e:8888/lab?token=facf01df8834bbe0cc0f0181c792597021052902c923dac2
        http://127.0.0.1:8888/lab?token=facf01df8834bbe0cc0f0181c792597021052902c923dac2
```

Remember to change the port number to 10000 (or whatever you used) so it looks
like
<http://127.0.0.1:10000/lab?token=facf01df8834bbe0cc0f0181c792597021052902c923dac2>.

Once you have the notebook loaded in a browser, look in the `work` directory to
see the project resources.

## References

-   <https://nces.ed.gov/programs/digest/d21/tables/dt21_213.10.asp>
