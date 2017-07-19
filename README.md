# osio_api_tests
API tests for Openshift online

# Package dependencies with minimum versions
python 2.7.3
pyresttest 1.7.1
pycurl 7.43
jsonschema 2.6.0
jmespath 0.9.3

# Command to run
pyresttest  https://api.openshift.io pyresttest_demo.yaml --vars="{'token':<<OSIO security token>>'}"
