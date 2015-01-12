# TODO: who has galaxyproject on Docker Hub???
FROM toolshed/base

RUN brew shed-install devteam package_bowtie_0_12_7
RUN brew shed-env devteam package_bowtie_0_12_7  >> /home/linuxbrew/.shedrc

CMD /bin/bash --init-file /home/linuxbrew/.shedrc
