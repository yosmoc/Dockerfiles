FROM jupyter/notebook

RUN pip3 install --upgrade pip \
  && pip3 install numpy \
  matplotlib \
  pandas \
  seaborn \
  plotly \
  scipy \
  bokeh \
  xlrd
  
CMD ["jupyter", "notebook", "--no-browser"]
