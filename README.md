# TractrBeam
A Sketch plugin for scraping website content

# Setting up with WebStorm, Karma and Jasmine

1. Get WebStorm https://www.jetbrains.com/webstorm/
2. Follow this guide: https://www.jetbrains.com/webstorm/help/preparing-to-use-karma-test-runner.html
  1. install in the project
3. And this one https://www.jetbrains.com/webstorm/help/creating-javascript-unit-tests.html
  1. Test (spec) folder is included in this repo
4. And this one: https://www.jetbrains.com/webstorm/help/running-unit-tests-on-karma.html
  1 For karma init:
    1 Framework - jasmine
    2 RequireJs - yes
    3 Browsers - PhantomJS
    4 Locations -
      * src/*.js
      * spec/*Spec.js
    5 Bootstrap - yes
    6 Watch - no
