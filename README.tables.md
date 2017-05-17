# extreme-defaults

## Run programs with the most extreme parameters.


| Option | Description |
| ------ | ----------- |
| ### data   | path to data files to supply the data that will be passed into templates. |
| **engine** | engine to be used for processing templates. Handlebars is the default. |
| ##ext    | ##extension to be used for dest files. |

### Multimedia
* **max-optipng:**
    Runs optipng with slowest settings to archieve maximum PNG file compression
* **max-pngcush:**
Produce the smallest possible PNG file pngcrush can produce
* **max-quality-yt-music-dl:** </n>Download the YouTube video with the highest audio quality and extract the audio file.

### Scheduling
* **max-nice:** <br>Run an application with the least intruding scheduling policies on CPU, IO, fsync operations.

### Development
* **max-exhaustive-valgrind-drd:** <br>Runs the valgrind DRD tool with settings for to find maximum numbers of errors
* **max-exhaustive-valgrind-exp-sgcheck:** <br>Runs the valgrind exp-sgcheck tool with settings for to find maximum numbers of errors
* **max-exhaustive-valgrind-helgrind:** <br>Runs the valgrind helgrind tool with settings for to find maximum numbers of errors
* **max-exhaustive-valgrind-memcheck:** <br>Runs the valgrind memcheck tool with settings for to find maximum numbers of errors

### Security
* **max-secure-luks-format:**  Create a LUKS dm-crypt volume with very secure crypto/hash settings.

### Virtualization
* **fast-qemu:** Start a qemu instance with settings optimized for speed
* **fast-qemu-no-kvm:** Start a qemu instance with settings optimized for speed but without hardware virtualization support
* **fast-qemu-img:** Create a new qcow2 virtual machine image with performance optimizations