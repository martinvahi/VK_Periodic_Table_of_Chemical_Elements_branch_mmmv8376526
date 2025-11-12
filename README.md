
# VK_Periodic_Table_of_Chemical_Elements_branch_mmmv8376526

...wraps and morphs the [MIT-licensed](https://github.com/valter1977/Pertable/blob/main/LICENSE) [Periodic Table of Chemical Elements](https://kodu.ut.ee/~kiisk/pertable/pertable.htm) 
by [Valter Kiisk](https://kodu.ut.ee/~kiisk/). The upstream project is
operating system neutral, but 
<span style="color:red"><strong>this branch is Linux specific</strong></span>.
It might also work on FreeBSD, but 
<span style="color:red"><strong>this branch is NOT tested on BSD</strong></span>.


## License

The licenses of different parts of this project vary, but all of them
allow unmodified use at closed source projects and most of the licenses
allow to keep the downstream modifications of this project as closed
source.


## Difference from Upstream

Currently the main difference is that this branch includes a
configured copy of the 
[wappskafander_t2](https://github.com/martinvahi/wappskafander_t2)
*([SourceForge copy](https://sourceforge.net/projects/wappskafander-t2/))*, 
which itself is a wrapper of an older version of the 
[Hiawatha](https://hiawatha.leisink.net/) 
[HTTP](https://datatracker.ietf.org/doc/html/rfc2616) server, 
which has been implemented in C++ and is built by wappskafander_t2 scripts
by using [CMake](https://cmake.org/).


## Usage on Linux

1. Please run the 
   **./src/HTTP_server_with_webapp_at_web_root/bin/start_or_restart_server.bash** .
   The Hiawatha HTTP server gets built/compiled at first run of that Bash script.
2. Please open a web browser and please use the 
   IP-address and the port number that were displayed by the 
   **./src/HTTP_server_with_webapp_at_web_root/bin/start_or_restart_server.bash**
3. Sometimes You may want to use the 
   **./src/HTTP_server_with_webapp_at_web_root/bin/stop_server.bash**


## Folder Structure

The folder **./attic** can be deleted without breaking anything. 
All of the morphed upstream 
code*(there are no significant modifications yet in this version)* 
resides at                                    
**./src/HTTP_server_with_webapp_at_web_root/web_root**


** Thank You for studying this project :-) **
