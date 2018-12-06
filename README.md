# demoConfigFail


Simple config mistake that caused spring boot to not boot and took me many hours to find a simple mistake. I ported that mistake into a basic project for demonstration purposes, and to get some help as to why this would not cause some kind of syntax error to be triggered.

The mis config was so bad that there was no error, and small enough to be hard to find.


1. Run as a spring boot app (I was doing the Spring Tools Suite method of demoConfigFail > Run As > Spring Boot App)

2. Watch how it does not start and gives no errors as to a cause.

3. The mistake, I was attempting to add a hostname environment variable to a log file and did it the wrong way.

See [application.properties](src/main/resources/application.properties) for the problem and the fix.


