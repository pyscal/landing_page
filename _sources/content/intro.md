# <font style="font-family:roboto;color:#455e6c;font-size:30px"> <b> Data analysis and workflows in Materials science </b> </font> </td>



::::::{grid} 2
:gutter: 3

:::::{grid-item-card} pyscal  
:columns: 6
:link: https://docs.pyscal.org
:img-top: /img/pyscal_v2_logo_1.png

pyscal is a python module for the calculation of local atomic structural environments including Steinhardt's bond orientational order parameters during post-processing of atomistic simulation data. pyscal is written in C++ and python and has been used in over 30 scientific publications.
:::::

:::::{grid-item-card} pyscal3  
:columns: 6
:link: https://v3.pyscal.org
:img-top: /img/pyscal_v3_logo_1.png

pyscal3, a completely new pyscal which is faster and can handle a large number of atoms, with a much more user-friendly and intuitive interface. Adds more features such as more structure creation including grain boundaries, selection, and deletion of atoms.
:::::

:::::{grid-item-card} pyscal-rdf  
:columns: 6
:link: https://rdf.pyscal.org
:img-top: /img/pyscal_rdf_logo_1.png

pyscal_rdf is a python tool for ontology-based creation, manipulation, and quering of structures. pyscal_rdf combines the power of pyscal3 and the [Computational Material Sample Ontology (CMSO)](https://github.com/Materials-Data-Science-and-Informatics/cmso-ontology) to create annotated structures than be queried.
:::::

:::::{grid-item} 
::::{grid} 1 1 1 1
:gutter: 0

:::{grid-item-card} rdfjobs  
:columns: 12
:link: https://github.com/pyscal/rdfjobs

Extension package to pyscal-rdf that provides fully annotated simulation outputs using the workflow environment [pyiron](https://pyiron.org).
:::
::::
:::::
::::::