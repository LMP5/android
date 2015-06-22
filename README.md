LMP5
=======

Initialize the Repo

repo init -u git://github.com/LMP5/android.git -b LMP5-5.1

repo sync

TO BUILD

. build/envsetup.sh

lunch

enter the number of the device you like to build

make bacon -j#

====================================================
To speed things up we have added a new script
from the root of LMP5 open terminal.
type ./mk
the script will start the rest is just pick what and how you would like to build
