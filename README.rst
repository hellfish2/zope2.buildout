zope2.buildout
==============

Configuración de buildout para el servidor de aplicaciones Zope2

Requerimientos
==============

Estos son los requerimientos mínimos de instalación: ::

  aptitude install gcc g++ make tar unzip bzip2 libssl-dev libxml2-dev zlib1g-dev libjpeg62-dev libreadline6-dev readline-common wv xpdf-utils python2.7-dev libxslt1-dev

Inicialización del proyecto
===========================

Para la inicialización del proyecto Buildout, ejecute el siguiente comando: ::

  python bootstrap.py

Construcción del proyecto
=========================

Para la construcción del proyecto Buildout, ejecute el siguiente comando: ::

  ./bin/buildout

Ejecutar servidor Zope2
=======================

Para ejecutar servidor Zope2, ejecute el siguiente comando: ::

  ./bin/zope2 fg
