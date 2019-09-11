Python 3 script to create data file for CudaText.
It must be run from the folder, which contains all "lexer.*.zip" CudaText lexers.
(Use menu "Plugins/ Addon Manager/ Download all" to get all .zip files).
It creates Python file in the same folder.
It has one variable like this:

TYPES = {
    "/.htaccess": ['Apache config'],
    "/Dockerfile": ['Dockerfile'],
    ...
    "as": ['ActionScript', 'Haskell'],
    "cla": ['Clavier', 'Clarion'],
    "h": ['CUDA C++', 'CodeVisionAVR', 'Great Cow Basic'],
    ...
}


Author: kvichans from GitHub
License: MIT
