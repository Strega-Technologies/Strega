# STREGA
The Encoder-decoders for STREGA devices are written in JSCRIPT.
The DECODERS and ENCODERS work for the entire STREGA devices.

For ChirpStack users, please use the ChirpStack CODECS as encoder and decoder.

We thank Scott Waller from THINGY (www.thingy.us) for providing the ones from TTI-v3-stack and the one for the Datacake
platform.

Each decoder file notates which LNS it was tested on as they each seem to behave a little different.
Scott tested each script against The Things Network (community), Things Industries Cloud Hosted, Tektelic-NS, and ChirpStack.

TTI codecs - works on the Things Industries Cloud Hosted v3 stack for decoding uplinks and encoding downlinks 
**!!! IT WILL NOT WORK FOR _THE THINGS STACK Community edition_ (= TTN-v3) as they limit the size of Payload Formatters to 4Kb...!!!!!**

Datacake - Supports uplinks. Tested from TTI v3 app server via HTTP to Datacake

Tektelic-NS: Decoder to be used in the "Data Converters" section
