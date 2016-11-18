# chromium-downloader-script
A simple bash script which downloads the latest Chromium version for your platform.
This script may be useful if you wish to update your web browser to the latest nightly build.
Works fine on Linux and macOS.

Usage: 

    ./chromium-downloader.sh [options]

Available options:

  - <code>--help</code>: displays information about the usage of the script.
  - <code>--path</code>: specifies where the file will be downloaded.
	
<strong>Notice:</strong> The <code>--path</code> option must be followed by a valid path.

Short options are also available. You can use <code>-h</code> instead of <code>--help</code> or
or <code>-p</code> instead of <code>--path</code>.

If no option has been provided, the script will download the latest Chromium build to your
current directory.
