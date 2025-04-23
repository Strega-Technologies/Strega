# STREGA
The Encoder-decoders for STREGA devices are written in JSCRIPT.
The DECODERS and ENCODERS work for all types of STREGA devices, however, the new generation named SE2/SV2 or Gen-2 use a little different encoder/decoder files..

For ChirpStack users, please use the ChirpStack CODECS as encoder and decoder: and select the pappropraite generation !!!!.

Since June 28, 2021, Payload Formatters for TTI and TTS (stack v3) is diirectly available from their "Device Repository".

Each decoder file notates which LNS it was tested on as they each seem to behave a little different.
Scott tested each script against The Things Network (community), Things Industries Cloud Hosted, Tektelic-NS, and ChirpStack.

Datacake - Supports uplinks. Tested from TTI v3 app server via HTTP to Datacake

Tektelic-NS: Decoder to be used in the "Data Converters" section

We thank Scott Waller from THINGY (www.thingy.us) for providing the one for the Datacake platform.
