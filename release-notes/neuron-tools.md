# Neuron Tools release notes

This documents lists the release notes for AWS Neuron tools. Neuron tools are used for debugging, profiling and gathering inferentia system information.

# [1.0.4587.0]

Date: 12/20/2019

## Summary

Minor bug fixes to neuron-top and neuron-ls.

## Major New Features

## Resolved Issues

* neuron-top: now shows model name and uuid to help distinguish which model is consuming resources.  Previously only showed model id.
* neuron-ls: lists device memory size correctly in MB

## Known Issues and Limitations

## Other Notes


# [1.0.4250.0]

Date:  12/1/2019

## Summary

## Major New Features

## Resolved Issues

* neuron-top may take longer to start and refresh when numerous models are loaded
* neuron-top may crash when trying to calculate the utilization of the devices

## Known Issues and Limitations

## Other Notes

# [1.0.3657.0]

Date:  11/25/2019


## Major New Features

N/A, this is the first release.

## Resolved Issues

N/A, this is the first release.

## Known Issues and Limits

* neuron-top may take longer to start and refresh when numerous models are loaded. 
    * Workaround: Unload the models not in use before using neuron-top
* neuron-top may crash when trying to calculate the utilization of the devices. 

## Other Notes


