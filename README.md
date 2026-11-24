# Relay Offline desktop releases

This repository distributes Windows installers and signed update manifests only. It does not contain the private application source or any customer database.

The first updater-enabled bootstrap is version 0.2.1. Older 0.1.x installations require one manual upgrade. Subsequent versions support Help → Check for updates, verified downloads and explicit restart/install.

Windows installers currently do not have an Authenticode publisher signature. Release metadata is separately Ed25519 signed and binds the exact installer SHA512 and size. Office servers and databases are updated separately.

Support: synexdevelopers@gmail.com
