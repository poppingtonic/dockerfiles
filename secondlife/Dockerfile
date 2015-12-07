# See it start
FROM f69m/ubuntu32:lts
MAINTAINER poppingtonic <poppingtonic@gmail.com>
RUN apt-get update && apt-get install wget -y
RUN apt-get update && apt-get install mesa-utils --no-install-recommends && rm -rf /var/lib/apt/lists/*
ENV LIBGL_DEBUG verbose
RUN wget http://download.cloud.secondlife.com/Viewer_3/Second_Life_3_8_6_305981_i686.tar.bz2
RUN tar xvvf Second_Life_3_8_6_305981_i686.tar.bz2
RUN cd Second_Life_3_8_6_305981_i686 && ./install.sh
