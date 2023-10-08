---
layout: default
modal-id: 2022060101
date: 2023-10-01
img: remote_video_backup.svg
alt: Scheduled Remote Video Backup
project-date: 2019
language: Powershell
category: Computer Science
description: Media management was becoming a huge chunk of my daily routine so I decided to automate it, creating a scheduled Powershell script to download video files from a fleet of Blackmagic Design Hyperdeck video recorders. The script searches for recorders distributed across several production networks, traversing all storage media on each recorder, ignoring missing or damaged SD cards/external SSDs. All media files on the recorder are downloaded via FTP, uploaded to a remote samba share and then removed from the recorder, reclaiming storage space for future video recordings. This process standardises file naming, filing footage into folders based on location (determined by IP address), date and camera position. Configurable logs are created, noting success/failure of the job including any missing/unreachable recorders, copy errors and/or unavailable storage media, enabling technical staff on site to troubleshoot and remedy issues. Footage is now available off site immediately after processing (via a Samba share), ready for remote production/editing staff soon after filming. This script saves up to 3 hours of manual media transfer and archival work every day, greatly increasing my productivity during peak production periods. 
---
