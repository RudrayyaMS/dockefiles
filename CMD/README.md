### CMD
CMD is the instruction that runs the container
  it should run in forground and it should run for infinite times
  There should be only one CMD for dockerfile , if you give multiple the last one will take the preference

### CMD vs RUN
RUN command will execute at the time of image creation   : docker build use to create image 
CMD command will exedcute at the time of running container