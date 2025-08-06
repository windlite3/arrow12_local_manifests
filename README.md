# arrow12_local_manifests
Redmi Note7 (Lavender) Arrow-12.0 的自定义项目

结合 repo init -u https://github.com/ArrowOS/android_manifest.git -b arrow-13.1 --git-lfs --depth=1 一起使用。

把项目中的 roomservice.xml 放置在 .repo/local_manifests/roomservice.xml 中，

然后 repo sync -c -j32 --no-clone-bundle --no-tags --force-sync 进行同步。


