ModularGrunt
============

Example for modularizing Gruntfile.js

1. For each task: Create a file in `grunt/` with `<taskname>.js` of the form:

    module.export = {
      // Task configuration.
    }

2. For each profile: Add an option in `grunt/aliases.yml`
