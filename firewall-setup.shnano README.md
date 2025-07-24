#!/bin/bash

sudo apt update
sudo apt install -y ufw

sudo ufw reset

sudo ufw default deny incoming
sudo ufw default allow outgoing

sudo ufw allow ssh
sudo ufw allow http
sudo ufw allow https

sudo ufw limit ssh

sudo ufw logging on

sudo ufw --force enable

sudo ufw status verbose
