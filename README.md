# Aseprite Builder

Build Aseprite for Windows or Linux using GitHub Actions.

1. Fork this repo and open **Actions**.
2. Choose **Build Aseprite** for Windows or **Build Aseprite (Linux)** for Linux.
3. Click **Run workflow**. The Linux workflow also lets you choose an Aseprite version tag.
4. Once the build finishes, download the files:
   - **Windows:** `aseprite-setup.exe` from Releases or the run's artifacts.
   - **Linux:** the `.deb` package or portable `.tar.gz` from the run's artifacts.

If a build fails, open the failed step to see the error.

The builds use the [official Aseprite source](https://github.com/aseprite/aseprite). Aseprite's own [license](https://github.com/aseprite/aseprite/blob/main/LICENSE.txt) applies to the resulting builds.
