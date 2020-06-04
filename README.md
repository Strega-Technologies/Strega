# Strega
The Encoder-decoder for STREGA devices is written in JSCRIPT.
The DECODER and ENCODER are initially made for the TTN and TTI environment
but can be used on other LNS. 

It works for the entire STREGA devices

For ChirpStack users, please use the ChirpStack CODEC encoder and decoder.

We thank Scott Waller from THINGY (www.thingy.us) for providing the ones from TTI-v3-stack and the one for the Datacake
platform.

Each decoder file notates which LNS it was tested on as they each seem to behave a little different.
Scott tested each script against Things Network (community), Things Industries Cloud Hosted, Tektelic, and ChirpStack.

TTI - Works on the Things Industries Cloud Hosted v3 stack for decoding uplinks

Datacake - Supports uplinks. Tested from TTI v3 app server via HTTP to Datacake
