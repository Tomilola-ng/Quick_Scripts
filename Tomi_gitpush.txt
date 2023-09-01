#!/bin/bash

# Add all changes
git add .

# Commit changes with the provided message or a default message
if [ -z "$1" ]; then
    git commit -m "Push codes by Tomi :)"
else
    git commit -m "$1"
fi

# Push changes
git push
