# Weather module patch for sfetch

Apply the weathermod.diff from within the original sfetch programs folder (diff -p1 < weathermod.diff) and run install.sh inside the installation folder.

# Usage 

"sfetch -u" for updating the cache manually.

The cache gets stored inside the /tmp folder, so you eventually **have** to update the cache after 
a restart of your system.

# Dependencies

- \>= libcurl/8.17.0

# Example:

![sfetchweatherpatch](weather.png)
