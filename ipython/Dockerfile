FROM miniconda3
LABEL mainainer=@joshuacook
RUN conda update conda && \
    conda install -y ipython && \
    conda clean -tipsy
CMD ["ipython"]