### Java

**File:** java-format.xml <br>
**File Location:** Anywhere (Specifically `~/.format` for vscode settings)

### C / C++

**File:** .clang-format <br>
**File Location:** Anywhere (Specifically `~/.format` for vscode settings)

### Rust

**File:** .rustfmt.toml <br>
**File Location:** In either the home directory `~` or the rustfmt config folder `~/.config/rustfmt`

### VSCode

**File:** settings.json <br>
**File Location:** Place into VSCode settings location, file paths may need to be updated where required

**File:** extensions.sh <br>
**Prerequisites:** `chmod u+x extensions.sh` to allow the current user to execute the file as a shell script <br>
**Use:** To install all the extensions listed in the file run it using `./extensions.sh`
**Creation:** To generate this file from the current VSCode run `code --list-extensions | xargs -L 1 echo code --install-extension > extensions.sh`, a file called extensions.sh will be produced in the currect directory