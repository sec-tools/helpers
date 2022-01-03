#!/bin/bash
#
# adds the current user to the sudo config so they can call it password-less-ly
#
echo "$(whoami) ALL=(ALL) NOPASSWD: ALL" | (sudo EDITOR="tee -a" visudo)
