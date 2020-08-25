# OSGeoLive Apply - OpenDroneMap #

## Please describe your application ##  
- What is its name? 
  - OpenDroneMap
- What is the home page URL?  
  - https://www.opendronemap.org/
- Which OSI approved Open Source Licence is used?  
  - Mix of GPL, AGPL, MPL, BSD, MIT, Apache, and The Unlicense.
- What does the application do and how does it add value to the GeoSpatial stack of software?  
  - OpenDroneMap is an open-source photogrammetry toolkit to process aerial survey imagery into maps and 3D models using the Structure From Motion principle. It is available for download in docker container format as well as in binary for Linux, MacOS, and Windows. Source code for all of the components is currently hosted on GitHub. 
- Does the application make use of OGC standards? Which versions of the standards? Client or server? You may wish to add comments about how standards are used.  
- What language is it written in?
  - Mix of JavaScript, Python, R, C++, Shell Scripts, and Go.
- Which version of the application should be included in the next OSGeo-Live release?  
Stability is very important to us on OSGeo-Live. If a new user finds a bug in one application, it will tarnish the reputation of all other OSGeo-Live applications as well. (We pay most attention to the following answers):   
- If risk adverse organisations have deployed your application into production, it would imply that these organisations have verified the stability of your software. Has the application been rolled out to production into risk (ideally risk adverse) organisations? Please mention some of these organisations?  
- Open HUB provides metrics to help assess the health of a project. Eg: http://adhoc.osgeo.osuosl.org/livedvd/docs/en/metrics.html Could you please ensure that your project is registered with Open HUB, and Open HUB has been updated to reference the correct code repository(s) for your project. What is the Open HUB URL for your project?  
- What is the size of the user community? You can often answer this by mentioning downloads, or describing a healthy, busy email list?  
- What is the size of your developer community?  
- Do you have a bug free, stable release?  
- Please discuss the level of testing that your project has gone through.  
- How long has the project has had mature code.  
OSGeo-Live is targeted at applications that people can use rather than libraries. Does the application have a user interface (possibly a command line interface) that a user can interact with? (We do make an exception for Incubated OSGeo Libraries, and will include Project Overviews for these libraries, even if they don't have a user interface.)  
We give preference to OSGeo Incubated Projects, or Projects which are presented at FOSS4G conferences. If your project is involved in OSGeo Incubation, or has been selected to be presented at FOSS4G, then please mention it.  
With around 50 applications installed on OSGeo-Live, us core packagers do not have the time to liaise with every single project email list for each OSGeo-Live release. So we require a volunteer (or two) to take responsibility for liaising between OSGeo-Live and the project's communities. This volunteer will be responsible for ensuring the install scripts and English documentation are updated by someone for each OSGeo-Live release. Also test that the installed application and Quickstart documentation works as expected on release candidate releases of OSGeo-Live. Who will act as the project's liaison person.  
OSGeo-Live is Ubuntu Linux based. Our installation preference is:  
1. Install from UbuntuGIS or DebianGIS  
2. Install .deb files from a PPA  
3. Write a custom install script  
Can you please discuss how your application will be installed.  
OSGeo-Live is memory and disk constrained. Can the application run in 512 Meg of RAM?  
How much disk space will be required to install the application and a suitable example application?  
We aim to reduce disk space by having all applications make use of a common dataset. We encourage applications to make use of the example datasets already installed:  
http://wiki.osgeo.org/wiki/Live_GIS_Add_Project#Example_Datasets If another dataset would be more appropriate, please discuss here. Is it appropriate, to remove existing demo datasets which may already be included in the standard release.  
Each OSGeo-Live application requires a Project Overview available under a CC By and a Quickstart available under a CC By-SA license. (You may release under a second license as well). Will you produce this?  
In past releases, we have included Windows and Mac installers for some applications. It is likely we won't have space for these in future releases. However, if there is room, would you be wishing to include Windows and/or Mac installers?  
