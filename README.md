_LineageOS 15.1 for LGE MSM8916 Devices_
---------------------------

the local manifests:

	$ repo init -u git://github.com/LineageOS/android.git -b lineage-15.1
	$ git clone https://github.com/LG-MSM8916/android_local_manifest -b lineage-15.1 .repo/local_manifests

Then sync up with this command:

	$ repo sync --force-sync
	
You can make the 4 higher depending on how fast your internet connection is. 
