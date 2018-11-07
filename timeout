#!/usr/bin/env bash

TIMEOUT=$1
shift
echo TIMEOUT $TIMEOUT $@
($@)  & sleep $TIMEOUT; kill $! && exit 1 2> /dev/null || :