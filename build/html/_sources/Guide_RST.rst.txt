.. \_settingup:

How to generate documentations
==============================

With Sphinx and GitHub
======================

good to know
------------

-  Git is an open source base technology for data storing with version
   management
-  GitHub and GitLab use Git as a core but offer some additional
   functionalities
-  GitHub and GitLab have - beside using Git as core - nothing in
   common: they are different communities and/or have different owners

prepare
-------

-  have Python installed,
   `MINICONDA <https://docs.conda.io/en/latest/miniconda.html>`__ e.g.

   -  install missing packeges with: ‘conda install newPackage’
   -  or when troubles have come up try: ‘conda install -c anaconda
      newPackage’

-  know how to start a CMD command line window from Anaconda or
   Miniconda

   -  click the windows sign at the bottom-left corner of your screen
   -  look for ‘Anaconda’ in the application list
   -  select ‘Anaconda prompt’
   -  here you can run installations of Python packages
   -  in order to work on your project: navigate with the ‘cd’-command
      to your project directory

-  know how to start Jupyter under Miniconda

   -  start a CMD command line window from Anaconda or Miniconda
   -  navigate with the ‘cd’-command to your project directory
   -  ‘jupyter notebook’ (enter)
   -  switch to the newer Lab-version: in the URL delete ‘tree’ and
      write ‘lab’ instead

-  Download and install the latest version of Git:
   https://git-scm.com/downloads
-  have a GitHub account https://github.com/

do the following setps
----------------------

1. login at your GitHub account
2. create a new repository
3. creat a new (even empty) file in the repository
4. clone the repository to your local desktop

   -  prepare a directory first on your local desktop
   -  start a CMD command line window from Anaconda or Miniconda
   -  navigate with ‘cd’-commands to the prepared directory
   -  on GitHub: –> Code –> Clone –> copy the URL
   -  on desktop CDM: type ‘git clone’ and paste the URL behind (enter)

5. start a new sphinx project with: ‘sphinx-quickstart’
6. modify the index.rst as you want (save it)
7. ‘make html’ (enter)
8. go to –> build –> html –> index.html (start it in your browser)

choose a theme
--------------

1. make a choice here: https://sphinx-themes.org/
2. click on the theme to see a sample website with this theme
3. look how to call the theme:

   -  import sphinx_redactor_theme
   -  html_theme = ‘sphinx_redactor_theme’
   -  html_theme_path = [sphinx_redactor_theme.get_html_theme_path()]

4. install the theme with: pip install sphinx_redactor_theme
5. open ‘source/conf.py’
6. replace the theme setting to:

   -  import sphinx_redactor_theme
   -  html_theme = ‘sphinx_redactor_theme’
   -  html_theme_path = [sphinx_redactor_theme.get_html_theme_path()]

7. ‘make html’ (enter)
8. go to –> build –> html –> index.html (start it in your browser)

Helpful ressources
------------------

**Sphinx Tutorial** lean and useful

-  1: setup: https://www.youtube.com/watch?v=WcUhGT4rs5o
-  2: themes: https://www.youtube.com/watch?v=RvJ54ADcVno
-  3: to format with reSt: https://www.youtube.com/watch?v=DSIuLnoKLd8
-  4: Push docs to github: https://www.youtube.com/watch?v=DSIuLnoKLd8

**Sphinx Templates**

-  https://www.youtube.com/watch?v=Zb_Oy5UG6Tw
-  https://sphinx-themes.org/sample-sites/sphinx-theme-pd/
-  https://sphinx-themes.org/sample-sites/sphinx-pdj-theme/
-  https://sphinx-themes.org/sample-sites/sphinx-adc-theme/
-  https://sphinx-themes.org/sample-sites/groundwork-sphinx-theme/
-  https://sphinx-themes.org/sample-sites/sphinx-sizzle-theme/
-  **https://sphinx-themes.org/sample-sites/sphinx-redactor-theme/**
-  https://sphinx-themes.org/
-  https://sphinxawesome.xyz/how-to/modify/ how to modify themes

**Applied example with eplanations**

-  https://geo-python-site.readthedocs.io/en/latest/lessons/L1/course-environment-components.html
-  https://geo-python-site.readthedocs.io/en/latest/index.html

**GitHub, Jupyter**

-  https://blog.reviewnb.com/github-jupyter-notebook/
-  https://stackoverflow.com/questions/48003022/jupyter-notebook-and-github
-  https://thenewstack.io/integrate-jupyter-notebooks-with-github/

**Collection**

-  https://www.bing.com/videos/search?q=using+sphinx+for+documentation&&view=detail&mid=4E8351B155222C9821484E8351B155222C982148&&FORM=VRDGAR&ru=%2Fvideos%2Fsearch%3Fq%3Dusing%2520sphinx%2520for%2520documentation%26qs%3DUT%26form%3DQBVR%26sp%3D3%26pq%3Dusing%2520sphinx%2520%26sk%3DHS1UT1%26sc%3D3-13%26cvid%3D5C7C670902F041679AAF81D1D4C8726E%26ajf%3D70



