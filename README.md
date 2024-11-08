# FRP Proxy Manager 🚀 ( BETA EDITION )

A simple, easy-to-use **web-based manager** for handling **FRP (Fast Reverse Proxy)** configurations. Manage, start, stop, and create proxy Configs through a web dashboard. make your process faster and more efficient. 💖

![Dashboard](https://media.discordapp.net/attachments/1263264045864321161/1304272303697432627/image.png?ex=672ec9bd&is=672d783d&hm=bfbdbc57e5bff4b49511f2745b1655a64abb388b0218c84bdb6ff1f58b1ba7f8&=&format=webp&quality=lossless&width=437&height=350)

## Features 🔥
- ✅ **Start, Stop, and Create Proxies**: Easily manage your FRP instances from a web interface.
- 🔒 **Secure and Fast**: Hassle-free proxy configurations with optimized performance.
- 📈 **Interactive Dashboard**: Monitor and control your proxies with a user-friendly web dashboard (see above!).
- ⚙️ **Configurable**: Customize your FRP settings to fit your needs.
- 💡 **Lightweight & Simple**: No complex setup, just works out of the box.

## Installation 🛠️ ( Nodejs Required ) 

1. Clone this repository:

   ```bash
   git clone https://github.com/abdalla435/FRP-Proxy-Web-.git
   cd FRP-Proxy-Web-
   wget https://github.com/fatedier/frp/releases/download/v0.61.0/frp_0.61.0_linux_amd64.tar.gz && \
   tar -xzf frp_0.61.0_linux_amd64.tar.gz && \
   rm frp_0.61.0_linux_amd64.tar.gz && \
   cp -r frp_0.61.0_linux_amd64/* ./ && \
   rm -rf frp_0.61.0_linux_amd64
   ```

2. Install required dependencies:

   ```bash
   npm install express
   ```

3. Run the application:

   ```bash
   node index.js
   ```

4. Configure your proxies and enjoy easy management!

## Contributing 🤝

We welcome contributions! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.
