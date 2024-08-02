# Opus-iOS

> Opus is a totally open, royalty-free, highly versatile audio codec. Opus is unmatched for interactive speech and music transmission over the Internet, but is also intended for storage and streaming applications. It is standardized by the Internet Engineering Task Force (IETF) as RFC 6716 which incorporated technology from Skype's SILK codec and Xiph.Org's CELT codec.

iOS build script for the [Opus Codec](http://www.opus-codec.org).


## Building the XCFramework

#### Step 1

Download the [latest stable tar file](http://opus-codec.org/downloads/) and place it into the `build/src` directory

Note: If it's a new version of opus or if the iOS SDKs changed since the last time you built it, update that version at the top of the `build-libopus.sh` file.

#### Step 2

From the command line, run:

```bash
$ ./build-libopus.sh
```

That will take the tar file and build the static libraries as well as the XCFramework in a directory called `dependencies`


## License

MIT
