FROM jupyter/base-notebook:python-3.7.6

ADD ./requirements.txt $HOME/.

RUN conda install --file $HOME/requirements.txt

RUN conda init bash
