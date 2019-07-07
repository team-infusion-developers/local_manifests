## Important for jfvelte
repopick 250445

LineageOS 16.0 for jfvelte
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using our trees, use a command like this:

```
1. mkdir -p InFusionX-i9515 && cd InFusionX-i9515

2. Initialize your local repository using the LineageOS trees with a command
  repo init -u git://github.com/LineageOS/android.git -b lineage-16.0
  
3. Clone this repo:
  git clone git://github.com/team-infusion-developers/android_local_manifest_jfvelte.git -b lineage-16.0

4. Sync LineageOS trees:
  repo sync --no-tags --no-clone-bundle --force-sync -c -j8


Building
---------------
6. To build:
  . build/envsetup.sh
  lunch lineage_jfvelte-userdebug
  make -j8 bacon

```
