# CDEX-Burn-Address
Deployed script for the CDEX burn address 


This script create a valid address without generate a private key, so the HTML or CDEX that go to this address will never be spent because the private key is not known.

Example address created with the command:

py .\burn_script.py HtmLToBurnSomeCDEXTokenS

http://cdexplorer.net/address/HtmLToBurnSomeCDEXTokenRzzzzudYFei


Never send coins or tokens to this addresses generated by this address if you want to use it later, it is impossible by humans or computers to recover the private key.
