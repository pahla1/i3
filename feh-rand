#!/bin/bash

dst='/tmp/backgrounds'
url='https://source.unsplash.com/1600x900'
filename=$(date +"%Y%m%d_%H%M%S.jpg")

export DISPLAY=":0.0"
mkdir -p $dst
wget $url -O $dst/$filename
feh --randomize --bg-fill  $dst/*.jpg
