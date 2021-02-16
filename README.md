#!/bin/bash

if [ ${UID} -ne 0 ]
then
echo
ehco "You need root access"
echo
exit 1
fi
