# How to Uninstall Software in Arch Linux

## 1. The Best Way (Recommended)
Use this method to remove the software, its unused dependencies, and configuration files (**Clean Uninstall**).

**Command:**
```bash
sudo pacman -Rns package_name
```
**Example:**

```bash
sudo pacman -Rns vlc
```
**-R :** Remove the package.

**-n :** Remove configuration files (No backup).

**-s :** Remove dependencies that are no longer needed.

## 2. The Basic Way
Use this if you only want to remove the specific software but keep the dependencies. (Not recommended as it leaves "junk" files).

**Command:**
```bash
sudo pacman -R package_name
```
## 3. Removing AUR Packages (using yay)
If you installed the software using yay (like Google Chrome or Zoom), use this command:

**Command:**
```bash
yay -Rns package_name
```
## 4. If you don't know the exact package name
If you are not sure about the software name, search for it first using this command:

**Command:**
```bash
pacman -Qs search_term
```
```bash
Example: pacman -Qs fire (to find Firefox).
```