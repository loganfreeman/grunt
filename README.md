# grunt


[angular-grunt-protractor-starter](https://github.com/matthiasn/angular-grunt-protractor-starter)

[karma-jasmine](https://github.com/karma-runner/karma-jasmine)

```
 grunt.file.copy('karma.conf.js.sample', 'karma.conf.js', {
      process: function(content) {
        return grunt.template.process(content, {
          data: {
            options: JSON.stringify(x)
          }
        });
      }
    });
