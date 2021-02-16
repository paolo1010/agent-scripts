#!/bin/bash

if [ ${UID} -ne 0 ]
then
ehco "You need root access"
exit 1
fi
