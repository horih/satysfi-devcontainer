FROM horih/satysfi:latest 

RUN eval $(opam env) && opam update && opam install -y\
    satysfi-class-stjarticle \
    satysfi-latexcmds \
    satysfi-easytable \
    satysfi-figbox \
    && satyrographos install

