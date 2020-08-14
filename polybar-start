#! /usr/bin/env bash

killall -q polybar
wait

{ polybar main 2>&1; } > /dev/null &
{ polybar hdmi 2>&1; } > /dev/null &
