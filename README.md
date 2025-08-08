# **Airlink Panel Image Repository**

Welcome to the **Airlink Panel Image Repository**! This central collection of Dockerfiles and JSON configurations powers the creation and deployment of airlink panel server images.

## 🔗 JSON Configuration Files

### Generic Images

* [Node.js 23 Generic Image](https://github.com/airlinklabs/images/blob/main/generic/node/23/image.json) – Configuration for building the **Node.js 23** image.
* [Node.js Base Generic Image](https://github.com/airlinklabs/images/blob/main/generic/node/image-node.json) – Base settings for **Node.js** generic image.
* [Python Base Generic Image](https://github.com/airlinklabs/images/blob/main/generic/python/image-python.json) – Base settings for **Python** generic image.

### Minecraft Server Images

* [Minecraft Fabric Server Image](https://github.com/airlinklabs/images/blob/main/minecraft/java/fabric/image-fabric.json) – JSON config for **Fabric**-based Minecraft server.
* [Minecraft Paper Server Image](https://github.com/airlinklabs/images/blob/main/minecraft/java/paper/image-paper.json) – JSON config for **Paper**-based Minecraft server.

### Virtual Machine Images

* [Debian VM Image](https://github.com/airlinklabs/images/blob/main/vm/image-debian.json) – Configuration for **Debian** virtual machine image.

### Other JSON Files

* [Master Index of Available Images](https://github.com/airlinklabs/images/blob/main/index.json) – Lists all image types and metadata.

## 📂 Repository Structure

```bash
images/
├── Docker_file/          # Base Dockerfiles
│   ├── java/21/         # Java 21 Docker setup
│   │   └── Dockerfile
│   └── node/23/         # Node.js 23 Docker setup
│       └── Dockerfile
├── LICENSE              # Project license
├── README.md            # This file
├── generic/             # Generic language images
│   ├── node/
│   │   ├── 23/           
│   │   │   └── image.json  # Node.js 23 generic image config
│   │   └── image-node.json # Node.js base image config
│   └── python/
│       └── image-python.json # Python base image config
├── index.json           # Master index of all image types
├── minecraft/           # Minecraft server images
│   └── java/
│       ├── fabric/
│       │   └── image-fabric.json # Minecraft Fabric server image
│       ├── paper/
│       │   └── image-paper.json  # Minecraft Paper server image
│       └── server.properties     # Default server properties
└── vm/
    └── image-debian.json  # Debian VM image config
```

### License
[MIT license](LICENSE)


