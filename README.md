# Ansible Role: Multimedia
[![Build Status](https://travis-ci.org/brentwg/ansible-role-multimedia.svg?branch=master)](https://travis-ci.org/brentwg/aansible-role-multimedia)

Ansible role that installs useful multimedia applications and codecs. This role was created for the following Ansible Playbook: [Linux DevOps Workstation](https://github.com/brentwg/ansible-linux-workstation).

## Requirements  

None.  

## Objectives
1. Install free and non-free codecs
1. Install [FFMpeg](https://www.ffmpeg.org/)
1. Install [VLC](https://www.videolan.org/vlc/index.html)  

> More applications to follow...

## Role Variables  
You can override the following variables:
```
multimedia_application_packages: []
```
Listing of RPMs or APT packages for multimedia applications that you wish to add.
```
multimedia_codec_packages: []
```
Listing of RPMs or APT packages for multimedia codecs that you wish to add.

## Dependencies

TODO

## Sample Playbook
```
- hosts: all
  
  roles:
    - brentwg.multimedia
```
