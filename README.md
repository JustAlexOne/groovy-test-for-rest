# REST API testing example on Groovy and Spock

To use this example you have to install json-server locally and run it:
```bash
$ sudo npm install -g json-server
$ json-server http://jsonplaceholder.typicode.com/db
```

More info about the json-server here:
* https://github.com/typicode/json-server

Then you can run the tests from IDE or by the command

```
gradlew clean test
```

To generate the report
```
gradlew allureReport
```

Report will be generated by default to:
```
build/allure-report/index.html
```

Also you can specify necessary properties via command line by using -Dproperty.name = "property.value" :

```
gradlew -Dapp.url="http://www.test.site" clean test
```

Additional info can be found here

* [Video from Selenium Camp 2017](https://www.youtube.com/watch?v=glY2q-HgIng)
* [Video from QA-Fest 2016](https://youtu.be/5elqH5UNwkk)
* [Groovy documentation](http://groovy-lang.org/documentation.html)
* [Spock documentation](http://spockframework.org/spock/docs/1.1-rc-2/all_in_one.html)
* [RESTClient documentation](https://github.com/jgritman/httpbuilder/wiki/RESTClient)
* [Allure home](http://allure.qatools.ru/)
