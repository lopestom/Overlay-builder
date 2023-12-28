# Overlay-builder
Using Github Actions to build device specific overlays for Phh based GSI's
# 2023
 - Changed URL to new base TD (Treble Droid) GSI https://github.com/trebledroid/vendor_hardware_overlay

## How to use
#Fork [vendor_hardware_overlay](https://github.com/phhusson/vendor_hardware_overlay) and make the necessary changes. --> Deprecated
1. Fork [TD-vendor_hardware_overlay](https://github.com/trebledroid/vendor_hardware_overlay) and make the necessary changes.
2. Fork [this repo](https://github.com/Johx22/Overlay-builder)
3. Click on Actions tab. Under workflows click Overlay
4. Click Run Workflow. 
5. In FORK_URL input the URL of vendor_hardware_overlay which was forked to your Github Repositories
6. Click Run Workflow
7. Once the building is done a zip file will be generated containing all overlays. Extract and get your Device Overlay
