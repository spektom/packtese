Packtese
========

Packtese is a collection of Eclipse PDE Builder projects for packaging various libraries as Eclipse (OSGi) bundles.

Building
--------

The following steps describe how to package 'foo' library as an OSGi bundle:

1. Have Eclipse (>= 3.5) installed.

2. Import needed project (foo.releng) into your workspace.

3. Import org.eclipse.pde.build into your workspace:

    * Click "File->Import..."
    * Choose "Plug-ins and Fragments", and press "Next".
    * Add "org.eclipse.pde.build" to plug-ins to import and press Finish.

4. Launch build:

    * Choose "Run -> Run Configurations...".
    * Select "foo Packaging", and press "Run".

5. The archived update site including bundled 'foo' will be placed into this folder:

    `foo.releng/build/result/`
