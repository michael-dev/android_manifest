_LineageOS 15.1 for LGE MSM8916 Devices_
---------------------------

the local manifests:

	$ repo init -u git://github.com/LineageOS/android.git -b lineage-15.1
	$ git clone https://github.com/michael-dev/android_manifest -b lineage-15.1 .repo/local_manifests

Apply Patches to LineageOS 15.1:

	$ cd frameworks/base/
	$ git fetch https://github.com/LineageOS/android_frameworks_base refs/changes/17/233917/2 && git cherry-pick FETCH_HEAD
	$ cd ../../

Then sync up with this command:

	$ repo sync --force-sync
	
You can make the 4 higher depending on how fast your internet connection is. 
