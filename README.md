# lotus-vsic-check
Script to scrape http://vsic.lotuscars.com for ECU calibration (CRP) files for customisable list of cars.
We store historical CRP versions in the script, for our own entertainment.

```
$ ./lotus_vsic_check
 [+] Loading CRP version data...
 [+] Sorting...
 [+] Checking Lotus VSIC for updates...
EVORA NA (ROW) '12-'15 :
	2017-03-01, TESTTESTTEST
	2017-04-18, TESTTESTTEST
	2017-04-19, P132E0092            <--( Current )
EVORA S (ROW) '12-'15 :
	2017-03-01, TESTTESTTEST
	2017-04-18, R132E0096            <--( Unchanged )
EXIGE S (ROW) '12-'16 :
	2017-03-01, TESTTESTTEST
	2017-04-18, TESTTESTTEST
	2017-04-19, N138E0009            <--( New CRP version! )
 [!] New CRP versions found, consider updating with './lotus_vsic_check --update'
```
