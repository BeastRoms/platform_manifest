<p align="center">
<img src="https://avatars1.githubusercontent.com/u/44024670?s=400&u=c5f798ffaa66ab14931176d77077fd2cd5bb83ca&v=4" >
</p>

---------------------------------------------------------------------------------------
 Getting Started:
 ==============

To get started with manifest/LeanOS-Project, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/LeanOS-Project/platform_manifest.git -b lean-9.x

```

Then to sync up:

```
repo sync -c -f --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j8
```

---------------------------------------------------------------------------------------
 Compilation of LeanOS:
 ==================

From root directory of Project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch lean_$device-userdebug
$ mka bacon lean
```

For maintainership refer [**HERE**](https://github.com/LeanOS-Project/Official-Tag.git)

---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**DotOS**](https://github.com/DotOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**CypherOS**](https://github.com/CypherOS)
 * [**Xtended**](https://github.com/Xtended-Pie)

---------------------------------------------------------------------------------------

