This is a dataset of more than 25 hours of driving captured by Comma Three (latest hardware from Comma.ai) in Makkah Province in KSA. The dataset includes routes (folders) that are divided into segments (subfolders) of one minute each. Each segment contains the following files:

- rlog.bz2: an archive of the serialized capnproto messages that contain all the messages passed amongst openpilot's processes and car. This file can be read and visualized using the PlotJuggler tool provided with OP.

- qlog.bz2: a decimated subset of the rlog that makes it easy to upload over a cellular network. This file can be read and visualized using the PlotJuggler tool provided with OP.

- fcamera.hevc: a H.265 encoded video of the road captured by the narrow back camera of Comma device.

- qcamera.ts: a lower resolution version of the fcamera.hevc that makes it easy to upload over a cellular network.

- ecamera.hevc: H.265 encoded video of the road captured by the wide back camera of Comma Three. 
 
Note that for privacy reasons, I did not include dcamera.hevc, a H.265 encoded video of the driver that can be captured by the front camera(s) of the Comma device. The dataset can be found in the Github page. 

The dataset will be updated regularly to include labels (day, night, sunny, rainy, long, short, etc, ), logs decoding, more drives, different cars, and regions.

The dataset can be downloaded via the provided Torrent files due to the large size of files

"All" (size: 342.85 GB) includes all recorded drives.

"Test2" (size: 90.44 GB) includes the drives used in Test2 of this paper:
XXXXX
