# lotus-vsic-check
Script to scrape http://vsic.lotuscars.com for ECU calibration (CRP) files for customisable list of cars.

We store historical CRP versions in the script, for our own entertainment.

```
./lotus_vsic_check
 [+] Loading CRP version data...
 [+] Sorting...
 [+] Checking Lotus VSIC for updates...
EVORA 400 Manual (ROW) '16 :
 2016-00-00, unknown
 2017-04-19, G132E0228            <--Unchanged
EVORA NA Manual (ROW) '11 :
 2011-00-00, unknown
 2011-00-01, F132E0009
 2011-00-02, H132E0009
 2011-00-03, J132E0009
 2011-00-04, K132E0072
 2017-04-19, A132E0090            <--Unchanged
EVORA NA Manual (ROW) '12-'15 :
 2012-00-00, unknown
 2012-00-01, B132E0092
 2012-00-02, F132E0092
 2012-00-03, H132E0092
 2017-04-19, P132E0092            <--Unchanged
EVORA S Manual (ROW) '11 :
 2011-00-00, unknown
 2011-00-01, A132E0077
 2011-00-02, B132E0077
 2017-04-19, G132E0075            <--Unchanged
EVORA S Manual (ROW) '12-'15 :
 2012-00-00, unknown
 2012-00-01, L132E0096
 2017-04-20, R132E0096            <--New CRP version!
                                     '12 - '15 Model Year Evora S & S-IPS Supercharged Models
EXIGE S Manual (ROW) '12-'16 :
 2012-00-00, unknown
 2012-00-01, D138E0009
 2012-00-02, E138E0009
 2012-00-03, F138E0009
 2017-04-19, N138E0009            <--Unchanged
 [!] New CRP versions found, update history with './lotus_vsic_check --update'
```
