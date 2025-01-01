```
ls -la ~/Library/Application\ Support/OrcaSlicer/user/default/
ls -la ~/Library/Application\ Support/OrcaSlicer/user/default/filament
ls -la ~/Library/Application\ Support/OrcaSlicer/user/default/machine
ls -la ~/Library/Application\ Support/OrcaSlicer/user/default/process

mv -iv ~/Library/Application\ Support/OrcaSlicer/user/default/* .

pwd
ORCA_GIT=<TODO>


ln -siv $ORCA_GIT/filament ~/Library/Application\ Support/OrcaSlicer/user/default/filament
ln -siv $ORCA_GIT/machine ~/Library/Application\ Support/OrcaSlicer/user/default/machine
ln -siv $ORCA_GIT/process ~/Library/Application\ Support/OrcaSlicer/user/default/process
```
