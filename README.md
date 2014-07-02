Example of writing API documentation using Robotframework
====

Setup environment
----

```
pip install -r requirements.pip
```

Run all test
----

```
pybot .
```

Run only tests tagged with table
----

```
pybot -i table .
```

The API documentation is the test report (`report.html`) that is generated for each test run.

References
----
<https://robotframework.googlecode.com/hg-history/2.1/doc/libraries/BuiltIn.html>
<http://bulkan.github.io/robotframework-requests/>
<http://robotframework.googlecode.com/hg/doc/libraries/Collections.html?r=2.8.5>
