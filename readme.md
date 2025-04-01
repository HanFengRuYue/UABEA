<p align="center"><img src="UABEAvalonia/Assets/logo.png" /></p>

**快速下载:**

[最新每日构建 (Windows)](https://nightly.link/nesrak1/UABEA/workflows/dotnet-desktop/master/uabea-windows.zip) | [最新每日构建 (Linux)](https://nightly.link/nesrak1/UABEA/workflows/dotnet-ubuntu/master/uabea-ubuntu.zip) | [最新正式版](https://github.com/nesrak1/UABEA/releases)

[![GitHub issues](https://img.shields.io/github/issues/nesrak1/UABEA?logo=GitHub&style=flat-square)](https://github.com/nesrak1/UABEA/issues) [![discord](https://img.shields.io/discord/862035581491478558?label=discord&logo=discord&logoColor=FFFFFF&style=flat-square)](https://discord.gg/hd9VdswwZs)

## UABEAvalonia

跨平台的Asset Bundle/序列化文件读取器和编辑器。最初基于(但不是分支自)[UABE](https://github.com/SeriousCache/UABE)。

## 提取资源

UABEA的开发更倾向于作为一个修改/研究工具，而非提取工具。如果您只想提取资源，请使用[AssetRipper](https://github.com/AssetRipper/AssetRipper)或[AssetStudio](https://github.com/Perfare/AssetStudio/)。

## 可寻址资源系统(Addressables)

现在很多游戏都在使用可寻址资源系统。如果您打开的bundle文件路径是`StreamingAssets/aa/XXX/something.bundle`，那它就是可寻址资源系统的一部分。[如果您想编辑这些bundle文件，您需要使用此处的CRC清理工具来清除CRC校验](https://github.com/nesrak1/AddressablesTools/releases)。使用`Example patchcrc catalog.json`，然后移动或重命名旧的catalog.json文件，并将catalog.json.patched重命名为catalog.json。

## 使用的库

- [Avalonia](https://github.com/AvaloniaUI/Avalonia) (MIT许可证)
  - [Dock.Avalonia](https://github.com/wieslawsoltes/Dock) (MIT许可证)
  - [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit) (MIT许可证)
- [AssetsTools.NET](https://github.com/nesrak1/AssetsTools.NET/tree/upd21-with-inst) (MIT许可证)
  - [Cpp2IL](https://github.com/SamboyCoding/Cpp2IL) (MIT许可证)
  - [Mono.Cecil](https://github.com/jbevain/cecil) (MIT许可证)
  - [AssetRipper.TextureDecoder](https://github.com/AssetRipper/TextureDecoder) (MIT许可证)
- [ISPC Texture Compressor](https://github.com/GameTechDev/ISPCTextureCompressor) (MIT许可证)
- [Unity crnlib](https://github.com/Unity-Technologies/crunch/tree/unity) (zlib许可证)
- [PVRTexLib](https://developer.imaginationtech.com/pvrtextool) (PVRTexTool许可证)
- [ImageSharp](https://github.com/SixLabors/ImageSharp) (Apache许可证2.0)
- [Fsb5Sharp](https://github.com/SamboyCoding/Fmod5Sharp) (MIT许可证)
- [Font Awesome](https://fontawesome.com) (CC BY 4.0许可证)
