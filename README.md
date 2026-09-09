# aosp-build

This is an example of how to build [Android Open Souce Project (AOSP)](https://source.android.com/) in GitHub Actions. With a 32-cores, 128 GB RAM, 1200 GB SSD runner, the build takes about 2 hours and 5 minutes to complete successfully. Obviously, this is too long. There are several opportunities to improve the build speeds by caching dependencies or building a custom runner with dependencies readily available.  
