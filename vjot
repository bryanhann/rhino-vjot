source ~/.config/rhino/sourceme
pushd $0/.. > ~/.local/tmp/deleteme

export RHINO_LOG=$RHINO_VOICE_ACC
export RHINO_STAGE=$RHINO_VOICE_STAGE
export RHINO_WS852=/Volumes/WS-852/RECORDER

if [ -f "./bin/$1" ] 
then
       ./bin/$* 
else
	echo usage: 
	echo "    $0 SUBCOMMAND"
	echo
	echo SUBCOMMANDS:
	for ii in `ls -1 ./bin`
	do
    	echo "    $ii"
	done
fi

popd > ~/.local/tmp/deleteme
