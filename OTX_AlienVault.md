# OTX Alienvault

Provide an overview of the tool and include the following:

* What the tool provides
  * 
* Who developed the tool?
* If it's open source, when was the last version developed? Or how often is it updated?
* Where can you go for more detailed documentation

## Setup

Does it require installation?

* The OTX Alienvault SDK can be installed using:

```terminal
pip install OTXv2
```

* Alternatively, the SDK can be cloned from GitHub at <https://github.com/AlienVault-OTX/OTX-Python-SDK>

Does it require any license?

* OTX Alienvault is licensed under the Apache License, Version 2.0. <br>
* The license is available at <http://www.apache.org/licenses/LICENSE-2.0>

Is there an academic license available?

* No, there is no academic license available.

## Input

What input do you provide to the tool?
    * For 
In what form do you need to provide the input?
* 
In particular, can you provide anything related to an organization?
What are some interesting command line switches or special search criteria?
Is there an API available that you can programmatically access?

## Output Summary

Describe the output from the tool
In what form is the output provided?
    * OTX Alienvault APi provides the output in JSON format. 

## Output Mapping to STIX 2.1

Explain how the output can be mapped to schema fields in STIX 2.1

* Using:

```terminal
from stix2 import Indicator, parse
```

* The output can be mapped to the following STIX 2.1 schema fields:

## Example

Provide an example use of the tool through text or screenshots. If it's possible to provide an organization as input, use UA Little Rock as the organization.
