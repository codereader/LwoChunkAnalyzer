# LwoChunkAnalyzer - Display Chunk Structure of a Lightwave LWO2 File

Command-line utility to display the contents of a single LWO file. For the purpose of analysis, it can optionally remove certain chunks from the file and save the modified file.

No guarantees whatsover, I just hope it's useful.

## Usage
> **LwoChunkAnalyzer** <model.lwo>

## Example Output

```
--- C:\Temp\model.lwo ---
FORM [26648]
  TAGS [40]
  LAYR [18]
  PNTS [6300]
  BBOX [24]
  POLS [3380]
  PTAG [1692]
  VMAP [5262]
  VMAP [9472]
  SURF [192]
    COLR [14]
    VCOL [26]
    SMAN [4]
    BLOK [100]
      IMAP [40]
        CHAN [4]
        ENAB [2]
      TMAP [20]
        SIZE [14]
      PROJ [2]
      AXIS [2]
      VMAP [6]
  SURF [184]
    COLR [14]
    VCOL [26]
    SMAN [4]
    BLOK [96]
      IMAP [36]
        CHAN [4]
        ENAB [2]
      TMAP [20]
        SIZE [14]
      PROJ [2]
      AXIS [2]
      VMAP [6]
```

## Compiling

Open the LwoChunkAnalyzer.sln (Visual Studio 2019) solution file in the root folder, compile and run. No dependencies, it just requires a modern C++ compiler.

There's no CMake file present yet at the time of writing. There's just a single main.cpp file to compile.

## License

All code is published under the MIT License. See the [LICENSE](https://github.com/codereader/LwoChunkAnalyzer/blob/main/LICENSE) file in this repository.
