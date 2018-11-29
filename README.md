# demoConfigFail


Simple config mistake that caused spring boot to not boot and took me many hours to find a simple mistake. I ported that mistake to a basic project for demonstration purposes.

The mis config was so bad that there was no error, and small enough to be hard to find.



1. Run as a spring boot app

2. Watch how it does not start and gives no errors as to a cause.

3. The mistake, I was attempting to add a hostname varible to a log file, so that each server would have its own log file.

in the application yaml I did  

