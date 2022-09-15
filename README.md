# Introduction 
    Maestro UI Automation for IOS

# Build and Test

# Install Maestro
    brew tap mobile-dev-inc/tap
    brew install maestro

# Setup Simulator IOS
    brew tap facebook/fb
    brew install idb-companion

# Launch Simulator
    idb_companion --udid {id of the iOS device}

# Run Test
    maestro test -c test AMA-Maestro.yaml