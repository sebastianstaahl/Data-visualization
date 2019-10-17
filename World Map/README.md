# Reademe

# PREREQUISITES
Docker
Docker-compose

# Starting docker container
In terminal, go to World Map folder
run: docker-compose up

# Start bokeh server
in terminal run: bokeh serve --show cancer.ipynb

# or

In the console output (after docker-compose up), copy the jupyter notebook url e.g. `http://localhost:8888/token?=xxxx` and enter in into your web browser to run the code in jupyter. Some features are not working while running code in jupyter
