<div align="center">
	<div>
		<img width="500" src="media/logo.svg" alt="Awesome AppImage">
	</div>
	<br>
	<br>
	<br>
	<a href="https://awesome.re">
		<img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
	</a>
	<p>
		<sub>Lovingly crafted AppImage tools and resources. Follow me on <a href="https://twitter.com/probonopd">Twitter</a>.</sub>
	</p>
	<br>
	<p>
		<a href="https://appimage.org">AppImage</a> is a format to distribute applications to various mainstream Linux distributions. One app = one file! As the vibrant community around AppImage is growing, so is this list.
	</p>
	<br>
</div>

## Contents

- [AppImage discovery](#appimage-discovery)
	- [App catalogs](#app-catalogs)
	- [App stores](#app-stores)
	- [App centers](#app-centers)
	- [App scrapers](#app-scrapers)
- [AppImage consumption tools](#appimage-consumption-tools)
	- [Desktop integration](#desktop-integration)
	- [Updaters](#updaters)
	- [Package managers](#package-managers)
- [AppImage developer tools](#appimage-developer-tools)
	- [Low-level tools](#low-level tools)
	- [Deployment tools for compiled applications](#deployment-tools-for-compiled-applications)
	- [Tools to convert from other package formats](#tools-to-convert-from-other-package-formats)
	- [Libraries](#libaries)
- [Resources](#resources)
	- [Specs](#specs)
	- [Documentation](#documentation)
	- [Tutorials](#tutorials)
	- [Articles](#articles)
	- [Newsletters](#newsletters)
	- [Videos](#videos)
	- [Books](#books)
	- [Blogs](#blogs)
	- [Courses](#courses)
	- [Cheatsheets](#cheatsheets)
	- [Community](#community)
	- [Miscellaneous](#miscellaneous-1)

## AppImage discovery

### App catalogs

- [appimage.github.io](https://appimage.github.io/) - Catalog of AppImages that passed an automated test, links to upstream download pages

### App stores

- [AppImageHub.com](https://www.appimagehub.com/) - Downloadable AppImages, powered by [Opendesktop.org](https://www.opendesktop.org/)
- [pling.com](https://www.pling.com/) - Open store where creators can publish their libre products and creative content including AppImages
- [Linux App Store](https://linuxappstore.io/) - Universal app store for Linux applications in AppImage, Flatpak, and Snap formats (project abandoned)

### App centers

- [NX Software Center](https://github.com/Nitrux/nx-software-center) - Portable Software Center for portable AppImage applications

### App scrapers

- [appimages.scraper](https://github.com/azubieta/appimages.scraper) - Search for AppImage releases over the web

## AppImage consumption tools

### Desktop integration

- [go-appimaged](https://github.com/probonopd/go-appimage/tree/master/src/appimaged) - Optional daemon that integrates AppImages into the system (experimental).
- [appimaged](https://github.com/AppImage/appimaged) - Optional daemon that integrates AppImages into the system (deprecated).
- [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher) - Asks user to move AppImages into applications directory and integrates them into the system.

### Updaters

- [AppImageUpdate](https://github.com/AppImage/AppImageUpdate) - Official grapical application to update AppImages; command-line tool to update AppImages
- [AppImageUpdater](https://github.com/antony-jr/AppImageUpdater) - Simple updater for humans written in C++ and Qt

### Package managers

- [appimage-installer](https://github.com/azubieta/appimage-installer) - Command-line tool for managing AppImages allowing to search, install, remove and update applications

## AppImage developer tools

### Low-level tools

- [appimagetool](https://github.com/AppImage/AppImageKit/releases/tag/continuous) - Converts AppDir into AppImage

### Deployment tools for compiled applications

- [linuxdeployqt](https://github.com/probonopd/linuxdeployqt) - Deploys dependencies into AppDirs and creates AppImages; for Qt and other compiled applications
- [linuxdeploy](https://github.com/linuxdeploy/linuxdeploy) - AppDir creation and maintenance tool using plugins

### Tools to convert from other package formats

- [pkg2appimage](https://github.com/AppImage/pkg2appimage) - Converts from deb, zip, tar.gz and other formats to AppImage using YAML recipes

### Libraries

- [AppImageUpdaterBridge](https://github.com/antony-jr/AppImageUpdaterBridge) - Qt5 library and plugin for updating AppImages, can be embedded into applications
- [AppImageServices](https://github.com/azubieta/AppImageServices) - D-Bus services providing a high-level interface over the AppImage manipulation libraries for file managers, software centers and other tools
- [libappimage](https://github.com/AppImage/libappimage) - Implements functionality for dealing with AppImage files, written in C++ using Boost

## Resources

### Specs

- [AppImageSpec](https://github.com/AppImage/AppImageSpec) - Official specification for the AppImage format
- [Desktop Entry Specification](https://specifications.freedesktop.org/desktop-entry-spec/latest/) - specification for the matadata used inside AppImages

### Documentation

- [docs.appimage.org](https://docs.appimage.org/) - Official AppImage documentation

### Tutorials

### Articles

### Newsletters

### Videos

- [AppImage: Portable applications for Linux](https://www.youtube.com/watch?v=nzZ6Ikc7juw) - Official AppImage introduction video by its founder 

### Books

### Blogs

- [TheAssassin Blog](https://assassinate-you.net/tags/appimage/) - Blog covering AppImage related topics by TheAssassin
- [AppImage Crafters Blog](https://appimagecrafters.github.io/) - Blog about AppImage creation an usage by azubieta

### Courses

### Community

- [discourse.appimage.org](https://discourse.appimage.org/) - Official AppImage forum for users and application developers

### Miscellaneous

- (appimage.org)[https://appimage.org/] - Official AppImage landing page