Jupiter als Version auf GitHub bringen und Versionen zurück holen
=================================================================

-  https://thenewstack.io/integrate-jupyter-notebooks-with-github/
-  https://stackoverflow.com/questions/48003022/jupyter-notebook-and-github




Pelican
=======

**Jupyter Pelican**

-  https://github.com/chrisalbon/notes/blob/master/make.ipynb
-  https://github.com/chrisalbon/notes
-  https://github.com/danielfrg/pelican-jupyter
-  https://pmbaumgartner.github.io/blog/jupyter-notebooks-for-pelican/
-  https://github.com/chuckpr/pelican-jupyter-reader
-  https://github.com/chuckpr/pelican-jupyter-reader/tree/main/demo
-  https://opensourcelibs.com/lib/pelican-jupyter
-  https://openbase.com/python/pelican-jupyter/documentation
-  https://github.com/AbdulSayyed/jupyter-pelican
-  **https://janakiev.com/blog/pelican-jupyter/**
-  http://www.legendu.net/misc/blog/use-jupyterlab-notebooks-in-pelican
-  **https://github.com/pelican-plugins**

**Pelican themes**

-  https://docs.getpelican.com/en/stable/themes.html
-  https://github.com/dokelung/jojo/tree/4b834ae02807ec41556e18758143f41d0aa8f937
   gut erklärt, mit Bild im trailer
-  https://github.com/claudio-walser/pelican-fh5co-marble/tree/b1264366d1381c87e2940dde5a34383f10ce7c69
-  https://github.com/getpelican/pelican-themes/tree/master/pelican-striped-html5up
-  https://github.com/nairobilug/pelican-alchemy
-  https://github.com/arulrajnet/attila enthält viel


.. code:: ipython3

    import numpy as np
    from scipy.interpolate import splprep, splev
    
    import matplotlib.pyplot as plt
    from matplotlib.path import Path
    from matplotlib.patches import PathPatch
    
    N = 400
    t = np.linspace(0, 2 * np.pi, N)
    r = 0.5 + np.cos(t)
    x, y = r * np.cos(t), r * np.sin(t)
    
    
    fig, ax = plt.subplots()
    ax.plot(x, y)
    plt.show()
    
    



.. image:: output_13_0.png


.. code:: ipython3

    # Error amplitudes depending on the curve parameter *t*
    # (actual values are arbitrary and only for illustrative purposes):
    err = 0.05 * np.sin(2 * t) ** 2 + 0.04 + 0.02 * np.cos(9 * t + 2)
    
    # calculate normals via derivatives of splines
    tck, u = splprep([x, y], s=0)
    dx, dy = splev(u, tck, der=1)
    l = np.hypot(dx, dy)
    nx = dy / l
    ny = -dx / l
    
    # end points of errors
    xp = x + nx * err
    yp = y + ny * err
    xn = x - nx * err
    yn = y - ny * err
    
    vertices = np.block([[xp, xn[::-1]],
                         [yp, yn[::-1]]]).T
    codes = Path.LINETO * np.ones(len(vertices), dtype=Path.code_type)
    codes[0] = codes[len(xp)] = Path.MOVETO
    path = Path(vertices, codes)
    
    patch = PathPatch(path, facecolor='C0', edgecolor='none', alpha=0.3)
    
    
    fig, ax = plt.subplots()
    ax.plot(x, y)
    ax.add_patch(patch)
    plt.show()
    



.. image:: output_14_0.png


Jinja - python template engine
==============================

-  https://jinja.palletsprojects.com/en/3.0.x/
-  https://www.youtube.com/watch?v=-Q1LZQygStw

PyTorch, GPU
~~~~~~~~~~~~

-  https://chrisalbon.com/code/deep_learning/pytorch/basics/check_if_pytorch_is_using_gpu/
-  https://www.amazon.com/Clean-Code-Python-maintainable-efficient/dp/1800560214?dchild=1&keywords=clean+code+in+python&qid=1613774923&sr=8-3&linkCode=sl1&tag=chrisalbon-20&linkId=6486b848f1198e477c80777c9616088b&language=en_US&ref_=as_li_ss_tl
-  https://pypi.org/project/markovify/
-  https://github.com/chrisalbon/sklearn-flask-docker
-  https://pmbaumgartner.github.io/blog/the-fastest-way-to-load-data-django-postgresql/

NLP, spacy
~~~~~~~~~~

-  https://pmbaumgartner.github.io/blog/spacy-rule-based-matcher-workflow/
-  https://pmbaumgartner.github.io/blog/applied-nlp-lessons/
-  https://pmbaumgartner.github.io/blog/notes-on-nlp-projects/
-  https://pmbaumgartner.github.io/blog/holy-nlp/

REST API mit Python
~~~~~~~~~~~~~~~~~~~

-  https://www.youtube.com/watch?v=W6JvboT8Uo8



.. code:: ipython3

    K_user = 10*9*12
    K_space = 30*0.5*12
    
    K = 1.07*(K_user + K_space)
    K




.. parsed-literal::

    1348.2




