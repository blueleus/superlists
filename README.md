# Run test in WSL2
Documentation: [How To Run Your Tests Headlessly with Xvfb](http://elementalselenium.com/tips/38-headless)

## Functional tests:
`xvfb-run -a python ./manage.py test functional_tests`

### In staging server:

`STAGING_SERVER=superlists-staging.blueleus.tk ./manage.py test functional_tests --failfast`
