---
title: RL Delivery Dispatcher
emoji: 🚚
colorFrom: blue
colorTo: indigo
sdk: docker
app_port: 7860
pinned: false
---

# Delivery Dispatcher RL Environment

A reinforcement learning environment simulating delivery dispatch for training intelligent routing agents.

## Overview
This repository contains the environment, server endpoints, and inference pipeline for training and evaluating reinforcement learning agents on delivery dispatch tasks.

## Local Setup & Usage

```bash
# Install dependencies
pip install -r requirements.txt

# Run server
python server/app.py