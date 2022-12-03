# stack-templates
Stack templates written in hsfiles format.

## How to use
Download the template defined by the file `simple.hsfiles`
``` sh
stack new project-name datalek/simple

# pass the `--bare` flag to create the project in the 
# current working directory rather than in a new project directory

# same as
stack new project-name github:datalek/simple

# from url
stack new project-name https://my-site.com/content/template9.hsfiles

# from local template
stack new project ~/location/of/your/template.hsfiles
```

## Simple Template
The smallest beginning

``` sh
stack new project-name datalek/vanilla
```

# Refs
1. https://docs.haskellstack.org/en/stable/GUIDE/#templates
