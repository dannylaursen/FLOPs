FLOPs
======

FLOPs (Floral Operators) is a set of HDAs centered around KineFX which simplify the generation and animation of high quality flora.

With preset recipes, it is easy to set up complex flower animations ready for render while being open for your custom changes. The toolkit plays well with standard Houdini nodes and allows you to inject and use custom attributes as needed.
## Installation
## Step 1: Downloading FLOPs
Download from GitHub or Gumroad to a location where your Houdini packages live. **Do not** download it directly into your `Documents/houdiniXX.X` folder.
For example's sake, I have downloaded FLOPs to `G:/HoudiniPackages/FLOPs`
## Step 2: Loading the package
Copy `FLOPs.json` into your Houdini preferences packages folder. On Windows the default location for this folder is `Documents/houdiniXX.X/packages`. For example's sake, mine is `C:/Users/Danny/Documents/houdini20.5/packages`.

Once `FLOPs.json` is in your packages folder, open it up and change the "FLOPs" variable to the path you downloaded FLOPs to in step 1. In my example, my `FLOPs.json` ends up looking like this:

```
{
    "path": "$FLOPs",
    "load_package_once": true,
    "env": [
        {
            "FLOPs": "G:/HoudiniPackages/FLOPs"
        }
    ]
}
```
## Step 3: Use FLOPs
Open a new instance of Houdini. Make a Geometry Container. Dive in, hit TAB and look for the FLOPs submenu. If it is there, you installed FLOPs correctly. Drop down a FLOPs Configure Simple Flower to get started quickly.
### Notice:
This software is provided AS-IS, with absolutely no warranty of any kind, express or otherwise. We disclaim any liability for damages resulting from using this software.
