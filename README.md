# Advanced Locomotion System - Community Version
![image](https://github.com/dyanikoglu/ALS-Community/raw/main/Resources/Readme_Content_2.gif)

Replicated and optimized version of [Advanced Locomotion System V4](https://www.unrealengine.com/marketplace/en-US/product/advanced-locomotion-system-v1) for **Unreal Engine 5.4** with additional bug fixes

<p align="center">
  <a href="https://discord.gg/6yhHP2e8Jx"><img src="https://i.imgur.com/LP9bZQj.png"></a>
</p>

## About This Repository

Advanced Locomotion system is built upon pretty outdated animation programming techniques of pre Unreal Engine 5 era, and I highly recommended to utilize other available locomotion systems, such as Epic's Lyra sample project. This repository will only receive engine compatibility fixes from now.

## Supported Platforms
- Windows
- Linux

*Console, Mac and mobile platforms are not tested and supported at the moment. Use the plugin on those platforms with your own risk.*

## Features
- Fully implemented and optimized in C++. Implementation is based on latest marketplace release (V4) of ALS
- Complete replication support with low bandwidth usage (Ragdoll replication is in experimental state)
- Redesigned as plugin
- Animation blueprint is optimized with new property binding feature
- Player input is handled with new Enhanced Input Plugin
- Mantling and debugging features are implemented as separate actor components to reduce total overhead on base character class
- Improved footstep system with decal & Niagara particle support
- Lots of additional bug fixes
