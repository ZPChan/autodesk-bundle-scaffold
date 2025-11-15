# Autodesk Bundle Scaffold

Scaffolding for Autodesk Bundle Loader / Autoloader

## Steps to Use

1. Put a copy of the `appname.bundle` folder into your `%appdata%\Autodesk\ApplicationPlugins` folder so Autodesk applications know where to find it.  This folder has to end `.bundle` to be picked up automatically.
2. Replace all instances of `appname` with your own custom app name.
3. Edit `PackageContents.xml` to contain whatever instructions you need for your Autodesk applications.
4. Load up the `Contents` folder with your code, resources, or whatever else you need to deploy.  Make sure entry points are specified in `PackageContents.xml`.
