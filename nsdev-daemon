#!/bin/sh

CONFIG=/etc/nsdev-daemon.cfg

source $CONFIG

if [ "$AUTORESTART" = true ] ; then
	while true; do
		`$RUN_CMD`
		echo "Restarting ..."
	done
else
	`$RUN_CMD`
fi
