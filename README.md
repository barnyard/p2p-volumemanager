# p2p-volumemanager

This application allows attaching persistent storage volumes to running compute instances.

## Build

This project depends upon `p2p-build` being setup with `ant` and `ant-contrib`. [See instructions](http://barnyard.github.io/p2p-build)

### Dependencies

The following projects should be siblings to this project and had 'publish' targets run on them.

- [p2p-instancemanager](http://barnyard.github.io/p2p-instancemanager)

### Compiling

Add a properties file with your configuration you'd like in the `properties` directory.

    ant

